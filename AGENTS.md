# AGENTS.md — Padrão TelaGo
Qualquer agente humano ou de IA deve seguir este padrão.

## Fluxo GitHub
1. Correção, melhoria ou nova função relevante começa em uma Issue.
2. Trabalhe em branch própria; não implemente diretamente em main.
3. Abra PR descrevendo mudanças e referenciando a Issue.
4. Revise visual, acessibilidade, segurança proporcional, SEO e testes antes do merge.
5. Merge em main somente após revisão; o workflow faz o deploy.
6. Nunca coloque segredos, tokens ou credenciais no front-end/repositório.

## Produto
Evite layouts genéricos de IA. Não adicione cards, gradientes, animações, skeleton ou loaders sem função. Motion deve explicar hierarquia/estado e respeitar prefers-reduced-motion. Mobile-first, HTML semântico, teclado e foco visível. Backend e observabilidade só quando a necessidade justificar.

## Definition of Done
Responsivo; teclado; foco visível; sem erro conhecido; metadados essenciais; CTA funcional; sem segredos; dependências justificadas; PR vinculado à Issue; deploy verificável.