# Guia de Contribuição para Documentação

Este repositório segue um padrão colaborativo para organização da documentação de requisitos. Siga as orientações abaixo para mantermos um fluxo de trabalho claro e eficiente.

## Branches

Use nomes curtos, descritivos e separados por hífens:

| Tipo          | Padrão de nome              | Exemplo                      |
|---------------|-----------------------------|------------------------------|
| Funcionalidade| feature/nome-curto          | feature/caso-de-uso-login    |
| Correção      | fix/descricao               | fix/erro-ortografia          |
| Documento     | doc/tipo-de-arquivo         | doc/especificacao-supp       |
| Refatoração   | refactor/parte              | refactor/casos-de-uso        |

## Commits

Formato: `<tipo>: <descrição breve>`

### Tipos comuns:

- `feat`: nova funcionalidade ou artefato
- `fix`: correção de erro
- `doc`: atualização de documentação
- `refactor`: reorganização sem alterar conteúdo
- `style`: ajustes de formatação ou layout
- `chore`: tarefas gerais

### Exemplos:

- `doc: adicionar glossário inicial`
- `feat: adicionar caso de uso para login`
- `fix: corrigir diagrama de atividades do cadastro`
- `refactor: reorganizar seções do documento de requisitos`

## Issues

Use títulos claros e rótulos como: `documentação`, `revisão`, `bug`, `caso-de-uso`, `história de usuário`, `dúvida`.

### Exemplo:

**Título:** `[documentação] Adicionar caso de uso "Recuperar Senha"`

**Descrição:**

```markdown
## Tarefa
Adicionar o caso de uso "Recuperar Senha" no documento de requisitos funcionais.

## Checklist
- [ ] Criar branch feature/caso-de-uso-recuperar-senha
- [ ] Criar diagrama de caso de uso
- [ ] Especificar fluxo principal e alternativo
```

## Pull Requests (PRs)

**Título:** `[documentação] Adicionar caso de uso "Recuperar Senha"`

**Corpo do PR:**
```markdown
## O que foi feito
- Adicionado caso de uso "Recuperar Senha"
- Atualizado o diagrama de casos de uso

## Issue relacionada
Closes #12

## Checklist
- [x] Texto revisado
- [x] Diagrama adicionado
```

## Template de PR

Crie o arquivo `.github/pull_request_template.md` com o conteúdo abaixo:

```markdown
## Descrição
Descreva as alterações realizadas.

## Checklist
- [ ] Título do PR segue o padrão
- [ ] Conteúdo revisado por outro membro
- [ ] Issue relacionada foi mencionada

## Issue relacionada
Closes #
```
