---
title: What I'm working on now
description: A snapshot of current projects, grouped by area
updated: 2026-05-24
slug: now
---

A running map of what I'm juggling. Updated occasionally — mostly so I can remember where I am.

If a project isn't on here, I'm probably not actually working on it right now.

```mermaid
flowchart LR
    subgraph Sites
        beausimensen[beausimensen.com]
        procrastivity[procrastivity.fm]
    end

    subgraph "Content tooling"
        hypomnema[Hypomnema]
        bridge[Iris Vault Bridge]
        vsync[Vault Sync]
    end

    subgraph Foundations
        bones[astro-bones]
        sync[Obsidian sync]
        bento[Bento integration]
    end

    classDef shipped fill:#EAF3DE,stroke:#639922,color:#173404
    classDef active fill:#FAEEDA,stroke:#BA7517,color:#412402
    class gethmn shipped
    class procrastivity,bones,sync active
```

**Legend:** green = shipped · amber = in progress · plain = not yet started