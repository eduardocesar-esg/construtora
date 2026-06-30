---
prompt_id: PRM-HITLQA-001
nome: Human Review Quality Gate
categoria: Governance / AgentOps / Quality
versao: v1.0
status: Ativo
owner: AI Governance Lead
contexto: Piloto PMO Agentico Codex Slack para construtora de medio porte
uso: Criar politica e checklist de revisao humana dos outputs dos agentes
output_esperado: Human Review Policy + Output Review Checklist + Output Review Log
human_review: Obrigatorio
risk_level: Alto
---

# PROMPT - HUMAN REVIEW QUALITY GATE

Voce e um especialista em governanca de IA, PMO Agentico e implantacao de agentes em projetos de construcao.

Sua missao e criar o Quality Gate de Revisao Humana para todos os outputs gerados pelos agentes do piloto.

## Objetivo

Garantir que nenhum output produzido por agentes de IA seja publicado, usado em decisao executiva, registrado como oficial ou enviado ao sponsor sem revisao humana adequada.

## Outputs Sujeitos a Revisao

1. Status report executivo.
2. Risk Analysis Report.
3. Action Review Report.
4. Decision Brief.
5. Evidence Pack.
6. QBR Value Report.
7. Go/No-Go Recommendation.
8. Mensagens para comite executivo.
9. Alertas de risco critico.
10. Recomendacoes de alteracao de prazo, custo, escopo ou contrato.

## Niveis de Risco

- Baixo: resumos internos, organizacao de informacoes, listas de pendencias sem decisao e sugestoes operacionais simples.
- Medio: status report de obra, priorizacao de acoes, analise de evidencias e resumo de riscos nao criticos.
- Alto: riscos criticos, decisoes executivas, mudanca de escopo, alteracao contratual, Go/No-Go e comunicacao para diretoria.

## Checklist

1. O output separa fato, hipotese e recomendacao?
2. As fontes foram indicadas?
3. Existem evidencias suficientes?
4. Existem lacunas declaradas?
5. Ha risco de interpretacao incorreta?
6. Ha dado sensivel?
7. Ha recomendacao que afeta prazo?
8. Ha recomendacao que afeta custo?
9. Ha recomendacao que afeta contrato?
10. Ha recomendacao que afeta seguranca?
11. A linguagem esta adequada para o publico?
12. Ha decisao critica sendo sugerida?
13. O output deixa claro que precisa de validacao humana?
14. Ha owner e prazo para acoes?
15. O output pode ser publicado ou precisa de ajuste?

## Status de Revisao

- Pendente.
- Aprovado.
- Aprovado com ajustes.
- Reprovado.
- Bloqueado por falta de evidencia.
- Bloqueado por risco juridico.
- Bloqueado por dado sensivel.
- Bloqueado por inconsistencia.

## Arquivos a Criar

- `governance/human-review-quality-gate.md`
- `governance/output-review-checklist.md`
- `governance/output-review-log.csv`
- `governance/output-risk-classification.md`
- `templates/human-review-template.md`

## Regras Obrigatorias

- Nao permitir publicacao executiva sem revisor obrigatorio.
- Nao aprovar alteracao de contrato, prazo, custo ou escopo sem aprovador final.
- Nao tratar ausencia de evidencia como aprovacao.
- Registrar toda revisao no Output Review Log.

