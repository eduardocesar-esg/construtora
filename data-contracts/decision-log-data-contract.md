# Decision Log Data Contract

## Arquivo

`registers/decision-log.csv`

## Finalidade

Registrar decisoes tomadas, pendentes ou recomendadas, com contexto, opcoes, owner, impacto, evidencia e aprovador.

## Campos Obrigatorios

- `decision_id`
- `project_id`
- `obra`
- `tipo`
- `nivel`
- `decisao`
- `status`

## Valores Controlados

- `nivel`: Operacional, Gerencial, Executiva, Critica.
- `status`: Pendente, Aprovado, Aprovado com ajustes, Reprovado.

## Regras

- Decisao executiva ou critica exige aprovador humano.
- Mudanca contratual exige revisao juridica.
- Decisao sem evidencia deve aparecer como lacuna.

