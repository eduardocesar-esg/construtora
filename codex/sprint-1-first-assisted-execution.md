# Sprint 1 - Primeira Execucao Assistida

## Objetivo

Executar a primeira rodada operacional com 1 obra piloto, gerando outputs iniciais para revisao humana e estabelecendo a linha de base do piloto.

## Pre-condicoes

| Pre-condicao | Status | Evidencia | Owner |
|---|---|---|---|
| Obra piloto confirmada |  |  | Sponsor / PMO Lead |
| Dados minimos obrigatorios coletados |  |  | Gerente da obra |
| Registers e schemas validados |  |  | Tech Lead |
| HITL Quality Gate ativo |  |  | AI Governance Lead |
| Slack/Teams Cockpit definido |  |  | PMO Lead |
| Revisor humano nomeado |  |  | PMO Lead |

## Execucao

| Ordem | Acao | Prompt/Artefato | Saida | Log |
|---:|---|---|---|---|
| 1 | Validar dados minimos | `docs/minimum-worksite-data.md` | Readiness da obra | `sprint-execution-log.csv` |
| 2 | Atualizar cadastro da obra | `project-register.csv` | Projeto registrado | `project-register.csv` |
| 3 | Registrar status base | `obra-status-register.csv` | Status inicial | `obra-status-register.csv` |
| 4 | Rodar diagnostico | PRM-DIAG-001 | Diagnostico inicial | `agent-run-log.csv` |
| 5 | Rodar status report | PRM-STATUS-001 | Status executivo draft | `agent-run-log.csv` |
| 6 | Rodar riscos | PRM-RISK-001 | Risk Analysis Report | `agent-run-log.csv` |
| 7 | Rodar acoes | PRM-ACTION-001 | Action Review Report | `agent-run-log.csv` |
| 8 | Rodar decisoes | PRM-DECISION-001 | Decision Brief | `agent-run-log.csv` |
| 9 | Rodar evidencias | PRM-EVIDENCE-001 | Evidence Pack | `agent-run-log.csv` |
| 10 | Revisar outputs | HITL Quality Gate | Outputs aprovados/bloqueados | `output-review-log.csv` |
| 11 | Aplicar pre-publicacao | PRM-PREPUBLICATION-001 | Parecer de publicacao | `pre-publication-review-log.csv` |

## Definition of Done

- Todos os outputs da Sprint 1 foram gerados ou tiveram lacuna declarada.
- Todo output critico passou por revisao HITL.
- Riscos criticos possuem owner ou lacuna registrada.
- Acoes criticas possuem owner, prazo ou lacuna registrada.
- Decisoes executivas estao marcadas para sponsor.
- Evidencias ausentes foram registradas.
- Itens publicaveis passaram no checklist pre-publicacao.

