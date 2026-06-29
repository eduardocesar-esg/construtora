# Fase 2 - Piloto PMO Agentico Codex Slack para Construtora Medio Porte

## Objetivo

Implantar o ciclo operacional minimo governado do piloto, saindo do diagnostico/status e entrando na rotina:

Status -> Risco -> Acao -> Decisao -> Evidencia -> Dashboard de Sucesso do Piloto

## Agentes da Fase 2

| Prompt | Agente | Finalidade | Saida esperada | HITL |
|---|---|---|---|---|
| PRM-RISK-001 | Agente de Riscos de Obras | Identificar, classificar e recomendar respostas a riscos | Risk Analysis Report + atualizacao sugerida do Risk Register | Obrigatorio |
| PRM-ACTION-001 | Agente de Acoes e Pendencias | Consolidar follow-ups, owners e prazos | Action Review Report + atualizacao sugerida do Action Log | Obrigatorio |
| PRM-DECISION-001 | Agente de Decisoes | Registrar decisoes, alternativas, impactos e responsaveis | Decision Brief + atualizacao sugerida do Decision Log | Obrigatorio |
| PRM-EVIDENCE-001 | Agente de Evidencias | Organizar provas, fotos, atas, medicoes, documentos e lacunas | Evidence Pack + atualizacao sugerida do Evidence Log | Obrigatorio |
| PRM-PILOTDASH-001 | Agente Codex de Dashboard do Piloto | Criar especificacao e estrutura inicial do painel de sucesso | Dashboard spec + componentes + dados mockados + README | Obrigatorio |

## Fluxo Operacional

1. O status report semanal identifica desvios e pontos de atencao.
2. O Agente de Riscos transforma desvios, sinais e lacunas em matriz de riscos.
3. O Agente de Acoes converte riscos, decisoes e pendencias em follow-ups com owner, prazo e criticidade.
4. O Agente de Decisoes separa decisoes tomadas, pendentes e recomendadas.
5. O Agente de Evidencias relaciona fotos, atas, medicoes e documentos aos itens de status, risco, acao e decisao.
6. O Dashboard de Sucesso consolida saude do piloto, uso dos agentes, revisoes humanas, valor percebido e recomendacao Go/No-Go.

## Regras de Governanca

- Agentes podem sugerir, estruturar, classificar e consolidar.
- Agentes nao aprovam riscos, nao alteram baseline, nao encerram acoes e nao registram decisao executiva como aprovada sem evidencia humana.
- Toda saida critica deve passar pelo `templates/human-review-template.md`.
- Toda revisao de saida de agente deve ser registrada em `governance/agent-output-review-log.csv`.
- Dados ausentes devem aparecer como lacuna, nao como inferencia.

## Entregaveis GitHub

| Grupo | Arquivos |
|---|---|
| Prompts | `prompts/PRM-RISK-001-risk-agent-obras.md`, `prompts/PRM-ACTION-001-action-agent-obras.md`, `prompts/PRM-DECISION-001-decision-log-agent.md`, `prompts/PRM-EVIDENCE-001-evidence-agent-obras.md`, `prompts/PRM-PILOTDASH-001-pilot-success-dashboard-codex.md` |
| Registers | `registers/risk-register.csv`, `registers/action-log.csv`, `registers/decision-log.csv`, `registers/evidence-log.csv`, `registers/pilot-success-metrics.csv` |
| Templates | `templates/risk-analysis-output-template.md`, `templates/action-review-template.md`, `templates/decision-record-template.md`, `templates/evidence-pack-template.md`, `templates/pilot-dashboard-spec-template.md` |
| Dashboard | `dashboards/pilot-success-dashboard/` |
| Governanca | `governance/prompt-review-checklist.md`, `governance/agent-output-review-log.csv`, `governance/hitl-policy.md` |

