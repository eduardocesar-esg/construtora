# Politica HITL - Human in the Loop

## Objetivo

Definir quando a intervencao humana e obrigatoria no piloto PMO Agentico.

## Principio Central

Agentes podem apoiar analise, consolidacao, classificacao preliminar e redacao, mas nao aprovam decisoes criticas.

## Revisao Humana Obrigatoria

Exige revisao humana antes de uso executivo:

- Status executivo enviado a sponsor, diretoria ou comite.
- Classificacao final de riscos criticos.
- Alertas com impacto potencial em contrato, custo, prazo, seguranca, qualidade ou reputacao.
- Recomendacoes de decisao.
- Priorizacao de acoes criticas.
- Evidencias usadas para sustentar escalonamento.
- Mudancas em prompts, templates ou criterios de dashboard.

## Registro da Revisao

Toda revisao deve registrar:

- Artefato revisado.
- Versao.
- Revisor.
- Data.
- Resultado.
- Ajustes solicitados.
- Evidencia da aprovacao.

## Estados Possiveis

| Estado | Uso |
|---|---|
| Draft | Gerado ou editado, ainda sem revisao |
| In Review | Em validacao humana |
| Approved | Aprovado para uso |
| Rejected | Rejeitado ou devolvido |
| Archived | Substituido ou encerrado |

