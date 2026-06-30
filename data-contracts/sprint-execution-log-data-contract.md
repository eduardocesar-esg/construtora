# Sprint Execution Log Data Contract

## Arquivo

`registers/sprint-execution-log.csv`

## Finalidade

Registrar a execucao da Sprint 1 e Sprint 1.1, conectando acoes, outputs, runs de agentes, revisoes e bloqueios.

## Campos Obrigatorios

- `sprint_id`
- `date`
- `phase`
- `worksite`
- `step`
- `action`
- `owner`
- `status`

## Valores Controlados

- `phase`: Sprint 1, Sprint 1.1.
- `status`: Pendente, Em andamento, Concluido, Bloqueado.

## Regras

- Toda execucao de agente deve apontar `run_id` quando aplicavel.
- Todo output revisado deve apontar `review_id` quando aplicavel.
- Item bloqueado deve ter `blocker` e `next_action`.
- Sprint 1.1 nao fecha enquanto houver lacuna critica sem owner.

