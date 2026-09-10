\# Arquitetura Geral — LOSTTECH



\## Objetivo



Este documento define a visão arquitetural do ecossistema tecnológico da LOSTTECH.



A arquitetura deve permitir que projetos sejam desenvolvidos de forma organizada, modular, segura e escalável.



\---



\## Visão do ecossistema



```text

&#x20;                             LOSTTECH

&#x20;                                │

&#x20;            ┌──────────────┼─────────────┐

&#x20;            │                  │                 │

&#x20;           Software        Infraestrutura     Operações

&#x20;              │                 │                │

&#x20;      ┌─────┼─────┐    ┌───┼───┐      ┌───┼───┐

&#x20;      │       │      │    │    │    │      │    │    │

&#x20;     Web   APIs  Apps  Docker Rede Servidores Automação

&#x20;      │       │      │    │    │    │      │

&#x20;      └─────┼─────┘    └───┼───┘      └───┘

&#x20;              │                 │

&#x20;              └─────────────┼──────────────┐

&#x20;                                │                  │

&#x20;                              Dados            Integrações

&#x20;                                │                  │

&#x20;                           MySQL/MariaDB       APIs REST

