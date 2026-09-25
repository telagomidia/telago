# Segurança

- Nenhuma credencial ou secret no front-end.
- Nenhum dado do formulário é armazenado.
- Sem dependências de runtime no navegador.
- Links externos abertos pelo JavaScript usam noopener/noreferrer.
- HTTPS deve ser obrigatório no provedor de hospedagem.
- Headers como CSP, HSTS e Referrer-Policy devem ser configurados no host quando aplicável.
- Dependências de build devem ser auditadas antes do deploy.
