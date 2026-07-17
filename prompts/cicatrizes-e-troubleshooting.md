# Cicatrizes e troubleshooting

Este arquivo registra os principais problemas encontrados durante a utilização do NotebookLM, suas possíveis causas, os ajustes realizados nos prompts e os resultados obtidos.

As “cicatrizes” representam situações em que a primeira resposta não estava necessariamente totalmente errada, mas apresentou limitações, generalizações, omissões ou dificuldades de verificação que exigiram reformulação do prompt e revisão manual.

## Resumo dos problemas

| Problema | Causa provável | Ajuste realizado | Resultado |
|---|---|---|---|
| Resposta genérica | Prompt inicial muito amplo | Definição de tópicos e sequência da resposta | Conteúdo mais organizado e detalhado |
| Conceitos diferentes misturados | Ausência de critérios de classificação | Separação entre canal, alvo, técnica e infraestrutura | Taxonomia mais clara |
| Referências ausentes ou incompletas | Fontes não solicitadas de forma detalhada | Pedido explícito de fonte em cada seção | Maior verificabilidade |
| Campos solicitados não preenchidos | Prompt com muitas categorias e informações obrigatórias | Uso de tabelas e instrução para informar dados ausentes | Resposta mais uniforme, embora ainda exija revisão |
| Métricas sem contexto | Pedido por desempenho sem exigência metodológica | Solicitação de dataset, métrica e método de validação | Resultados apresentados com maior cautela |
| Inferências apresentadas como fatos | Falta de distinção entre fonte e interpretação | Pedido para separar fatos, inferências e exemplos fictícios | Menor risco de generalizações |
| Prevenção, detecção e resposta misturadas | Conceitos relacionados tratados como equivalentes | Definição prévia das etapas de defesa | Classificação mais precisa das medidas |
| Tópicos solicitados omitidos | Prompt extenso e fontes com cobertura desigual | Solicitação para informar explicitamente quando não houver dados | Omissões ficaram mais visíveis |
| Afirmações excessivamente absolutas | Ausência de orientação sobre linguagem crítica | Proibição de expressões absolutas sem evidência | Resposta mais cuidadosa |
| Português europeu na resposta | Padrão linguístico adotado automaticamente pelo sistema | Solicitação explícita de português brasileiro | Maior consistência linguística |
| Identificação genérica das fontes | Uso de rótulos como “Fonte 1” e “Fonte 2” | Pedido pelo título ou abreviação do documento | Referências mais transparentes |
| Resposta desigual em prompts muito detalhados | Grande quantidade de campos em uma única solicitação | Divisão da análise em etapas e revisão manual | Melhor cobertura dos tópicos |

---

## Problema 1 — Resposta muito genérica

### Situação

O prompt utilizado foi:

> Como a inteligência artificial pode detectar phishing?

A resposta apresentou conceitos gerais sobre machine learning, deep learning e processamento de linguagem natural, mas não explicou de forma organizada as etapas de um sistema de detecção.

Também foram misturados dados de entrada, algoritmos, características, resultados e vantagens.

### Possível causa

A pergunta era ampla e não especificava:

- Quais dados deveriam ser analisados;
- Como os dados seriam preparados;
- Quais métodos deveriam ser diferenciados;
- Como ocorria a classificação;
- Quais métricas deveriam ser apresentadas;
- Quais limitações deveriam ser discutidas.

### Ajuste realizado

O prompt foi reformulado para solicitar:

- Tipos de dados de entrada;
- Preparação e processamento;
- Características linguísticas;
- Características de URLs e páginas;
- Machine learning;
- Redes neurais;
- Deep learning;
- Processo de classificação;
- Métricas;
- Falsos positivos e falsos negativos;
- Limitações;
- Situações que exigem análise humana;
- Fontes utilizadas.

### Resultado

A nova resposta apresentou uma sequência mais clara, desde a coleta e preparação dos dados até a classificação e a avaliação do modelo.

Também foi possível diferenciar melhor machine learning tradicional, redes neurais, deep learning e processamento de linguagem natural.

### Aprendizado

Prompts amplos são úteis para uma exploração inicial, mas prompts estruturados produzem materiais de estudo mais organizados e permitem verificar com maior facilidade quais tópicos foram respondidos.

---

## Problema 2 — Mistura de diferentes critérios de classificação

### Situação

No prompt inicial:

> Quais são os principais tipos de phishing?

A resposta colocou no mesmo nível:

- Phishing por e-mail;
- Smishing;
- Vishing;
- Spear phishing;
- Whaling;
- Pharming;
- Evil twin;
- Malware phishing;
- Pop-up phishing.

Entretanto, esses termos representam critérios diferentes, como canal, perfil do alvo, grau de personalização, técnica utilizada, infraestrutura ou carga maliciosa.

### Possível causa

O prompt pediu apenas os “principais tipos”, sem definir:

- O critério de classificação;
- Como lidar com categorias sobrepostas;
- Como separar tipos de técnicas auxiliares;
- Como comparar as taxonomias das fontes.

### Ajuste realizado

O prompt aprimorado passou a separar:

1. Canal de comunicação;
2. Nível de direcionamento;
3. Técnica utilizada;
4. Infraestrutura ou mecanismo relacionado.

Também foi solicitado que a resposta informasse se um elemento era:

- Tipo de phishing;
- Técnica auxiliar;
- Infraestrutura;
- Ataque relacionado;
- Forma de distribuição de malware.

### Resultado

A nova resposta reconheceu que um ataque pode pertencer a mais de uma categoria.

Por exemplo, um ataque pode ser simultaneamente:

- Enviado por e-mail;
- Direcionado a uma pessoa específica;
- Classificado como spear phishing;
- Baseado em uma página falsa;
- Utilizado para distribuir malware.

### Aprendizado

Quando as fontes utilizam taxonomias diferentes, o prompt deve pedir explicitamente os critérios de classificação antes de solicitar a lista de tipos.

Caso contrário, o modelo pode reunir canais, alvos e técnicas como se fossem categorias equivalentes.

---

## Problema 3 — Referências ausentes ou incompletas

### Situação

Mesmo quando o prompt solicitava fontes, algumas respostas apresentavam apenas:

> Fonte:

ou utilizavam rótulos genéricos como:

> Fonte 1  
> Fonte 2  
> Fonte 5

Em algumas seções, nenhuma fonte era indicada.

### Possível causa

O pedido por referências não especificava:

- Como as fontes deveriam ser identificadas;
- Se cada afirmação deveria ter uma referência;
- O que fazer quando a informação não estivesse disponível;
- Se o número indicado era uma fonte do NotebookLM ou uma referência interna do artigo.

### Ajuste realizado

Os prompts passaram a solicitar:

- Fonte correspondente em cada seção;
- Título ou abreviação clara do documento;
- Indicação explícita quando a informação não estivesse disponível;
- Separação entre fonte primária e citação secundária;
- Identificação da fonte de estatísticas e exemplos reais.

### Resultado

As respostas ficaram mais verificáveis, embora algumas referências ainda tenham permanecido incompletas.

Por isso, continuou sendo necessária a conferência manual das citações do NotebookLM nos documentos originais.

### Aprendizado

Pedir apenas “indique as fontes” pode não ser suficiente.

É mais eficaz solicitar:

- A fonte em cada afirmação relevante;
- O título abreviado do documento;
- A indicação de ausência de informação;
- A identificação de citações secundárias.

---

## Problema 4 — Preenchimento incompleto dos campos solicitados

### Situação

Nos prompts sobre tipos de phishing e técnicas de prevenção, foram solicitados vários campos para cada item, como:

- Nome;
- Funcionamento;
- Problema reduzido;
- Responsável;
- Vantagens;
- Limitações;
- Exemplo;
- Fonte.

Entretanto, algumas técnicas receberam descrições completas, enquanto outras apresentaram apenas nome e funcionamento.

Em determinados casos, o campo de fonte ficou vazio.

### Possível causa

O prompt continha muitas categorias, técnicas e campos obrigatórios em uma única solicitação.

Além disso, as fontes não possuíam o mesmo nível de informação sobre todos os itens.

### Ajuste realizado

Foram adotadas as seguintes orientações:

- Apresentar os dados em tabela;
- Informar explicitamente quando um campo não estivesse disponível;
- Não completar lacunas por inferência;
- Dividir análises muito extensas em mais de uma pergunta;
- Revisar manualmente o cumprimento de cada campo.

### Resultado

A estrutura melhorou, mas o preenchimento continuou desigual em alguns casos.

A tabela facilitou a identificação das informações ausentes e das categorias que precisavam de nova consulta.

### Aprendizado

Um prompt detalhado não garante que todos os campos serão preenchidos com a mesma profundidade.

Quando houver muitos elementos, pode ser mais confiável analisar grupos menores em consultas separadas.

---

## Problema 5 — Métricas e estatísticas sem contexto

### Situação

As respostas apresentaram afirmações como:

- Random Forest com desempenho superior a 98%;
- NLP com desempenho acima de 90%;
- MFA capaz de prevenir 99,9% dos comprometimentos;
- Simulações reduzindo cliques em 55%;
- Filtros com desempenho superior a 95%.

Entretanto, não foram apresentados:

- Dataset;
- Tamanho da amostra;
- Métrica utilizada;
- Balanceamento;
- Divisão entre treinamento e teste;
- Método de validação;
- Período do estudo;
- Fonte original do dado.

### Possível causa

O prompt solicitava métodos, vantagens e resultados, mas não exigia o contexto metodológico das métricas.

O NotebookLM reuniu valores presentes nos documentos sem explicar as condições em que foram obtidos.

### Ajuste realizado

Os prompts passaram a determinar que nenhum valor de desempenho deveria ser apresentado sem informar:

- Fonte;
- Dataset;
- Quantidade de exemplos;
- Métrica;
- Balanceamento;
- Estratégia de divisão;
- Método de validação;
- Contexto do experimento.

Também foi incluída a orientação para não comparar resultados obtidos com datasets e metodologias diferentes.

### Resultado

As respostas seguintes passaram a apresentar as métricas de forma mais cautelosa.

Também ficou mais evidente que uma alta acurácia isolada não garante bom desempenho em situações reais.

### Aprendizado

Métricas sem contexto podem gerar conclusões enganosas.

Em estudos de detecção, é necessário verificar se o resultado foi influenciado por:

- Desbalanceamento;
- Dados duplicados;
- Vazamento entre treinamento e teste;
- Ausência de validação temporal;
- Dataset pequeno ou pouco representativo.

---

## Problema 6 — Inferências apresentadas como informações das fontes

### Situação

Em algumas respostas, o NotebookLM atribuiu classificações como:

- Personalização baixa;
- Personalização média;
- Personalização extrema;
- Dependência tecnológica alta;
- Dependência psicológica total;
- Ataque mais difícil de detectar;
- Método mais eficaz.

Nem sempre ficou claro se essas classificações estavam explicitamente presentes nos documentos.

### Possível causa

O prompt solicitava o preenchimento de campos comparativos, mesmo quando as fontes não apresentavam uma classificação direta.

O modelo tentou completar as lacunas por meio de inferências.

### Ajuste realizado

Foi adicionada a orientação para:

- Informar quando um dado não estivesse disponível;
- Diferenciar informação explícita de inferência;
- Não inventar níveis ou categorias;
- Justificar classificações qualitativas;
- Evitar superlativos sem referência.

### Resultado

As respostas passaram a sinalizar melhor a ausência de informações, embora algumas inferências ainda tenham exigido revisão manual.

### Aprendizado

Quando o prompt exige um campo que não está presente na fonte, o modelo pode tentar preenchê-lo com uma conclusão plausível.

Por isso, é importante incluir a instrução:

> Quando a informação não estiver disponível, informe explicitamente,
> sem completar o campo por inferência.

---

## Problema 7 — Prevenção, detecção, mitigação e resposta misturadas

### Situação

Na resposta sobre técnicas de prevenção, foram incluídas como medidas preventivas:

- Monitoramento de login anormal;
- Planos de resposta a incidentes;
- Triagem humana;
- Bloqueio de contas comprometidas;
- Recuperação de sistemas.

Essas ações não atuam todas no mesmo momento.

### Possível causa

A pergunta inicial solicitava “técnicas para prevenir ataques”, mas as fontes apresentavam medidas de todo o ciclo de segurança.

O prompt não exigia a diferenciação entre as etapas.

### Ajuste realizado

O prompt aprimorado passou a separar:

1. Prevenção;
2. Detecção;
3. Mitigação;
4. Resposta;
5. Recuperação.

Para cada técnica, também foi solicitado o momento em que ela atua.

### Resultado

A resposta apresentou uma estratégia em camadas e diferenciou melhor o papel de:

- Treinamento;
- Filtros;
- Autenticação;
- Monitoramento;
- Resposta a incidentes.

### Aprendizado

Medidas relacionadas ao mesmo problema não devem ser tratadas como equivalentes.

Por exemplo:

- Filtros podem prevenir e detectar;
- MFA reduz o impacto do roubo de credenciais;
- Monitoramento identifica possível comprometimento;
- Planos de resposta reduzem danos após o incidente.

---

## Problema 8 — Tópicos solicitados foram omitidos

### Situação

No prompt sobre limitações da detecção automática, foram solicitados temas como:

- Privacidade;
- Validação temporal;
- Redes neurais;
- Deep learning;
- NLP;
- Metadados;
- Dependência humana.

Entretanto, alguns deles foram apenas mencionados brevemente ou não apareceram na tabela principal.

### Possível causa

O prompt continha um número elevado de tópicos, enquanto as fontes possuíam cobertura desigual.

O modelo priorizou os assuntos mais frequentes nos documentos.

### Ajuste realizado

Foram adicionadas instruções para:

- Informar explicitamente quando um tópico não estivesse disponível;
- Verificar cada item solicitado;
- Separar a resposta por subseções;
- Utilizar uma tabela de cobertura;
- Dividir consultas extensas em etapas.

### Resultado

As omissões ficaram mais visíveis e puderam ser registradas como parte da análise crítica.

Entretanto, ainda foi necessário verificar manualmente se todos os tópicos haviam sido respondidos.

### Aprendizado

Uma lista extensa de itens no prompt não garante cobertura uniforme.

Após a resposta, é necessário conferir:

- Quais itens foram respondidos;
- Quais foram apenas citados;
- Quais foram omitidos;
- Quais não estavam presentes nas fontes.

---

## Problema 9 — Afirmações excessivamente absolutas

### Situação

Algumas respostas utilizaram formulações como:

- A IA detecta ataques zero-day;
- Deep learning elimina a engenharia manual de características;
- LSTM é ideal para textos;
- CNN é altamente eficaz;
- MFA impede 99,9% dos ataques;
- Usuários são o elo mais fraco;
- Máquinas raciocinam como seres humanos.

### Possível causa

O prompt inicial não solicitava uma análise crítica nem restringia o uso de expressões absolutas.

O modelo transformou resultados ou possibilidades descritas nas fontes em conclusões gerais.

### Ajuste realizado

Os prompts passaram a incluir regras como:

- Não apresentar possibilidades como garantias;
- Não utilizar “elimina”, “sempre”, “ideal” ou “totalmente eficaz” sem
  evidência;
- Apresentar limitações;
- Contextualizar resultados;
- Diferenciar padrão estatístico de raciocínio humano.

### Resultado

As respostas seguintes passaram a apresentar maior cautela ao discutir as capacidades da inteligência artificial.

### Aprendizado

Sistemas generativos podem transformar afirmações condicionais em declarações gerais.

A revisão precisa verificar se a fonte afirma que um método:

- Pode auxiliar;
- Apresentou resultado em um estudo;
- É promissor;
- Ou realmente resolve o problema.

---

## Problema 10 — Uso de termos do português europeu

### Situação

As respostas apresentaram termos como:

- Utilizador;
- Ficheiro;
- Palavra-passe;
- Ecrã;
- Telemóvel;
- Deteção;
- Treino;
- Monitorização;
- Consciencialização.

O restante do projeto estava sendo produzido em português brasileiro.

### Possível causa

O NotebookLM adotou automaticamente outra variante da língua portuguesa.

### Ajuste realizado

Foi adicionada a instrução:

> Utilize português brasileiro.

Também foi realizada revisão manual das expressões utilizadas.

### Resultado

As respostas ficaram mais consistentes com o padrão linguístico do projeto.

### Aprendizado

A definição do idioma não garante a definição da variante linguística.

Quando a padronização for importante, é necessário especificar explicitamente “português brasileiro”.

---

## Problema 11 — Fonte secundária tratada como fonte original

### Situação

Algumas estatísticas foram apresentadas como fatos confirmados, embora os artigos apenas citassem outros relatórios.

Entre os exemplos estavam percentuais relacionados a:

- Participação do fator humano em violações;
- Eficácia da autenticação multifator;
- Redução de cliques após treinamentos.

### Possível causa

O NotebookLM apresentou a informação encontrada no artigo sem diferenciar se o dado havia sido produzido pelo próprio estudo ou citado de outra publicação.

### Ajuste realizado

Os prompts passaram a solicitar:

- Fonte original;
- Ano;
- Contexto;
- Identificação de citação primária ou secundária;
- Remoção do dado quando a fonte original não pudesse ser confirmada.

### Resultado

A análise passou a diferenciar melhor evidências produzidas pelo estudo de informações citadas de outros trabalhos.

### Aprendizado

Uma informação presente em um artigo não necessariamente foi produzida por ele.

Estatísticas devem ser rastreadas até a referência original sempre que forem utilizadas como evidência importante.

---

## Problema 12 — Definições técnicas imprecisas

### Situação

Alguns conceitos foram apresentados com definições incompletas ou tecnicamente problemáticas.

Exemplos:

- Clone phishing descrito apenas como imitação de serviços internos;
- Angler phishing tratado como combinação de smishing e vishing;
- HTTPS apresentado como mecanismo para injetar malware;
- Watering hole limitado à alteração de endereço IP;
- Pharming limitado à infecção de servidores DNS;
- Pop-up phishing descrito como instalação automática de vírus.

### Possível causa

Algumas fontes apresentavam descrições breves ou taxonomias próprias.

O NotebookLM também reuniu explicações de documentos diferentes e produziu uma definição única.

### Ajuste realizado

Foi necessário:

- Comparar as definições entre as fontes;
- Verificar o trecho original;
- Separar técnica, infraestrutura e consequência;
- Evitar complementar definições com conhecimento não presente nos
  documentos;
- Registrar divergências conceituais.

### Resultado

As definições foram revisadas e apresentadas com maior cautela.

Também ficou registrado quando um termo aparecia em apenas uma fonte ou possuía classificação divergente.

### Aprendizado

Termos técnicos semelhantes podem possuir definições diferentes entre os autores.

O modelo não deve ser utilizado como única fonte para resolver uma divergência conceitual; é necessário consultar o documento original.

---

## Problema 13 — Prompt muito detalhado gerou resposta desigual

### Situação

Alguns prompts exigiam muitas categorias e até doze informações para cada item.

A resposta ficou extensa, mas ainda apresentou:

- Campos vazios;
- Tabelas incompletas;
- Diferenças de profundidade;
- Fontes ausentes;
- Categorias apenas mencionadas.

### Possível causa

A quantidade de requisitos ultrapassou o nível de detalhe disponível nas fontes e dificultou a manutenção de uma estrutura uniforme.

### Ajuste realizado

A estratégia recomendada passou a ser:

1. Solicitar primeiro uma visão geral;
2. Identificar os grupos principais;
3. Analisar um grupo por vez;
4. Produzir a tabela final apenas depois;
5. Solicitar verificação de lacunas.

### Resultado

Consultas menores permitiram respostas mais específicas e facilitaram a verificação das fontes.

### Aprendizado

Um prompt muito detalhado pode melhorar a estrutura, mas também pode aumentar:

- Omissões;
- Inferências;
- Inconsistências;
- Preenchimento superficial.

Em análises extensas, dividir a atividade em etapas pode ser mais confiável do que pedir tudo em uma única resposta.

---

## Checklist de troubleshooting

Antes de utilizar uma resposta do NotebookLM no miniguia, verificar:

- [ ] A resposta utilizou apenas as fontes selecionadas;
- [ ] Todas as seções solicitadas foram respondidas;
- [ ] As fontes foram identificadas claramente;
- [ ] Não existem campos de referência vazios;
- [ ] Estatísticas apresentam fonte, ano e contexto;
- [ ] Não foram comparados estudos com datasets diferentes sem ressalva;
- [ ] Fatos e inferências estão diferenciados;
- [ ] Exemplos inventados estão identificados como fictícios;
- [ ] Não existem afirmações absolutas sem evidência;
- [ ] Canais, técnicas, alvos e mecanismos não foram misturados;
- [ ] Prevenção, detecção e resposta foram diferenciadas;
- [ ] Termos técnicos foram conferidos nas fontes;
- [ ] Métricas foram utilizadas corretamente;
- [ ] O texto está em português brasileiro;
- [ ] A resposta passou por revisão manual.

---

## Aprendizado geral

O uso do NotebookLM facilitou a síntese e a comparação das fontes, mas não eliminou a necessidade de revisão humana.

Os principais aprendizados foram:

- Prompts estruturados produzem respostas mais organizadas;
- Solicitar referências não garante que todas serão apresentadas;
- Campos ausentes podem ser preenchidos por inferência;
- Estatísticas precisam ser verificadas na fonte original;
- Taxonomias diferentes não devem ser unificadas automaticamente;
- Respostas detalhadas podem continuar apresentando omissões;
- A revisão manual das citações permanece necessária;
- A inteligência artificial deve ser utilizada como apoio à análise,
  e não como substituição da leitura crítica das fontes.