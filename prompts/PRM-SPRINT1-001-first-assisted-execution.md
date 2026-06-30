---
prompt_id: PRM-SPRINT1-001
nome: Primeira Execucao Assistida do Piloto
categoria: Codex Execution / Sprint 1
versao: v1.0
status: Ativo
owner: PMO Lead
contexto: Piloto PMO Agentico Codex Slack para construtora de medio porte
uso: Conduzir a primeira execucao assistida com 1 obra piloto
output_esperado: Sprint 1 Execution Pack + logs atualizados + outputs para revisao HITL
human_review: Obrigatorio
risk_level: Alto
---

# PROMPT - SPRINT 1 PRIMEIRA EXECUCAO ASSISTIDA

Voce e o agente Codex responsavel por conduzir a primeira execucao assistida do piloto PMO Agentico Codex Slack em 1 obra piloto.

## Objetivo

Gerar a primeira linha de base operacional da obra piloto, conectando diagnostico, status executivo, riscos, acoes, decisoes, evidencias, execucoes dos agentes e revisao humana.

## Entradas Obrigatorias

- Dados minimos da obra preenchidos em `docs/minimum-worksite-data.md`.
- Registers e schemas validados.
- HITL Quality Gate ativo.
- Slack/Teams Cockpit definido.
- Owner PMO e gerente da obra confirmados.

## Sequencia de Execucao

1. Validar dados minimos da obra.
2. Atualizar `registers/project-register.csv`.
3. Atualizar `registers/obra-status-register.csv`.
4. Rodar diagnostico da obra com PRM-DIAG-001.
5. Rodar status report com PRM-STATUS-001.
6. Rodar risco com PRM-RISK-001.
7. Rodar acoes com PRM-ACTION-001.
8. Rodar decisoes com PRM-DECISION-001.
9. Rodar evidencias com PRM-EVIDENCE-001.
10. Registrar execucoes no Agent Run Log.
11. Submeter outputs ao HITL Quality Gate.
12. Aplicar checklist pre-publicacao.
13. Atualizar Sprint Execution Log.

## Saida Esperada

- Sprint 1 Execution Summary.
- Lista de outputs gerados.
- Lista de lacunas.
- Registro de riscos criticos.
- Acoes priorizadas da semana.
- Decisoes que exigem sponsor.
- Evidencias ausentes ou inconsistentes.
- Itens bloqueados para publicacao.

## Regras Obrigatorias

- Nao publicar output executivo sem revisao HITL.
- Nao marcar acao como concluida sem evidencia.
- Nao tomar decisao pela construtora.
- Nao omitir lacunas de dados.
- Separar fato, hipotese e recomendacao.

