# Arquitetura Geral — LOSTTECH

## Objetivo

Este documento define a visão arquitetural do ecossistema tecnológico da LOSTTECH.

A arquitetura deve permitir que os projetos sejam desenvolvidos de forma organizada, modular, segura e escalável.

---

## Visão do ecossistema

```text
                              LOSTTECH
                                  │
                 ┌────────────────┼────────────────┐
                 │                │                │
              Software       Infraestrutura     Operações
                 │                │                │
          ┌──────┼──────┐    ┌────┼────┐           │
          │      │      │    │    │    │           │
         Web    APIs   Apps Docker Rede Servidores Automação
          │      │      │    │    │    │           │
          └──────┼──────┘    └────┼────┘           │
                 │                │                │
                 └────────────────┼────────────────┘
                                  │
                     ┌────────────┴────────────┐
                     │                         │
                   Dados                  Integrações
                     │                         │
               MySQL / MariaDB              APIs REST
