# Data Contracts - Register Factory

Contratos de dados da Fase 3 para padronizar entradas e saidas consumidas por agentes, dashboards, revisao humana e relatorios executivos.

## Regras Gerais

- Campos obrigatorios nao devem ficar vazios.
- IDs devem ser estaveis e rastreaveis.
- Alteracoes de campos devem ser revisadas por Tech Lead e PMO Lead.
- Dados criticos devem ter evidencia e status de revisao humana.
- Campos de status devem respeitar os valores controlados dos schemas.

## Contratos

| Register | Contrato | Schema |
|---|---|---|
| `project-register.csv` | `project-register-data-contract.md` | `schemas/project-register.schema.json` |
| `obra-status-register.csv` | `obra-status-data-contract.md` | `schemas/obra-status-register.schema.json` |
| `risk-register.csv` | `risk-register-data-contract.md` | `schemas/risk-register.schema.json` |
| `action-log.csv` | `action-log-data-contract.md` | `schemas/action-log.schema.json` |
| `decision-log.csv` | `decision-log-data-contract.md` | `schemas/decision-log.schema.json` |
| `evidence-log.csv` | `evidence-log-data-contract.md` | `schemas/evidence-log.schema.json` |
| `agent-run-log.csv` | `agent-run-log-data-contract.md` | `schemas/agent-run-log.schema.json` |
| `output-review-log.csv` | `output-review-log-data-contract.md` | `schemas/output-review-log.schema.json` |
| `pilot-success-metrics.csv` | `pilot-success-metrics-data-contract.md` | `schemas/pilot-success-metrics.schema.json` |

