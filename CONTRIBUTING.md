Primeiramente, obrigado pelo seu interesse em contribuir! Este é um projeto de estudo e toda colaboração é uma oportunidade de aprendizado.

## Fluxo de Trabalho (Workflow)

Utilizamos um fluxo simples para manter o projeto organizado:

### 1. Issues

Para cada nova tarefa (feature, bug, etc.), uma issue deve ser criada no nosso quadro Kanban no GitHub.

### 2. Branches

- **`main`**: Contém o código de produção/estável. Apenas merges de `dev` são permitidos.
- **`dev`**: Branch de desenvolvimento principal. Todo o trabalho em andamento é integrado aqui.
- **`feat/<resumo>`**: Para novas funcionalidades (ex: `feat/cria-pagina-contato`).
- **`fix/<resumo>`**: Para correção de bugs (ex: `fix/corrige-link-quebrado-footer`).
- Sempre crie sua branch a partir da `dev`.

### 3. Commits

- Use o padrão [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) (ou uma versão simplificada).
- Exemplos: `feat:`, `fix:`, `docs:`, `style:`, `refactor:`, `test:`, `chore:`.
- Exemplo de mensagem: `feat: adiciona formulário de contato com validação básica`.

### 4. Pull Requests (PRs)

- Ao concluir sua tarefa, abra um Pull Request da sua branch para a `dev`.
- Utilize o `PULL_REQUEST_[TEMPLATE.md](http://TEMPLATE.md)` para descrever suas mudanças.
- **Associe o PR à issue correspondente.**
- Aguarde a revisão cruzada. O outro membro da dupla deve revisar e aprovar as mudanças.
- Após a aprovação, o merge será feito usando "Squash and merge" para manter o histórico da `dev` limpo.

---

## Definição de Pronto (Definition of Done - DoD)

Uma tarefa só é considerada "Pronta" quando:

- ✅ O código HTML abre no navegador sem erros de renderização.
- ✅ Foram aplicadas boas práticas de semântica (tags como `<header>`, `<main>`, `<nav>`, `<section>`, etc.).
- ✅ Acessibilidade básica foi considerada (ex: `lang="pt-BR"`, `alt` em imagens, `label` associado a `input`).
- ✅ O checklist da tarefa na issue foi completamente marcado.
- ✅ O Pull Request foi revisado e aprovado pelo outro membro da equipe.

---

## Configuração do Ambiente

Para a v1.0.0, não há necessidade de dependências. Apenas um editor de código (como o VS Code) e um navegador são suficientes.