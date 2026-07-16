# Inteligência Artificial Aplicada à Detecção de Phishing e Golpes de Engenharia Social

## Sobre o projeto

Este repositório apresenta um caderno temático sobre o uso de técnicas de inteligência artificial na identificação de phishing, mensagens fraudulentas e golpes de engenharia social.

O projeto foi desenvolvido com o apoio do NotebookLM, utilizando fontes abertas previamente selecionadas. A ferramenta foi utilizada para comparar documentos, esclarecer conceitos, produzir resumos e analisar como a inteligência artificial pode auxiliar na detecção de mensagens suspeitas.

Além do conteúdo estudado, o repositório documenta o processo de elaboração e aprimoramento dos prompts, incluindo dificuldades encontradas, respostas incompletas e ajustes realizados para obter resultados mais precisos.

---

# 1. Contexto e objetivos

## 1.1 Contexto

Com o aumento do uso de aplicativos de mensagens, redes sociais, plataformas de comércio eletrônico e serviços bancários digitais, as tentativas de golpes pela internet tornaram-se mais frequentes e sofisticadas.

Golpes de phishing e engenharia social utilizam técnicas de manipulação para convencer usuários a fornecer senhas, dados pessoais, códigos de autenticação ou realizar transferências financeiras.

Essas abordagens costumam explorar sentimentos como medo, urgência, curiosidade e confiança. Em muitos casos, os criminosos também utilizam o nome de empresas, bancos, instituições públicas ou pessoas conhecidas para tornar as mensagens mais convincentes.

Nesse contexto, a inteligência artificial pode auxiliar na análise de mensagens, identificação de padrões suspeitos e geração de alertas para os usuários.

## 1.2 Pergunta de estudo

> Como a inteligência artificial pode identificar características linguísticas e técnicas presentes em mensagens de phishing e golpes de engenharia social?

## 1.3 Objetivo geral

Investigar como técnicas de inteligência artificial podem ser utilizadas para identificar mensagens fraudulentas e auxiliar na prevenção de golpes digitais.

## 1.4 Objetivos específicos

* Compreender os conceitos de phishing e engenharia social;
* Identificar características comuns em mensagens fraudulentas;
* Estudar como o processamento de linguagem natural pode analisar mensagens suspeitas;
* Compreender como sistemas classificam textos como legítimos ou fraudulentos;
* Investigar o uso de OCR na análise de capturas de tela;
* Analisar as vantagens e limitações da inteligência artificial;
* Compreender os riscos de falsos positivos e falsos negativos;
* Investigar como criminosos também podem utilizar inteligência artificial;
* Criar materiais para futuras revisões sobre o tema.

---

# 2. Curadoria de fontes

Foram selecionadas fontes abertas em formato de artigo, página informativa ou PDF.

Os materiais foram adicionados ao NotebookLM e utilizados como base para as perguntas, respostas e análises apresentadas neste projeto.

| Fonte   | Autor ou instituição | Tipo              | Link         | Motivo da escolha                          |
| ------- | -------------------- | ----------------- | ------------ | ------------------------------------------ |
| Fonte 1 | Nome da instituição  | Artigo ou PDF     | Inserir link | Apresenta os fundamentos do phishing       |
| Fonte 2 | Nome da instituição  | Relatório         | Inserir link | Apresenta dados sobre golpes digitais      |
| Fonte 3 | Nome da instituição  | Artigo científico | Inserir link | Explica o uso de IA na detecção de ameaças |
| Fonte 4 | Nome da instituição  | Guia              | Inserir link | Apresenta práticas de prevenção            |
| Fonte 5 | Nome da instituição  | Relatório ou PDF  | Inserir link | Discute limitações e riscos da IA          |

## 2.1 Critérios de seleção

As fontes foram selecionadas de acordo com os seguintes critérios:

* Disponibilidade pública;
* Confiabilidade do autor ou da instituição;
* Relação direta com o tema;
* Clareza das explicações;
* Presença de informações técnicas;
* Complementaridade entre os materiais;
* Atualidade das informações.

A descrição completa das fontes utilizadas está disponível em [`fontes/fontes.md`](fontes/fontes.md).

---

# 3. Engenharia de prompts

A utilização do NotebookLM foi realizada de forma progressiva.

Inicialmente, foram elaboradas perguntas gerais para compreender os conceitos presentes nas fontes. Em seguida, os prompts foram aprimorados com instruções mais específicas sobre estrutura, referências, nível de profundidade e formato da resposta.

## 3.1 Perguntas iniciais

Algumas das primeiras perguntas utilizadas foram:

```text
O que é phishing?
```

```text
Quais são os principais tipos de golpes digitais?
```

```text
Como a inteligência artificial pode detectar mensagens fraudulentas?
```

```text
Quais são os principais sinais de uma mensagem de phishing?
```

Essas perguntas foram úteis para obter uma visão geral do conteúdo. Entretanto, algumas respostas apresentaram explicações muito amplas ou pouco organizadas.

As perguntas iniciais estão documentadas em [`prompts/perguntas-iniciais.md`](prompts/perguntas-iniciais.md).

---

## 3.2 Prompts aprimorados

Após analisar as primeiras respostas, foram elaboradas versões mais detalhadas.

### Prompt para identificar sinais de phishing

```text
Com base exclusivamente nas fontes fornecidas, identifique os principais
sinais linguísticos e técnicos presentes em mensagens de phishing.

Organize a resposta nas seguintes categorias:

1. Linguagem utilizada;
2. Identidade do remetente;
3. Links e anexos;
4. Solicitações feitas à vítima;
5. Técnicas psicológicas;
6. Informações solicitadas.

Apresente um exemplo fictício para cada categoria e indique as fontes
utilizadas.
```

### Prompt para estudar o uso da inteligência artificial

```text
Com base nas fontes fornecidas, explique como a inteligência artificial
pode ser utilizada na detecção de phishing e golpes de engenharia social.

Apresente:

1. Técnicas utilizadas;
2. Dados que podem ser analisados;
3. Possíveis resultados do sistema;
4. Vantagens;
5. Limitações;
6. Riscos de falsos positivos e falsos negativos;
7. Situações que ainda exigem análise humana.

Indique as fontes utilizadas em cada parte da resposta.
```

### Prompt para comparação

```text
Compare a atuação da inteligência artificial na criação e na detecção
de golpes digitais.

Organize a resposta em uma tabela contendo:

- Forma de utilização;
- Técnicas envolvidas;
- Benefícios para quem utiliza;
- Riscos;
- Formas de mitigação;
- Referências encontradas nas fontes.
```

### Prompt para verificar uma afirmação

```text
Analise a seguinte afirmação:

"A inteligência artificial é capaz de identificar qualquer tentativa
de phishing."

Informe:

1. Se a afirmação é verdadeira, parcialmente verdadeira ou falsa;
2. Quais fontes sustentam a análise;
3. Quais são as principais limitações;
4. Em quais situações a análise humana ainda é necessária.

Não utilize informações externas às fontes.
```

Os prompts aprimorados estão disponíveis em [`prompts/prompts-aprimorados.md`](prompts/prompts-aprimorados.md).

---

# 4. Cicatrizes e troubleshooting

Esta seção registra as dificuldades encontradas durante o uso do NotebookLM e os ajustes realizados nos prompts.

O objetivo é mostrar que os resultados não foram obtidos apenas por meio de uma única pergunta, mas por um processo de análise, teste e melhoria.

| Tentativa | Problema encontrado             | Possível causa                     | Ajuste realizado                                  | Resultado                           |
| --------- | ------------------------------- | ---------------------------------- | ------------------------------------------------- | ----------------------------------- |
| 1         | Resposta muito genérica         | Pergunta ampla                     | Foram definidos tópicos obrigatórios              | Resposta mais estruturada           |
| 2         | Ausência de referências         | O prompt não solicitava as fontes  | Foi adicionada a solicitação de referências       | Resposta mais verificável           |
| 3         | Informações além dos documentos | Falta de restrição                 | Foi incluído “com base exclusivamente nas fontes” | Maior fidelidade aos documentos     |
| 4         | Explicação muito técnica        | Público-alvo não definido          | Foi solicitada linguagem para iniciantes          | Explicação mais acessível           |
| 5         | Resposta muito longa            | Não havia limite de tamanho        | Foi definido um número máximo de palavras         | Resposta mais adequada para revisão |
| 6         | Comparação pouco clara          | Formato não especificado           | Foi solicitada uma tabela comparativa             | Resultado mais organizado           |
| 7         | Falta de análise crítica        | Pergunta buscava apenas definições | Foram solicitadas limitações e riscos             | Resposta mais completa              |

## 4.1 Exemplo de evolução de prompt

### Primeira versão

```text
Como a IA detecta golpes?
```

### Problema encontrado

A resposta apresentou apenas uma visão geral, sem explicar as técnicas utilizadas, os dados analisados ou as limitações do processo.

### Segunda versão

```text
Com base exclusivamente nas fontes fornecidas, explique como sistemas
de inteligência artificial podem detectar mensagens de phishing.

Apresente:

1. Dados de entrada;
2. Técnicas de processamento;
3. Características analisadas;
4. Forma de classificação;
5. Resultado apresentado ao usuário;
6. Limitações do sistema;
7. Referências utilizadas.
```

### Resultado após o ajuste

A nova resposta apresentou uma sequência mais clara do funcionamento de um possível sistema, desde a entrada da mensagem até a classificação do risco.

Também foram identificadas limitações que não haviam aparecido na primeira resposta.

## 4.2 Aprendizados obtidos

Os testes mostraram que os prompts produziram melhores resultados quando apresentavam:

* Um objetivo claro;
* Uma definição do público-alvo;
* Uma estrutura esperada;
* Limites de tamanho;
* Solicitação de exemplos;
* Solicitação de referências;
* Restrição ao conteúdo das fontes;
* Orientação para indicar informações ausentes;
* Solicitação de vantagens e limitações.

O registro completo está disponível em [`prompts/cicatrizes-e-troubleshooting.md`](prompts/cicatrizes-e-troubleshooting.md).

---

# 5. Miniguia de estudo

O miniguia representa a entrega consolidada do projeto.

Ele reúne os principais conceitos encontrados nas fontes, as explicações produzidas durante o estudo e os materiais que podem ser utilizados em futuras revisões.

## 5.1 Resumo estruturado

O resumo está organizado nos seguintes tópicos:

1. Definição de phishing;
2. Engenharia social;
3. Tipos de golpes digitais;
4. Sinais de uma mensagem fraudulenta;
5. Processamento de linguagem natural;
6. Classificação de textos;
7. Uso de OCR;
8. Análise de links;
9. Pontuação de risco;
10. Limitações da inteligência artificial;
11. Prevenção de golpes.

O conteúdo está disponível em [`miniguia/resumo-estruturado.md`](miniguia/resumo-estruturado.md).

---

## 5.2 Glossário

O glossário reúne os principais termos encontrados durante o estudo.

| Termo                              | Definição                                                                              |
| ---------------------------------- | -------------------------------------------------------------------------------------- |
| Phishing                           | Tentativa de obter informações da vítima por meio de mensagens ou páginas fraudulentas |
| Smishing                           | Tipo de phishing realizado por SMS ou aplicativos de mensagens                         |
| Engenharia social                  | Manipulação de pessoas para obtenção de dados ou realização de ações                   |
| Processamento de Linguagem Natural | Área da IA dedicada à análise e interpretação da linguagem humana                      |
| Classificação de textos            | Processo de atribuir uma categoria a uma mensagem                                      |
| OCR                                | Tecnologia utilizada para extrair texto de imagens                                     |
| Falso positivo                     | Quando uma mensagem legítima é classificada como fraude                                |
| Falso negativo                     | Quando uma mensagem fraudulenta é classificada como legítima                           |
| Pontuação de risco                 | Valor utilizado para representar a probabilidade de uma mensagem ser perigosa          |
| Deepfake                           | Conteúdo de áudio, imagem ou vídeo manipulado ou gerado artificialmente                |

A versão completa está disponível em [`miniguia/glossario.md`](miniguia/glossario.md).

---

## 5.3 Prompts reutilizáveis

### Revisar um conceito

```text
Com base exclusivamente nas fontes fornecidas, explique [conceito].

Apresente:

1. Definição;
2. Funcionamento;
3. Exemplo;
4. Aplicações;
5. Limitações;
6. Referências utilizadas.
```

### Criar um resumo

```text
Produza um resumo de revisão sobre [tema] com no máximo 500 palavras.

Destaque:

- Definições;
- Conceitos principais;
- Etapas;
- Exemplos;
- Riscos;
- Limitações.
```

### Comparar conceitos

```text
Compare [conceito A] e [conceito B].

Apresente a resposta em uma tabela contendo:

- Definição;
- Características;
- Semelhanças;
- Diferenças;
- Exemplos;
- Limitações.
```

### Criar perguntas de revisão

```text
Crie dez perguntas sobre [tema].

Divida as perguntas nos níveis:

- Básico;
- Intermediário;
- Avançado.

Depois, apresente um gabarito comentado em uma seção separada.
```

### Verificar conhecimento

```text
Faça cinco perguntas sobre [tema], uma de cada vez.

Aguarde minha resposta antes de continuar.

Depois de cada resposta, informe:

1. O que está correto;
2. O que precisa ser corrigido;
3. Uma explicação baseada nas fontes;
4. A referência utilizada.
```

### Identificar lacunas

```text
Analise as fontes fornecidas e identifique:

1. Quais aspectos de [tema] são bem explicados;
2. Quais aspectos possuem informações insuficientes;
3. Quais pontos apresentam divergências;
4. Quais novas fontes seriam necessárias.

Não complete as lacunas com conhecimento externo.
```

A coleção completa está disponível em [`miniguia/prompts-reutilizaveis.md`](miniguia/prompts-reutilizaveis.md).

---

# 6. Principais aprendizados

O desenvolvimento deste projeto permitiu compreender tanto o tema estudado quanto o processo de interação com ferramentas de inteligência artificial.

Entre os principais aprendizados estão:

* Importância da seleção de fontes confiáveis;
* Necessidade de verificar as referências apresentadas;
* Influência da estrutura do prompt na resposta;
* Importância de definir o público-alvo;
* Necessidade de registrar tentativas que não funcionaram;
* Diferença entre respostas gerais e respostas orientadas;
* Limitações de sistemas de inteligência artificial;
* Importância da análise humana em decisões relacionadas à segurança.

---

# 7. Conclusão

A inteligência artificial pode auxiliar na detecção de phishing e golpes de engenharia social por meio da análise de textos, links, imagens e padrões presentes nas mensagens.

Entretanto, esses sistemas apresentam limitações e podem produzir classificações incorretas. Por esse motivo, devem ser utilizados como ferramentas de apoio, acompanhados de orientações de segurança e análise humana.

O uso do NotebookLM permitiu organizar as informações presentes nas fontes, comparar conceitos e produzir materiais para revisão. O processo também demonstrou que a qualidade das respostas depende da clareza dos prompts, da qualidade dos documentos e da análise crítica realizada pelo usuário.

---

# 8. Estrutura do repositório

```text
.
├── README.md
├── fontes/
│   └── fontes.md
├── prompts/
│   ├── perguntas-iniciais.md
│   ├── prompts-aprimorados.md
│   └── cicatrizes-e-troubleshooting.md
├── respostas/
│   ├── resposta-phishing.md
│   ├── resposta-engenharia-social.md
│   └── resposta-ia-na-deteccao.md
├── miniguia/
│   ├── resumo-estruturado.md
│   ├── glossario.md
│   └── prompts-reutilizaveis.md
└── assets/
    └── capturas-notebooklm/
```