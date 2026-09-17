# 14 — Definition of Ready / Done

Fonte lite: playbook Torre (`torre-gestao-projetos` / `docs/14-dor-dod.md`). DoR/DoD **só de documentação Git**: pacote `vale-doc-arquitetura-kit` / `docs/10-dor-dod-docs.md`.

## DoR — lite (mínimo)

- [ ] Relacionado ao nível superior (Feature/Epic) quando existir
- [ ] Problema e valor claros
- [ ] Owner e critérios de aceite
- [ ] Critérios testáveis (Dado/Quando/Então ou checklist)
- [ ] Dependências, dados e acessos avaliados
- [ ] Classificação / segurança (sem segredo no Git)
- [ ] Impacto arquitetural (nenhum / ADR se mudança dura)
- [ ] Estimativa ou tamanho compatível com sprint
- [ ] Prioridade aprovada pelo PO/owner
- [ ] Bloqueios tratados ou explícitos

## DoD — lite (mínimo)

- [ ] Implementação no branch
- [ ] Revisão + PR mergeado (ou equivalente aprovado)
- [ ] Testes / validação do aceite
- [ ] Alertas críticos tratados (se houver monitoramento)
- [ ] Documentação Git atualizada
- [ ] ADR/HLD se decisão arquitetural
- [ ] Logs/monitoramento mínimos se job agendado
- [ ] Rollback conhecido (reprocessar / restaurar / desligar task)
- [ ] Ausência de segredos no histórico recente do PR
- [ ] Evidências (link WI, PR, captura se preciso)
- [ ] Aceite do PO/owner
- [ ] Release notes curtas (changelog ou comentário no WI)

## Full (adicional)

Business Case / LeanIX / benefícios — só se `docs/00` disser **full**. Validar normas no SISPAV (`APLICABILIDADE A VALIDAR`).
