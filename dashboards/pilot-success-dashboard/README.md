# Pilot Success Dashboard

Dashboard de sucesso do piloto PMO Agentico Codex Slack para construtora de medio porte.

## Objetivo

Consolidar a saude do piloto de 3 a 6 meses, acompanhando adocao, uso dos agentes, riscos, acoes, decisoes, evidencias, revisoes humanas, valor percebido e recomendacao Go/No-Go.

## Estrutura

| Caminho | Finalidade |
|---|---|
| `pilot-success-dashboard-spec.md` | Especificacao funcional do dashboard |
| `pilot-success-metrics-schema.json` | Schema das metricas de sucesso |
| `mock-data/` | Dados mockados para prototipacao |
| `components/` | Especificacao dos componentes visuais |

## Fontes Governadas

- `registers/pilot-success-metrics.csv`
- `registers/risk-register.csv`
- `registers/action-log.csv`
- `registers/decision-log.csv`
- `registers/evidence-log.csv`
- `governance/agent-output-review-log.csv`

## Regra HITL

A recomendacao Go/No-Go e uma sugestao estruturada para sponsor e PMO. A decisao final e humana.

