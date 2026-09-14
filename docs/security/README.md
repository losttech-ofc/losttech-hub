# Segurança — LOSTTECH

## Objetivo

Estabelecer práticas para proteger código, sistemas, infraestrutura, dados e credenciais utilizados pela LOSTTECH.

---

## Princípios

A segurança deve considerar:

- Confidencialidade
- Integridade
- Disponibilidade
- Controle de acesso
- Rastreabilidade
- Princípio do menor privilégio

---

## Credenciais

Nunca armazenar no repositório:

- Senhas
- Tokens
- API Keys
- Chaves privadas
- Certificados privados
- Credenciais de banco de dados
- Segredos de serviços

Utilizar variáveis de ambiente ou mecanismos apropriados de gerenciamento de segredos.

---

## Arquivos de ambiente

Arquivos `.env` contendo informações reais nunca devem ser versionados.

Quando necessário, utilizar:

```text
.env.example
