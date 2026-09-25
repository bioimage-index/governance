# Governance and operations

This repository contains information on how the Bioimage Index is run,
and is currently under active development.

Documents in this repository that have not yet been approved by the Interim Steering Council 
are labeled with [DRAFT] at the top of the page.

Please [file an issue](https://github.com/bioimage-index/governance/issues) with any questions or corrections.

## Overview of governance

*This overview was shared with with Interim Steering Council on September 17, 2026 for review and feedback prior to posting.*

Petabytes of public bioimage data are effectively invisible to researchers, with no unified way to discover what data exists and where across independent repositories. The Bioimage Index is a federated, image-level "existence + location" search layer that seeks to build this gap. This document describes the basic governance structure for the Bioimage Index, focusing on the Phase 1 proof-of-concept project: a search API and portal by Q3 2027.

### Participating organizations

Representatives from seven organizations collectively developed the project plan for Phase 1. Referred to as Founding Partners, these organizations include:

- Allen Institute
- Biohub
- EMBL-EBI: BioImage Archive (BIA)
- University of Dundee: Image Data Resource (IDR)
- RIKEN: Systems Science of Biological Dynamics (SSBD)
- GerBI
- openRxiv

### Roles and responsibilities

For Phase 1, Biohub is serving as driver for the overall project, with other partner organizations receiving Biohub funding or providing in-kind support to meet the goals of the shared work plan. Project implementation is best described as a hub-and-spoke model, with Biohub providing centralized project management, communications, and milestone tracking, and other Founding Partners responsible for specific deliverables and onboarding their own repositories to the index. Overall decision-making is a shared responsibility among representatives of the Founding Partners.

An Interim Steering Council is the formal decision-making body for the project, and will meet every two months to review progress and align on upcoming priorities. All individuals involved in the project so far will receive an invitation to these meetings, and are also invited to the shared Slack channel (#bioimage-index-coordination) for asynchronous communication. The goal is to make decisions based on collaborative discussion and consensus-building among the entire group. In the event that consensus cannot be reached and voting is required, each Founding Partner will receive one vote, and the leader of the working group to which the decision is most closely aligned will serve as tie-breaker if necessary. 

Work streams are focused on specific deliverables and are each associated with a Working Group. A lead is assigned to each working group, and can develop governance, ways of working, and meeting cadence  as best suits their needs. Each working group will be asked to provide regular updates to the Interim Steering Council, as well as to other working groups on which their work is closely aligned.

| Working group and tasks | Dependent working groups |
| --- | --- |
| **Core Schema Definition:** schema development, metadata gap analysis | |
| **Metadata Exchange Protocol (MEP):** product roadmap, index build | |
| **Portal search infrastructure:** Product roadmap & technical build | |
| **BioFile Finder (BFF) search infrastructure:** Product roadmap & technical build | |
| **Hosting and infrastructure:** Hosting setup, infrastructure handoff, publishing ecosystem integration | Portal search infrastructure, Governance and sustainability |
| **Governance and sustainability:** decision-making, licensing, business model, Repository Certification Process (RCP) | Core Schema Definition |
| **Program and community management:** communications, stakeholder relationships, milestone tracking, reporting | All Working Groups |

### Deliverables and licensing

The main deliverables planned for Phase 1 are defined below. Licenses for types of deliverables and their current locations are included where available.

- Governance (CC-BY 4.0)
    - BII Github organization (this organization)
    - Governance repository (this repository)
    - Repository Certification Process (location TBD)
    - Project website content (location TBD)
- Technical schema/specifications (MIT preferred, checking dependencies for each project)
    - Core Schema
    - Metadata Exchange Protocol
- Search infrastructure (Apache-2.0 preferred, checking dependencies)
    - Search system/API
    - Search portal
- Image-level metadata (CC0 1.0 proposed, each repository will need to confirm)
    - Note: Each data record retains the licensing named in the repository of origin, which includes a variety of licenses with different levels of restriction. 

### Changes to the project

Updates to this document must be approved by the Interim Steering Council.

If an organization chooses to end its collaboration with the Bioimage Index, their assigned work will be redistributed among the other Founding Partners as necessary. If an organization responsible for onboarding their own repository is no longer participating, the data from that repository will not be indexed. If the organization was leading a working group, another member of the working group will be asked to take over leadership. In the event that another working group leader is unavailable, Biohub will assume responsibility for the work.

## Acknowledgements

The first draft of these materials were developed by Kate Hertweck (@k8hertweck) and relied on the following sources:

- [foundingGIDE](https://founding-gide.eurobioimaging.eu/): [governance](https://founding-gide.eurobioimaging.eu/about-us/#governance)
- [Project Jupyter](https://jupyter.org): [governance](https://jupyter.org/governance/) and [Executive Council Team Compass](https://ec.jupyter.org/#)
- [Infra Finder](https://infrafinder.investinopen.org/solutions): [documentation](https://hackmd.io/@investinopen/Infra-Finder/https%3A%2F%2Fhackmd.io%2FmXGCn7NyQeOjBewRQPlJFQ?ref=investinopen.org#Policies-amp-Governance)
- [The Data Catalyst³ (Cubed): Accelerating Data Governance with Change Management and Data Fluency](https://technicspub.com/the-data-catalyst/) by Robert S. Seiner
