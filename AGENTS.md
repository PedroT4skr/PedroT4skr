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
   - Dynamic Typing SVG com rotação de competências-chave: Engenharia de Software, Full-Stack (TS/React/Node), Mobile (Flutter/Dart/MVVM) e Visão Computacional / Sistemas Edge.
   - Quick action badges padronizados (LinkedIn e Repositórios).
2. **About Me (`README.md#L20-L29`)**:
   - Formação em Sistemas de Informação.
   - Especialização Full-Stack e Mobile.
   - Padrões arquiteturais: Clean Architecture, MVVM, SOLID, Offline-First.
3. **Featured Engineering Projects Showcase (`README.md#L31-L119`)**:
   - Grid 2x2 com cards ricos estruturados em HTML Table com renderização fluida no GitHub (desktop e mobile).
   - `gabaritei-ia`: Foco em Visão Computacional (OMR) on-device, arquitetura offline-first e UI glassmorphic.
   - `react-media-streaming-app`: Monorepo com engine backend de in-memory cache (<200ms) e sync Trakt.
   - `controle-financeiro-app`: Flutter com MVVM estrito, persistência local SQLite offline-first e Material Design 3.
   - `harbor-1` & `stremio-releases`: Ecossistema de client customizado, stream ranking engine e pipeline OTA de releases.
4. **Tech Stack & Tooling (`README.md#L121-L149`)**:
   - Tabela de competências agrupada por domínios (Languages, Frontend, Mobile, Backend, Architecture).
   - Badges estilizados com layout limpo e consistente.
5. **GitHub Analytics (`README.md#L151-L163`)**:
   - Cards com tema escuro compatível com GitHub Dark (`bg_color=0d1117`, `border_color=30363d`, acento `#58a6ff`).
   - GitHub Stats, Top Languages e Streak Stats alinhados.
6. **Get in Touch / Footer (`README.md#L165-L175`)**:
   - Canais de contato profissionais limpos e objetivos.

---

## Histórico de Mudanças & Refatores
- **2026-10-20**:
  - **Diagnóstico**: O layout antigo continha divisores gif arco-íris datados e repetitivos, falta de categorização de stacks, apenas 1 linha estática no typing SVG, e uma tabela básica que escondia a complexidade técnica dos projetos.
  - **Refatoração Completa**:
    - Removidos todos os GIFs arco-íris clichês.
    - Implementado Typing SVG dinâmico e multi-cargo com fonte Inter e azul nativo GitHub.
    - Adicionado showcase 2x2 com cards técnicos aprofundados para os 4 principais projetos (Gabaritei OMR, Streaming App, Controle Financeiro Flutter, Harbor).
    - Unificação do idioma para Inglês Técnico internacional.
    - Padronização das cores dos cards de métricas do GitHub para `#0d1117` e borda `#30363d`.
    - Criação do documento `AGENTS.md` para governança de contexto.
