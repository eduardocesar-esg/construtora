# Workflow Templates - Slack Cockpit

## Workflow de Status Semanal

1. Gerente da obra publica atualizacao no canal da obra.
2. PMO consolida no `obra-status-register.csv`.
3. Agente de status gera minuta.
4. Revisor humano valida.
5. Status aprovado alimenta dashboard e comite.

## Workflow de Risco Critico

1. Risco e sinalizado no canal da obra ou `#pmo-riscos-obras`.
2. Agente de risco estrutura Risk Analysis Report.
3. PMO valida classificacao e owner.
4. Se houver impacto executivo, escalonar para `#pmo-decision-log`.
5. Atualizar Risk Register.

## Workflow de Acao Bloqueada

1. Acao bloqueada e sinalizada em `#pmo-acoes-pendencias`.
2. PMO confirma owner, prazo e criticidade.
3. Bloqueios de alta criticidade entram em pauta semanal.
4. Conclusao exige evidencia.

## Workflow de Evidencia

1. Solicitacao e publicada em `#pmo-evidencias`.
2. Responsavel envia link ou referencia.
3. Agente de evidencia qualifica.
4. Revisor valida.
5. Evidence Log e atualizado.

## Workflow HITL

1. Output de agente e publicado em `#pmo-hitl-review`.
2. Revisor aplica checklist.
3. Resultado e registrado em `output-review-log.csv`.
4. Apenas outputs aprovados podem ser publicados externamente.

