# Pilot Success Dashboard Spec

## Proposito

Demonstrar se o piloto esta gerando valor mensuravel, com governanca suficiente para avancar, ajustar, pausar ou encerrar.

## Principais Perguntas

1. As obras piloto estao gerando status report semanal confiavel?
2. Riscos criticos estao identificados, com owner e resposta?
3. Acoes possuem prazo, owner e acompanhamento?
4. Decisoes executivas estao registradas com contexto e evidencia?
5. Evidencias sustentam status, riscos, acoes e decisoes?
6. Agentes estao sendo usados de forma regular e revisada por humanos?
7. O sponsor percebe valor suficiente para o segundo ciclo ou rollout?

## Indicadores

| Indicador | Meta | Fonte | Frequencia |
|---|---:|---|---|
| Status reports no prazo | 100% | Status reports | Semanal |
| Riscos criticos com owner | >= 90% | Risk Register | Semanal |
| Acoes com prazo | >= 90% | Action Log | Semanal |
| Decisoes com evidencia | >= 95% | Decision Log | Semanal |
| Itens criticos com evidencia suficiente | >= 80% | Evidence Log | Semanal |
| Cobertura HITL | 100% | Agent Output Review Log | Semanal |
| Feedback do sponsor | Positivo | Feedback summary | Por ciclo |

## Componentes

- PilotOverviewCard.
- PilotSuccessScoreCard.
- AgentUsageTable.
- RiskSummaryPanel.
- ActionHealthPanel.
- DecisionLogPanel.
- EvidenceReadinessPanel.
- HITLReviewPanel.
- FeedbackSummaryCard.
- GoNoGoPanel.

## Regras de Interpretacao

- Dados ausentes reduzem confianca do score.
- Dados mockados nao devem ser usados em decisao real.
- Saidas criticas sem revisao humana devem aparecer como bloqueio de governanca.
- Go/No-Go e recomendacao, nao decisao automatica.

