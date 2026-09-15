# BPMN — LOSTTECH

> Documentação e modelagem de processos de negócio utilizando BPMN (Business Process Model and Notation).

---

## Objetivo

O diretório **BPMN** centraliza os diagramas e documentos relacionados à modelagem dos processos da LOSTTECH.

A utilização de BPMN permite representar visualmente processos, responsabilidades, decisões, integrações e fluxos operacionais de forma padronizada.

---

## Fluxo Geral

```text
Processo de negócio
        ↓
Modelagem BPMN
        ↓
Validação
        ↓
Definição de requisitos
        ↓
Desenvolvimento
        ↓
Testes
        ↓
Implantação
        ↓
Monitoramento
        ↓
Melhoria contínua
```

---

## Estrutura

```text
BPMN
 ↓
├── README.md
├── processos/
├── modelos/
├── arquivos/
└── exportados/
```

### Processos

```text
processos/
    ↓
Processos BPMN
    ↓
Organização por área ou projeto
```

### Modelos

```text
modelos/
    ↓
Modelos reutilizáveis
    ↓
Novos diagramas BPMN
```

### Arquivos

```text
arquivos/
    ↓
Arquivos-fonte
    ↓
Edição e versionamento
```

### Exportados

```text
exportados/
    ↓
PDF / SVG / PNG
    ↓
Visualização e distribuição
```

---

## Elementos BPMN

```text
Evento
   ↓
Atividade
   ↓
Gateway
   ↓
Decisão
   ↓
Fluxo de sequência
   ↓
Resultado
```

Principais elementos:

- **Eventos**
- **Atividades**
- **Gateways**
- **Fluxos de sequência**
- **Pools**
- **Lanes**
- **Mensagens**
- **Objetos de dados**
- **Anotações**

---

## Organização de um Processo

```text
Processo
   ↓
Objetivo
   ↓
Gatilho
   ↓
Entradas
   ↓
Atividades
   ↓
Decisões
   ↓
Responsáveis
   ↓
Integrações
   ↓
Saídas
   ↓
Resultado esperado
```

---

## Integração com Desenvolvimento

```text
Processo de negócio
        ↓
Modelagem BPMN
        ↓
Requisitos
        ↓
Desenvolvimento
        ↓
Testes
        ↓
Homologação
        ↓
Implantação
        ↓
Operação
        ↓
Monitoramento
```

---

## Versionamento

Os arquivos BPMN devem ser versionados utilizando Git.

Fluxo recomendado:

```text
Alteração
   ↓
Validação
   ↓
Commit
   ↓
Push
   ↓
Revisão
   ↓
Atualização do processo
```

Exemplos de commits:

```text
docs: adicionar processo de atendimento
docs: atualizar fluxo de suporte
docs: corrigir processo de abertura de chamado
docs: adicionar modelo BPMN de vendas
```

---

## Convenção de Nomes

```text
processo-atendimento-cliente.bpmn
processo-suporte-tecnico.bpmn
processo-abertura-chamado.bpmn
processo-manutencao.bpmn
processo-vendas.bpmn
```

Para processos específicos de projetos:

```text
projeto-nome-processo.bpmn
```

---

## Boas Práticas

```text
Processo simples
      ↓
Fluxo claro
      ↓
Responsabilidades definidas
      ↓
Decisões identificadas
      ↓
Integrações documentadas
      ↓
Processo validado
      ↓
Processo versionado
```

- Manter os processos simples e legíveis
- Utilizar nomes objetivos
- Identificar responsáveis e sistemas
- Documentar decisões importantes
- Evitar fluxos sem destino definido
- Manter os diagramas atualizados
- Validar alterações antes da publicação
- Manter os arquivos-fonte junto às versões exportadas

---

## Segurança

Não incluir nos diagramas:

```text
Senhas
   ↓
Tokens
   ↓
Chaves de API
   ↓
Credenciais
   ↓
Dados pessoais desnecessários
   ↓
Informações confidenciais sem autorização
```

As informações de segurança devem seguir:

```text
docs/security/
```

---

## Manutenção

```text
Alteração no processo
        ↓
Revisão do BPMN
        ↓
Validação
        ↓
Atualização do arquivo
        ↓
Versionamento
        ↓
Publicação
```

Processos obsoletos devem ser identificados ou arquivados para evitar sua utilização como referência atual.

---

## Status

**Status:** Em desenvolvimento  
**Última atualização:** 2026

---

> **LOSTTECH**  
> *Tecnologia funcionando. Você tranquilo.*
