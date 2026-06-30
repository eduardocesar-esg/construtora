# Setup Execution Log Data Contract

## Arquivo

`registers/setup-execution-log.csv`

## Finalidade

Registrar a execucao controlada do Sprint 0 do piloto.

## Campos Obrigatorios

- `setup_id`
- `date`
- `step`
- `action`
- `owner`
- `status`

## Valores Controlados

`status`: Pendente, Em andamento, Concluido, Bloqueado.

## Regras

- Setup bloqueado deve ter `blocker` e `next_action`.
- Setup concluido deve ter evidencia.
- A primeira rodada assistida so deve iniciar sem bloqueios criticos.

