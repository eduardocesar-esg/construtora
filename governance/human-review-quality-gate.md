# Human Review Quality Gate

## Objetivo

Garantir que nenhum output de agente seja publicado, usado em decisao executiva, registrado como oficial ou enviado ao sponsor sem revisao humana proporcional ao risco.

## Outputs Sujeitos a Revisao

- Status report executivo.
- Risk Analysis Report.
- Action Review Report.
- Decision Brief.
- Evidence Pack.
- QBR Value Report.
- Go/No-Go Recommendation.
- Mensagens para comite executivo.
- Alertas de risco critico.
- Recomendacoes de alteracao de prazo, custo, escopo ou contrato.

## Matriz de Aprovacao

| Output | Risco | Revisor obrigatorio | Aprovador final | Pode publicar? |
|---|---|---|---|---|
| Status report executivo | Medio | PMO Lead / Gerente da obra | Sponsor se for diretoria | Somente aprovado |
| Risk Analysis Report critico | Alto | PMO Lead / Gerente da obra | Sponsor | Somente aprovado |
| Action Review Report | Medio | PMO Lead | PMO Lead | Somente aprovado |
| Decision Brief executivo | Alto | PMO Lead / Juridico se contrato | Sponsor | Somente aprovado |
| Evidence Pack | Medio | PMO Lead | PMO Lead | Somente aprovado |
| QBR Value Report | Alto | PMO Lead / AI Governance Lead | Sponsor | Somente aprovado |
| Go/No-Go Recommendation | Alto | PMO Lead / Tech Lead / AI Governance Lead | Sponsor | Somente aprovado |
| Alerta de risco critico | Alto | PMO Lead | Sponsor quando executivo | Somente aprovado |

## Status de Revisao

- Pendente.
- Aprovado.
- Aprovado com ajustes.
- Reprovado.
- Bloqueado por falta de evidencia.
- Bloqueado por risco juridico.
- Bloqueado por dado sensivel.
- Bloqueado por inconsistencia.

## Regras

- Output alto risco nao pode ser publicado sem aprovador final.
- Lacunas devem ser preservadas no output.
- Fato, hipotese e recomendacao devem estar separados.
- Alteracoes em contrato, baseline, prazo ou custo exigem aprovacao formal.
- A revisao deve ser registrada em `registers/output-review-log.csv`.

