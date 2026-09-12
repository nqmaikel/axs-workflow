![AXS Workflow project cover](assets/showcase/cover.png)

*Concept illustration created for this showcase.*

<div align="center">

<h1>AXS Workflow</h1>
<p><strong>A browser-automation prototype for event browsing and ticket selection.</strong></p>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Camoufox-6B4EFF?style=flat-square" alt="Camoufox" />
  <img src="https://img.shields.io/badge/Requests-2A6F97?style=flat-square" alt="Requests" />
</p>

</div>

## Purpose

AXS Workflow is a Python browser-automation prototype covering event-page browsing and ticket-selection steps. The project includes a local dashboard component and keeps final checkout as a manual action.

Its documented scope follows the transition from an event page to a ticket listing and selection. The public showcase presents that workflow at a product level without exposing operational details.

## Prototype scope

- Event-page and ticket-listing workflows.
- Listing selection and ticket-quantity handling.
- A local dashboard component.
- A manual handoff for final checkout completion.

## Visual overview

![AXS Workflow feature overview](assets/showcase/overview.png)

## High-level workflow

```mermaid
flowchart LR
    A["Selected event"] --> B["Browse ticket listings"]
    B --> C["Choose listing and quantity"]
    C --> D["User review"]
    D --> E["Manual checkout"]

    classDef stage fill:#f1f5f9,stroke:#64748b,color:#0f172a
    classDef manual fill:#fef3c7,stroke:#d97706,color:#78350f
    class A,B,C stage
    class D,E manual
```

The browser remains available for the user to review the selection and complete final checkout manually.

## Stack

Python, Camoufox and Requests support the documented browser workflow.

## Development status

Local prototype focused on event browsing and ticket selection, with user-controlled final checkout.

## About this repository

This repository is a public showcase. Only presentation material is published; source code and private data remain private.

**Last showcase review:** 2026-09-12 (Europe/Paris).
