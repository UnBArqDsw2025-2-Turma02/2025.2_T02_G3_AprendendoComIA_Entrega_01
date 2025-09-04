# Metodologia BPMN

O BPMN (Business Process Model and Notation) é uma notação gráfica padronizada para desenhar processos de negócio de uma forma que seja compreensível para todas as partes interessadas, desde analistas de negócio e desenvolvedores até gestores. O objetivo principal do BPMN é fornecer uma linguagem comum que preencha a lacuna entre o design e a implementação de processos de negócio.

Para este projeto, utilizaremos o BPMN para modelar os fluxos de trabalho, identificar gargalos e propor melhorias, garantindo que a solução de software desenvolvida esteja alinhada com as necessidades e os processos do negócio.

---

## Sumário

- [Elementos do BPMN](#elementos-do-bpmn)
- [Ferramenta Utilizada](#ferramenta-utilizada)
- [Processos Modelados](#processos-modelados)
- [Bibliografia](#bibliografia)
- [Histórico de Versões](#histórico-de-versões)

---

## Elementos do BPMN

A notação BPMN é composta por um conjunto de elementos gráficos, que podem ser divididos em quatro categorias principais:

1.  **Objetos de Fluxo (Flow Objects):**
    *   **Eventos (Events):** Representados por círculos, indicam algo que acontece durante um processo (início, meio ou fim).
    *   **Atividades (Activities):** Representadas por retângulos de cantos arredondados, mostram o trabalho a ser realizado (uma tarefa ou um subprocesso).
    *   **Gateways:** Representados por losangos, são utilizados para controlar a divergência e a convergência do fluxo do processo (decisões, paralelismo).

2.  **Objetos de Conexão (Connecting Objects):**
    *   **Fluxo de Sequência (Sequence Flow):** Linha contínua com uma seta, mostra a ordem em que as atividades serão executadas.
    *   **Fluxo de Mensagem (Message Flow):** Linha tracejada, representa as mensagens trocadas entre diferentes participantes (piscinas).
    *   **Associação (Association):** Linha pontilhada, usada para associar informações e artefatos a objetos de fluxo.

3.  **Raias (Swimlanes):**
    *   **Piscinas (Pools):** Representam os principais participantes de um processo (ex: diferentes empresas ou departamentos).
    *   **Pistas (Lanes):** São subdivisões dentro de uma piscina, usadas para organizar as atividades por função ou papel (ex: "Gerente", "Analista").

4.  **Artefatos (Artifacts):**
    *   **Objeto de Dados (Data Object):** Mostra os dados necessários ou produzidos por uma atividade.
    *   **Grupo (Group):** Agrupa visualmente um conjunto de elementos, sem afetar o fluxo.
    *   **Anotação (Annotation):** Permite adicionar texto explicativo ao diagrama.

---

## Ferramenta Utilizada

Para a criação e modelagem dos diagramas BPMN neste projeto, a equipe utilizará o **Miro**.

O Miro é uma plataforma de lousa digital online e versátil que permite o trabalho colaborativo em tempo real. Embora não seja uma ferramenta dedicada exclusivamente ao BPMN, ele oferece templates e um conjunto de formas que o tornam adequado para a criação e discussão de diagramas de processo de forma colaborativa. Suas principais vantagens são a flexibilidade, a facilidade de uso e os recursos de colaboração, ideais para sessões de brainstorming e ciclos de desenvolvimento ágil da equipe.

---



## Bibliografia

> <p><small>CONTENT STUDIO. O que é um dicionário de dados? Disponível em: <a href="https://www.purestorage.com/br/knowledge/what-is-a-data-dictionary.html">https://www.purestorage.com/br/knowledge/what-is-a-data-dictionary.html</a>. Acesso em: 30 abr. 2025.</small></p>

> <p><small>BIZAGI. BPMN Tutorial. Disponível em: <a href="https://www.bizagi.com/pt/plataforma/modeler/tutorial-bpmn">https://www.bizagi.com/pt/plataforma/modeler/tutorial-bpmn</a>. Acesso em: 01 set. 2025.</small></p>

---

## Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | Incremento do Revisor|
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: | :-------------: |
| `1.0` | Modelagem inicial | [Felipe das Neves](https://github.com/FelipeFreire-gf) | 01/09/2025 | | | |
| `1.1` | Desenvolvimento do artefato | [Felipe das Neves](https://github.com/FelipeFreire-gf) | 03/09/2025 | | | |