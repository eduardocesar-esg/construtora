# Piloto PMO AGENTICO CODEX SLACK para Gestao de Obras, Riscos e Status Executivo

Repositorio governado para o piloto de PMO Agentico em construtora de medio porte.

## Objetivo

Validar, em ambiente controlado, o uso de Codex, GitHub e Slack/Teams como apoio a gestao executiva de obras, riscos, pendencias, evidencias e decisoes, mantendo validacao humana obrigatoria para artefatos sensiveis.

## Duracao Recomendada

O piloto esta estruturado em dois ciclos:

| Ciclo | Duracao | Objetivo |
|---|---:|---|
| Ciclo 1 - MVP Controlado | 90 dias | Validar status report, riscos, pendencias, evidencias e governanca HITL em 2 a 4 obras. |
| Ciclo 2 - Expansao Assistida | +90 dias | Ampliar para mais obras, consolidar dashboard executivo, refinar prompts e preparar rollout. |

## Escopo Inicial

1. Status executivo das obras
2. Matriz de riscos agentica
3. Controle de acoes e pendencias
4. Registro de decisoes
5. Registro de evidencias
6. Dashboard executivo inicial
7. Slack ou Teams como cockpit operacional
8. GitHub como repositorio governado de prompts, templates e artefatos
9. Codex como agente de apoio a criacao, revisao e versionamento dos artefatos

## Metodologia

O piloto segue a trilha:

MVP -> Piloto -> Operacao Assistida -> Evidencia de Valor -> Ajustes -> Segundo Ciclo -> Rollout -> Escala

## Pastas Principais

| Pasta/arquivo | Finalidade |
|---|---|
| `prompts/` | Prompts versionados e reutilizaveis |
| `agents/` | Agent cards com papel, limites e governanca |
| `templates/` | Modelos de status, risco, reporte executivo e revisao humana |
| `slack/` | Estrutura de canais e mensagens operacionais |
| `dashboards/` | Especificacao do dashboard executivo |
| `governance/` | RACI, politica HITL, governanca de prompts e ciclo de vida |
| `registers/` | Logs operacionais da Fase 2 para riscos, acoes, decisoes, evidencias e metricas |
| `*-register.csv` | Registros governados de artefatos, agentes, prompts, riscos, decisoes, acoes e evidencias |

## Principios de Governanca

- Nenhuma decisao critica deve ser automatizada sem aprovacao humana.
- Todo artefato relevante deve ter owner, versao, status, local no GitHub, evidencia e ciclo de revisao.
- Toda recomendacao de agente deve ser rastreavel ate dados, evidencias ou premissas.
- Prompts, templates e dashboards devem evoluir por versao, com historico e aprovacao.
- O piloto deve comecar pequeno, mensuravel e auditavel.

## Fase 2 - Ciclo Operacional Governado

A Fase 2 aprofunda o fluxo operacional minimo:

Status -> Risco -> Acao -> Decisao -> Evidencia -> Dashboard de Sucesso do Piloto

Essa fase implanta os agentes PRM-RISK-001, PRM-ACTION-001, PRM-DECISION-001, PRM-EVIDENCE-001 e PRM-PILOTDASH-001, mantendo revisao humana obrigatoria antes de alteracao de dados criticos, envio ao sponsor ou publicacao executiva.

## Fase 3 - Industrializacao do Piloto

A Fase 3 transforma o piloto em um sistema governado e escalavel, com registers padronizados, schemas, data contracts, cockpit Slack/Teams, quality gate HITL, relatorio executivo de valor e preparacao para rollout por ondas.

Entregaveis principais:

- Register Factory em `registers/`, `schemas/` e `data-contracts/`.
- Cockpit operacional em `slack/`.
- Quality Gate HITL em `governance/`.
- QBR Value Report e Rollout Recommendation em `reports/`.
- Prompts oficiais PRM-REGFACTORY-001 a PRM-ROLLOUT-001.

## Fase 4 - Execucao Controlada do Setup

A Fase 4 operacionaliza o setup inicial antes do uso amplo de dados reais. O piloto comeca com 1 obra, dados minimos, execucao assistida por Codex e validacao humana antes de qualquer publicacao executiva.

Entregaveis principais:

- Prompt mestre e Sprint 0 em `codex/`.
- Checklist bloqueante de publicacao em `governance/pre-publication-validation-checklist.md`.
- Intake de dados minimos da obra em `docs/minimum-worksite-data.md`.
- Plano de 10 dias uteis em `docs/next-10-business-days-plan.md`.
- Logs de execucao controlada em `registers/setup-execution-log.csv` e `registers/pre-publication-review-log.csv`.

## Sprint 1 e Sprint 1.1 - Primeira Execucao Assistida

Depois do setup controlado, o piloto entra na primeira execucao operacional com 1 obra piloto.

- Sprint 1: gerar a primeira linha de base operacional com diagnostico, status, riscos, acoes, decisoes, evidencias e revisao HITL.
- Sprint 1.1: corrigir lacunas, ajustar prompts/templates/registers e preparar a cadencia semanal recorrente.

Entregaveis principais:

- Runbooks em `codex/sprint-1-first-assisted-execution.md` e `codex/sprint-1-1-stabilization-cycle.md`.
- Plano executivo em `docs/sprint-1-and-1-1-execution-plan.md`.
- Registro de execucao em `registers/sprint-execution-log.csv`.
- Template de review em `templates/sprint-review-template.md`.
