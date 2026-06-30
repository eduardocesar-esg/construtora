# Risk Register Data Contract

## Arquivo

`registers/risk-register.csv`

## Finalidade

Registrar riscos de obra com categoria, causa, impacto, severidade, resposta, owner, evidencia e necessidade de decisao.

## Campos Obrigatorios

- `risk_id`
- `project_id`
- `obra`
- `categoria`
- `risco`
- `classificacao`
- `owner`
- `status`

## Valores Controlados

- `classificacao`: Baixo, Medio, Alto, Critico.
- `status`: Aberto, Em andamento, Concluido, Bloqueado, Cancelado.
- `decision_required`: Sim, Nao.

## Regras

- Risco critico exige validacao humana.
- Risco sem owner deve aparecer no cockpit e no QBR como lacuna.
- Risco concluido deve ter evidencia ou justificativa.

