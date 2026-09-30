![Static Badge](https://img.shields.io/badge/WIP-In%20Development-blue?style=flat)

# semantiquary [work in progress]

## Aims

Semantiquary leverages the [Solid](https://solidproject.org/) ([protocol](https://solidproject.org/TR/protocol)) and [Linked Data Event Streams](https://interoperable-europe.ec.europa.eu/collection/semic-support-centre/linked-data-event-streams-ldes) ([spec](https://semiceu.github.io/LinkedDataEventStreams/releases/1.0.0/index.html)) to delivery a decoupled cultural heritage-specific semantic layer comprising the [CIDOC CRM](https://cidoc-crm.org/) ontology and the [Getty Arts & Architecture Thesaurus (AAT)](https://www.getty.edu/research/tools/vocabularies/aat/) to improve federated querying. 

## Background

Cultural heritage fosters social cohesion through mutual understanding, intercultural dialogue, and psychological resilience during crises ([G20 2025 South Africa, Culture Working Group](https://articles.unesco.org/sites/default/files/medias/fichiers/2025/03/Issue%20Note_Culture%20WG%20official%203.pdf)). 

Two persistent problems in cultural heritage management and conservation are (1) the issue of hindered cross-repository search and discovery (e.g. due to intensive queries across federated endpoints) and (2) a missing mechanism for recording contributions from those  outside of the data-holding institutions.  For example, if a researcher from an indigenous community were to identify a meaningful link between two heritage assets, one in Institution A and the other in Institution B, there would be limited means to make a contextualised, logged and secure annotation.  Presently, the researcher must rely on institutions A and B to modify their records, which would be time-delayed and have practical, bureaucratic, and potential legal ramifications that don’t guarantee the meaningful information will be retained or shared.  The Semantiquary project seeks to improve cross-repository search and discovery and enable new contribution routes to knowledge frameworks using Solid pods. 

The envisioned added value of Semantiquary are:  (1) off-loading performance-heavy queries away from the federated institutions, (2) embed research practice into a Solid ecosystem, providing the much-needed tracking for more democratised, crowdsourced contributions. (An outside researcher could contribute new triples via their own pods without altering any institutions’ collection database.)  (3) It provides an audit trail for data changes, which can spur future research (i.e. a means to review the evolving semantic understanding of a heritage asset over time). (4) Leveraging Solid pod permission controls and event logging (LDES) supports legal protection frameworks.

## Related Work

A combined implementation of the CIDOC CRM and Getty AAT solution is already a part of the [Linked Art](https://linked.art/) initiative.  However, unlike Linked Art which enforces a strict design scope that is limited to only a subset of core classes and does not log data provenance events, Semantiquary seeks to preserve the graph structure and formal logic of the whole ontology with the full Getty AAT within Solid pods and preserve the event-centric model of the CIDOC CRM via Linked Data Event Streams (LDES).  

Other projects that tackle the cross-repository search and discovery challenge in the cultural heritage data space include the aggregator model of the European [ARIADNE](https://www.ariadne-research-infrastructure.eu/) project for archaeological data and the hybrid effort by the UK’s [HSDS/RICHeS](https://www.riches.ukri.org/) programme for conservation and heritage science which accesses distributed databases via a centralised search portal supported by a high-performance computing backend.  

Semantiquary presents an alternative approach that avoids limited semantic implementations (Linked Art), the data syncing issues of an aggregator model (ARIADNE) and reduces the need for supercomputing infrastructure (RICHeS).  

Semantiquary does not seek to compete with existing efforts.  Instead, working towards a proof-of-concept, it will offer an alternative avenue to address technical bottlenecks that work in tandem to further cultural heritage research and conservation.  


