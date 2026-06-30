# Obra Status Register Data Contract

## Arquivo

`registers/obra-status-register.csv`

## Finalidade

Registrar o status periodico de cada obra piloto, incluindo avanco fisico-financeiro, semaforos, desvios, riscos, decisoes e revisao humana.

## Campos Obrigatorios

- `status_id`
- `project_id`
- `obra`
- `periodo`
- `status_geral`
- `human_review_status`
- `owner`

## Valores Controlados

- Status por dimensao: Verde, Amarelo, Vermelho.
- `human_review_status`: Pendente, Aprovado, Aprovado com ajustes, Reprovado.

## Regras

- Status executivo nao pode ser publicado com `human_review_status` pendente.
- Desvios relevantes devem apontar evidencias ou lacunas.
- Decisoes necessarias devem ser refletidas no Decision Log.

