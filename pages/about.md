---
title: About the Methods Commons
permalink: /about
sidebar: main
summary: UK national infrastructure for FAIR computational workflows in the life sciences.
---

## The programme

The BioFAIR Methods Commons (MC) is a two-year, UKRI/BioFAIR-funded
programme to build a UK national infrastructure for FAIR (Findable,
Accessible, Interoperable, Reusable) computational workflows in the life
sciences. Led by Carole Goble (University of Manchester) with partners at
the Earlham Institute and Seqera, the consortium brings together the teams
behind **Galaxy**, **Nextflow** and the **WorkflowHub** registry. Building
on 20+ years of experience running Europe's shared workflow services, it
joins up the UK's currently siloed workflow provision into a single,
standards-based environment.

## Goals and ambitions

The MC's strategic goal is to establish and operate standards-based,
user-driven technical infrastructure; to engage and onboard the UK research
community; and to put in place the processes needed for sustainable
operation, with FAIR practice embedded throughout.

The underlying ambition is a **federated, cooperatively-governed commons**
that partners and institutions build together, where diverse workflow
systems interoperate, users get reproducible results on infrastructure they
don't have locally, and workflow developers get credit and reuse for their
FAIR contributions.

## Objectives

### 1. Scalable execution infrastructure

A national Galaxy instance, an enterprise-grade Seqera/Nextflow platform,
and JupyterLab (with containerised support for Snakemake, R and more) on
AWS, built on standard APIs (GA4GH, Conda, RO-Crate).

### 2. Workflow discovery

WorkflowHub as the single access point for discovering, reusing and sharing
workflows across languages, hosting a curated **BioFAIR Workflow
Collection** of endorsed, canonical workflows.

### 3. Secure collaboration

A **Shared Project Space** for private, access-controlled management of user
data and results, using Workflow Run RO-Crate provenance, foreshadowing the
future BioFAIR Data Commons.

### 4. Community mobilisation

Scaling support from no-code biologists to expert developers, through:

- **Concierge Service**: a tiered, user-led support model covering the whole
  workflow lifecycle (design, selecting existing workflows, evaluation,
  debugging), from intensive co-development with Exemplar Use Cases and
  premium support for complex projects, through self-service onboarding to
  lighter-touch community outreach.
- **CRM and direct engagement**: tracking each user and project as a coherent
  journey rather than isolated tickets, backed by clinics, hackathons, a User
  Forum and Club, and Champions, with AI agents increasingly automating
  routine support.
- **Workflow Observatory**: the quality-assurance layer built into
  WorkflowHub that curates, tests, benchmarks and FAIR-vets workflows (using
  tools such as LifeMonitor and the ELIXIR FAIR Checker), issuing quality
  indicators and endorsement decisions for the BioFAIR Workflow Collection.
- **Knowledge Hub**: curated guides, playbooks and training materials
  supporting self-service and onboarding.

### 5. Operational excellence

Governance, playbooks, an operations handbook and standardised APIs that
embed FAIR practice across the workflow lifecycle, with clear pathways for
onboarding further workflow systems and agentic AI.

## Delivery

Delivery is a two-year, two-phase MVP, organised as eight work packages
spanning platform DevOps (core infrastructure, workflow execution, the Shared
Project Space, the Commons Hub/registry) and community work (workflow
collection curation, concierge support, community engagement and governance).

- **Phase 1 (months 1–12)**: stand up core services, launch the concierge
  model, and co-design intensively with a small set of workflow-ready
  Exemplar Use Cases and BioFAIR Fellows to establish features and processes.
- **Phase 2 (months 12–24)**: shift to feedback-driven feature development,
  operational consolidation, broader recruitment, integration with other
  BioFAIR spokes, and support for additional workflow systems (Snakemake, R)
  and agentic AI.
- **Beyond (Year 3+)**: transition to a lower-friction "MC-as-a-service"
  mode, with users interacting mainly through documented APIs and catalogues.

Progress is tracked against milestones (for example, cloud/IaC foundations
and single sign-on by month 6; Galaxy and Nextflow instances with most
Exemplar Use Cases onboarded, an MVP RO-Crate catalogue and a Knowledge Hub
by month 12) and against KPIs covering usage growth, community adoption,
training uptake and FAIR compliance.
