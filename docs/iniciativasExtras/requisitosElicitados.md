# Requisitos Elicitados

---

## Sumário

- [Técnica Utilizada](#Técnica-Utilizada)
- [Requisitos Funcionais (RF)](#requisitos-funcionais-rf)
- [Requisitos Não Funcionais (RNF)](#requisitos-não-funcionais-rnf)
- [Bibliografia](#bibliografia)
- [Histórico de Versões](#histórico-de-versões)

---

## Técnica Utilizada

Para a elicitação dos requisitos deste projeto, foi utilizada a técnica de **Brainstorming** onde a equipe se reuniu para discutir e listar livremente todas as funcionalidades e características desejadas para o sistema, sem restrições iniciais,  **Observação** onde levamos em consideração nossa experiência com aplicativos de aprendizado de idiomas, bem como pesquisas relacionadas na técnica de **Análise de Documentos**.

Após a coleta, os requisitos foram analisados, categorizados e refinados, resultando nas listas de Requisitos Funcionais e Não Funcionais detalhadas abaixo.

---

## Requisitos Funcionais (RF)

Os requisitos funcionais descrevem o que o sistema deve fazer, ou seja, suas funcionalidades e comportamentos específicos.

| ID | Descrição | Rastreabilidade/Origem |
| :--- | :--- | :--- |
| **RF01** | O sistema deve fornecer um chatbot com IA para que o usuário possa praticar conversação por texto. | [Brainstorming](artefatosGeneralistas/brainstorming.md), [Observação](artefatosGeneralistas/observacao.md) e [Análise de Documentos](iniciativasExtras/analiseDeDocumentos.md) |
| **RF02** | O sistema deve permitir que o usuário interaja com diferentes "tutores de IA", cada um com personalidades e estilos de interação distintos. | [Brainstorming](iniciativasExtras/brainstorming.md), [Observação](artefatosGeneralistas/observacao.md) e [Análise de Documentos](iniciativasExtras/analiseDeDocumentos.md) |
| **RF03** | O sistema deve analisar a gramática do usuário em tempo real, indicando e corrigindo erros. | [Brainstorming](artefatosGeneralistas/brainstorming.md) e [Observação](artefatosGeneralistas/observacao.md) |
| **RF04** | O sistema deve registrar o progresso do usuário através de Nível e Pontos de Experiência (XP). | [Brainstorming](artefatosGeneralistas/brainstorming.md) e [Observação](artefatosGeneralistas/observacao.md) |
| **RF05** | O sistema deve fornecer feedback sonoro imediato para acertos e erros. | [Brainstorming](artefatosGeneralistas/brainstorming.md) e [Observação](artefatosGeneralistas/observacao.md) |
| **RF06** | O usuário deve poder selecionar palavras no chat para ver sua definição diretamente na tela. | [Brainstorming](artefatosGeneralistas/brainstorming.md) e[Observação](artefatosGeneralistas/observacao.md) |
| **RF07** | O sistema deve possuir um dicionário para pesquisa de palavras, com definição em inglês e português, e um exemplo de uso em frase. | [Brainstorming](artefatosGeneralistas/brainstorming.md)|
| **RF08** | O sistema deve propor missões semanais com metas específicas (ex: "praticar 30 minutos" ou "escrever 100 palavras"). | [Brainstorming](artefatosGeneralistas/brainstorming.md) e [Análise de Documentos](iniciativasExtras/analiseDeDocumentos.md) |
| **RF09** | O sistema deve enviar mensagens motivacionais quando o usuário atingir metas ou acertar respostas. | [Brainstorming](artefatosGeneralistas/brainstorming.md) e [Análise de Documentos](iniciativasExtras/analiseDeDocumentos.md)|
| **RF10** | O sistema deve emitir avisos sobre o uso de gírias e informalidades, explicando o contexto adequado para seu uso. | [Brainstorming](artefatosGeneralistas/brainstorming.md) e [Análise de Documentos](iniciativasExtras/analiseDeDocumentos.md) |
| **RF11** | A IA deve ser capaz de utilizar a câmera do dispositivo para identificar objetos e criar um contexto de conversação. | [Brainstorming](artefatosGeneralistas/brainstorming.md) |
| **RF12** | O sistema deve oferecer uma funcionalidade de "conversa por carta", permitindo uma interação assíncrona com a IA ou outros usuários. | [Brainstorming](artefatosGeneralistas/brainstorming.md) |
| **RF13** | O sistema deve oferecer "flashcards inteligentes" que utilizam repetição espaçada para otimizar a memorização. | [Brainstorming](artefatosGeneralistas/brainstorming.md) |
| **RF14** | O sistema deve incluir um jogo de soletrar palavras (*spelling bee*). | [Brainstorming](artefatosGeneralistas/brainstorming.md) |
| **RF15** | O sistema deve oferecer exercícios de ditado com frases e expressões populares. | [Brainstorming](artefatosGeneralistas/brainstorming.md) |
| **RF16** | O sistema deve conter quizzes de compreensão auditiva (*listening*) baseados em músicas. | [Brainstorming](artefatosGeneralistas/brainstorming.md) e [Observação](artefatosGeneralistas/observacao.md) |
| **RF17** | O sistema deve apresentar um ranking de pontuação entre amigos (participação opcional). | [Brainstorming](artefatosGeneralistas/brainstorming.md) |
| **RF18** | O dicionário deve conter a pronúncia da palavra em IPA (alfabeto fonético). | [Brainstorming](artefatosGeneralistas/brainstorming.md) e [Observação](artefatosGeneralistas/observacao.md) |
| **RF19** | O sistema deve fornecer um chatbot com IA para que o usuário possa praticar conversação por voz. | [Brainstorming](artefatosGeneralistas/brainstorming.md) e [Observação](artefatosGeneralistas/observacao.md) |
| **RF20** | O sistema deve utilizar detecção de voz para avaliar a dicção e a pronúncia do usuário. | [Brainstorming](artefatosGeneralistas/brainstorming.md) |
| **RF21** | O sistema deve possuir uma ferramenta de conversação entre usuários da plataforma. | [Brainstorming](artefatosGeneralistas/brainstorming.md) e [Observação](artefatosGeneralistas/observacao.md) |

<div align="center"> <p>Autores: <a href="https://github.com/UnBArqDsw2025-2-Turma02/2025.2_T02_G3_AprendendoComIA_Entrega_01">Felipe, Pedro e Mateus</a>.</p> </div>

---

## Requisitos Não Funcionais (RNF)

Os requisitos não funcionais descrevem *como* o sistema deve operar, definindo suas qualidades e restrições. Eles não se referem a funcionalidades específicas, mas a critérios para julgá-las.

**Legenda de Categorias:**
*   **PE:** Performance
*   **SE:** Segurança
*   **CO:** Confiabilidade
*   **US:** Usabilidade
*   **PO:** Portabilidade
*   **AC:** Acessibilidade
*   **MA:** Manutenibilidade

| ID | Categoria | Descrição | Rastreabilidade/Origem |
| :--- | :--- | :--- | :--- |
| **RNF01** | PE | O tempo de resposta da IA em uma conversação deve ser inferior a 2 segundos para garantir um diálogo fluido. | [Brainstorming](artefatosGeneralistas/brainstorming.md) |
| **RNF02** | SE | A aplicação deve proteger todos os dados de cadastro e progresso do usuário com criptografia. | [Brainstorming](artefatosGeneralistas/brainstorming.md) |
| **RNF03** | CO | O sistema deve garantir o armazenamento persistente do progresso do usuário (XP, nível, lições), mesmo com conexão de internet intermitente. | [Brainstorming](artefatosGeneralistas/brainstorming.md) |
| **RNF04** | US | O usuário deve conseguir iniciar uma atividade principal (ex: conversar com IA) em, no máximo, 3 cliques após o login. | [Brainstorming](artefatosGeneralistas/brainstorming.md) |
| **RNF05** | PO | A aplicação deve ser totalmente funcional e ter sua interface adaptada para dispositivos móveis (celulares e tablets) e desktop. | [Brainstorming](artefatosGeneralistas/brainstorming.md) |
| **RNF06** | SE | O login e o acesso a dados pessoais devem possuir ao menos uma etapa de verificação de segurança (ex: senha). | [Brainstorming](artefatosGeneralistas/brainstorming.md)|
| **RNF07** | MA | A arquitetura deve permitir que o banco de palavras e exercícios seja atualizado sem a necessidade de reinstalar o aplicativo. | [Brainstorming](artefatosGeneralistas/brainstorming.md) |
| **RNF08** | AC | A aplicação deve ser compatível com as principais ferramentas de acessibilidade do sistema operacional (leitores de tela, modo de alto contraste). | [Brainstorming](artefatosGeneralistas/brainstorming.md) |
| **RNF09** | PE | O aplicativo deve carregar completamente e estar pronto para uso em menos de 5 segundos após ser iniciado. | [Brainstorming](artefatosGeneralistas/brainstorming.md) |
| **RNF10** | PE | O sistema deve processar os comandos de voz (fala-para-texto) com uma latência inferior a 3 segundos. | [Brainstorming](artefatosGeneralistas/brainstorming.md)|

<div align="center"> <p>Autores: <a href="https://github.com/UnBArqDsw2025-2-Turma02/2025.2_T02_G3_AprendendoComIA_Entrega_01">Felipe, Pedro, Mateus e Samuel</a>.</p> </div>

---

## Bibliografia

> <p><small>SOMMERVILLE, Ian. **Engenharia de Software**. 10. ed. Pearson Education, 2019.</small></p>

---

## Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | Incremento do Revisor|
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: | :-------------: |
| `1.0` | Criação do documento e elicitação inicial dos requisitos. | [Felipe das Neves](https://github.com/FelipeFreire-gf) | 03/09/2025 | | | |
| `1.1` | Estruturação dos requisitos em tabelas, priorização e refinamento das descrições. | [Felipe das Neves](https://github.com/FelipeFreire-gf) | 03/09/2025 | | | |