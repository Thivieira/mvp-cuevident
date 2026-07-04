# MVP CueVident Acadêmico

Entrega da Sprint **Gestão Ágil de Projetos e Produtos** — Pós-graduação em Engenharia de Software, PUC-Rio.

Este repositório contém a ideação e o planejamento inicial de um MVP: Lean Inception no Miro, Product Backlog e Sprint Backlog construídos no Jira (entregues em PDF), wireframes de baixa fidelidade no Figma e vídeo de apresentação.

## O problema

Criadores de conteúdo, editores de vídeo e social medias gastam muito tempo assistindo vídeos longos para descobrir quais momentos valem virar cortes curtos para redes sociais. O processo é manual, demorado e pouco organizado.

## A solução proposta

O **CueVident Acadêmico** é uma proposta de plataforma de **curadoria assistida de cortes**. No MVP, o usuário:

1. Cadastra um vídeo por URL;
2. Acompanha o status de uma análise simulada;
3. Revisa sugestões ranqueadas de clipes, cada uma com score e justificativa;
4. Aceita ou rejeita sugestões e ajusta início e fim dos melhores trechos;
5. Exporta um plano simples de cortes para orientar edição e publicação.

O sistema sugere, explica e organiza; **o humano permanece no controle da decisão final**.

## Objetivo do MVP

Validar se uma interface de curadoria assistida reduz o tempo necessário para selecionar bons cortes em vídeos longos, antes de investir em funcionalidades mais complexas (IA real, editor completo, publicação automática e integrações externas).

## Objetivo da Sprint 1

Validar o fluxo principal com dados fictícios: criação de análise por URL, acompanhamento de status, revisão de sugestões, aceite ou rejeição de clipes, ajuste simples de tempos e exportação de um plano de cortes.

## Artefatos da entrega

| Artefato | Descrição |
|---|---|
| `canvas-url.txt` | Link público (view-only) do board do Miro com a Lean Inception completa e o MVP Canvas |
| `product-backlog.pdf` | Product Backlog emergente construído no Jira (projeto Scrum), com Definition of Ready, Definition of Done e requisitos não funcionais |
| `sprint-backlog.pdf` | Sprint Backlog da Sprint 1, com histórias detalhadas, estimativas em story points e critérios de aceitação |
| `wireframes/` | Imagens dos wireframes de baixa fidelidade exportadas do Figma |
| `video-url.txt` | Link do vídeo de apresentação (2 a 4 minutos) |

## Estrutura do repositório

```txt
.
├── README.md
├── canvas-url.txt
├── product-backlog.pdf
├── sprint-backlog.pdf
├── video-url.txt
└── wireframes/
    ├── 01-dashboard.png
    ├── 02-nova-analise.png
    ├── 03-processamento.png
    ├── 04-editor-sugestoes.png
    ├── 05-exportacao-plano.png
    └── descricao-wireframes.md
```

## Observação sobre dados

Esta é uma versão acadêmica e conceitual do MVP. Todos os dados apresentados (vídeos, títulos, scores, clientes e canais) são **fictícios** e não representam clientes, métricas ou integrações reais.
