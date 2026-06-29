---
prompt_id: PRM-PILOTDASH-001
nome: Codex Pilot Success Dashboard
categoria: Codex Automation / Dashboard
versao: v1.0
status: Ativo
owner: Tech Lead
contexto: Piloto PMO Agentico Codex Slack para construtora de medio porte
uso: Criar especificacao e estrutura inicial do dashboard de sucesso do piloto
output_esperado: Dashboard spec + componentes + dados mockados + README
human_review: Obrigatorio
risk_level: Medio
---

# PROMPT - CODEX PILOT SUCCESS DASHBOARD

Voce e um agente Codex responsavel por criar a estrutura inicial do Pilot Success Dashboard do PMO Agentico Codex Slack para uma construtora de medio porte.

O dashboard deve demonstrar a saude do piloto de 3 a 6 meses, consolidando adocao, uso dos agentes, riscos, acoes, decisoes, evidencias, valor percebido e recomendacao Go/No-Go.

## Objetivo

Criar os arquivos iniciais do dashboard para o repositorio GitHub do projeto piloto.

## Contexto Funcional

O piloto acompanha:

1. Obras piloto.
2. Status reports semanais.
3. Riscos criticos.
4. Acoes e pendencias.
5. Decisoes executivas.
6. Evidencias coletadas.
7. Uso dos agentes.
8. Revisoes humanas.
9. Metricas de sucesso.
10. Feedback do sponsor.
11. Decisao Go/No-Go.

## Estrutura a Criar

```text
dashboards/pilot-success-dashboard/
|-- README.md
|-- pilot-success-dashboard-spec.md
|-- pilot-success-metrics-schema.json
|-- mock-data/
|   |-- pilot-overview.json
|   |-- agent-usage.json
|   |-- risk-summary.json
|   |-- action-summary.json
|   |-- decision-summary.json
|   |-- evidence-summary.json
|   `-- feedback-summary.json
`-- components/
    |-- PilotOverviewCard.md
    |-- PilotSuccessScoreCard.md
    |-- AgentUsageTable.md
    |-- RiskSummaryPanel.md
    |-- ActionHealthPanel.md
    |-- DecisionLogPanel.md
    |-- EvidenceReadinessPanel.md
    |-- HITLReviewPanel.md
    |-- FeedbackSummaryCard.md
    `-- GoNoGoPanel.md
```

## Regras Obrigatorias

- O dashboard deve diferenciar dados reais, dados mockados e lacunas.
- Metricas criticas devem indicar fonte e data de atualizacao.
- Go/No-Go deve ser recomendacao para revisao humana, nao decisao automatica.
- O dashboard deve evidenciar uso dos agentes e taxa de revisao HITL.
- Dados de risco, acao, decisao e evidencia devem ser rastreaveis aos registers.

