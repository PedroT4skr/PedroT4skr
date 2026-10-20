# AGENTS.md — PedroT4skr Profile Documentation

## Visão Geral
Este repositório (`PedroT4skr/PedroT4skr`) é o repositório especial de perfil do GitHub de **Pedro Tigre** (@PedroT4skr). O objetivo do arquivo principal `README.md` é atuar como vitrine profissional (portfolio / profile README) para recrutadores, desenvolvedores e colaboradores da comunidade tech internacional e nacional.

---

## Estrutura do Repositório
- `README.md`: Arquivo principal renderizado na página de perfil do GitHub (`https://github.com/PedroT4skr`).
- `AGENTS.md`: Registro de arquitetura, decisões técnicas de design, histórico de mudanças e mapeamento de seções.

---

## Mapeamento de Seções do README.md
1. **Header / Hero Section (`README.md#L1-L18`)**:
   - Apresentação de alto nível.
   - Dynamic Typing SVG com rotação de competências-chave: Engenharia de Software, Full-Stack (TS/React/Node), Sistemas & Desktop (Rust/Tauri/Windows Internals) e Visão Computacional / Edge AI.
   - Quick action badges padronizados (LinkedIn e Repositórios).
2. **About Me (`README.md#L20-L29`)**:
   - Formação em Sistemas de Informação.
   - Especialização Full-Stack e Systems/Desktop Engineering.
   - Padrões arquiteturais: Clean Architecture, MVVM, SOLID, Offline-First.
3. **Featured Engineering Projects Showcase (`README.md#L31-L121`)**:
   - Grid 2x2 com cards ricos estruturados em HTML Table com renderização fluida no GitHub (desktop e mobile).
   - `gabaritei-ia`: Foco em Visão Computacional (OMR) on-device, arquitetura offline-first e UI glassmorphic.
   - `react-media-streaming-app`: Monorepo com engine backend de in-memory cache (<200ms) e sync Trakt.
   - `Windows-Toolkit`: Arquitetura de deployment do Windows em Rust + Tauri + React, Zero-Desktop OOBE Hijack, fileless USB media generator via WMI/PowerShell e desinstalador heurístico de bloatware.
   - `Pizza-Flow`: Sistema full-stack para gestão de pizzarias integrado a bot de WhatsApp para captura automática de pedidos, painel em tempo real para cozinha e containers Docker.
4. **Tech Stack & Tooling (`README.md#L123-L151`)**:
   - Tabela de competências agrupada por domínios (Languages, Frontend & Desktop, Mobile & Systems, Backend & APIs, Architecture & Tools).
   - Badges estilizados com layout limpo e consistente.
5. **GitHub Analytics (`README.md#L153-L165`)**:
   - Endpoint oficial e estável `github-readme-stats.vercel.app` para evitar esgotamento de PAT/tokens de terceiros.
   - Cards com tema escuro nativo do GitHub (`bg_color=0d1117`, `border_color=30363d`, acento `#58a6ff`).
   - GitHub Stats, Top Languages e Streak Stats alinhados.
6. **Get in Touch / Footer (`README.md#L167-L177`)**:
   - Canais de contato profissionais limpos e objetivos.

---

## Histórico de Mudanças & Refatores
- **2026-10-20 (v2 - Atualização de Projetos & Fix de Métricas)**:
  - Substituído `controle-financeiro-app` por **`Pizza-Flow`** (Sistema de pedidos com bot WhatsApp + Docker).
  - Substituído `harbor-1`/`stremio-releases` por **`Windows-Toolkit`** (Projeto de altíssimo nível técnico com Rust + Tauri + Windows APIs).
  - Corrigido o host dos cards de métricas do GitHub: migrado de `github-readme-stats-sigma-five.vercel.app` (fork cujo token PAT de API estava estourado) para a instância oficial e estável `github-readme-stats.vercel.app`.
  - Atualizado o Typing SVG e badges para incluir Rust, Tauri e Windows APIs.
- **2026-10-20 (v1 - Refatoração Inicial)**:
  - Removidos divisores gif arco-íris e elementos datados.
  - Implementado layout profissional modular estilo Dark Minimalist.
  - Adicionado `AGENTS.md` para documentação de contexto.
