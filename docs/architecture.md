# Arquitetura

## Decisão
Site institucional estático. Não existe back-end, autenticação ou banco de dados porque o caso de uso não exige armazenamento de dados.

## Estrutura
- HTML semântico
- CSS responsivo/mobile first
- JavaScript mínimo para montar a mensagem de contato
- Conteúdo versionado no GitHub

## Segurança
A redução de componentes server-side reduz a superfície de ataque. Qualquer funcionalidade futura que armazene dados deve passar por nova revisão arquitetural e de segurança.
