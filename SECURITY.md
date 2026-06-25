# Security Policy

## Escopo

Este repositório contém prompts, documentação, templates e exemplos. Mesmo assim, riscos de segurança podem existir em:

- prompts que induzam exposição de dados sensíveis
- exemplos com credenciais
- instruções inseguras de integração
- ausência de governança de dados
- automações mal configuradas

## Reporte

Nunca abra uma issue pública com segredo, token, chave, credencial ou vulnerabilidade explorável.

Use um canal privado do mantenedor do projeto.

## Boas práticas

- Não versionar segredos.
- Usar `.env.example`, nunca `.env`.
- Revisar prompts contra prompt injection.
- Documentar riscos e mitigação em ADRs.
