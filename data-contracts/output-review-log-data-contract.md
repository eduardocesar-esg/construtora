# Output Review Log Data Contract

## Arquivo

`registers/output-review-log.csv`

## Finalidade

Registrar revisao humana de outputs gerados por agentes.

## Campos Obrigatorios

- `review_id`
- `run_id`
- `agent_id`
- `prompt_id`
- `reviewer`
- `review_status`

## Valores Controlados

`review_status`: Aprovado, Aprovado com ajustes, Reprovado, Pendente, Bloqueado por falta de evidencia, Bloqueado por risco juridico, Bloqueado por dado sensivel, Bloqueado por inconsistencia.

## Regras

- Output alto risco nao pode ser publicado sem aprovacao.
- Ajustes solicitados devem ser registrados.
- `aprovado_para_publicacao` deve ser `true` apenas apos aprovacao humana.

