# Message Templates - Slack Cockpit

## Status de Obra

```text
[STATUS OBRA] {obra} | {periodo}
Semaforo geral: {Verde/Amarelo/Vermelho}
Prazo: {status_prazo}
Custo: {status_custo}
Qualidade: {status_qualidade}
Seguranca: {status_seguranca}
Suprimentos: {status_suprimentos}
Principais desvios: {desvios}
Riscos: {risk_ids}
Decisoes necessarias: {decision_ids}
Evidencias: {evidence_ids}
Revisao humana: {status}
```

## Risco Critico

```text
[RISCO CRITICO] {obra}
Risk ID: {risk_id}
Categoria: {categoria}
Classificacao: {classificacao}
Impacto: {impacto}
Owner: {owner}
Resposta recomendada: {resposta}
Decisao requerida: {Sim/Nao}
Evidencia: {evidence_id}
Requer validacao humana: Sim
```

## Revisao HITL

```text
[HITL REVIEW] {output_type}
Run ID: {run_id}
Agent ID: {agent_id}
Prompt ID: {prompt_id}
Risco do output: {baixo/medio/alto}
Revisor requerido: {papel}
Status: {Pendente/Aprovado/Aprovado com ajustes/Reprovado/Bloqueado}
Ajustes solicitados: {ajustes}
```

