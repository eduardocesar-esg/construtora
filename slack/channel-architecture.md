# Arquitetura de Canais Slack ou Teams

## Objetivo

Criar um cockpit operacional governado para capturar status, riscos, acoes, decisoes, evidencias, revisoes HITL e execucoes Codex.

## Canais

| Canal | Finalidade | Owner |
|---|---|---|
| `#pmo-agentico-piloto` | Comunicacao geral do piloto | PMO Lead |
| `#obra-001-status` | Status e atualizacoes da Obra 001 | Gerente da obra |
| `#obra-002-status` | Status e atualizacoes da Obra 002 | Gerente da obra |
| `#obra-003-status` | Status e atualizacoes da Obra 003 | Gerente da obra |
| `#pmo-riscos-obras` | Riscos, alertas e mitigacoes | PMO Lead |
| `#pmo-acoes-pendencias` | Acoes, owners, prazos e bloqueios | PMO Lead |
| `#pmo-evidencias` | Evidencias, lacunas e validacoes | PMO Lead |
| `#pmo-decision-log` | Decisoes tomadas, pendentes e recomendadas | Sponsor/PMO |
| `#pmo-hitl-review` | Revisao humana de outputs | AI Governance Lead |
| `#pmo-governance-board` | Governanca de prompts, agentes e artefatos | PMO/Tech Lead |
| `#pmo-codex-runs` | Execucoes Codex, outputs e erros | Tech Lead |

## Regras

- Canal nao substitui register oficial.
- Toda decisao deve ter `decision_id`.
- Todo risco critico deve ter `risk_id`.
- Toda acao critica deve ter `action_id`.
- Toda evidencia relevante deve ter `evidence_id`.
- Todo output de agente deve ter `run_id` quando usado oficialmente.

