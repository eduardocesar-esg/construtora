# Ciclo de Vida dos Artefatos

## Estados

| Estado | Descricao |
|---|---|
| Draft | Artefato criado, ainda nao revisado |
| In Review | Artefato em validacao humana |
| Approved | Artefato aprovado para uso |
| Active | Artefato em uso operacional |
| Superseded | Substituido por nova versao |
| Archived | Encerrado e mantido apenas para historico |

## Regras de Versionamento

- Alteracoes editoriais pequenas podem manter a mesma versao menor.
- Mudancas de criterio, fluxo, responsabilidade ou decisao devem gerar nova versao.
- Artefatos usados em comite executivo devem ter versao aprovada.
- Registros CSV devem ser atualizados quando um artefato mudar de status.

## Campos de Controle

Todo artefato relevante deve ter:

- Owner.
- Versao.
- Status.
- Local no GitHub.
- Evidencia.
- Ciclo de revisao.
- Data da ultima revisao.

## Encerramento de Ciclo

Ao fim de cada ciclo:

1. Revisar artefatos ativos.
2. Arquivar versoes substituidas.
3. Atualizar registros.
4. Consolidar evidencias de valor.
5. Definir ajustes para o proximo ciclo.

