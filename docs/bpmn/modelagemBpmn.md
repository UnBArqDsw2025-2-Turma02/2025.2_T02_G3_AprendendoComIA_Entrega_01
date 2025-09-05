# Modelagem do BPMN

---

## Sumário

- [Técnica Utilizada](#Técnica-Utilizada)
- [Objetivos](#Objetivos)
- [Bibliografia](#bibliografia)
- [Histórico de Versões](#histórico-de-versões)

---

## Processos Modelados

A seguir, são apresentados os processos de negócio modelados com BPMN para este projeto.

### Processo 1: [Prática de conversação com IA]

**Descrição:** O processo descreve o fluxo de interação de um usuário com uma plataforma de conversação com IA, desde o primeiro acesso até a finalização da sessão. Ele integra ações do usuário, do sistema central (core) e de um sistema de gamificação, funcionando em um ciclo contínuo de prática, análise e feedback.

O diagrama está dividido em três raias (lanes): **Usuário**, **Sistema (Core)** e **Sistema de Gamificação**. O fluxo de trabalho também é categorizado em cinco fases: **Descoberta**, **Preparação**, **Interação e Análise**, **Feedback e Gamificação** e **Finalização**.

---

### Fluxo do Processo

O processo começa com o evento de **Início** (círculo verde).

#### Fase 1: Descoberta e Preparação
* O **Usuário** decide se quer **"Praticar"** ou apenas **"Explorar"** a plataforma.
* Para iniciar a prática, o usuário precisa **"Fazer Login"** ou fazer um **"Cadastro"**. O fluxo então converge para o **Sistema (Core)**, que **"Valida credenciais"**.
* Se as credenciais não forem válidas, o processo volta para o login/cadastro. Se forem válidas, o sistema **"Analisa acessos do app"** antes de iniciar a prática.

#### Fase 2: Interação e Análise
* O **Usuário** define os parâmetros da prática, escolhendo o **"Tema da conversa"** e o **"Nível de dificuldade"**.
* O **Sistema (Core)** recebe essas informações e **"Monta texto base"** para a conversação.
* Em seguida, começa o ciclo principal de interação: o sistema **"Apresenta/Classifica"** a pergunta/resposta e o **Usuário** **"Responde (fala ou escreve)"**.
* A cada resposta, o sistema entra em um **Sub-processo** para **"Avaliar Progresso Completo"**, que inclui análises internas, como a avaliação gramatical.

#### Fase 3: Feedback e Gamificação
* Após a avaliação, um gateway verifica se a sessão deve continuar. Se sim, o fluxo segue para a fase de gamificação.
* O **Sistema de Gamificação** **"Analisa Progresso e Métricas"** para fornecer feedback relevante.
* Simultaneamente, o **Sistema (Core)** pode **"Escolher mensagem motivacional"** e o **Sistema de Gamificação** pode **"Tocar som de campo"** (sons ambientais), criando uma experiência mais imersiva.

#### Fase 4: Finalização
* Ao final do ciclo de interação, o **Usuário** decide se **"Deseja continuar?"**.
* Se o usuário responder **"Não"**, o **Sistema (Core)** executa a tarefa **"Sessão finalizada"** e o processo termina no evento de **Fim** (círculo vermelho).
* Se o usuário responder **"Sim"**, o fluxo retorna para o início da fase de interação, permitindo que a prática continue.

<center>
  <span style="background-color:#c5a352; color:white; font-size:0.8em; font-weight: bold; padding:2px 6px; border-radius:4px;"> BPMN | Versão 1.0</span>
  <br>

![Bpmn](https://raw.githubusercontent.com/UnBArqDsw2025-2-Turma02/2025.2_T02_G3_AprendendoComIA_Entrega_01/refs/heads/main/docs/assets/BPNM.jpg)
<center> Autores: <a href="https://github.com/FelipeFreire-gf" target = "_blank">Felipe das Neves e Leonardo de Melo</a></center>



  <span style="background-color:#c5a352; color:white; font-size:0.8em; font-weight: bold; padding:2px 6px; border-radius:4px;"> Legenda BPMN | Versão 1.0</span>
  <br>

<div align="center">
<iframe width="50%" height="450" src="https://miro.com/app/board/uXjVJMHJOCk=/" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe>

 <p>Autores: <a href="https://github.com/UnBArqDsw2025-2-Turma02/2025.2_T02_G3_AprendendoComIA_Entrega_01">Arthur, Emivalto, Felipe, Gabriel, Leonardo, Pedro, Samuel e Vitor</a>.</p>

</div> 

![legenda bpmn](https://raw.githubusercontent.com/UnBArqDsw2025-2-Turma02/2025.2_T02_G3_AprendendoComIA_Entrega_01/refs/heads/main/docs/assets/LegendaBPNM.jpg)
<center> Autores: <a href="https://github.com/FelipeFreire-gf" target = "_blank">Felipe das Neves e Leonardo de Melo</a></center>

</center>
---

## Bibliografia

> <p><small>CONTENT STUDIO. O que é um dicionário de dados? Disponível em: <a href="https://www.purestorage.com/br/knowledge/what-is-a-data-dictionary.html">https://www.purestorage.com/br/knowledge/what-is-a-data-dictionary.html</a>. Acesso em: 30 abr. 2025.</small></p>

---

## Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | Incremento do Revisor|
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: | :-------------: |
| `1.0` | Modelagem inicial | [Felipe das Neves](https://github.com/FelipeFreire-gf) | 01/09/2025 | | | |
| `1.0` | Inserção do BPMN | [Felipe das Neves](https://github.com/FelipeFreire-gf) | 04/09/2025 | | | |