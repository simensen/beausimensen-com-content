---
title: What I'm working on now
description: A snapshot of current projects, grouped by area
updated: 2026-05-24
slug: now
---

A running map of what I'm juggling. Updated occasionally — mostly so I can remember where I am.

If a project isn't on here, I'm probably not actually working on it right now. Or I simply forgot. :)

```mermaid
flowchart LR
    subgraph Products
        hypomnema[Hypomnema]
        proxenos[Proxenos]
    end

    subgraph ”DX tooling”
        scind[Scind]
        xcind[Xcind]
    end

    subgraph ”AI tooling”
        wip[wip]
        duo[duo]
        clast[clast]
    end

    subgraph Sites
        beausimensen[beausimensen.com]
        procrastivity[procrastivity.fm]
    end

    subgraph Foundations
        sync[Obsidian sync]
        bento[Bento integration]
    end

    classDef shipped fill:#EAF3DE,stroke:#639922,color:#173404
    classDef active fill:#FAEEDA,stroke:#BA7517,color:#412402
    class gethmn shipped
    class beausimensen,procrastivity,hypomnema,sync,bento,xcind,scind,wip,duo,proxenos,clast active
```

**Legend:** green = shipped · amber = in progress · plain = not yet started