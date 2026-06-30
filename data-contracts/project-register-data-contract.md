# Project Register Data Contract

## Arquivo

`registers/project-register.csv`

## Finalidade

Registrar obras/projetos participantes do piloto, com dados basicos de governanca, contrato, sponsor, fase e status geral.

## Campos Obrigatorios

- `project_id`
- `obra`
- `status_geral`
- `fase`
- `owner`

## Valores Controlados

`status_geral`: Verde, Amarelo, Vermelho.

## Consumidores

- Dashboard executivo.
- Pilot Success Dashboard.
- Agentes de status, risco, QBR e rollout.

## Regras

- Cada obra piloto deve ter um `project_id` unico.
- `valor_contrato` deve ser numerico quando informado.
- Mudancas de sponsor, fase ou status geral exigem revisao PMO.

