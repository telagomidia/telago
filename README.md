# TelaGo — site demonstrativo v2

Projeto piloto do padrão profissional de sites comerciais.

## Arquitetura
Site estático e responsivo, sem banco de dados ou back-end desnecessário. A v2 adota direção de arte editorial, motion progressivo, acessibilidade, SEO básico e padrões internos de revisão.

## Processo de engenharia
Consulte `AGENTS.md`, `docs/qa-checklist.md` e as skills em `skills/`. Mudanças relevantes seguem Issue → branch → PR → revisão → merge → deploy.

## Desenvolvimento
```bash
npm install
npm run dev
npm run build
```

## Publicação
GitHub Pages via workflow em `.github/workflows/pages.yml`.

> Importante: o WhatsApp em `src/main.js` ainda é placeholder. Substituir pelo número comercial real antes de produção comercial.