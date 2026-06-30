# Agent Run Log Data Contract

## Arquivo

`registers/agent-run-log.csv`

## Finalidade

Registrar execucoes dos agentes, relacionando prompt, entrada, saida, executor, status, custo estimado e erros.

## Campos Obrigatorios

- `run_id`
- `agent_id`
- `prompt_id`
- `data_execucao`
- `executado_por`
- `status`

## Valores Controlados

`status`: Sucesso, Erro, Pendente, Cancelado.

## Regras

- Todo output sujeito a revisao deve ter `run_id`.
- Falhas devem registrar `erro`.
- Outputs executivos devem apontar `output_ref`.

