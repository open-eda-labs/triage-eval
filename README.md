# triage-eval

Runner de replay, gabarito de desfecho em JSONL, canários D2/D3, suíte de injeção em português e casos de tool-calling. Só dados sintéticos ou públicos.

## Estado

Esqueleto inicial, sem implementação. Etapas do plano: P0, P1, P3, P4. Decisões relacionadas: D-34, D-38, D-44.

## Contexto

Este repositório faz parte do laboratório open-eda-labs: workflows agênticos disparados por eventos, com Argo Workflows e padrões abertos. Cada peça trocável é um repositório que só depende do contrato versionado em `triage-contract` (D-01, D-27).

A fonte da verdade é o [Plano Mestre](https://github.com/open-eda-labs/open-eda-labs.github.io/blob/main/docs/PLANO_MESTRE.md).

## Regras

- Só dados sintéticos ou públicos; nenhum dado, código ou nome de empresa (D-24, D-27).
- Tudo como código, versões pinadas e segredos fora do Git (D-40).
- Mudanças entram por pull request; o agente nunca faz merge (D-02, D-31).
