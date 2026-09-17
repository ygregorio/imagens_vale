# 15 — Git e Pull Requests

Convenção Facilities alinhada ao Vale Flow corporativo. Detalhe no pacote: `vale-doc-arquitetura-kit` / `docs/08-git-pr.md`.

## Branch

`feature/<wi-id>-curto`, `fix/<wi-id>-curto` ou `hotfix/<wi-id>-curto`, sempre nascendo de `main` → PR.

Com promoção entre ambientes: PR entra em `release/<versao>` e a `release` volta para `main` depois de estável em produção. Sem promoção (ETL direto em VM): PR direto em `main`.

## Commits

Prefixos: `feat`, `fix`, `docs`, `refactor`, `test`, `chore`, `ci`, `security`.

## PR

- [ ] Objetivo claro
- [ ] **WI relacionado**
- [ ] Testes / validação descritos
- [ ] Docs atualizados se impacto
- [ ] Sem segredos no diff
- [ ] Deploy/rollback se aplicável

Checklist colável: `vale-doc-arquitetura-kit/app/templates/pr-checklist.md`.
