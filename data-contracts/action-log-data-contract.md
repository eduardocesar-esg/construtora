# Action Log Data Contract

## Arquivo

`registers/action-log.csv`

## Finalidade

Registrar acoes e pendencias com owner, prazo, status, criticidade, bloqueios e relacao com riscos, decisoes e evidencias.

## Campos Obrigatorios

- `action_id`
- `project_id`
- `obra`
- `acao`
- `owner`
- `prazo`
- `status`
- `criticidade`

## Valores Controlados

- `status`: Aberto, Em andamento, Concluido, Bloqueado, Cancelado.
- `criticidade`: Baixa, Media, Alta, Critica.

## Regras

- Acao concluida deve ter evidencia.
- Acao critica bloqueada deve ser escalada.
- Alteracao de prazo oficial exige aprovacao humana.

