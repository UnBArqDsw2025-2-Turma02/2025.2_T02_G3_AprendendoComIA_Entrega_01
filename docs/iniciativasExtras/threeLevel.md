# Three Level Scale

---

## Sumário

- [Técnica Utilizada](#técnica-utilizada)
- [Objetivos](#objetivos)
- [Requisitos Priorizados](#requisitos-priorizados)
- [Histórico de Versões](#histórico-de-versões)
- [Requisitos Priorizados](#Requisitos-Priorizados)
- [Bibliografia](#bibliografia)

---

## Técnica Utilizada

A técnica **Three-Level Scale** é um método de priorização de requisitos que categoriza tarefas ou funcionalidades em três níveis de prioridade: **Alta**, **Média** e **Baixa**. Essa abordagem é simples e eficaz, permitindo que equipes de desenvolvimento e stakeholders alinhem expectativas e foquem nos itens mais críticos para o sucesso do projeto. A técnica é especialmente útil em projetos ágeis, onde é necessário tomar decisões rápidas sobre o que implementar primeiro.

- **Alta Prioridade**: Requisitos essenciais que devem ser implementados imediatamente, pois são críticos para o funcionamento ou sucesso do sistema.
- **Média Prioridade**: Requisitos importantes que agregam valor, mas podem ser implementados em iterações futuras sem comprometer a entrega inicial.
- **Baixa Prioridade**: Requisitos desejáveis, mas não essenciais, que podem ser adiados ou descartados sem impacto significativo.

A aplicação da técnica envolve listar todos os requisitos, classificá-los com base em critérios como impacto no negócio, dependências e esforço, e validar as prioridades com os stakeholders.

<center>
  <span style="background-color:#c5a352; color:white; font-size:0.8em; font-weight: bold; padding:2px 6px; border-radius:4px;"> Three-Level Scale | Versão 1.0</span>
</center>

---

## Objetivos

- **Estabelecer Prioridades Claras**: Garantir que a equipe foque nos requisitos mais críticos para o sucesso do projeto.
- **Facilitar a Tomada de Decisão**: Proporcionar uma estrutura simples para decidir quais funcionalidades implementar em cada iteração.
- **Alinhar Expectativas**: Promover consenso entre stakeholders e equipe de desenvolvimento sobre a importância relativa dos requisitos.
- **Reduzir Escopo**: Evitar sobrecarga ao adiar ou descartar requisitos de baixa prioridade.

---

## Requisitos Priorizados

Os requisitos do projeto foram categorizados usando a técnica Three-Level Scale. Abaixo está a lista de requisitos priorizados para um projeto exemplo de desenvolvimento de um aplicativo de gerenciamento de tarefas:


### Requisitos funcionais
| **ID** | **Requisito**                              | **Prioridade** | **Justificativa**                                                                 |
|--------|--------------------------------------------|----------------|----------------------------------------------------------------------------------|
| RF01.1 | Chatbot IA para praticar conversação por texto | Alta           | Essencial para a principal funcionalidade de interação do usuário com o sistema. |
| RF01.2 | Interação com diferentes tutores de IA     | Alta           | Diversifica a prática e aumenta engajamento.                                      |
| RF01.7 | Tutores com personalidades distintas       | Alta           | Personalização que melhora a experiência de aprendizado.                          |
| RF01.8 | Pesquisa direta de definições no chat      | Média          | Facilita a consulta rápida de palavras, mas não é crítica para o uso inicial.     |
| RF02.1 | Dicionário para pesquisa de palavras       | Média          | Complementa o aprendizado, essencial para estudo de vocabulário.                 |
| RF02.3 | Definição de palavras em inglês e português | Média          | Ajuda na compreensão, melhora experiência educativa.                              |
| RF02.4 | Exemplos em frases comuns                  | Média          | Auxilia na contextualização do aprendizado, mas não impede uso do app.            |
| RF03.3 | Missões semanais com metas específicas     | Média          | Engaja usuários, mas é funcionalidade secundária.                                 |
| RF03.4 | Mensagens motivacionais ao atingir metas   | Média          | Incentiva prática regular, não crítico para funcionamento.                        |
| RF04.3 | Avisos sobre gírias e informalidades       | Média          | Melhora aprendizado cultural, mas não impede uso.                                 |
| RF04.4 | Efeitos na personalidade IA                | Média          | Incrementa experiência, não essencial para operação do sistema.                   |
| RF01.3 | IA identifica objetos pela câmera          | Baixa          | Funcionalidade adicional de contexto visual, não essencial.                       |
| RF01.4 | Conversa por carta (interação assíncrona) | Baixa          | Interação avançada opcional, não crítica.                                         |
| RF02.2 | Pronúncia da palavra em IPA                | Baixa          | Melhoria educativa opcional, não bloqueia o aprendizado.                           |
| RF02.5 | Flashcards inteligentes (repetição espaçada) | Baixa          | Otimiza memorização, mas pode ser implementado depois.                             |
| RF02.6 | Jogo de soletrar palavras                  | Baixa          | Funcionalidade de engajamento opcional.                                           |
| RF02.7 | Exercícios de ditado com frases populares | Baixa          | Complementa aprendizado, não crítico.                                             |
| RF02.8 | Quizzes de listening com músicas           | Baixa          | Reforço de listening, pode ser implementado posteriormente.                        |
| RF03.2 | Ranking entre amigos (opt-in)             | Baixa          | Funcionalidade social opcional.                                                  |
| RF03.4 | Sons de feedback ao atingir objetivos      | Baixa          | Experiência de gamificação opcional.                                             |
| RF04.2 | Avaliação de dicção e pronúncia via voz   | Baixa          | Funcionalidade extra, não essencial para operação.                                |
| RF04.4 | Feedback sonoro imediato                   | Baixa          | Melhoria de experiência, não bloqueia uso.                                        |
| RF01.5 | Conversa entre usuários da plataforma     | Baixa     | Funcionalidade social mínima, não crítica.                                        |
| RF01.6 | Chatbot IA para prática de voz             | Baixa     | Funcionalidade extra, não essencial.                                             |
| RNF01 | Tempo de resposta IA < 2s                   | Alta           | Essencial para manter diálogo fluido e experiência positiva.                      |



### Requisitos não funcionais

| **ID** | **Requisito**                              | **Prioridade** | **Justificativa**                                                                 |
|--------|--------------------------------------------|----------------|----------------------------------------------------------------------------------|
| RNF01 | Tempo de resposta IA < 2s                   | Alta           | Essencial para manter diálogo fluido e experiência positiva.                      |
| RNF02 | Criptografia de dados                       | Alta           | Necessário para segurança e conformidade com proteção de dados.                  |
| RNF03 | Armazenamento persistente do progresso     | Alta           | Garante continuidade do aprendizado, mesmo sem conexão constante.                |
| RNF04 | Iniciar atividade principal em ≤ 3 cliques | Alta           | Melhora usabilidade e experiência do usuário.                                     |
| RNF05 | Interface adaptada para dispositivos móveis | Alta           | Necessário para acesso em diferentes plataformas.                                 |
| RNF09 | Login e acesso com verificação de segurança | Alta           | Garante proteção de dados e acesso seguro.                                        |
| RNF10 | Banco de palavras e exercícios atualizável | Média         | Permite manutenção e atualização contínua sem reinstalação.                       |
| RNF08 | Compatibilidade com ferramentas de acessibilidade | Média          | Garante inclusão de usuários com necessidades especiais.                           |
| RNF06 | Processamento de comandos de voz < 3s      | Baixa          | Melhoria na experiência de voz, não impede funcionalidade principal.             |
| RNF11 | Aplicativo pronto para uso em < 5s         | Baixa          | Performance desejável, mas não crítica para funcionamento.                        |


## Bibliografia

> <p><small>WIEGERS, Karl. Five Requirements Prioritization Methods. Business Analyst Times. Disponível em: <a href="https://www.batimes.com/articles/five-requirements-prioritization-methods/">https://www.batimes.com/articles/five-requirements-prioritization-methods/</a>. Acesso em: 05 set. 2025.</small></p>
> <p><small>MODERN ANALYST. Techniques to Prioritize Requirements. Disponível em: <a href="https://www.modernanalyst.com/Resources/Articles/tabid/115/ID/1413/Techniques-to-Prioritize-Requirements.aspx">https://www.modernanalyst.com/Resources/Articles/tabid/115/ID/1413/Techniques-to-Prioritize-Requirements.aspx</a>. Acesso em: 05 set. 2025.</small></p>


---




## Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | Incremento do Revisor|
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: | :-------------: |
| `1.0` | Modelagem inicial | [Felipe das Neves](https://github.com/FelipeFreire-gf) | 03/09/2025 | | | |
| `1.1` | Modelagem inicial | [Mateus Bastos](https://github.com/MateuSansete) | 05/09/2025 | | | |