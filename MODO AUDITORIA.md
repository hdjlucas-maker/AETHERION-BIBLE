Você agora está em MODO AUDITORIA.

Sua única função é auditar TODO o projeto.

Você NÃO pode criar funcionalidades novas.

Você NÃO pode melhorar arquitetura.

Você NÃO pode fazer refatoração desnecessária.

Sua missão é encontrar TODOS os problemas existentes.

Faça uma auditoria completa do projeto.

Checklist obrigatório:

1. Verifique TODOS os scripts C#.
2. Verifique TODOS os namespaces.
3. Verifique TODOS os using.
4. Verifique TODAS as referências quebradas.
5. Verifique TODOS os métodos inexistentes.
6. Verifique TODAS as interfaces.
7. Verifique TODAS as classes abstratas.
8. Verifique TODOS os MonoBehaviour.
9. Verifique TODOS os ScriptableObjects.
10. Verifique TODAS as dependências entre scripts.
11. Verifique TODAS as referências nulas possíveis.
12. Verifique TODOS os ServiceLocator.Get<>.
13. Verifique TODAS as chamadas para componentes inexistentes.
14. Verifique TODAS as cenas.
15. Verifique TODOS os Prefabs.
16. Verifique TODOS os Assets obrigatórios.
17. Verifique TODOS os erros que impedem compilação.
18. Verifique TODOS os warnings importantes.
19. Verifique TODO código morto.
20. Verifique TODOS os TODO/FIXME.

Ao terminar:

Crie um arquivo chamado:

COMPILATION_REPORT.md

Organize o relatório em:

## Erros críticos

## Erros de compilação

## Referências quebradas

## Métodos inexistentes

## Namespaces incorretos

## Riscos de NullReferenceException

## Objetos obrigatórios ausentes

## Problemas encontrados por script

## Ordem recomendada de correção

Depois corrija SOMENTE os erros críticos que impedem a compilação.

Não implemente nenhuma funcionalidade nova.

Pare quando terminar.
