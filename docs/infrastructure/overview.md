# Infraestrutura — LOSTTECH

## Objetivo

Definir a visão geral da infraestrutura tecnológica utilizada nos projetos e operações da LOSTTECH.

---

## Princípios

A infraestrutura deve priorizar:

- Segurança
- Disponibilidade
- Confiabilidade
- Escalabilidade
- Monitoramento
- Backup
- Recuperação
- Automação

---

## Ambientes

Os projetos podem utilizar diferentes ambientes:

- Desenvolvimento
- Testes
- Homologação
- Produção

Cada ambiente deve possuir configurações adequadas ao seu propósito, mantendo separação e controle quando necessário.

---

## Servidores

Quando aplicável, os servidores podem hospedar:

- Aplicações web
- APIs
- Bancos de dados
- Serviços internos
- Automações
- Sistemas administrativos

As configurações devem ser documentadas e versionadas sempre que possível.

---

## Banco de dados

### Tecnologias atualmente utilizadas

- MySQL
- MariaDB

### Boas práticas

- Backups periódicos
- Controle de acesso
- Migrations
- Monitoramento
- Documentação das alterações
- Procedimentos de recuperação

---

## Containers

Projetos compatíveis podem utilizar Docker para:

- Padronização de ambientes
- Isolamento de serviços
- Desenvolvimento local
- Testes
- Deploy

A configuração dos containers deve ser documentada e mantida de forma consistente entre os ambientes.

---

## Redes

A infraestrutura deve considerar:

- Controle de acesso
- Firewall
- Segmentação quando necessária
- Segurança de serviços expostos
- Monitoramento de conectividade

Serviços expostos à rede devem ser avaliados quanto à necessidade, segurança e nível de acesso.

---

## Backup

Dados importantes devem possuir uma estratégia de backup adequada.

O planejamento deve considerar:

- Frequência
- Retenção
- Local de armazenamento
- Segurança
- Testes de restauração
- Procedimentos de recuperação

Backups devem ser periodicamente verificados para garantir sua integridade e possibilidade de restauração.

---

## Monitoramento

Quando necessário, os ambientes devem possuir mecanismos para acompanhar:

- Disponibilidade
- Uso de recursos
- Erros
- Serviços
- Bancos de dados
- Aplicações
- Conectividade

O monitoramento deve permitir identificar problemas e apoiar a manutenção preventiva da infraestrutura.

---

## Segurança

Credenciais e informações sensíveis nunca devem ser armazenadas diretamente no código ou no repositório.

Devem ser utilizados mecanismos apropriados para:

- Configuração de ambientes
- Gerenciamento de segredos
- Controle de acesso
- Proteção de credenciais
- Auditoria quando aplicável

---

## Deploy

O processo de implantação deve ser controlado e documentado.

Sempre que possível, utilizar o seguinte fluxo:

```text
Desenvolvimento
      ↓
Testes
      ↓
Homologação
      ↓
Produção
