# Pilot Success Dashboard Spec

## 1. Objetivo

Demonstrar a saude do piloto, adocao, uso dos agentes, riscos, acoes, decisoes, evidencias, valor percebido e recomendacao Go/No-Go.

## 2. Publico

- Sponsor.
- Diretoria.
- PMO.
- Engenharia.
- Tech Lead.

## 3. Fontes

| Fonte | Arquivo |
|---|---|
| Metricas do piloto | `registers/pilot-success-metrics.csv` |
| Riscos | `registers/risk-register.csv` |
| Acoes | `registers/action-log.csv` |
| Decisoes | `registers/decision-log.csv` |
| Evidencias | `registers/evidence-log.csv` |
| Revisoes humanas | `governance/agent-output-review-log.csv` |

## 4. Visoes

1. Overview do piloto.
2. Score de sucesso.
3. Uso dos agentes.
4. Saude de riscos.
5. Saude de acoes.
6. Decisoes e comites.
7. Prontidao de evidencias.
8. Cobertura HITL.
9. Feedback do sponsor.
10. Go/No-Go.

## 5. Regras de Go/No-Go

Go: metas principais atingidas e sponsor satisfeito.  
Adjust: valor observado, mas lacunas relevantes de dados, processo ou governanca.  
Pause: riscos de governanca, baixa adocao ou dados insuficientes.  
No-Go: ausencia de valor mensuravel ou risco operacional inaceitavel.

