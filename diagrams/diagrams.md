# Diagrams

All diagrams use [Mermaid](https://mermaid.js.org/), which GitHub renders automatically.

## 1. Big picture: from space microbes to Earth medicine

```mermaid
flowchart TD
    A[Spaceflight environment] --> B[Microbial changes]
    A --> C[Human host changes]
    B --> D[Biofilms]
    B --> E[Virulence]
    B --> F[Antibiotic resistance]
    C --> G[Immune dysregulation]
    C --> H[Microbiome shift]
    D --> I[Equipment and health risk]
    E --> I
    F --> I
    G --> I
    H --> I
    I --> J[Countermeasures]
    J --> K[Earth benefits: AMR, infection control, diagnostics]
```

## 2. Research workflow used in this project

```mermaid
flowchart LR
    A[Pick question] --> B[Literature search]
    B --> C[Download public data]
    C --> D[Analyse in notebook]
    D --> E[Interpret and cite]
    E --> F[Publish notes on site]
```

## 3. Clinical-trial tracker workflow

```mermaid
flowchart LR
    A[ClinicalTrials.gov search: spaceflight, microgravity] --> B[Export CSV]
    B --> C[Clean and categorise]
    C --> D[Plots: phase, status, condition]
    D --> E[Summary of research gaps]
```
