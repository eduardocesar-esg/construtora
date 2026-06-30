# Pilot Success Metrics Data Contract

## Arquivo

`registers/pilot-success-metrics.csv`

## Finalidade

Registrar scores de sucesso do piloto e recomendacao Go/No-Go.

## Campos Obrigatorios

- `metric_id`
- `periodo`
- `pilot_success_score`
- `go_no_go_recommendation`

## Escala

Scores de 0 a 5.

## Interpretacao

- 0 a 2,4: No-Go.
- 2,5 a 3,4: Go com correcoes obrigatorias.
- 3,5 a 4,2: Go com ressalvas.
- 4,3 a 5,0: Go para expansao.

## Regras

- Recomendacao nao substitui decisao do sponsor.
- Score com dados ausentes deve declarar lacuna.
- Beneficio estimado deve ser separado de beneficio medido.

