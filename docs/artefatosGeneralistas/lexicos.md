# Léxico

---

## Sumário

- [Introdução](#Introdução)
- [Objetivo](#Objetivo)
- [Metodologia](#Metodologia)
- [Bibliografia](#bibliografia)
- [Histórico de Versões](#histórico-de-versões)

---

## Introdução

Léxico, por definição na linguística, é o repertório de palavras existentes numa determinada língua. Dentro de um escopo completamente diferente da linguística clássica, a engenharia de requisitos, o léxico é um artefato intrinsecamente importante num projeto de software, para que todos os vocábulos, ou seja, expressões oriundas do contexto em que esse software esteja inserido, sejam devidamente catalogados e definidos.
Os símbolos são definidos da seguinte forma:

  - **Noção**: é o que significa (denotação).
  - **Impacto**: descreve o efeito/uso/ocorrência do símbolo na aplicação ou no efeito de algo na aplicação sobre ele (conotação).
  - **Classificação**: estado, verbo ou objeto.
  - **Sinônimos**: símbolos/palavras diferentes que possuem significado similar ou idêntico. Opcional.
  
---

## Objetivo

O objetivo de se ter um documento de léxico, durante esse processo de modelagem de requisitos, é que a equipe de desenvolvimento e possíveis clientes e ou responsáveis pelo negócio, de maneira direta e denotativa, falem na mesma língua, ou seja, se entendam melhor, dentro do contexto do projeto.
É interessante salientar que esse é um artefato altamente mutável, portanto ele pode e deve ser alterado diversas vezes ao longo do desenvolvimento, conforme novos vocábulos surjam.

---

## Metodologia

Utilizaremos o modelo de tabela abaixo para registrar e definir cada palavra ao léxico:

### **Símbolo**

| Classificação | Noção | Impacto | Sinônimos |
| --- | --- | --- | --- |
| Objeto/Estado/Verbo | Denotação | Conotação | Opcional |

---

## Vocábulos

### L1 - Tutor de Conversação IA

| Classificação | Noção | Impacto | Sinônimos |
| --- | --- | --- | --- |
| Objeto | Funcionalidade de diálogo interativo com uma inteligência artificial para prática de inglês. | Permite ao usuário praticar conversação, receber correções em tempo real e treinar a pronúncia de palavras. | Chatbot com IA, Conversação com voz IA. |

### L2 - Personalidade da IA

| Classificação | Noção | Impacto | Sinônimos |
| --- | --- | --- | --- |
| Objeto | Diferentes "personas" ou estilos de conversação para o tutor de IA, podendo incluir variações de sotaques, regionalismos e gírias. | Aumenta o engajamento do usuário, oferecendo uma experiência de aprendizado mais dinâmica, divertida e adaptada a diferentes contextos culturais. | Tutores distintos, IAs com personalidade. |

### L3 - Detecção de Voz

| Classificação | Noção | Impacto | Sinônimos |
| --- | --- | --- | --- |
| Verbo | Ação de captar e analisar a fala do usuário para avaliação da pronúncia e dicção. | Fornece feedback sobre a pronúncia, ajudando o usuário a corrigir erros e aprimorar a dicção e a capacidade de soletrar palavras. | Análise de pronúncia. |

### L4 - Correção Gramatical

| Classificação | Noção | Impacto | Sinônimos |
| --- | --- | --- | --- |
| Objeto | Ferramenta que analisa textos e diálogos para identificar e sugerir correções de erros gramaticais. | Auxilia o usuário a entender e corrigir seus erros de escrita e fala, com feedback detalhado e sugestões. | Writing Correction, Análise de gramática. |

### L5 - Progresso de Aprendizagem

| Classificação | Noção | Impacto | Sinônimos |
| --- | --- | --- | --- |
| Objeto | Sistema de acompanhamento do desempenho do usuário, incluindo métricas como nível, pontos de experiência (XP) e posição em um ranking. | Motiva o usuário a continuar aprendendo através da gamificação, estabelecendo metas diárias e mostrando sua evolução. | Progress Tracking, Nível, XP. |

### L6 - Missões Semanais

| Classificação | Noção | Impacto | Sinônimos |
| --- | --- | --- | --- |
| Objeto | Tarefas ou metas específicas de prática (e.g., minutos de conversação, número de exercícios de escrita) a serem cumpridas pelo usuário em uma semana. | Engaja o usuário com desafios de curto prazo, incentivando o uso contínuo e consistente do aplicativo para formar um hábito de estudo. | Desafios, Metas. |

### L7 - Feedback Motivacional

| Classificação | Noção | Impacto | Sinônimos |
| --- | --- | --- | --- |
| Objeto | Retornos positivos e encorajadores, visuais (mensagens) e sonoros, exibidos ao usuário quando ele acerta uma questão ou atinge um objetivo. | Reforça positivamente o aprendizado, aumenta a confiança e mantém o usuário motivado durante as sessões de estudo. | Mensagens motivacionais, Sons de Acerto/Erro. |

### L8 - Vocabulário SRS

| Classificação | Noção | Impacto | Sinônimos |
| --- | --- | --- | --- |
| Objeto | Sistema de Repetição Espaçada para aprendizado de vocabulário. | Otimiza a memorização de novas palavras, apresentando-as ao usuário em intervalos crescentes para maior eficiência no aprendizado. | Spaced Repetition System. |

### L9 - Nível CEFR

| Classificação | Noção | Impacto | Sinônimos |
| --- | --- | --- | --- |
| Estado | Adaptação do conteúdo do aplicativo ao nível de proficiência do usuário, segundo o Quadro Europeu Comum de Referência para Línguas (A1-C1). | Garante que o usuário receba conteúdo e desafios adequados ao seu nível de conhecimento, tornando o aprendizado mais eficiente e personalizado. | Nível de proficiência. |

### L10 - Portabilidade

| Classificação | Noção | Impacto | Sinônimos |
| --- | --- | --- | --- |
| Objeto | Capacidade do aplicativo de ser executado em dispositivos móveis. | Permite que o usuário acesse e utilize a aplicação em diferentes plataformas, como smartphones, garantindo a continuidade dos estudos em qualquer lugar. | Versão mobile, Aplicativo para celular. |

### L11 - Gamificação

| Classificação | Noção | Impacto | Sinônimos |
| --- | --- | --- | --- |
| Objeto | Aplicação de elementos e mecânicas de jogos em contextos não-lúdicos para engajar e motivar os usuários. | É a estratégia central para manter o usuário engajado. Engloba o progresso de aprendizagem (L5), missões semanais (L6) e feedback motivacional (L7), criando uma experiência de estudo mais divertida e recompensadora. | Ludificação. |

### L12 - Flashcards Inteligentes

| Classificação | Noção | Impacto | Sinônimos |
| --- | --- | --- | --- |
| Objeto | Ferramenta de estudo baseada em cartões virtuais que utilizam o sistema de repetição espaçada (SRS) para otimizar a memorização. | Permite que o usuário pratique e memorize vocabulário de forma eficiente, fortalecendo a retenção de novas palavras aprendidas durante as conversações ou exercícios. Conecta-se diretamente com o "Vocabulário SRS" (L8). | Cartões de memorização, Deck de estudo. |

### L13 - Alfabeto Fonético Internacional (IPA)

| Classificação | Noção | Impacto | Sinônimos |
| --- | --- | --- | --- |
| Objeto | Sistema de notação fonética utilizado para representar os sons da fala de forma padronizada. | Oferece ao usuário uma referência visual precisa para a pronúncia correta das palavras, complementando a "Detecção de Voz" (L3) e auxiliando no aprimoramento do sotaque. | IPA, Notação Fonética. |

### L14 - Trilha de Aprendizado

| Classificação | Noção | Impacto | Sinônimos |
| --- | --- | --- | --- |
| Objeto | Caminho de estudo estruturado e sequencial, composto por diferentes atividades e desafios, que guia o usuário em sua jornada de aprendizado. | Personaliza a experiência do usuário com base em seu "Nível CEFR" (L9), garantindo que ele progrida de forma lógica e consistente, sem se sentir perdido ou sobrecarregado. | Jornada do usuário, Plano de estudos. |

### L15 - Interação Social

| Classificação | Noção | Impacto | Sinônimos |
| --- | --- | --- | --- |
| Objeto | Ação de conectar-se e competir com outros usuários da plataforma, como amigos, através de rankings e desafios. | Aumenta o engajamento e a retenção de usuários ao introduzir um elemento de competição saudável e comunidade. Está diretamente ligado a funcionalidades como "Ranking entre amigos" (RF17). | Socialização, Competição entre amigos. |

---

## Bibliografia

> 1.  SAYÃO, Miriam; CARVALHO, Gustavo. **Construção do léxico de aplicações**. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. Disponível em: [http://www-di.inf.puc-rio.br/\~julio/bnncap3.pdf/](http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf/).

> 2.  SERRANO, Milene. **Requisitos – Aula 10**. 2017. Apresentação de slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523091/mod\_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf).

> 3.  ZOWGHI, D.; COULIN, C. **Requirements Elicitation: A Survey of Techniques, Approaches and Tools**. Disponível em: [https://web.eecs.umich.edu/\~weimerw/2018-481/readings/requirements.pdf](https://web.eecs.umich.edu/~weimerw/2018-481/readings/requirements.pdf).

---

## Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | Incremento do Revisor|
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: | :-------------: |
| `1.0` | Construção do artefato 'Léxico'| [Leonardo de Melo](https://github.com/leozinlima) | 03/09/2025 | [Felipe das Neves](https://github.com/FelipeFreire-gf) | 03/09/2025  | Padronização na bibliográfia: correção no título do tópico 5, foi utilizado o título como "referência", mas como não teve a devida referênciação no texto, modifiquei para bibliografia. A ordem também estava fora de padronização, sendo o histórico de versões o ultimo tópico de cada documento.  |
| `1.1` | Inserção de novos Léxicos. | [Emivalto Junior](https://github.com/EmivaltoJrr) | 04/09/2025 | | | |