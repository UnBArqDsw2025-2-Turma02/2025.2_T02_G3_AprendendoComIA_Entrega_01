# MoScoW
---


## Sumário

- [Introdução](#introducao)
- [Integrantes que atuaram no desenvolvimento do artefato](#integrantes-que-atuaram-no-desenvolvimento-do-artefato)
- [Metodologia](#metodologia)
- [Must "Deve ter"](#must-deve-ter)
- [Should "Deveria ter"](#should-deveria-ter)
- [Could "Poderia ter"](#could-poderia-ter)
- [Won't "Não vai ter"](#wont-nao-vai-ter)
- [Histórico de Versões](#historico-de-versoes)

---

## Introdução
O método de MoSCoW é uma técnica de priorização utilizada para alinhar os requisitos do projeto com as expectativas das partes interessadas. Ele categoriza as funcionalidades em quatro grupos: **Must, Should, Could e Won't**, garantindo que a equipe de desenvolvimento foque no que é mais crítico para o lançamento de uma versão inicial de sucesso.

---

## Objetivo
O objetivo deste artefato é estabelecer de forma clara e consensual a priorização dos requisitos do projeto, utilizando a técnica MoSCoW para orientar a equipe no desenvolvimento do aplicativo de prática de conversação com IA. A priorização garante que o Produto Mínimo Viável (MVP) seja construído com foco nos elementos essenciais para usabilidade, desempenho e segurança, enquanto funcionalidades adicionais são planejadas de acordo com sua relevância e viabilidad

---

## Metodologia
Para a priorização, a equipe analisou a importância de cada requisito funcional e não funcional em relação ao objetivo central do projeto: a criação de um aplicativo de prática de conversação com IA. As prioridades foram definidas em consenso, levando em conta o valor entregue ao usuário, a viabilidade técnica e a necessidade para o Produto Mínimo Viável (MVP).

---

## Must "Deve ter"
Os requisitos classificados como Must representam a base inegociável do produto. Sem eles, o sistema não teria utilidade ou não atenderia a critérios mínimos de segurança e funcionalidade. A implementação desses itens é a prioridade máxima da equipe.

### Requisitos Must

| ID | Descrição do Requisito | Tipo | Prioridade | Dificuldade |
|----|-----------------------|------|------------|------------|
| RF01.1 | Chatbot de IA para conversação por texto. | Funcional | Must | Média |
| RF04.1 | Análise de gramática em tempo real. | Funcional | Must | Alta |
| RNF01 | Tempo de resposta da IA < 2s. | Não Funcional | Must | Alta |
| RNF02 | Criptografia dos dados do usuário. | Não Funcional | Must | Média |
| RNF03 | Armazenamento persistente do progresso. | Não Funcional | Must | Média |
| RNF05 | Adaptabilidade para dispositivos móveis. | Não Funcional | Must | Baixa |
| RNF09 | Verificação de segurança no login. | Não Funcional | Must | Baixa |

Exportar para as Planilhas

## Should "Deveria ter"
A categoria Should inclui requisitos que são importantes para a experiência completa do usuário. O produto ainda seria viável sem eles, mas sua ausência seria notada. Estes itens adicionam valor significativo e devem ser implementados logo após a conclusão dos requisitos "Must".

### Requisitos Should

| ID | Descrição do Requisito | Tipo | Prioridade | Dificuldade |
|----|-----------------------|------|------------|------------|
| RF01.2 | Tutores com personalidades distintas. | Funcional | Should | Baixa |
| RF01.6 | Chatbot de IA para prática de voz. | Funcional | Should | Alta |
| RF01.7 | Tutores com Personalidades Distintas. | Funcional | Should | Baixa |
| RF02.1-4 | Dicionário com definições, pronúncia e exemplos. | Funcional | Should | Média |
| RF03.1 | Nível e Pontos de Experiência (XP). | Funcional | Should | Média |
| RF04.2 | Detecção de voz para avaliar pronúncia. | Funcional | Should | Alta |
| RF04.4 | Feedback sonoro para acertos/erros. | Funcional | Should | Baixa |
| RNF04 | Acesso rápido a atividades (< 3 cliques). | Não Funcional | Should | Baixa |
| RNF06 | Latência da fala para texto < 3s. | Não Funcional | Should | Média |
| RNF11 | Tempo de carregamento do app < 5s. | Não Funcional | Should | Média |


## Could "Poderia ter"
Os itens da categoria Could são desejáveis e de menor prioridade. Eles podem ser considerados para inclusão se houver tempo e recursos disponíveis, servindo para aprimorar e diferenciar o produto. Não são críticos para a versão inicial.

### Requisitos Could

| ID | Descrição do Requisito | Tipo | Prioridade | Dificuldade |
|----|-----------------------|------|------------|------------|
| RF01.8 | Pesquisa direta de definições. | Funcional | Could | Baixa |
| RF02.5 | Flashcards inteligentes. | Funcional | Could | Média |
| RF02.6-8 | Jogos de soletrar, ditado e quizzes. | Funcional | Could | Média |
| RF03.2 | Ranking entre amigos. | Funcional | Could | Média |
| RF03.3 | Missões semanais. | Funcional | Could | Baixa |
| RF03.4 | Mensagens motivacionais/sons de feedback. | Funcional | Could | Baixa |
| RF04.3 | Avisos sobre gírias e sotaques. | Funcional | Could | Média |
| RNF08 | Compatibilidade com acessibilidade. | Não Funcional | Could | Média |
| RNF10 | Atualização do banco sem reinstalação. | Não Funcional | Could | Alta |


## Won't "Não vai ter"
Por fim, a categoria Won’t inclui requisitos que foram definidos como fora do escopo para esta fase do projeto. A decisão de não implementá-los agora permite que a equipe foque os recursos nos itens de maior impacto.

### Requisitos Won't 

| ID | Descrição do Requisito | Tipo | Prioridade | Dificuldade |
|----|-----------------------|------|------------|------------|
| RF01.3 | IA com uso de câmera. | Funcional | Won't | Alta |
| RF01.4 | Conversa por carta. | Funcional | Won't | Baixa |
| RF01.5 | Conversação entre usuários. | Funcional | Won't | Média |




## Bibliografia

1. Leite, J. C. S. P., & Silva, C. T. (2005). *Rastreabilidade de Requisitos: Uma Revisão de Literatura*. Disponível em: [https://www.cos.ufrj.br/~jcspl/publications/monografias/20-05.pdf](https://www.cos.ufrj.br/~jcspl/publications/monografias/20-05.pdf)

2. Cohn, M. (2004). *User Stories Applied: For Agile Software Development*. Addison-Wesley. Disponível em: [https://www.mountaingoatsoftware.com/books/user-stories-applied](https://www.mountaingoatsoftware.com/books/user-stories-applied)



## Histórico de Versões

| Versão | Data de produção | Descrição da Alteração | Autor(es) | Revisor(es) | Data de Revisão |
|--------|----------------|----------------------|------------|------------|----------------|
| 1.0    | 04/09/2025     | Desenvolvimento do artefato. | [Mateus Bastos](https://github.com/MateuSansete) | [Revisor](https://github.com/Outro-Github) | 04/09/2025 |







