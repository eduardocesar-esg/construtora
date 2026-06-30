# Evidence Log Data Contract

## Arquivo

`registers/evidence-log.csv`

## Finalidade

Registrar evidencias associadas a status, riscos, acoes e decisoes.

## Campos Obrigatorios

- `evidence_id`
- `project_id`
- `obra`
- `tipo`
- `descricao`
- `fonte`
- `qualidade`
- `status`

## Valores Controlados

- `qualidade`: Forte, Media, Fraca, Ausente, Inconsistente.
- `status`: Pendente, Validado, Rejeitado, Substituido.

## Regras

- Evidencia nao deve ser inventada.
- Fonte e data devem ser preservadas quando disponiveis.
- Evidencia inconsistente deve bloquear aprovacao de output critico.

