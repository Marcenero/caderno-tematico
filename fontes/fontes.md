# Fontes utilizadas

| Nº | Fonte | Tipo | Principal contribuição |
|---:|---|---|---|
| 1 | A Briefed Review on Phishing Attacks and Detection Approaches | Artigo de revisão | Fundamentos, tipos, prevenção e detecção |
| 2 | Deep Learning for Phishing Detection: Taxonomy, Current Challenges and Future Directions | Revisão sistemática | Deep learning, taxonomia, desafios e pesquisas futuras |
| 3 | Anti-Phishing Techniques – A Review of Cyber Defense Mechanisms | Artigo de revisão | Mecanismos anti-phishing e estratégias de defesa |
| 4 | Machine Learning and Neural Networks for Phishing Detection: A Systematic Review (2017–2024) | Revisão sistemática | Machine learning, redes neurais, dados, métricas e limitações |
| 5 | Social Engineering Attacks: Trends, Detection, and Prevention | Artigo de revisão | Engenharia social, fator humano, IA e prevenção |

## Fonte 1 - A Briefed Review on Phishing Attacks and Detection Approaches

### Motivo da escolha

Esta fonte foi escolhida por apresentar uma introdução ampla aos ataques de phishing, abordando seu funcionamento, sua relação com a engenharia social, os principais tipos de ataque e algumas estratégias de prevenção e detecção.

O artigo também apresenta exemplos de phishing por e-mail, páginas falsas, links maliciosos e ataques direcionados, sendo adequado para construir uma visão inicial do tema.

### Contribuição esperada

A fonte será utilizada para construir a parte introdutória do miniguia, especialmente nas seções relacionadas a:

- Definição de phishing;
- Funcionamento geral de um ataque;
- Relação entre phishing e engenharia social;
- Principais tipos de phishing;
- Sinais comuns de mensagens e páginas fraudulentas;
- Introdução aos métodos de prevenção e detecção.

Também poderá servir como base para a elaboração do glossário, fornecendo conceitos como phishing por e-mail, spear phishing, falsificação de sites e técnicas baseadas em URLs.

### Limitações iniciais

O artigo apresenta uma revisão breve e predominantemente descritiva. Embora mencione técnicas de machine learning e deep learning, não aprofunda a implementação, o treinamento ou a avaliação desses modelos.

Além disso, o trabalho não descreve um protocolo sistemático detalhado para a seleção dos estudos analisados. Alguns dados e exemplos utilizados também correspondem a períodos anteriores, devendo ser comparados com fontes mais recentes antes de serem apresentados como representativos do cenário atual.

## Fonte 2 - Deep Learning for Phishing Detection: Taxonomy, Current Challenges and Future Directions

### Motivo da escolha

Esta fonte foi escolhida por apresentar uma revisão sistemática especificamente direcionada ao uso de deep learning na detecção de phishing.

O artigo analisa 81 trabalhos, propõe uma taxonomia das técnicas utilizadas e discute vantagens, desvantagens, desafios atuais e possíveis direções para pesquisas futuras. Também diferencia abordagens tradicionais de machine learning de modelos de deep learning, destacando questões como extração automática de características, ajuste de parâmetros, tempo de treinamento e precisão.

### Contribuição esperada

A fonte será uma das principais bases técnicas do projeto e será utilizada para:

- Explicar o conceito de deep learning;
- Diferenciar inteligência artificial, machine learning e deep learning;
- Apresentar arquiteturas usadas na detecção de phishing;
- Analisar vantagens e desvantagens dos modelos;
- Explicar a extração automática de características;
- Discutir custo computacional e tempo de treinamento;
- Apresentar dificuldades na detecção de ataques desconhecidos;
- Identificar desafios e oportunidades de pesquisa.

O artigo também contribuirá para a seção de limitações da detecção automática e para a comparação entre métodos tradicionais de machine learning e modelos de deep learning.

### Limitações iniciais

Apesar de ser uma revisão sistemática abrangente, o artigo concentra-se principalmente em deep learning. Portanto, aspectos relacionados ao comportamento humano, conscientização, políticas organizacionais e prevenção não técnica recebem menor atenção.

O conjunto principal de trabalhos revisados corresponde ao período entre 2018 e 2021. Dessa forma, técnicas mais recentes, como aplicações modernas de modelos de linguagem e IA generativa, não são abordadas de maneira aprofundada.

Além disso, os estudos comparados utilizam diferentes datasets, métricas e estratégias de validação. Por esse motivo, os resultados de desempenho não devem ser comparados apenas com base na acurácia informada.

## Fonte 3 - Anti-Phishing Techniques: A Review of Cyber Defense Mechanisms

### Motivo da escolha

Esta fonte foi selecionada por concentrar sua análise nos mecanismos utilizados para detectar e prevenir ataques de phishing.

O artigo apresenta conceitos introdutórios sobre phishing, destaca a importância da conscientização dos usuários e descreve diferentes tecnologias anti-phishing, incluindo ferramentas de navegador, sistemas de alerta e algoritmos de detecção.

### Contribuição esperada

A fonte será utilizada principalmente na seção de prevenção e defesa do miniguia, apoiando a discussão sobre:

- Ferramentas anti-phishing;
- Sistemas de alerta;
- Verificação de mensagens e links;
- Proteções incorporadas a navegadores;
- Algoritmos de detecção;
- Educação e conscientização dos usuários;
- Identificação de características suspeitas em e-mails;
- Combinação entre medidas técnicas e comportamento seguro.

Também será útil para diferenciar três momentos de proteção:
1. Prevenção do ataque;
2. Detecção de uma tentativa;
3. Alerta e orientação ao usuário.

### Limitações iniciais

O artigo apresenta uma visão geral dos mecanismos de defesa, mas não descreve detalhadamente como os algoritmos são implementados, treinados ou avaliados.

A metodologia de revisão também não apresenta, de maneira aprofundada, as bases consultadas, os critérios de seleção dos estudos ou um processo sistemático de avaliação da qualidade das referências.

Algumas conclusões sobre a eficácia das técnicas são apresentadas de forma ampla. Por isso, devem ser complementadas pelas revisões sistemáticas mais detalhadas presentes nas outras fontes.

## Fonte 4 - Machine Learning and Neural Networks for Phishing Detection: A Systematic Review (2017–2024)

### Motivo da escolha

Esta fonte foi escolhida por apresentar uma revisão sistemática recente e abrangente sobre machine learning e redes neurais aplicados à detecção de phishing.

O artigo organiza os estudos de acordo com diferentes canais de propagação, incluindo:

- Websites;
- E-mails;
- Redes sociais;
- Malware.

Além dos algoritmos, a revisão analisa questões metodológicas importantes, como qualidade dos dados, desbalanceamento das classes, risco de vazamento entre treinamento e teste, validação temporal, escolha de modelos e métricas de avaliação.

### Contribuição esperada

Esta será uma das fontes técnicas centrais do projeto. Ela será utilizada para:

- Apresentar métodos de machine learning;
- Explicar o uso de redes neurais;
- Identificar características extraídas de URLs, páginas, mensagens e metadados;
- Discutir classificação e métodos ensemble;
- Explicar engenharia de características;
- Apresentar métricas como precisão, recall, F1-score e acurácia;
- Discutir desbalanceamento de classes;
- Explicar vazamento de dados;
- Analisar validação temporal;
- Discutir a generalização para ataques novos;
- Identificar desafios para implantação de modelos em sistemas reais.

A fonte também permitirá demonstrar por que uma acurácia elevada, isoladamente, não é suficiente para comprovar a confiabilidade de um detector.

### Limitações iniciais

Por ser uma revisão sistemática, o artigo consolida e avalia resultados de outros estudos, mas não representa a implementação de um único sistema completo de detecção.

O trabalho analisa publicações do período de 2017 a 2024. Dessa forma, pesquisas publicadas depois desse intervalo não fazem parte do conjunto principal avaliado.

Além disso, a amplitude do artigo — que envolve diversos canais de phishing, datasets e técnicas — faz com que algumas arquiteturas sejam apresentadas de forma comparativa, sem detalhar completamente sua implementação.

Os resultados dos estudos também são heterogêneos. Portanto, qualquer comparação entre modelos deverá considerar o dataset, a divisão dos dados, as métricas e o procedimento de validação adotado.

## Fonte 5 - Social Engineering Attacks: Trends, Detection, and Prevention

### Motivo da escolha

Esta fonte foi escolhida para complementar a perspectiva técnica dos outros artigos com uma análise voltada ao fator humano e à engenharia social.

O artigo aborda como os atacantes exploram sentimentos e comportamentos como confiança, medo, curiosidade, autoridade e urgência. Também apresenta diferentes ataques de engenharia social, incluindo phishing, spear phishing, pretexting, baiting e vishing.

Além disso, discute o uso de inteligência artificial, machine learning, processamento de linguagem natural, deepfakes, análise comportamental, autenticação multifator e treinamento de usuários.

### Contribuição esperada

A fonte será utilizada para:

- Definir engenharia social;
- Explicar sua relação com phishing;
- Diferenciar phishing de outras formas de manipulação;
- Identificar elementos psicológicos usados nos ataques;
- Discutir o uso de IA e deepfakes pelos criminosos;
- Apresentar o uso de NLP na identificação de mensagens suspeitas;
- Analisar a importância da conscientização e do treinamento;
- Discutir autenticação multifator;
- Apresentar análise comportamental e monitoramento de usuários;
- Defender uma estratégia de segurança em camadas;
- Mostrar a necessidade de colaboração entre humanos e sistemas automatizados.

A fonte será especialmente importante para demonstrar que soluções exclusivamente tecnológicas não eliminam os riscos associados à manipulação humana.

### Limitações iniciais

O artigo apresenta uma visão ampla sobre engenharia social, mas possui extensão reduzida e não aprofunda a implementação dos modelos de inteligência artificial mencionados.

Embora o trabalho declare utilizar revisão de literatura e análise de casos, sua metodologia é descrita de maneira resumida. Não são detalhados com precisão:

- As bases acadêmicas pesquisadas;
- Os termos de busca utilizados;
- Os critérios de inclusão e exclusão;
- A quantidade de documentos inicialmente encontrados;
- O processo de avaliação da qualidade dos estudos.

O artigo também apresenta diversas porcentagens, exemplos e afirmações de eficácia. Antes de utilizar esses números no miniguia, será importante consultar e verificar as referências originais citadas pelos autores.