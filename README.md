# Estudos — GitHub Actions / CI-CD

Repositório de acompanhamento do curso de GitHub Actions, com anotações e os pipelines
(workflows) que eu for praticando.

> Contexto: hoje meu currículo/LinkedIn deixam claro que CI/CD ainda **não é ownership em
> produção** — só simulei em projeto pessoal. Este repositório documenta o processo real
> de aprender e aplicar isso.

## Progresso

| Módulo | Status | Data |
|---|---|---|
| Fundamentos de workflows (YAML, triggers) | 🔲 não iniciado | |
| Build e testes automatizados (Java/Maven) | 🔲 não iniciado | |
| Cache e artefatos | 🔲 não iniciado | |
| Secrets e ambientes | 🔲 não iniciado | |
| Deploy automatizado | 🔲 não iniciado | |

Legenda: 🔲 não iniciado · 🟡 em andamento · ✅ concluído

## Estrutura

- `anotacoes/` — resumos por módulo/aula
- `exercicios/` — exercícios práticos que não sejam workflow (scripts, configs)
- `.github/workflows/` — os pipelines (arquivos `.yml`) que eu for criando durante o curso

## Pipelines salvos

| Arquivo | O que faz | Módulo do curso |
|---|---|---|
| `ci-maven-exemplo.yml` | Build + testes de um projeto Java/Maven a cada push | Fundamentos |

*(atualizar esta tabela a cada novo workflow adicionado)*

