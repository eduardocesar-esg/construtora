# Especificacao do Dashboard Executivo Inicial

## Objetivo

Dar visibilidade executiva ao andamento das obras piloto, riscos criticos, acoes pendentes, decisoes e evidencias.

## Publico

- Sponsor.
- Diretoria.
- PMO.
- Engenharia.
- Responsaveis das obras piloto.

## Indicadores Minimos

| Indicador | Fonte | Frequencia |
|---|---|---|
| Semaforo por obra | Status report | Semanal |
| Desvio de prazo por obra | Cronograma/status report | Semanal |
| Desvio de custo por obra | Financeiro/status report | Semanal |
| Riscos criticos abertos | `risk-register.csv` | Semanal |
| Riscos sem owner | `risk-register.csv` | Semanal |
| Acoes vencidas | `action-log.csv` | Semanal |
| Decisoes pendentes | `decision-log.csv` | Semanal |
| Evidencias pendentes de validacao | `evidence-log.csv` | Semanal |
| Artefatos criticos revisados | `artifact-register.csv` | Por ciclo |

## Visoes

1. Visao executiva consolidada.
2. Visao por obra.
3. Mapa de riscos.
4. Acoes e pendencias.
5. Decisoes de comite.
6. Evidencias e rastreabilidade.

## Regras

- O dashboard deve mostrar data de atualizacao.
- Indicadores criticos devem ter fonte rastreavel.
- Semaforos devem depender de criterio acordado e revisado por humano.
- Dados incompletos devem aparecer como lacuna, nao como status positivo.

