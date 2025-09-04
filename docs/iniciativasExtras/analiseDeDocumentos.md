# Análise de Documentos - Perfil do Público Interessado no Aprendizado de Inglês

---

## Sumário
- [Técnica Utilizada](#técnica-utilizada)
- [Objetivos](#objetivos)
- [Faixa Etária](#faixa-etária)
- [Gênero](#gênero)
- [Nível de Escolaridade](#nível-de-escolaridade)
- [Fluência em Outros Idiomas](#fluência-em-outros-idiomas)
- [Análise de Aplicativos Concorrentes](#análise-de-aplicativos-concorrentes)
- [Requisitos Funcionais (ADRF)](#requisitos-funcionais-adrf)
- [Requisitos Não Funcionais (ADNRF)](#requisitos-não-funcionais-adnrf)
- [Processo da IA](#processo-da-ia)
- [Bibliografia](#bibliografia)
- [Histórico de Versões](#histórico-de-versões)

---

## Técnica Utilizada

A técnica aplicada foi a **Análise de Documentos**, que reuniu diferentes fontes de informação para estruturar os requisitos do software. Foram considerados os registros do [brainstorm em Miro](https://miro.com/), as respostas coletadas pelo [questionário Google Forms](https://forms.gle/cB4qXso3j3tm2LVh6), e referências de aplicações já consolidadas no mercado, como o [Duolingo](https://en.wikipedia.org/wiki/Duolingo), o [Babbel](https://www.babbel.com/) e o [ELSA Speak](https://elsaspeak.com/en/). Além disso, utilizamos bibliografia especializada como o [SWEBOK](https://www.computer.org/education/bodies-of-knowledge/software-engineering) e [Sommerville (2019)](https://www.pearson.com/en-us/subject-catalog/p/software-engineering/P200000003546/9780137035151), garantindo embasamento teórico.

<center>
  <span style="background-color:#c5a352; color:white; font-size:0.8em; font-weight: bold; padding:2px 6px; border-radius:4px;"> Design Sprint | Versão 1.0</span>
</center>

---

## Objetivos

O objetivo principal desta análise é organizar e validar informações que permitam o desenvolvimento do aplicativo **Aprendendo com IA**. A partir de documentos coletados, buscou-se compreender o perfil dos usuários interessados em aprender inglês, identificar seus hábitos, dificuldades e preferências, além de estabelecer requisitos funcionais e não funcionais que orientem a arquitetura da solução. Essa etapa também visa assegurar a aderência às normas da [LGPD](https://www.gov.br/cidadania/pt-br/acesso-a-informacao/lgpd) e inspirar-se em boas práticas aplicadas por sistemas como o [Duolingo](https://pt.wikipedia.org/wiki/Duolingo) e o [Babbel](https://www.babbel.com/).

---

## Faixa Etária

De acordo com as respostas do [questionário aplicado](https://forms.gle/cB4qXso3j3tm2LVh6), a maior parte dos usuários encontra-se na faixa entre 18 e 34 anos. Esse resultado mostra que o público predominante é jovem adulto, acostumado com o uso de aplicativos móveis e plataformas digitais. Essa faixa etária também apresenta alta receptividade a metodologias de gamificação, já consolidadas em aplicativos de aprendizado como o [Duolingo](https://en.wikipedia.org/wiki/Duolingo), o que reforça a importância de implementar elementos como pontos de experiência, missões diárias e rankings de amigos.

---

## Gênero

A análise do [questionário](https://forms.gle/cB4qXso3j3tm2LVh6) revelou diversidade de gênero entre os respondentes. Por isso, o sistema deve adotar linguagem inclusiva, comunicação neutra e oferecer possibilidade de personalização do perfil do usuário. Aplicativos como o [Babbel](https://www.babbel.com/) já utilizam avatares e conteúdos adaptativos que podem servir de referência para garantir representatividade e inclusão.

---

## Nível de Escolaridade

Os resultados do [questionário](https://forms.gle/cB4qXso3j3tm2LVh6) indicam que o público possui, em sua maioria, ensino médio completo ou nível superior. Esse dado demonstra que o perfil do usuário é compatível com métodos de ensino online e plataformas estruturadas, mas que também valoriza recursos práticos. O [Babbel](https://medium.com/%40emmamillerw1990/babbel-duolingo-and-chatterfox-a-comparative-analysis-for-english-learners-582c0957095d), por exemplo, foca em situações do cotidiano de adultos, como entrevistas de emprego e viagens, o que pode inspirar o direcionamento do conteúdo do Aprendendo com IA.

---

## Fluência em Outros Idiomas

O [questionário](https://forms.gle/cB4qXso3j3tm2LVh6) revelou que a maioria dos usuários é monolíngue em português e possui nível de inglês entre iniciante e intermediário. Esse resultado demonstra a necessidade de oferecer trilhas adaptativas baseadas no [CEFR](https://www.coe.int/en/web/common-european-framework-reference-languages), cobrindo desde o A1 até o C1. Aplicativos como o [Duolingo](https://en.wikipedia.org/wiki/Duolingo) já implementam essa progressão, porém o nosso diferencial será a integração com correção automatizada de pronúncia, inspirada em soluções como o [ELSA Speak](https://elsaspeak.com/en/).

---

## Análise de Aplicativos Concorrentes

O [Duolingo](https://en.wikipedia.org/wiki/Duolingo) destaca-se pelo uso intenso de gamificação, oferecendo pontos de experiência, rankings e desafios diários. Apesar de popular, alguns estudos apontam que o excesso de gamificação pode prejudicar a retenção do aprendizado, como discutido em [Arxiv (2022)](https://arxiv.org/abs/2203.16175). O [Babbel](https://www.babbel.com/), por sua vez, foca em lições estruturadas voltadas para adultos, oferecendo conteúdo mais profundo e aplicável a contextos profissionais e de viagem. Já o [ELSA Speak](https://elsaspeak.com/en/) tem como diferencial a correção de pronúncia por meio de IA em tempo real, atendendo usuários que desejam melhorar especificamente sua fala. Estudos comparativos como o publicado em [Language in India (2024)](https://www.languageinindia.com/oct2024/drsunandauseAIEnglishlearning1.pdf) e em [Sciedupress (2024)](https://www.sciedupress.com/journal/index.php/jct/article/download/25589/16050) mostram que nenhum desses aplicativos consegue integrar plenamente gamificação, conteúdo estruturado e feedback de IA de forma equilibrada, abrindo espaço para a proposta do Aprendendo com IA.

---

## Requisitos Funcionais (ADRF)

Os requisitos funcionais foram extraídos a partir do [Miro](https://miro.com/), das respostas do [questionário](https://forms.gle/cB4qXso3j3tm2LVh6) e da análise de concorrentes como [Duolingo](https://pt.wikipedia.org/wiki/Duolingo), [Babbel](https://www.babbel.com/) e [ELSA Speak](https://elsaspeak.com/en/). Cada requisito foi nomeado com a sigla ADRF para facilitar rastreabilidade.

| Sigla   | Requisito Funcional | Fonte |
|---------|---------------------|-------|
| ADRF01 | Cadastro com nível inicial de inglês | [Questionário](https://forms.gle/cB4qXso3j3tm2LVh6) |
| ADRF02 | Chatbot de IA para conversação e entrevistas simuladas | [Miro](https://miro.com/) + [Duolingo Max](https://en.wikipedia.org/wiki/Duolingo) |
| ADRF03 | Correção automática de pronúncia | [ELSA Speak](https://elsaspeak.com/en/) |
| ADRF04 | Exercícios de listening com músicas e ditados | [Duolingo](https://pt.wikipedia.org/wiki/Duolingo) |
| ADRF05 | Atividades de writing com correção de gramática | [Babbel](https://www.babbel.com/) |
| ADRF06 | Flashcards com repetição espaçada (SRS) | [Duolingo](https://pt.wikipedia.org/wiki/Duolingo) |
| ADRF07 | Gamificação: XP, badges, streaks, ranking entre amigos | [Duolingo](https://en.wikipedia.org/wiki/Duolingo) |
| ADRF08 | Missões diárias/semanas e notificações | [Questionário](https://forms.gle/cB4qXso3j3tm2LVh6) |
| ADRF09 | Relatórios de desempenho e gráficos de progresso | [Sciedupress](https://www.sciedupress.com/journal/index.php/jct/article/download/25589/16050) |
| ADRF10 | Tutores com personalidades distintas | [Duolingo Max](https://en.wikipedia.org/wiki/Duolingo) |
| ADRF11 | Correção de gramática, gírias e sotaques | [Language in India](https://www.languageinindia.com/oct2024/drsunandauseAIEnglishlearning1.pdf) |

---

## Requisitos Não Funcionais (ADNRF)

Os requisitos não funcionais foram derivados das diretrizes da [LGPD](https://www.gov.br/cidadania/pt-br/acesso-a-informacao/lgpd), das boas práticas em Engenharia de Software segundo [Sommerville (2019)](https://www.pearson.com/en-us/subject-catalog/p/software-engineering/P200000003546/9780137035151) e do [SWEBOK](https://www.computer.org/education/bodies-of-knowledge/software-engineering). Também foram avaliadas demandas observadas em aplicativos concorrentes.

| Sigla   | Requisito Não Funcional | Fonte |
|---------|-------------------------|-------|
| ADNRF01 | Conformidade LGPD com anonimização e consentimento | [LGPD](https://www.gov.br/cidadania/pt-br/acesso-a-informacao/lgpd) |
| ADNRF02 | Disponibilidade mínima de 99% | [Sommerville](https://www.pearson.com/en-us/subject-catalog/p/software-engineering/P200000003546/9780137035151) |
| ADNRF03 | Baixa latência para feedback em tempo real | [ELSA Speak](https://elsaspeak.com/en/) |
| ADNRF04 | Arquitetura escalável e cloud-native | [SWEBOK](https://www.computer.org/education/bodies-of-knowledge/software-engineering) |
| ADNRF05 | Portabilidade: web responsiva e PWA | [Duolingo](https://en.wikipedia.org/wiki/Duolingo) + [Babbel](https://www.babbel.com/) |
| ADNRF06 | Usabilidade e acessibilidade (contraste e teclado IPA) | [Miro](https://miro.com/) + [Questionário](https://forms.gle/cB4qXso3j3tm2LVh6) |
| ADNRF07 | Criptografia em trânsito e repouso | [LGPD](https://www.gov.br/cidadania/pt-br/acesso-a-informacao/lgpd) |
| ADNRF08 | Confiabilidade mínima em respostas de IA | [Miro](https://miro.com/) |
| ADNRF09 | Arquitetura modular para evolução | [SWEBOK](https://www.computer.org/education/bodies-of-knowledge/software-engineering) |
| ADNRF10 | Evitar excesso de gamificação | [Arxiv](https://arxiv.org/abs/2203.16175) |

---

## Processo da IA

O processo de funcionamento do sistema combina diferentes tecnologias já disponíveis no mercado. O usuário interage com o aplicativo fornecendo voz ou texto, que pode ser capturado por [WebRTC](https://webrtc.org/). Em seguida, um serviço de reconhecimento de fala como o [Google Speech-to-Text](https://cloud.google.com/speech-to-text/) realiza a transcrição. Os dados são processados por um modelo de linguagem como o [GPT-4](https://platform.openai.com/), que gera feedback personalizado e adaptado ao nível do usuário. A correção gramatical pode ser auxiliada por ferramentas como o [LanguageTool](https://languagetool.org/pt-BR), enquanto a análise de pronúncia utiliza padrões do [IPA](https://www.internationalphoneticalphabet.org/). A resposta ao usuário é retornada via síntese de fala com serviços como o [Amazon Polly](https://aws.amazon.com/polly/). Todas as interações alimentam mecanismos de gamificação inspirados no [Duolingo](https://en.wikipedia.org/wiki/Duolingo) e são acompanhadas por métricas via [Google Analytics](https://marketingplatform.google.com/about/), garantindo rastreabilidade, métricas de desempenho e aderência à [LGPD](https://www.gov.br/cidadania/pt-br/acesso-a-informacao/lgpd).

---

## Bibliografia

- [Duolingo – Wikipedia](https://en.wikipedia.org/wiki/Duolingo)  
- [Babbel – Site Oficial](https://www.babbel.com/)  
- [ELSA Speak – Site Oficial](https://elsaspeak.com/en/)  
- [Language in India – Comparative Study](https://www.languageinindia.com/oct2024/drsunandauseAIEnglishlearning1.pdf)  
- [Sciedupress – Teaching with Apps](https://www.sciedupress.com/journal/index.php/jct/article/download/25589/16050)  
- [Arxiv – Gamification Misuse](https://arxiv.org/abs/2203.16175)  
- [SWEBOK – IEEE](https://www.computer.org/education/bodies-of-knowledge/software-engineering)  
- [LGPD – Gov.br](https://www.gov.br/cidadania/pt-br/acesso-a-informacao/lgpd)  
- [Sommerville – Engenharia de Software](https://www.pearson.com/en-us/subject-catalog/p/software-engineering/P200000003546/9780137035151)  
- [Miro – Arquitetura G3](https://miro.com/)  
- [Google Forms – Público Alvo](https://forms.gle/cB4qXso3j3tm2LVh6)

---

## Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | Incremento do Revisor |
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: | :-------------------: |
| `1.0`  | Modelagem inicial | [Felipe das Neves](https://github.com/FelipeFreire-gf) | 01/09/2025 | [arthurlleite](https://github.com/arthurlleite) | 04/09/2025 | Inclusão de revisão inicial |
| `1.1`  | Inclusão de explicações detalhadas, links em todos os tópicos, requisitos ADRF/ADNRF, análise de concorrentes e atualização do sumário | [arthurlleite](https://github.com/arthurlleite) | 04/09/2025 |  |  |  |
