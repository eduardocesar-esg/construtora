# Fase 3 - Industrializacao do Piloto PMO Agentico Codex Slack para Construtora

## Objetivo

Transformar o piloto em um sistema governado, auditavel e preparado para escala, conectando Codex, GitHub, Slack/Teams, dados, logs, agentes, dashboards, seguranca, governanca HITL e evidencias de valor.

## Mudanca de Maturidade

Na Fase 1 e Fase 2, o foco foi validar o MVP operacional. Na Fase 3, o piloto passa a operar como plataforma governada:

1. Registers padronizados.
2. Schemas JSON e data contracts.
3. Cockpit Slack/Teams.
4. Quality Gate de revisao humana.
5. QBR Value Report.
6. Go/No-Go Scorecard.
7. Planejamento de rollout por ondas.

## Prompts Oficiais

| Ordem | Prompt | Finalidade |
|---:|---|---|
| 9 | PRM-REGFACTORY-001 | Criar registers padronizados, schemas e data contracts |
| 10 | PRM-SLACKCOCKPIT-001 | Estruturar cockpit operacional no Slack/Teams |
| 11 | PRM-HITLQA-001 | Criar gate de revisao humana e qualidade dos outputs |
| 12 | PRM-QBRVALUE-001 | Gerar relatorio executivo de valor do piloto |
| 13 | PRM-ROLLOUT-001 | Preparar Go/No-Go e plano de expansao por ondas |

## Arquitetura de Industrializacao

```text
Status reports
  -> registers padronizados
  -> schemas e contratos de dados
  -> execucoes de agentes
  -> revisao HITL
  -> cockpit Slack/Teams
  -> dashboard e QBR
  -> scorecard Go/No-Go
  -> rollout por ondas
```

## Entregaveis GitHub

| Grupo | Arquivos |
|---|---|
| Prompts | `prompts/PRM-REGFACTORY-001-register-factory-codex.md`, `prompts/PRM-SLACKCOCKPIT-001-slack-cockpit-obras.md`, `prompts/PRM-HITLQA-001-human-review-quality-gate.md`, `prompts/PRM-QBRVALUE-001-qbr-value-report.md`, `prompts/PRM-ROLLOUT-001-wave-rollout-planning.md` |
| Schemas | `schemas/*.schema.json` |
| Data contracts | `data-contracts/*-data-contract.md` |
| Slack/Teams | `slack/channel-architecture.md`, `slack/workflow-templates.md`, `slack/message-templates.md`, `slack/escalation-rules.md` |
| Governanca | `governance/human-review-quality-gate.md`, `governance/output-review-checklist.md`, `governance/output-review-log.csv`, `governance/output-risk-classification.md`, `governance/go-no-go-scorecard.csv`, `governance/rollout-readiness-checklist.md` |
| Reports | `reports/qbr-value-report-template.md`, `reports/rollout-recommendation-template.md` |

## Principios

- Nada critico e publicado sem revisao humana.
- Nenhum dado ausente deve virar inferencia silenciosa.
- Todo output de agente deve ser rastreavel a prompt, run, evidencia, revisor e status.
- Go/No-Go e recomendacao estruturada, nao decisao automatica.
- Rollout so avanca se houver valor, governanca, dados minimos, HITL funcionando e sponsor engajado.

