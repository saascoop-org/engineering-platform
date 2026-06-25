# Architecture

## Visão geral

A solução é composta por um tutor orquestrador e tutores especialistas.

```mermaid
flowchart TD
    U[Usuário] --> C[Chief AI Mentor]
    C --> A[AI Engineering Mentor]
    C --> R[Research Mentor]
    C --> O[Open Source Architect]
    C --> F[Microsoft Fabric Mentor]
    C --> S[SaaSCoop Advisor]
    C --> KB[Knowledge Base]
    A --> KB
    R --> KB
    O --> KB
    F --> KB
    S --> KB
```

## Decisão inicial

O MVP usa ChatGPT Project + Markdown versionado no GitHub.

## Evolução possível

1. ChatGPT Project
2. GPTs especializados
3. Assistente com RAG
4. Multiagentes via API
5. Plataforma SaaSCoop de tutoria técnica
