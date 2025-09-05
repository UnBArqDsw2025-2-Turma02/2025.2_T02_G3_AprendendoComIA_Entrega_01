# Design Sprint Teste (Verificação & Validação)
A fase **Teste** é a quinta etapa da Design Sprint e funciona como uma **ponte entre verificação e validação**.  
- **Verificação**: confirma se aquilo que projetamos **foi construído de forma utilizável** (fluxos, rótulos, feedbacks, affordances).  
- **Validação**: comprova se a solução **resolve o problema do usuário e do negócio**, gerando valor real.

Na prática, colocamos o **protótipo** (baixa ou alta fidelidade) diante de pessoas representativas do público-alvo, **observamos tarefas reais**, medimos **eficácia, eficiência e satisfação** e transformamos os achados em **decisões de produto e arquitetura** (o que manter, ajustar ou descartar). O resultado é **evidência** para priorizar backlog, reduzir riscos e orientar o caminho do **MVP**.

---

## Sumário
- [Técnica Utilizada](#técnica-utilizada)
- [Objetivos](#objetivos)
- [Escopo do Teste](#escopo-do-teste)
- [Perfil do Usuário (Persona)](#perfil-do-usuário-persona)
- [Hipóteses a Validar](#hipóteses-a-validar)
- [Métricas de Sucesso](#métricas-de-sucesso)
- [Roteiro de Teste de Usabilidade](#roteiro-de-teste-de-usabilidade)
- [Cenários & Tarefas](#cenários--tarefas)
- [Matriz de Validação (ADRF/ADNRF)](#matriz-de-validação-adrfadnrf)
- [Instrumentação & Coleta de Dados](#instrumentação--coleta-de-dados)
- [Critérios de Aceite & Decisão](#critérios-de-aceite--decisão)
- [Riscos & Mitigações](#riscos--mitigações)
- [Integração com as Demais Etapas](#integração-com-as-demais-etapas)
- [Resultados Esperados & Próximos Passos](#resultados-esperados--próximos-passos)
- [Bibliografia](#bibliografia)
- [Histórico de Versões](#histórico-de-versões)

---

## Técnica Utilizada

Aplicamos **testes de usabilidade moderados** com protótipos de **baixa** e **alta fidelidade**, combinando:
- evidências da **Análise de Documentos** (ADRF/ADNRF e comparativos de mercado);
- resultados do **Questionário** (gráficos interativos *pubchart* do Google Sheets);
- protótipos do documento de **Prototipação**.

**Gráficos (pubchart) — referências principais**  
Faixa etária, nível, uso prévio, objetivos, motivação, frequência, dificuldades, recursos, rankings e notificações:  
<https://docs.google.com/spreadsheets/d/e/2PACX-1vRsTKWx3yzWxlDve5ha8S5K9j5HVmsYVj3eUaCXGGxeSi-sg8fO5L92c5e0zJySKEFyX6Ph3-xQDtWe/pubchart?oid=267573972&format=interactive>  
<https://docs.google.com/spreadsheets/d/e/2PACX-1vRsTKWx3yzWxlDve5ha8S5K9j5HVmsYVj3eUaCXGGxeSi-sg8fO5L92c5e0zJySKEFyX6Ph3-xQDtWe/pubchart?oid=621527094&format=interactive>  
<https://docs.google.com/spreadsheets/d/e/2PACX-1vRsTKWx3yzWxlDve5ha8S5K9j5HVmsYVj3eUaCXGGxeSi-sg8fO5L92c5e0zJySKEFyX6Ph3-xQDtWe/pubchart?oid=2128305900&format=interactive>  
<https://docs.google.com/spreadsheets/d/e/2PACX-1vRsTKWx3yzWxlDve5ha8S5K9j5HVmsYVj3eUaCXGGxeSi-sg8fO5L92c5e0zJySKEFyX6Ph3-xQDtWe/pubchart?oid=1430692516&format=interactive>  
<https://docs.google.com/spreadsheets/d/e/2PACX-1vRsTKWx3yzWxlDve5ha8S5K9j5HVmsYVj3eUaCXGGxeSi-sg8fO5L92c5e0zJySKEFyX6Ph3-xQDtWe/pubchart?oid=923948395&format=interactive>  
<https://docs.google.com/spreadsheets/d/e/2PACX-1vRsTKWx3yzWxlDve5ha8S5K9j5HVmsYVj3eUaCXGGxeSi-sg8fO5L92c5e0zJySKEFyX6Ph3-xQDtWe/pubchart?oid=1324111381&format=interactive>  
<https://docs.google.com/spreadsheets/d/e/2PACX-1vRsTKWx3yzWxlDve5ha8S5K9j5HVmsYVj3eUaCXGGxeSi-sg8fO5L92c5e0zJySKEFyX6Ph3-xQDtWe/pubchart?oid=1107678513&format=interactive>  
<https://docs.google.com/spreadsheets/d/e/2PACX-1vRsTKWx3yzWxlDve5ha8S5K9j5HVmsYVj3eUaCXGGxeSi-sg8fO5L92c5e0zJySKEFyX6Ph3-xQDtWe/pubchart?oid=1546509149&format=interactive>  
<https://docs.google.com/spreadsheets/d/e/2PACX-1vRsTKWx3yzWxlDve5ha8S5K9j5HVmsYVj3eUaCXGGxeSi-sg8fO5L92c5e0zJySKEFyX6Ph3-xQDtWe/pubchart?oid=2124834409&format=interactive>  
<https://docs.google.com/spreadsheets/d/e/2PACX-1vRsTKWx3yzWxlDve5ha8S5K9j5HVmsYVj3eUaCXGGxeSi-sg8fO5L92c5e0zJySKEFyX6Ph3-xQDtWe/pubchart?oid=1137807209&format=interactive>

---

## Objetivos

- **Verificar** a **usabilidade** dos fluxos críticos (onboarding CEFR, chat IA, exercícios, pronúncia, gamificação opt-in).  
- **Validar** se as soluções combatem as principais dores (pronúncia, listening, gramática/vocabulário) e suportam os objetivos (carreira, viagens, estudos).  
- **Mensurar** intenção de uso e adequação ao público predominante (18–34, níveis iniciante/intermediário).  
- **Evidenciar** decisões de arquitetura (latência, personalização, LGPD) e priorização do MVP.

---

## Escopo do Teste

**Protótipos**  
- Baixa fidelidade (rascunhos `.jpg`):  
  <figure markdown>
<font size="3"><p style="text-align: center"><b>Figura 1</b> – Protótipo de baixa fidelidade (Tela inicial e login).</p></font>
<center>
  <img src="https://raw.githubusercontent.com/UnBArqDsw2025-2-Turma02/2025.2_T02_G3_AprendendoComIA_Entrega_01/refs/heads/main/docs/assets/Notes_250904_174739_page-0001.jpg" alt="Priorização Colaborativa" width="600px">
</center>
</figure>



<figure markdown>
<font size="3"><p style="text-align: center"><b>Figura 2</b> – Protótipo de baixa fidelidade (Fluxo de cadastro e escolha de nível).</p></font>
<center>
  <img src="https://raw.githubusercontent.com/UnBArqDsw2025-2-Turma02/2025.2_T02_G3_AprendendoComIA_Entrega_01/refs/heads/main/docs/assets/Notes_250904_174739_page-0002.jpg" alt="Priorização Colaborativa" width="600px">
</center>
</figure>

<figure markdown>
<font size="3"><p style="text-align: center"><b>Figura 3</b> – Protótipo de baixa fidelidade (Menu principal e desafios).</p></font>
<center>
  <img src="https://raw.githubusercontent.com/UnBArqDsw2025-2-Turma02/2025.2_T02_G3_AprendendoComIA_Entrega_01/refs/heads/main/docs/assets/Notes_250904_174739_page-0003.jpg" alt="Priorização Colaborativa" width="600px">
</center>
</figure>


<figure markdown>
<font size="3"><p style="text-align: center"><b>Figura 4</b> – Protótipo de alta fidelidade (Dashboard e progressão de XP).</p></font>
<center>
  <img src="https://raw.githubusercontent.com/UnBArqDsw2025-2-Turma02/2025.2_T02_G3_AprendendoComIA_Entrega_01/refs/heads/main/docs/assets/Notes_250904_174739_page-0004.jpg" alt="Priorização Colaborativa" width="600px">
</center>

</figure>
 
- Alta fidelidade (versão digital do documento de Prototipação).

**Fluxos avaliados**  
Onboarding (nível CEFR + perfil), Home, Chat IA, Exercícios (listening/writing/flashcards), Pronúncia (ASR + scoring), Gamificação (XP/streaks/ranking **opt-in**), Notificações.

---

## Perfil do Usuário (Persona)

<figure markdown>
<font size="3"><p style="text-align: center"><b>Persona – Ana</b>Imagem ilustrativa da persona utilizada nos testes.</p></font>
<center>
  <img src="https://raw.githubusercontent.com/UnBArqDsw2025-2-Turma02/2025.2_T02_G3_AprendendoComIA_Entrega_01/refs/heads/main/docs/assets/download.jfif" alt="Priorização Colaborativa" width="600px">
</center>

</figure>

**Ana**, 22 anos — estudante e em início de carreira.  
**Objetivos:** melhorar inglês para **entrevistas** e **viagens**.  
**Nível:** A2–B1 (intermediário baixo).  
**Dores:** **pronúncia**, **listening**, vocabulário prático.  
**Hábitos:** quer praticar **todos os dias** (ou 3–4x/semana), aceita **notificações moderadas**, já usou apps (Duolingo), busca **feedback mais inteligente**.  
**Motivações:** carreira, gostar de aprender; prefere **ranking opt-in**.

---

## Hipóteses a Validar

1. **H1 – Onboarding CEFR**: configuração do nível **sem ajuda** em < 2 min.  
2. **H2 – IA útil**: chat melhora compreensão e escrita em tarefas contextualizadas.  
3. **H3 – Pronúncia**: feedback é claro/acionável (dicas + IPA + áudio-modelo).  
4. **H4 – Listening + SRS**: áudio + flashcards elevam retenção percebida.  
5. **H5 – Gamificação Opt-in**: ranking/ligas motivam sem atrito e com privacidade.  
6. **H6 – Notificações**: preferências granulares elevam engajamento sem incômodo.  
7. **H7 – Desempenho**: latência de chat/voz em patamar aceitável.

---

## Métricas de Sucesso

- **Eficácia**: % de tarefas concluídas sem ajuda (≥ **85%**).  
- **Eficiência**: tempo (onboarding < **2 min**; 1ª conversa < **3 min**; exercício < **4 min**).  
- **SUS** ≥ **75**; **NPS** ≥ **40**.  
- **Clareza de feedback** (Likert 1–5) ≥ **4,0**.  
- **Intenção de uso** (Likert 1–5) ≥ **4,0**.  
- **Desempenho** (mocks): tutor < **800 ms**; scoring de voz < **1,5 s**.

---

## Roteiro de Teste de Usabilidade

1. **Boas-vindas + LGPD** (consentimento, anonimato, gravação opcional).  
2. **Contexto**: “Você quer melhorar inglês para entrevistas e viagens.”  
3. **Tarefas** (ver *Cenários & Tarefas*).  
4. **Pós-tarefa**: o que foi fácil/difícil? O que esperava ver?  
5. **Pós-sessão**: SUS + NPS + intenção de uso + sugestões.  
6. **Encerramento**: agradecimento e reforço de privacidade.

---

## Cenários & Tarefas

- **T1 — Onboarding/CEFR** → chegar ao dashboard com trilha sugerida.  
- **T2 — Primeira conversa com IA** → pedir dicas para entrevista; receber correção de writing.  
- **T3 — Pronúncia** → gravar frase; ver pontuação e dicas fonéticas; repetir.  
- **T4 — Listening + Flashcards** → consumir áudio curto + revisar 5 cartões SRS.  
- **T5 — Gamificação (opt-in)** → ativar ranking, ver ligas, sair quando quiser.  
- **T6 — Notificações** → definir horário/tipo e silenciar fim de semana.

---

## Matriz de Validação (ADRF/ADNRF)

| Hipótese | Evidência (Docs/Questionário) | Requisitos Relacionados |
|---|---|---|
| H1 Onboarding CEFR | Questionário: maioria iniciante/intermediário; Docs: CEFR | **ADRF01**, **ADNRF03**, **ADNRF05** |
| H2 Chat IA útil | Questionário: “chat com IA” entre os preferidos | **ADRF02**, **ADRF05**, **ADNRF02** |
| H3 Pronúncia clara | Dores: pronúncia; refs. ELSA | **ADRF03**, **ADNRF02** |
| H4 Listening + SRS | Dores: listening/vocab; preferência por flashcards | **ADRF04**, **ADRF06** |
| H5 Gamificação opt-in | Preferência dividida → opt-in | **ADRF07**, **ADNRF05** |
| H6 Notificações | Aceitas com moderação → controle granular | **ADRF06**, **ADNRF01** |
| H7 Desempenho | Feedback em tempo real | **ADNRF02**, **ADNRF04** |

---

## Instrumentação & Coleta de Dados

- **Quantitativo**: tempos, taxa de sucesso, SUS, NPS, cliques, erros.  
- **Qualitativo**: gravação tela/áudio (opt-in), notas do moderador, comentários.  
- **LGPD**: consentimento explícito, anonimização, retenção mínima, opt-out.

---

## Critérios de Aceite & Decisão

- Alvos de **Métricas de Sucesso** atingidos; **H1–H7** validadas ou com plano de ajuste.  
- Sem bloqueadores de usabilidade nos fluxos críticos (T1–T4).  
- *Insights* priorizados para a próxima iteração de protótipo e MVP.

---

## Riscos & Mitigações

- **Latência** alta → fila assíncrona + cache + fallback texto.  
- **Excesso de gamificação** → opt-in, lembretes saudáveis, sinais de bem-estar.  
- **Privacidade** → anonimização, criptografia, consentimento granular.  
- **Feedback ambíguo** → exemplos de áudio, destaque fonético/IPA, histórico de erros.

---

## Integração com as Demais Etapas

- **Compreensão** → hipóteses e dores originadas do brainstorming.  
- **Diversão (Ideação)** → ideias agora **testadas**.  
- **Decisão (Priorização)** → teste confirma/ajusta o quadro priorizado.  
- **Prototipação** → atualizar fluxos/textos/dicas conforme achados.

---

## Resultados Esperados & Próximos Passos

- Relatório com métricas (SUS/NPS/tempos/sucesso), gravações opt-in e *insights*.  
- Atualizar **ADRF/ADNRF** e backlog (histórias de usuário).  
- Nova rodada de **alta fidelidade** e **reteste** focado em pronúncia/listening.  
- Preparar **MVP**: Onboarding CEFR, Chat IA, Pronúncia, Listening+SRS, Notificações.

---

## Bibliografia

> KNAPP, Jake; ZERATSKY, John; KOWITZ, Braden. **Sprint**. Intrínseca, 2016.  
> RUBIN, Jeffrey. **Handbook of Usability Testing**. Wiley, 2011.  
> NIELSEN, Jakob. **Usability Engineering**. Morgan Kaufmann, 1994.  
> SWEBOK — IEEE. <https://www.computer.org/education/bodies-of-knowledge/software-engineering>  
> LGPD — Gov.br. <https://www.gov.br/cidadania/pt-br/acesso-a-informacao/lgpd>

---

## Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | Incremento do Revisor |
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: | :-------------------: |
| `1.0`  | Etapa 5 (Teste) com tema/introdução, persona com imagem, hipóteses, métricas, roteiro, matriz ADRF/ADNRF e integração com as demais fases | [arthurlleite](https://github.com/arthurlleite) | 04/09/2025 |  |  |  |
