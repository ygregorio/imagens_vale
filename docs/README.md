# Documentação técnica — <!-- TODO: Nome da Solução -->

<!-- TODO: Parágrafo introdutório: o que a solução faz, de onde vêm os dados e para onde vão. -->

**Projeto Azure DevOps:** [<!-- TODO: Nome do Projeto -->](<!-- TODO: URL -->) · Organização `vale-devops`

**Solução relacionada:** <!-- TODO: link para projeto upstream/downstream -->

**Caminho:** lite <!-- TODO: lite \| full — ver 00-enquadramento -->

---

## Índice

| # | Documento | Descrição |
|---|-----------|-----------|
| 00 | [Enquadramento](00-enquadramento.md) | Lite/full, owner, IDs Boards |
| 01 | [Visão geral](01-visao-geral.md) | Contexto, objetivo, escopo e premissas |
| 02 | [Arquitetura](02-arquitetura.md) | Componentes, fluxo de dados, diagramas |
| 03 | [Inventário de arquivos](03-inventario-arquivos.md) | Scripts, módulos, responsabilidades |
| 04 | [Parâmetros e configuração](04-parametros-configuracao.md) | Env vars, cofre, CLI, arquivos de parâmetro |
| 05 | [Queries / integrações](05-queries-hana.md) | <!-- TODO: HANA, API Graph, etc. --> |
| 07 | [Modelo de dados de saída](07-modelo-dados-saida.md) | Colunas, tipos, chaves |
| 09 | [Operação (runbook)](09-operacao-runbook.md) | Execução, logs, troubleshooting |
| 10 | [Testes e validação](10-testes-validacao.md) | Cenários, critérios de aceite |
| 12 | [Azure DevOps](12-azure-devops.md) | Publicação, Wiki VPS vs operacional, Registry |
| 13 | [Deploy VM](13-devops-deploy-vm.md) | Implantacao, agendamento, checklist |
| 14 | [DoR / DoD](14-dor-dod.md) | Pronto para iniciar / concluir |
| 15 | [Git / PR](15-git-pr.md) | Branch, commits, checklist PR |
| 17 | [Catálogo Tech4All](17-tech4all-catalogo.md) | Rascunho para cadastro no Power Apps (condicional) |

> Remova linhas da tabela cujos documentos não se aplicam ao seu projeto. Mantenha `00`, `14` e `15` em demandas Torre.

---

## Versão documentada

| Campo | Valor |
|-------|-------|
| Solução | <!-- TODO: nome --> |
| Entry point | `<!-- TODO: script.py -->` v<!-- TODO: versão --> |
| Ambiente | <!-- TODO: HANA LP0, Azure PRD, etc. --> |
| Data da documentação | <!-- TODO: mês/ano --> |

---

## Leitura recomendada por perfil

| Perfil | Documentos |
|--------|------------|
| Desenvolvedor / sustentação | 00, 02, 03, 04, 05, 09, 14, 15 |
| Analista de negócio | 00, 01, 07, 17 |
| Operação / VM | 04, 09, 10, 13 |
| DevOps / publicação | 12, 13, 15 |
| DBA / Azure SQL | 07, `sql/` |
| PO / coordenação | 00, 14, 17 |
