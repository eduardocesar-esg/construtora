# Pre-publication Review Log Data Contract

## Arquivo

`registers/pre-publication-review-log.csv`

## Finalidade

Registrar a validacao final antes de publicar outputs de agentes.

## Campos Obrigatorios

- `review_id`
- `date`
- `output_ref`
- `output_type`
- `reviewer`
- `status`
- `approved_for_publication`

## Valores Controlados

`status`: Aprovado, Aprovado com ajustes, Bloqueado.

## Regras

- Item bloqueante impede publicacao.
- Decisao critica exige sponsor.
- Impacto contratual exige juridico.
- Alteracao de prazo, custo ou baseline exige aprovacao formal.
- Output publicado deve ter `approved_for_publication=true`.

