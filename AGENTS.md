# AGENTS.md — Padrão profissional de criação
Qualquer agente humano ou de IA deve seguir este padrão.

## Princípio central
Reutilize o processo e os critérios de qualidade, nunca a estética de um projeto anterior. Cada negócio exige uma direção criativa própria derivada do briefing.

## Ordem obrigatória
1. Briefing e verdade factual do negócio.
2. Creative Direction: segmento, público, posicionamento, personalidade, objetivo, conteúdo, referências e anti-referências.
3. Front-end Designer implementa a direção aprovada.
4. Anti-AI Design Review verifica genericidade e incompatibilidade de segmento.
5. Motion, acessibilidade, SEO, segurança e performance.
6. QA em desktop e mobile.
7. Issue → branch → PR → revisão → merge → deploy.

## Regras universais
Mobile-first; HTML semântico; teclado e foco visível; contraste; performance; conversão; SEO verdadeiro; segurança proporcional; sem segredos; dependências justificadas. Backend, observabilidade, skeleton, loader e animações somente quando a necessidade real justificar.

## Regra de diversidade
Não assumir que “profissional” significa tech/SaaS, minimalista, escuro, futurista ou editorial. Clínica, restaurante, advocacia, beleza, educação, fitness, varejo, indústria e tecnologia devem poder resultar em linguagens radicalmente diferentes.

## GitHub
Mudança relevante começa em Issue, usa branch própria, PR referencia a Issue e main só recebe merge após revisão.

## Definition of Done
Direção criativa documentada; interface coerente com o negócio; responsiva; acessível; CTA funcional; conteúdo factual; sem erro conhecido; metadados essenciais; sem segredos; QA concluído; PR vinculado; deploy verificável.