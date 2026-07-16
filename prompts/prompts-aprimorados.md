# Prompts aprimorados

## Prompt 1 - Aplicação de IA na detecção de phishing

### Versão inicial

> Como a inteligência artificial pode detectar phishing?

### Problema encontrado

A resposta obtida com o prompt inicial apresentou uma definição geral de phishing, mas reuniu diferentes aspectos do tema sem uma organização clara.

### Versão aprimorada

> Com base exclusivamente nas fontes selecionadas, explique o conceito
> de phishing para um estudante da área de Computação que está tendo
> o primeiro contato com o tema.
>
> Organize a resposta nas seguintes seções:
> 1. Definição de phishing;
> 2. Objetivo dos atacantes;
> 3. Funcionamento geral de um ataque;
> 4. Elementos de engenharia social utilizados;
> 5. Elementos técnicos utilizados;
> 6. Informações normalmente buscadas pelos criminosos;
> 7. Exemplo fictício de uma tentativa de phishing;
> 8. Consequências para indivíduos e organizações.
>
> Indique as fontes utilizadas em cada seção.
>
> Caso exista mais de uma definição nas fontes, compare-as e apresente os pontos em comum e as diferenças.
>
> Não utilize informações externas aos documentos selecionados.

### Alterações realizadas

- Restrição do conteúdo exclusivamente às fontes selecionadas;
- Definição do público-alvo como um estudante de Computação em contato inicial com o tema;
- Divisão da resposta em seções específicas;
- Separação entre definição, objetivos, funcionamento e consequências;
- Separação entre elementos de engenharia social e elementos técnicos;
- Solicitação de comparação entre diferentes definições de phishing;
- Inclusão das informações normalmente procuradas pelos criminosos;
- Solicitação de um exemplo fictício para facilitar a compreensão;
- Inclusão dos impactos para indivíduos e organizações;
- Solicitação da indicação das fontes utilizadas em cada seção;
- Proibição do uso de informações externas aos documentos.

### Resultado

A resposta obtida com o prompt aprimorado apresentou uma estrutura mais completa e organizada.

Inicialmente, foram comparadas diferentes definições de phishing, destacando como ponto comum o uso de engano e falsificação de identidade para obtenção de informações confidenciais. A resposta também diferenciou definições mais simples de outras que incluem engenharia social e subterfúgio técnico.

Em seguida, foram apresentados:s
- Os principais objetivos dos atacantes, como obtenção de ganhos financeiros, acesso indevido a sistemas e roubo de informações;
- Um ciclo geral do ataque, dividido em planejamento, preparação, distribuição, exploração e exfiltração;
- Elementos de engenharia social, como urgência, medo, autoridade, curiosidade e personificação de entidades confiáveis;
- Elementos técnicos, como páginas falsas, URLs enganosas, malware, manipulação de DNS e uso indevido de certificados;
- Os principais dados procurados pelos criminosos, incluindo credenciais, informações financeiras, dados pessoais e códigos de autenticação;
- Um exemplo fictício demonstrando a combinação entre manipulação psicológica e recursos técnicos;
- Possíveis consequências para indivíduos e organizações.

A resposta passou a apresentar uma sequência lógica, começando pela definição do conceito e avançando até o funcionamento e os impactos de um ataque.

### Avaliação

O prompt aprimorado foi mais eficiente que o inicial porque definiu uma
estrutura clara e orientou o NotebookLM a produzir uma explicação
adequada para um estudante iniciante.

A comparação entre as definições foi um dos principais avanços, pois
permitiu perceber que as fontes enfatizam diferentes aspectos do
phishing. Algumas destacam principalmente o engano e a falsificação de
identidade, enquanto outras também incluem engenharia social, malware,
redirecionamento e outros recursos técnicos.

A divisão entre elementos psicológicos e técnicos também tornou a
explicação mais didática. Além disso, o exemplo fictício ajudou a
demonstrar como os diferentes componentes podem aparecer conjuntamente
em uma tentativa de phishing.

Entretanto, alguns problemas ainda permaneceram:
- A afirmação de que todas as fontes apresentam a mesma definição central precisa ser confirmada individualmente;
- O termo “ignorância do usuário” possui tom inadequado e pode responsabilizar excessivamente a vítima;
- A expressão “elo mais fraco” simplifica o problema, pois o sucesso do phishing também depende de falhas técnicas, organizacionais e de processo;
- Termos como “exfiltração”, “weaponization” e “backdoor” deveriam ser explicados em linguagem introdutória;
- A criação de “réplicas visualmente idênticas” foi apresentada de maneira generalizada, embora páginas fraudulentas também possam apenas imitar parcialmente um serviço legítimo;
- O pharming foi limitado à infecção de servidores DNS, apesar de poder envolver outros mecanismos de redirecionamento;
- O uso de HTTPS deveria ser apresentado como um recurso que pode gerar falsa sensação de segurança, e não como prova de legitimidade;
- Objetivos como espionagem, sabotagem e ataques a infraestruturas críticas são possíveis, mas deveriam ser diferenciados dos objetivos mais comuns do phishing;
- A afirmação sobre prejuízos de centenas de milhões de dólares não foi acompanhada de período, contexto ou fonte específica;
- O exemplo da rede elétrica da Ucrânia precisa ser apresentado com cautela e diretamente associado à fonte correspondente;
- A resposta ainda utilizou expressões do português europeu, como “utilizador”, “planeamento”, “ficheiro”, “palavra-passe” e “ecrã”;
- As referências precisam ser verificadas para confirmar se sustentam integralmente cada afirmação.

De modo geral, o novo prompt melhorou significativamente a organização, a profundidade e a clareza da resposta. No entanto, o conteúdo ainda precisa passar por revisão linguística, verificação das citações e substituição de afirmações excessivamente amplas por formulações mais cuidadosas.

## Prompt 2 — Relação entre phishing e engenharia social

### Versão inicial

> Qual é a relação entre phishing e engenharia social?

### Problema encontrado

A resposta obtida com o prompt inicial apresentou corretamente a engenharia social como um conceito mais amplo e o phishing como uma de suas formas de aplicação. Entretanto, a relação entre os conceitos foi explicada de maneira pouco controlada.

Foram identificados os seguintes problemas:
- Phishing e engenharia social foram diferenciados, mas sem uma comparação estruturada entre abrangência, objetivo e forma de execução;
- A resposta não apresentou exemplos suficientes de engenharia social que não envolvessem phishing;
- Elementos psicológicos e recursos técnicos foram mencionados sem uma separação clara;
- Algumas afirmações foram excessivamente categóricas, como a ideia de que o phishing seria apenas o “meio técnico” da engenharia social;
- A expressão “elo mais fraco” simplificou o papel do fator humano e desconsiderou vulnerabilidades técnicas e organizacionais;
- Não ficou claro se todas as fontes utilizavam as mesmas definições;
- Dados estatísticos foram apresentados sem o contexto completo das referências originais;
- A resposta utilizou termos do português europeu.

### Versão aprimorada

> Com base exclusivamente nas fontes selecionadas, explique a relação entre phishing e engenharia social.
>
> Organize a resposta da seguinte maneira:
>
> 1. Definição de phishing;
> 2. Definição de engenharia social;
> 3. Relação entre os dois conceitos;
> 4. Principais diferenças;
> 5. Elementos psicológicos explorados em ataques de phishing;
> 6. Exemplos de engenharia social que não envolvem phishing;
> 7. Exemplo fictício de phishing baseado em engenharia social;
> 8. Papel da tecnologia em conjunto com a manipulação humana.
>
> Apresente também uma tabela comparativa contendo:
>
> - Conceito;
> - Objetivo;
> - Forma de execução;
> - Alvo principal;
> - Exemplos;
> - Dependência de recursos tecnológicos;
> - Dependência de manipulação psicológica.
>
> Indique as fontes utilizadas e informe quando houver divergências conceituais entre os documentos.
>
> Não trate phishing e engenharia social como termos equivalentes sem explicar a relação entre eles.

### Alterações realizadas

Para tornar a resposta mais clara e conceitualmente precisa, foram
realizadas as seguintes alterações:
- Restrição do conteúdo exclusivamente às fontes selecionadas;
- Solicitação de definições separadas para phishing e engenharia social;
- Inclusão de uma seção específica para explicar a relação entre os conceitos;
- Solicitação das principais diferenças entre phishing e engenharia social;
- Separação entre elementos psicológicos e recursos tecnológicos;
- Inclusão de exemplos de engenharia social que não envolvem phishing;
- Solicitação de um exemplo fictício que demonstrasse a combinação entre manipulação humana e subterfúgio técnico;
- Inclusão de uma tabela comparativa;
- Solicitação da identificação das fontes utilizadas;
- Orientação para destacar divergências conceituais entre os artigos;
- Orientação explícita para não tratar os dois termos como equivalentes.

### Resultado

A resposta obtida com o prompt aprimorado apresentou uma comparação mais organizada entre phishing e engenharia social.

A engenharia social foi apresentada como uma categoria ampla de técnicas de manipulação do comportamento humano. O phishing, por sua vez, foi descrito como uma forma de ataque que frequentemente aplica esses princípios por meio de mensagens, páginas falsas, chamadas, links e outros recursos de comunicação.

A resposta também apresentou:
- Definições separadas para os dois conceitos;
- A relação entre a manipulação psicológica e os mecanismos técnicos utilizados em phishing;
- Diferenças relacionadas à abrangência e à forma de execução;
- Gatilhos psicológicos, como urgência, medo, autoridade, confiança e curiosidade;
- Exemplos de engenharia social que não dependem necessariamente de phishing, como baiting, tailgating e pretexting;
- Um exemplo fictício de spear phishing que combinou autoridade, urgência e página fraudulenta;
- O papel de tecnologias como redes sociais, análise de dados, deepfakes e certificados digitais na criação de ataques mais convincentes;
- Uma tabela comparativa entre engenharia social e phishing;
- Uma tentativa de identificar diferenças de ênfase entre as fontes.

A inclusão de exemplos não digitais ajudou a demonstrar que engenharia social possui maior abrangência do que phishing. As fontes realmente apresentam engenharia social como exploração do comportamento humano eo phishing como uma ameaça que pode combinar manipulação psicológica esubterfúgio técnico.

### Avaliação

O prompt aprimorado foi mais eficiente porque obrigou o NotebookLM a
definir os conceitos separadamente antes de explicar sua relação.

A inclusão de exemplos de baiting, tailgating e pretexting tornou mais
claro que nem toda engenharia social é phishing. O artigo sobre
engenharia social apresenta essas técnicas como formas distintas de
exploração da confiança e do comportamento humano.

A tabela comparativa também facilitou a visualização das diferenças de
abrangência, execução e dependência tecnológica.

Entretanto, alguns problemas ainda permaneceram:
- A relação foi chamada de “interdependência”, embora a engenharia social não dependa do phishing. Uma formulação mais adequada seria afirmar que o phishing frequentemente utiliza princípios de engenharia social;
- A expressão “ciência do hacking humano” é didática, mas não deveria substituir uma definição acadêmica do conceito;
- O phishing foi tratado como um subconjunto de engenharia social de maneira absoluta. Algumas fontes também enfatizam o subterfúgio técnico, malware, redirecionamentos e exploração de infraestrutura;
- A afirmação de que o phishing é estritamente digital ou mediado por telecomunicações precisa ser apresentada com cautela, pois existem estratégias híbridas e diferentes critérios de classificação;
- A resposta afirmou que a engenharia social fornece a metodologia e o phishing fornece o veículo técnico. Essa divisão é útil didaticamente, mas simplifica o conceito, pois o próprio phishing é uma estratégia de ataque, e não apenas um canal;
- A dependência tecnológica do phishing foi classificada como “alta”, embora alguns ataques possam utilizar recursos tecnicamente simples, como uma mensagem fraudulenta ou uma chamada telefônica;
- A dependência de manipulação psicológica foi classificada como “total” para engenharia social e “alta” para phishing, mas essas classificações não foram justificadas por critérios presentes nas fontes;
- O termo “impersonação” deveria ser substituído por “falsificação de identidade” ou “personificação”, mais naturais em português brasileiro;
- A expressão “elo mais fraco” responsabiliza excessivamente o usuário e ignora controles técnicos, interfaces, processos e políticas organizacionais;
- O pharming e o uso de HTTPS foram incluídos como elementos do phishing, mas deveriam ser descritos cuidadosamente como mecanismos técnicos relacionados ao redirecionamento ou à falsa aparência de legitimidade;
- A resposta mencionou IA, big data e deepfakes, mas deveria indicar com precisão qual fonte sustenta cada aplicação;
- A afirmação de que todas as fontes concordam que o usuário é o alvo central precisa ser verificada individualmente, pois algumas fontes também tratam de sistemas, credenciais, organizações e infraestruturas;
- A análise das divergências entre as fontes foi útil, mas permaneceu superficial. Seria melhor indicar o trecho ou a definição específica de cada documento;
- A resposta ainda utilizou expressões do português europeu, como “utilizador”, “eletrónicos”, “logótipos”, “prémios”, “recolhem” e “bónus”.

De modo geral, o prompt aprimorado melhorou significativamente a comparação e evitou que phishing e engenharia social fossem tratados como sinônimos. Ainda assim, o resultado precisa de revisão para evitar relações absolutas, classificações não justificadas e simplificações sobre o papel da tecnologia.

## Prompt 3 — Principais tipos de phishing

### Versão inicial

> Quais são os principais tipos de phishing?

### Problema encontrado

A resposta obtida com o prompt inicial apresentou uma lista extensa de tipos de phishing, mas reuniu diferentes critérios de classificação como se todos pertencessem ao mesmo nível.

Foram identificados os seguintes problemas:
- Canais de comunicação, níveis de direcionamento, técnicas de execução e mecanismos de infraestrutura foram misturados;
- Não ficou claro por que determinadas variantes foram consideradas os “principais” tipos;
- Algumas categorias podiam se sobrepor, mas essa possibilidade não foi explicada;
- Técnicas relacionadas, como pharming, evil twin e watering hole, foram apresentadas diretamente como tipos de phishing;
- Algumas definições, como clone phishing, angler phishing, watering hole e HTTPS phishing, apresentaram imprecisões;
- Não houve comparação entre as diferentes taxonomias adotadas pelas fontes;
- Não ficou evidente qual documento sustentava cada definição;
- Foram utilizadas expressões do português europeu.

### Versão aprimorada

> Com base exclusivamente nas fontes selecionadas, identifique e explique os principais tipos de phishing para um estudante da área de Computação.
>
> Antes de apresentar os tipos, informe quais critérios de classificação são utilizados pelas fontes. Não reúna automaticamente classificações diferentes em uma única taxonomia.
>
> Organize a resposta nas seguintes categorias, quando elas forem sustentadas pelos documentos:
> 1. Classificação por canal de comunicação:
>    - E-mail;
>    - SMS ou mensagens de texto;
>    - Chamadas de voz ou VoIP;
>    - Redes sociais;
>    - Websites;
>    - Outros canais mencionados nas fontes.
>
> 2. Classificação pelo nível de direcionamento:
>    - Phishing genérico;
>    - Spear phishing;
>    - Whaling;
>    - Outras formas direcionadas encontradas nas fontes.
>
> 3. Classificação pela técnica utilizada:
>    - Clone phishing;
>    - Páginas falsas;
>    - Redirecionamento para páginas fraudulentas;
>    - Links ou URLs enganosas;
>    - Pop-ups fraudulentos;
>    - Distribuição de malware;
>    - Outras técnicas mencionadas.
>
> 4. Mecanismos e ataques relacionados:
>    - Pharming;
>    - Evil twin;
>    - Watering hole;
>    - Uso indevido de HTTPS;
>    - Outros mecanismos encontrados nas fontes.
>
> Para os elementos do quarto grupo, informe se as fontes os classificam como:
>
> - Tipo de phishing;
> - Técnica auxiliar;
> - Infraestrutura utilizada no ataque;
> - Ataque relacionado;
> - Forma de distribuição de malware.
>
> Para cada tipo ou técnica, apresente:
>
> 1. Nome;
> 2. Definição;
> 3. Critério de classificação;
> 4. Canal utilizado;
> 5. Perfil do alvo;
> 6. Nível de personalização;
> 7. Forma de funcionamento;
> 8. Elementos de engenharia social utilizados;
> 9. Elementos técnicos envolvidos;
> 10. Sinais que podem ajudar na identificação;
> 11. Exemplo fictício;
> 12. Fonte ou fontes correspondentes.
>
> Apresente também uma tabela comparativa com as colunas:
> 
> | Tipo ou técnica | Categoria | Canal | Alvo | Personalização | Principal característica | Pode se sobrepor a outros tipos? | Fonte |
>
> Ao final:
>
> 1. Identifique quais tipos aparecem em mais de uma fonte;
> 2. Apresente separadamente os termos encontrados em apenas um documento;
> 3. Explique as principais diferenças de classificação entre as fontes;
> 4. Informe quais categorias podem se sobrepor;
> 5. Indique quais podem ser consideradas os principais tipos de phishing com base na recorrência e na relevância atribuída pelos documentos.
>
> Regras para a resposta:
>
> - Utilize exclusivamente as fontes selecionadas;
> - Não inclua categorias que não estejam presentes nos documentos;
> - Não trate canais, alvos, técnicas e mecanismos como conceitos equivalentes;
> - Não apresente ataques relacionados como tipos de phishing sem informar como eles são classificados pelas fontes;
> - Não utilize expressões como “mais comum”, “mais perigoso” ou “mais difícil de detectar” sem apresentar a fonte e a justificativa;
> - Informe quando as fontes utilizarem nomes diferentes para ataques semelhantes;
> - Identifique todos os exemplos criados como fictícios;
> - Indique a fonte utilizada em cada definição;
> - Informe explicitamente quando uma informação não estiver disponível;
> - Utilize português brasileiro.

### Alterações realizadas

Para corrigir os problemas da resposta inicial, foram realizadas as
seguintes alterações:
- Restrição da resposta exclusivamente às fontes selecionadas;
- Solicitação dos critérios de classificação utilizados nos documentos;
- Separação entre canal de comunicação, nível de direcionamento, técnica de execução e infraestrutura;
- Orientação para não reunir automaticamente taxonomias diferentes;
- Separação entre tipos de phishing e ataques ou mecanismos apenas relacionados;
- Solicitação de informações detalhadas para cada tipo, incluindo canal, alvo, personalização, funcionamento e sinais de identificação;
- Inclusão de elementos psicológicos e técnicos;
- Solicitação de exemplos fictícios claramente identificados;
- Inclusão de uma tabela comparativa;
- Solicitação da identificação das categorias que podem se sobrepor;
- Inclusão de uma análise sobre os termos recorrentes e os encontrados em apenas uma fonte;
- Solicitação de comparação entre as classificações adotadas pelos diferentes documentos;
- Definição de critérios para determinar os principais tipos com base na recorrência e na relevância nas fontes;
- Orientação para informar quando um dado não estivesse disponível;
- Solicitação das fontes correspondentes a cada definição;
- Padronização da resposta em português brasileiro.

### Resultado

A resposta obtida com o prompt aprimorado apresentou uma organização mais clara das diferentes formas de phishing.

Antes de listar os ataques, foram identificados quatro critérios de classificação:
1. Canal de comunicação;
2. Nível de direcionamento;
3. Técnica de execução;
4. Infraestrutura ou mecanismo de rede.

Na classificação por canal, foram apresentados:
- Phishing por e-mail;
- Smishing;
- Vishing;
- Phishing em redes sociais;
- Phishing por websites.

Na classificação por direcionamento, foram apresentados:
- Spear phishing;
- Whaling.

Na classificação por técnica, foram apresentados:
- Clone phishing;
- Angler phishing.

Também foram separados mecanismos e ataques relacionados, como:
- Pharming;
- Evil twin;
- Watering hole;
- Uso indevido de HTTPS;
- Pop-up phishing.

Para a maior parte dos tipos, a resposta informou definição, canal, perfil do alvo, grau de personalização, funcionamento, elementos de engenharia social, elementos técnicos, sinais de identificação e um exemplo fictício.

A resposta também apresentou uma tabela comparativa e reconheceu que um ataque pode se enquadrar em mais de uma categoria. Por exemplo, um spear phishing pode ser enviado por e-mail, usar HTTPS e conduzir a uma página fraudulenta.

Ao final, houve uma tentativa de identificar:
- Tipos mencionados em várias fontes;
- Termos encontrados em apenas um documento;
- Diferenças entre as taxonomias;
- Categorias que podem se sobrepor;
- Tipos considerados mais recorrentes.

### Avaliação

O prompt aprimorado foi mais eficiente porque obrigou o NotebookLM a explicitar os critérios de classificação antes de apresentar os tipos de phishing.

A principal melhoria foi a separação entre:
- Canal utilizado para alcançar a vítima;
- Grau de direcionamento do ataque;
- Técnica empregada;
- Infraestrutura ou mecanismo auxiliar.

Essa estrutura tornou mais evidente que as categorias não são mutuamente exclusivas. Um ataque pode ser simultaneamente phishing por e-mail, spear phishing, direcionado a um executivo e baseado em uma página fraudulenta.

A inclusão de uma tabela comparativa e de uma seção sobre sobreposição também tornou a resposta mais adequada para fins de estudo.

Entretanto, o resultado ainda apresentou problemas e informações que precisam ser verificadas.

## Prompt 4 - Aplicação de IA na detecção de phishing

### Versão inicial

> Como a inteligência artificial pode detectar phishing?

### Problema encontrado

A resposta apresentou diferentes técnicas de inteligência artificial, como machine learning, deep learning, processamento de linguagem natural e análise comportamental, mas não explicou de forma clara como essas técnicas fazem parte de um fluxo completo de detecção.

### Versão aprimorada

>Com base exclusivamente nas fontes selecionadas, explique como técnicas de inteligência artificial podem ser utilizadas na detecção de phishing.
>
>Organize a resposta em:
>1. Tipos de dados de entrada;
>2. Preparação e processamento dos dados;
>3. Características linguísticas analisadas;
>4. Características de URLs e páginas;
>5. Técnicas de machine learning;
>6. Técnicas de deep learning;
>7. Processo de classificação;
>8. Métricas de avaliação;
>9. Falsos positivos e falsos negativos;
>10. Limitações;
>11. Situações que ainda exigem análise humana.
>
>Diferencie claramente machine learning tradicional, redes neurais e deep learning.
>
>Indique a fonte utilizada em cada seção. Quando uma informação não estiver disponível, informe explicitamente.

### Alterações realizadas

- A resposta passou a seguir um fluxo mais próximo das etapas de um sistema real de detecção;
- Foram separados os diferentes tipos de dados analisados, como textos, URLs, páginas e metadados;
- Foi solicitada a distinção entre características linguísticas e características técnicas;
- Machine learning tradicional, redes neurais e deep learning passaram a ser tratados separadamente;
- Foram incluídas as etapas de preparação dos dados, treinamento e classificação;
- Foi solicitada a apresentação das métricas utilizadas para avaliar os modelos;
- Falsos positivos e falsos negativos foram incluídos como elementos obrigatórios;
- As limitações técnicas e metodológicas passaram a fazer parte da estrutura da resposta;
- Foi incluída a necessidade de indicar situações em que a análise humana ainda é necessária;
- Cada seção passou a exigir a indicação da fonte correspondente;
- O prompt passou a exigir que a ausência de informações nas fontes fosse informada explicitamente.

### Resultado

A resposta obtida com o prompt aprimorado apresentou uma estrutura mais completa e próxima do fluxo de desenvolvimento de um sistema de detecção de phishing.
A resposta também conseguiu diferenciar, de forma introdutória, machine learning tradicional, redes neurais e deep learning.

Foram descritos:
- Diferentes dados de entrada, como URLs, e-mails, páginas web, imagens e metadados;
- Etapas de limpeza, normalização, rotulagem e transformação dos dados;
- Características linguísticas analisadas por técnicas de processamento de linguagem natural;
- Características léxicas, estruturais e visuais de URLs e páginas;
- Algoritmos tradicionais de machine learning;
- Arquiteturas de deep learning, como CNN, RNN, LSTM e GRU;
- O processo de classificação por meio de redes neurais;
- Métricas como acurácia, precisão, recall, F1-score e AUC-ROC;
- A diferença geral entre falsos positivos e falsos negativos;
- Limitações relacionadas aos dados, ao treinamento e à explicabilidade;
- Situações em que a revisão de analistas humanos continua necessária.

A resposta também conseguiu diferenciar, de forma introdutória, machine learning tradicional, redes neurais e deep learning.

### Avaliação

O prompt aprimorado apresentou um resultado significativamente melhor que o inicial, pois definiu uma estrutura clara e orientou o NotebookLM a explicar diferentes etapas de um sistema de detecção.

A resposta passou a mostrar não apenas quais algoritmos podem ser utilizados, mas também quais dados são analisados, como eles são preparados, de que forma ocorre a classificação e como o desempenho pode ser avaliado.

A separação entre machine learning, redes neurais e deep learning também ficou mais clara. O machine learning tradicional foi associado à seleção manual de características, enquanto o deep learning foi apresentado como uma abordagem capaz de aprender representações diretamente dos dados.

Entretanto, alguns problemas ainda permaneceram:
- A resposta afirmou que o deep learning aprende sem intervenção humana, ignorando decisões relacionadas à seleção dos dados, arquitetura, hiperparâmetros e validação;
- O valor de 98,35% foi apresentado sem contexto metodológico;
- CNN, LSTM e outras arquiteturas foram descritas como naturalmente eficazes ou ideais, sem considerar as características de cada dataset;
- A explicação de precisão e recall ficou pouco clara;
- A acurácia foi apresentada sem discutir sua limitação em datasets desbalanceados;
- A relação entre desbalanceamento e overfitting foi simplificada;
- Os exemplos de análise humana foram limitados e não incluíram revisão de casos ambíguos, investigação de incidentes e atualização dos modelos;
- Ainda foram utilizados termos do português europeu, como “treino”, “utilizador”, “ecrã” e “detetar”.

Assim, o prompt aprimorado foi eficiente para melhorar a organização e a profundidade da resposta, mas os resultados ainda precisam ser verificados nas fontes e revisados criticamente antes de serem utilizados no miniguia.

## Prompt 5 — Limitações dos sistemas automáticos de detecção de phishing

### Versão inicial

> Quais são as limitações da detecção automática de phishing?

### Problema encontrado

A resposta obtida com o prompt inicial identificou limitações
importantes, como problemas nos datasets, dificuldade de detectar
ataques desconhecidos, custo computacional e falta de explicabilidade.

Entretanto, a análise permaneceu ampla e pouco sistemática.

Foram identificados os seguintes problemas:
- Métodos baseados em listas, heurísticas, machine learning, redes neurais e deep learning não foram comparados de forma estruturada;
- Limitações relacionadas aos dados, aos modelos, à implantação e ao fator humano foram apresentadas no mesmo nível;
- Falsos positivos e falsos negativos não foram relacionados aos diferentes métodos de detecção;
- Vazamento entre treinamento e teste e falta de validação temporal receberam pouca atenção;
- A resposta não diferenciou suficientemente análise textual, análise de URLs e análise de páginas;
- Não foram apresentadas formas de mitigação para todas as limitações;
- Algumas afirmações sobre ataques zero-day e deep learning foram excessivamente otimistas;
- Valores e estatísticas foram apresentados sem contexto metodológico;
- Não ficou claro qual documento sustentava cada afirmação;
- A importância da análise humana foi mencionada, mas não foi relacionada a situações concretas de uso.

### Versão aprimorada

> Com base exclusivamente nas fontes selecionadas, analise criticamente as limitações dos sistemas automáticos de detecção de phishing.

> Diferencie, quando possível:
> 1. Métodos baseados em listas de bloqueio;
> 2. Métodos baseados em regras e heurísticas;
> 3. Métodos de machine learning;
> 4. Redes neurais;
> 5. Métodos de deep learning;
> 6. Análise textual com processamento de linguagem natural;
> 7. Análise de URLs, páginas e metadados.
>
> Considere as seguintes limitações:
> - Falsos positivos;
> - Falsos negativos;
> - Detecção de ataques novos ou desconhecidos;
> - Mudança dos padrões de ataque ao longo do tempo;
> - Dependência da qualidade dos datasets;
> - Desbalanceamento das classes;
> - Dados duplicados;
> - Vazamento entre dados de treinamento e teste;
> - Falta de validação temporal;
> - Necessidade de engenharia manual de características;
> - Custo computacional;
> - Tempo de treinamento;
> - Interpretabilidade dos modelos;
> - Privacidade dos dados analisados;
> - Dificuldade para compreender contexto e intenção;
> - Dependência de análise humana.
>
> Para cada limitação, informe:
> 1. Em que tipo de método ela aparece;
> 2. Qual impacto pode causar;
> 3. Se as fontes apresentam alguma forma de mitigação;
> 4. Qual documento sustenta a informação.
>
> Ao final, responda:
> - Por que uma alta acurácia isolada não garante que o sistema seja confiável?
> - Em quais situações a decisão humana continua necessária?
> - Quais lacunas ainda permanecem abertas?
>
> Não compare valores de desempenho de estudos diferentes sem considerar dataset, divisão dos dados, métricas e metodologia de validação.

### Alterações realizadas

Para produzir uma análise mais crítica e comparável, foram realizadas
as seguintes alterações no prompt:
- Restrição da resposta exclusivamente às fontes selecionadas;
- Solicitação de diferenciação entre listas de bloqueio, regras, heurísticas, machine learning, redes neurais e deep learning;
- Separação entre análise textual e análise de URLs, páginas e metadados;
- Definição prévia das limitações que deveriam ser investigadas;
- Inclusão explícita de falsos positivos e falsos negativos;
- Inclusão de problemas relacionados à qualidade e ao desbalanceamento dos datasets;
- Inclusão de dados duplicados e vazamento entre treinamento e teste;
- Solicitação de análise da validação temporal;
- Inclusão de custo computacional, tempo de treinamento e interpretabilidade;
- Inclusão da privacidade dos dados e da dificuldade de interpretar contexto e intenção;
- Solicitação de identificação dos métodos afetados por cada limitação;
- Solicitação dos impactos e das possíveis formas de mitigação;
- Exigência de indicação do documento que sustenta cada informação;
- Inclusão de questões críticas sobre acurácia, decisão humana e lacunas de pesquisa;
- Orientação para evitar comparações diretas entre resultados obtidos com datasets e metodologias diferentes.

### Resultado

A resposta obtida com o prompt aprimorado apresentou uma análise mais estruturada do que a resposta inicial.

Foi criada uma comparação contendo:
- Limitação analisada;
- Métodos afetados;
- Possível impacto;
- Forma de mitigação;
- Fonte correspondente.

A resposta abordou limitações relacionadas a:
- Falsos positivos e falsos negativos;
- Ataques novos ou desconhecidos;
- Mudanças temporais nos padrões de phishing;
- Qualidade e desbalanceamento dos dados;
- Dados duplicados e vazamento entre treinamento e teste;
- Engenharia manual de características;
- Custo computacional;
- Tempo de treinamento;
- Falta de interpretabilidade;
- Dificuldade de compreender contexto e intenção.

Também foram apresentadas diferenças gerais entre:
- Listas de bloqueio;
- Métodos heurísticos;
- Machine learning tradicional;
- Deep learning;
- Análise de URLs e metadados.

Na conclusão, a resposta explicou que uma acurácia elevada pode ser enganosa quando o dataset está desbalanceado ou quando existe vazamento entre treinamento e teste.

Também foram indicadas situações em que analistas humanos continuam necessários, como a revisão de casos ambíguos, ataques direcionados e resultados de baixa confiança.

Por fim, foram identificadas lacunas relacionadas a ataques zero-day, qualidade dos datasets, privacidade, explicabilidade e custo computacional.

### Avaliação

O prompt aprimorado foi mais eficiente porque orientou o NotebookLM a relacionar cada limitação aos métodos afetados, aos impactos e às possíveis formas de mitigação.

A inclusão de problemas metodológicos, como dados duplicados, desbalanceamento e vazamento entre treinamento e teste, também tornou a análise mais crítica. A resposta deixou de tratar o desempenho dos modelos apenas como uma questão de escolha do algoritmo e passou a considerar a qualidade da avaliação experimental.

A explicação sobre a acurácia foi outro ponto positivo. A resposta reconheceu que um resultado elevado pode ser artificialmente favorecido por datasets desbalanceados ou pela presença de dados semelhantes no treinamento e no teste.

Entretanto, a resposta não atendeu integralmente a todos os elementos solicitados pelo prompt.

## Prompt 6 — Técnicas para prevenir e reduzir os impactos do phishing

### Versão inicial

> Quais técnicas podem prevenir ataques de phishing?

### Problema encontrado

A resposta obtida com o prompt inicial identificou diferentes medidas de proteção, como autenticação multifator, filtros de e-mail, treinamento de usuários e planos de resposta a incidentes.

Entretanto, as medidas foram apresentadas de maneira ampla e sem uma classificação suficientemente precisa.

Foram identificados os seguintes problemas:
- Prevenção, detecção, mitigação e resposta a incidentes foram apresentadas como se fossem atividades equivalentes;
- Não ficou claro em que momento cada técnica atua;
- As responsabilidades de usuários, equipes de segurança, administradores e organizações não foram diferenciadas;
- As vantagens foram apresentadas com mais destaque do que as limitações;
- Estatísticas de eficácia foram mencionadas sem contexto metodológico;
- Diferentes métodos de autenticação multifator foram tratados como se apresentassem o mesmo nível de proteção;
- Algumas medidas, como análise comportamental e resposta a incidentes, foram classificadas como prevenção, embora geralmente atuem após a tentativa ou o comprometimento;
- Não foi apresentada uma estratégia em camadas suficientemente estruturada;
- A colaboração entre sistemas automáticos e analistas humanos recebeu pouca atenção;
- Não ficou claro qual fonte sustentava cada técnica ou afirmação.

### Versão aprimorada

> Com base exclusivamente nas fontes selecionadas, identifique as principais técnicas utilizadas para prevenir e reduzir os impactos de ataques de phishing.
>
> Organize as técnicas nas seguintes categorias:
> 1. Medidas voltadas ao usuário;
> 2. Medidas organizacionais;
> 3. Medidas técnicas;
> 4. Autenticação e controle de acesso;
> 5. Detecção e filtragem;
> 6. Resposta a incidentes;
> 7. Políticas e processos;
> 8. Colaboração entre humanos e sistemas de inteligência artificial.
>
> Para cada técnica, informe:
> - Nome;
> - Funcionamento;
> - Problema que busca reduzir;
> - Responsável pela aplicação;
> - Vantagens;
> - Limitações;
> - Exemplo de uso;
> - Fonte correspondente.
>
> Inclua, quando sustentadas pelas fontes, medidas como:
> - Educação e conscientização;
> - Simulações de phishing;
> - Verificação de remetentes e URLs;
> - Filtros de e-mail;
> - Ferramentas anti-phishing;
> - Machine learning;
> - Processamento de linguagem natural;
> - Autenticação multifator;
> - Políticas de senhas;
> - Monitoramento comportamental;
> - Canais seguros de comunicação;
> - Planos de resposta a incidentes;
> - Denúncia e compartilhamento de ameaças.
>
> Ao final:
> 1. Diferencie prevenção, detecção e resposta;
> 2. Explique por que nenhuma técnica isolada oferece proteção completa;
> 3. Proponha uma estratégia em camadas baseada nas fontes;
> 4. Indique quais medidas dependem mais da tecnologia e quais dependem mais do comportamento humano.
>
> Não apresente uma medida como totalmente eficaz quando as fonte indicarem limitações.

### Alterações realizadas

Para produzir uma resposta mais organizada e crítica, foram realizadas
as seguintes alterações no prompt:
- Restrição do conteúdo exclusivamente às fontes selecionadas;
- Separação das medidas em categorias humanas, técnicas, organizacionais e operacionais;
- Inclusão de autenticação e controle de acesso como uma categoria específica;
- Separação entre detecção, filtragem e resposta a incidentes;
- Inclusão de políticas, processos e canais de comunicação;
- Solicitação de uma seção dedicada à colaboração entre analistas humanos e sistemas de inteligência artificial;
- Definição de informações obrigatórias para cada técnica, incluindo funcionamento, responsável, vantagens e limitações;
- Solicitação da fonte correspondente para cada medida;
- Inclusão explícita de educação, simulações, filtros, machine learning, NLP, MFA e monitoramento comportamental;
- Solicitação da diferenciação entre prevenção, detecção e resposta;
- Inclusão de uma estratégia de proteção em camadas;
- Solicitação da diferenciação entre medidas mais dependentes de tecnologia e medidas mais dependentes do comportamento humano;
- Orientação para não apresentar nenhuma técnica como totalmente eficaz.

### Resultado

A resposta obtida com o prompt aprimorado apresentou uma estrutura mais abrangente e organizada do que a resposta inicial.

As medidas foram distribuídas em oito categorias:
1. Medidas voltadas ao usuário;
2. Medidas organizacionais;
3. Medidas técnicas;
4. Autenticação e controle de acesso;
5. Detecção e filtragem;
6. Resposta a incidentes;
7. Políticas e processos;
8. Colaboração entre humanos e inteligência artificial.

Foram abordadas técnicas como:
- Educação e conscientização;
- Verificação de remetentes e URLs;
- Simulações de phishing;
- Denúncia de ameaças;
- Ferramentas e extensões anti-phishing;
- Autenticação multifator;
- Certificados de dispositivos;
- Políticas de senhas;
- Filtros de e-mail;
- Machine learning e deep learning;
- Processamento de linguagem natural;
- Monitoramento comportamental;
- Planos de resposta a incidentes;
- Canais seguros de comunicação;
- Sistemas de inteligência artificial explicável.

A resposta também apresentou uma estratégia em camadas composta por filtragem, autenticação, treinamento, monitoramento e resposta a incidentes.

Na conclusão, houve uma tentativa de diferenciar prevenção, detecção e resposta, além de identificar medidas mais dependentes de tecnologia e medidas mais dependentes da participação humana.

### Avaliação

O prompt aprimorado foi mais eficiente porque orientou o NotebookLM a apresentar a proteção contra phishing como uma combinação de técnicas, processos e responsabilidades.

A organização por categorias ajudou a demonstrar que a segurança não depende apenas de filtros automáticos ou da atenção dos usuários. Também foi positivo incluir uma estratégia em camadas e uma seção voltada à colaboração entre pessoas e inteligência artificial.

Entretanto, a resposta não cumpriu integralmente todos os requisitos do prompt e ainda apresentou problemas conceituais e de documentação.