# Politica de Governanca de Prompts

## Objetivo

Controlar criacao, revisao, versionamento e uso dos prompts do piloto.

## Regras

- Todo prompt deve ter ID unico.
- Todo prompt deve ter owner.
- Toda alteracao relevante deve gerar nova versao.
- Prompts usados em reports executivos devem estar registrados no `prompt-register.csv`.
- Prompts com impacto em decisoes devem passar por revisao humana.
- Prompts obsoletos devem ser arquivados, nao apagados sem registro.

## Campos Minimos

- Prompt ID.
- Nome.
- Owner.
- Versao.
- Status.
- Local no GitHub.
- Agente relacionado.
- Ciclo de revisao.
- Ultima revisao.
- Evidencia.

## Criterios de Qualidade

- Objetivo claro.
- Entrada esperada definida.
- Saida esperada definida.
- Restricoes e limites explicitos.
- Regras HITL quando aplicavel.
- Linguagem consistente com o piloto.

