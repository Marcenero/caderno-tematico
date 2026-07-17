# Resumo estruturado

## 1. Introdução

O phishing é uma forma de fraude que utiliza falsificação de identidade, manipulação psicológica e, em muitos casos, recursos técnicos para induzir pessoas a fornecer informações ou realizar ações prejudiciais.

Os ataques podem ocorrer por e-mail, mensagens de texto, chamadas, redes sociais e páginas falsas. Seus objetivos podem incluir o roubo de credenciais, dados pessoais, informações financeiras ou acesso a sistemas organizacionais.

Devido à grande quantidade de mensagens e páginas analisadas diariamente, sistemas automáticos passaram a ser utilizados para auxiliar na identificação de possíveis ataques. Entre esses sistemas estão abordagens baseadas em regras, listas de bloqueio, machine learning, redes neurais, deep learning e processamento de linguagem natural.

Este resumo apresenta os principais conceitos relacionados ao phishing, à engenharia social e ao uso de inteligência artificial na detecção desses ataques. Também são discutidas suas limitações e as principais medidas de prevenção.

---

## 2. Phishing

Phishing é uma tentativa de fraude na qual o atacante finge representar uma pessoa, empresa, instituição ou serviço confiável para induzir a vítima a fornecer informações ou realizar determinada ação.

As fontes apresentam definições com diferentes ênfases. Algumas destacam principalmente o engano e a falsificação de identidade, enquanto outras definem phishing como uma combinação de engenharia social e subterfúgio técnico.

Os pontos em comum entre as definições são:

- Uso do engano;
- Falsificação ou personificação de uma fonte confiável;
- Tentativa de influenciar a vítima;
- Busca por informações, acesso ou vantagem ilícita;
- Possível utilização de recursos técnicos.

### 2.1 Como funciona

Um ataque de phishing pode ser dividido, de forma geral, nas seguintes
etapas:

1. **Planejamento:** o atacante escolhe o alvo, o canal e o tipo de abordagem;

2. **Preparação:** são criadas mensagens, páginas, perfis ou arquivos fraudulentos;

3. **Distribuição:** o conteúdo é enviado por e-mail, SMS, chamada, rede social ou outro canal;

4. **Manipulação:** a vítima é pressionada ou convencida a realizar uma ação;

5. **Coleta:** informações são inseridas em uma página falsa, enviadas ao atacante ou capturadas por um programa malicioso;

6. **Uso das informações:** os dados podem ser empregados para acessar contas, realizar fraudes, comprometer sistemas ou atingir outras vítimas.

Nem todo ataque utiliza todas essas etapas. Alguns buscam apenas fazer com que a vítima forneça uma informação por mensagem ou telefone, enquanto outros utilizam páginas falsas, redirecionamentos e malware.

### 2.2 Principais sinais

Alguns sinais que podem indicar uma tentativa de phishing são:

- Solicitações inesperadas de informações pessoais;
- Mensagens que exigem ação imediata;
- Ameaças de bloqueio, cobrança ou perda de acesso;
- Ofertas ou recompensas incomuns;
- Remetentes ou domínios suspeitos;
- Links encurtados ou endereços semelhantes aos legítimos;
- Erros de escrita ou formatação;
- Anexos não solicitados;
- Pedidos de senha ou código de autenticação;
- Solicitações fora dos procedimentos habituais da organização.

Esses sinais não são provas definitivas. Ataques sofisticados podem utilizar linguagem correta, domínios convincentes e informações reais sobre a vítima.

### 2.3 Tipos de phishing

As fontes utilizam diferentes critérios para classificar os tipos de phishing.

#### Por canal

- **Phishing por e-mail:** utiliza mensagens fraudulentas enviadas por correio eletrônico;

- **Smishing:** utiliza SMS ou serviços de mensagens;

- **Vishing:** utiliza chamadas telefônicas ou serviços de voz;

- **Phishing em redes sociais:** utiliza perfis, publicações ou mensagens em plataformas sociais;

- **Phishing por website:** utiliza páginas fraudulentas para capturar informações.

#### Por nível de direcionamento

- **Phishing genérico:** enviado para grande número de pessoas, com pouca personalização;

- **Spear phishing:** direcionado a uma pessoa, grupo ou organização específica;

- **Whaling:** forma direcionada a pessoas em cargos de liderança ou com acesso privilegiado.

#### Por técnica

- **Clone phishing:** utiliza como base uma comunicação legítima, substituindo links ou anexos por versões maliciosas;

- **Phishing com página falsa:** utiliza uma página que imita um serviço legítimo;

- **Phishing com malware:** busca induzir a instalação ou execução de software malicioso.

Também existem mecanismos relacionados, como pharming, redes Wi-Fi falsas e redirecionamentos. Eles podem apoiar um ataque de phishing, mas não são necessariamente classificados da mesma maneira por todas as fontes.

### 2.4 Possíveis consequências

Para indivíduos, as consequências podem incluir:

- Roubo de identidade;
- Perdas financeiras;
- Comprometimento de contas;
- Exposição de informações privadas;
- Instalação de malware;
- Uso dos contatos da vítima em novos ataques.

Para organizações, podem ocorrer:

- Vazamento de informações;
- Acesso indevido a sistemas;
- Interrupção de serviços;
- Perda financeira;
- Danos à reputação;
- Custos de investigação e recuperação;
- Comprometimento de clientes e parceiros.

---

## 3. Engenharia social

Engenharia social é o conjunto de técnicas utilizadas para manipular o comportamento humano e induzir uma pessoa a fornecer informações, conceder acesso ou realizar determinada ação.

Trata-se de um conceito mais amplo do que phishing. A engenharia social pode ocorrer em ambientes digitais, por telefone ou presencialmente.

O phishing é uma forma de ataque que frequentemente aplica princípios da engenharia social por meio de mensagens, identidades falsas, links, páginas ou outros recursos técnicos.

Nem toda engenharia social é phishing. Técnicas como tailgating, baiting e pretexting podem ocorrer sem utilizar e-mail, SMS ou páginas fraudulentas.

### 3.1 Técnicas de manipulação

Entre as técnicas de engenharia social relacionadas ao tema estão:

- **Personificação:** fingir ser uma pessoa ou instituição confiável;

- **Pretexting:** criar uma história ou situação falsa para justificar uma solicitação;

- **Baiting:** oferecer algo atrativo para despertar a curiosidade da vítima;

- **Spear phishing:** utilizar informações específicas para tornar a abordagem mais convincente;

- **Autoridade falsa:** fingir ocupar um cargo ou representar um setor importante;

- **Pressão temporal:** reduzir o tempo disponível para que a vítima analise a solicitação.

### 3.2 Emoções exploradas

Ataques podem explorar diferentes emoções e tendências humanas, como:

- Urgência;
- Medo;
- Curiosidade;
- Confiança;
- Autoridade;
- Ganância;
- Solidariedade;
- Desejo de evitar prejuízo;
- Desejo de receber recompensa.

Esses elementos são combinados com recursos técnicos para tornar a mensagem mais convincente.

### 3.3 Relação entre engenharia social e tecnologia

A tecnologia amplia o alcance e a velocidade da engenharia social.

Informações publicadas em redes sociais podem ser utilizadas para personalizar mensagens. Ferramentas automáticas podem facilitar o envio em massa, a criação de páginas e a adaptação do conteúdo para diferentes grupos.

Por outro lado, a existência de recursos técnicos não elimina o papel da manipulação humana. Uma mensagem pode utilizar um site tecnicamente bem construído, mas ainda depender de confiança, medo ou urgência para convencer a vítima.

---

## 4. Inteligência artificial na detecção

A inteligência artificial pode auxiliar na detecção de phishing por meio da identificação de padrões em e-mails, textos, URLs, páginas, imagens e metadados.

Os sistemas podem ser treinados para classificar uma entrada como legítima, suspeita ou fraudulenta. O resultado também pode ser apresentado como uma probabilidade ou pontuação de risco.

### 4.1 Dados de entrada e preparação

Os principais tipos de dados analisados incluem:

- Corpo e assunto de e-mails;
- Cabeçalhos e informações do remetente;
- URLs;
- Código HTML e elementos da página;
- Imagens e capturas de tela;
- Certificados e dados de domínio;
- Informações de DNS;
- Metadados;
- Dados comportamentais.

Antes do treinamento, os dados podem passar por:

- Limpeza;
- Remoção de duplicatas;
- Tratamento de valores ausentes;
- Normalização;
- Rotulagem;
- Transformação de textos em representações numéricas;
- Separação entre treinamento, validação e teste.

A preparação inadequada pode provocar vazamento de dados e resultados artificialmente elevados.

### 4.2 Machine learning tradicional

Em machine learning tradicional, especialistas geralmente definem ou selecionam características que serão analisadas pelo modelo.

Exemplos de algoritmos incluem:

- Random Forest;
- Support Vector Machine;
- Regressão logística;
- Naive Bayes;
- Árvores de decisão;
- Métodos ensemble.

As características podem incluir comprimento da URL, presença de caracteres especiais, quantidade de subdomínios, palavras suspeitas e informações do remetente.

A eficácia depende da qualidade das características, dos dados e da metodologia de avaliação.

### 4.3 Redes neurais e deep learning

Redes neurais processam os dados por meio de camadas de unidades computacionais.

Deep learning utiliza arquiteturas com várias camadas, capazes de aprender representações complexas a partir dos dados.

Entre as arquiteturas mencionadas nas fontes estão:

- CNN;
- RNN;
- LSTM;
- GRU;
- Autoencoders;
- Modelos híbridos.

Essas técnicas podem reduzir parte da engenharia manual de características, mas ainda dependem de decisões humanas relacionadas a dados, arquitetura, parâmetros, treinamento e validação.

### 4.4 Processamento de linguagem natural

O processamento de linguagem natural pode analisar textos de e-mails, SMS e mensagens.

Entre os elementos analisados estão:

- Palavras e expressões;
- Estrutura das frases;
- Entidades mencionadas;
- Pedidos de informações;
- Linguagem de urgência ou ameaça;
- Semântica;
- Contexto;
- Similaridade com comunicações legítimas.

A análise não deve depender apenas de erros gramaticais, pois mensagens de phishing podem ser bem escritas.

### 4.5 Classificação de textos

Textos podem ser convertidos em representações numéricas e usados como entrada para classificadores.

O processo pode envolver:

1. Tokenização;
2. Remoção ou tratamento de elementos irrelevantes;
3. Stemming ou lematização;
4. Conversão em vetores;
5. Treinamento do modelo;
6. Classificação;
7. Geração de uma probabilidade ou alerta.

A classificação pode combinar texto com outras informações, como URL, remetente e metadados.

### 4.6 OCR

OCR é a sigla de *Optical Character Recognition*, ou Reconhecimento Óptico de Caracteres.

Essa tecnologia permite extrair texto de:

- Capturas de tela;
- Fotografias;
- Documentos digitalizados;
- Imagens recebidas por mensagens;
- Páginas que apresentam conteúdo textual como imagem.

Após a extração, o texto pode ser analisado por regras, NLP ou modelos de machine learning.

O OCR pode cometer erros quando a imagem possui baixa resolução, fontes incomuns, distorção ou elementos sobrepostos.

### 4.7 Análise de URLs, páginas e metadados

A análise de URLs pode considerar:

- Comprimento;
- Número de subdomínios;
- Caracteres especiais;
- Uso de endereço IP;
- Palavras suspeitas;
- Semelhança com domínios conhecidos;
- Uso de encurtadores;
- Informações do registro do domínio.

A análise de páginas pode considerar:

- Estrutura HTML;
- Elementos do DOM;
- Scripts;
- Formulários;
- Imagens;
- Similaridade visual;
- Redirecionamentos.

Os metadados podem incluir informações sobre certificados, DNS, registro de domínio e origem da mensagem.

Essas características podem ser manipuladas pelos atacantes, e serviços legítimos também podem apresentar alguns sinais semelhantes.

### 4.8 Métricas de avaliação

As principais métricas incluem:

- **Acurácia:** proporção total de classificações corretas;

- **Precisão:** entre os exemplos classificados como phishing, quantos realmente eram phishing;

- **Recall:** entre os ataques existentes, quantos foram detectados;

- **F1-score:** equilíbrio entre precisão e recall;

- **Taxa de falsos positivos:** proporção de exemplos legítimos classificados como fraudulentos;

- **Taxa de falsos negativos:** proporção de ataques classificados como legítimos.

Uma acurácia alta não garante confiabilidade quando o dataset está desbalanceado ou possui vazamento entre treinamento e teste.

### 4.9 Pontuação de risco

Em vez de apresentar apenas uma classificação binária, o sistema pode produzir uma pontuação de risco.

Essa pontuação pode considerar diferentes sinais, como:

- Conteúdo textual suspeito;
- Domínio desconhecido;
- URL semelhante à de uma marca;
- Solicitação de credenciais;
- Presença de urgência;
- Anexo incomum;
- Falta de correspondência entre remetente e organização.

A pontuação pode ser utilizada para:

- Exibir um alerta;
- Colocar a mensagem em quarentena;
- Bloquear o acesso;
- Solicitar revisão humana;
- Priorizar incidentes.

O significado da pontuação e o limiar utilizado devem ser explicados ao usuário ou analista.

---

## 5. Limitações

Sistemas automáticos podem reduzir o volume de ameaças, mas não são capazes de identificar corretamente todos os ataques.

As limitações podem estar relacionadas aos dados, aos modelos, à avaliação, à implantação e ao contexto humano.

### 5.1 Falsos positivos

Um falso positivo ocorre quando uma mensagem, página ou URL legítima é classificada como phishing.

Possíveis consequências:

- Bloqueio de comunicações legítimas;
- Perda de mensagens importantes;
- Sobrecarga de analistas;
- Desconfiança nos alertas;
- Fadiga dos usuários.

A redução dos falsos positivos pode envolver ajuste de limiares, combinação de diferentes sinais e revisão humana.

### 5.2 Falsos negativos

Um falso negativo ocorre quando um ataque é classificado como legítimo.

Possíveis consequências:

- Roubo de credenciais;
- Comprometimento de contas;
- Instalação de malware;
- Perda financeira;
- Acesso indevido a sistemas.

Ataques novos, direcionados ou muito semelhantes a mensagens legítimas podem aumentar o risco de falsos negativos.

### 5.3 Qualidade dos datasets

Os datasets podem apresentar:

- Dados antigos;
- Links inativos;
- Exemplos duplicados;
- Rótulos incorretos;
- Classes desbalanceadas;
- Pouca diversidade;
- Falta de exemplos reais;
- Problemas de privacidade.

Modelos treinados em dados inadequados podem apresentar bons resultados em testes, mas baixo desempenho em situações reais.

### 5.4 Vazamento e validação temporal

O vazamento de dados ocorre quando informações do conjunto de teste influenciam o treinamento ou a seleção do modelo.

Isso pode acontecer quando:

- A mesma URL aparece no treinamento e no teste;
- Dados do mesmo domínio são divididos entre os conjuntos;
- O pré-processamento utiliza todos os dados antes da divisão;
- O conjunto de teste influencia a escolha dos parâmetros.

A validação temporal busca avaliar o modelo com dados posteriores aos utilizados no treinamento, aproximando-se do cenário real.

### 5.5 Privacidade

A análise de e-mails, mensagens e comportamentos pode envolver dados pessoais, corporativos ou confidenciais.

Por isso, é necessário considerar:

- Finalidade da coleta;
- Permissão de acesso;
- Armazenamento seguro;
- Minimização dos dados;
- Compartilhamento;
- Anonimização;
- Tempo de retenção;
- Controle de acesso.

### 5.6 Mudança dos padrões de golpe

Os atacantes modificam constantemente:

- Linguagem;
- Domínios;
- Aparência das páginas;
- Canais de distribuição;
- Técnicas de redirecionamento;
- Formas de personalização.

Essa mudança pode reduzir o desempenho de modelos treinados com dados antigos. Esse fenômeno pode ser relacionado ao `concept drift`, ou mudança na distribuição dos dados ao longo do tempo.

### 5.7 Interpretabilidade

Alguns modelos, especialmente os mais complexos, podem apresentar dificuldade para explicar por que classificaram uma entrada como phishing.

A ausência de explicação pode dificultar:

- Revisão de decisões;
- Correção de erros;
- Confiança do usuário;
- Investigação de incidentes;
- Auditoria;
- Definição de ações de resposta.

### 5.8 Custo computacional

Modelos complexos podem exigir:

- Hardware especializado;
- Tempo elevado de treinamento;
- Grande quantidade de memória;
- Atualizações frequentes;
- Infraestrutura de implantação;
- Baixa latência para análise em tempo real.

A escolha do modelo deve considerar não apenas a qualidade da classificação, mas também sua viabilidade operacional.

### 5.9 Dependência de análise humana

A análise humana continua relevante em:

- Casos com baixa confiança;
- Ataques direcionados;
- Mensagens legítimas bloqueadas;
- Incidentes de alto impacto;
- Investigação de campanhas;
- Atualização de regras e datasets;
- Interpretação de alertas;
- Decisões sobre bloqueio ou liberação.

A IA deve ser apresentada como apoio à decisão, e não como substituição completa do julgamento humano.

---

## 6. Boas práticas de prevenção

A proteção contra phishing deve utilizar uma estratégia em camadas.

### 6.1 Medidas voltadas ao usuário

- Treinamento e conscientização;
- Verificação de remetentes e domínios;
- Confirmação de solicitações por canais oficiais;
- Cuidado com links e anexos;
- Denúncia de mensagens suspeitas;
- Uso de gerenciadores de senhas.

### 6.2 Medidas técnicas

- Filtros de e-mail;
- Ferramentas anti-phishing;
- Análise de links e anexos;
- Proteções de navegador;
- Antimalware;
- Sandboxing;
- Listas de bloqueio;
- Modelos de machine learning e deep learning.

### 6.3 Autenticação e controle de acesso

- Autenticação multifator;
- Controle de privilégios;
- Políticas de acesso;
- Certificados de dispositivos;
- Gerenciamento de credenciais;
- Separação de responsabilidades.

A autenticação multifator reduz o impacto do roubo de senhas, mas não impede todas as formas de phishing.

### 6.4 Medidas organizacionais

- Políticas de segurança;
- Simulações de phishing;
- Canais para denúncia;
- Procedimentos de verificação;
- Treinamento periódico;
- Compartilhamento de informações sobre ameaças;
- Monitoramento;
- Planos de resposta.

### 6.5 Resposta a incidentes

Quando um ataque é identificado, a organização pode:

- Bloquear contas comprometidas;
- Redefinir credenciais;
- Revogar sessões;
- Remover mensagens;
- Bloquear URLs e domínios;
- Verificar dispositivos;
- Comunicar usuários afetados;
- Investigar o incidente;
- Atualizar regras e modelos.

### 6.6 Estratégia em camadas

Uma estratégia em camadas pode combinar:

1. **Treinamento:** melhorar o reconhecimento por parte dos usuários;

2. **Filtragem:** reduzir a quantidade de conteúdo malicioso recebido;

3. **Autenticação:** dificultar o uso de credenciais roubadas;

4. **Monitoramento:** identificar atividades anormais;

5. **Revisão humana:** analisar casos ambíguos ou de alto risco;

6. **Resposta:** conter o incidente e reduzir os danos.

Nenhuma dessas medidas oferece proteção completa isoladamente.

---

## 7. Conclusão

O phishing combina manipulação humana, falsificação de identidade e recursos técnicos para induzir vítimas a fornecer informações ou realizar ações prejudiciais.

A engenharia social constitui um elemento importante desses ataques, mas não deve ser tratada como sinônimo de phishing. Ela representa um conjunto mais amplo de técnicas de manipulação que podem ocorrer em ambientes digitais ou físicos.

A inteligência artificial pode apoiar a detecção ao analisar textos, URLs, páginas, imagens e metadados. Machine learning, redes neurais, deep learning, NLP e OCR podem identificar padrões que seriam difíceis de analisar manualmente em grande escala.

Entretanto, o desempenho desses sistemas depende da qualidade dos dados, da metodologia de avaliação, da atualização dos modelos e do contexto em que são utilizados. Falsos positivos, falsos negativos, mudanças nos ataques, privacidade e falta de explicabilidade permanecem como desafios relevantes.

Por esse motivo, a proteção mais adequada combina controles técnicos, autenticação, treinamento, políticas organizacionais, monitoramento, análise humana e resposta a incidentes.

A inteligência artificial deve funcionar como uma ferramenta de apoio dentro de uma estratégia de segurança em camadas, e não como uma solução isolada ou totalmente autônoma.