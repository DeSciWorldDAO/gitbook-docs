---
description: Composable, on-chain units of knowledge
---

# kEngrams (kE)

**kEngram**\
/ˈɛnˌɡɹæm/\
_noun_\
&#x20;   _1._ a composable, on-chain unit of knowledge\
&#x20;   2\. a provenance and usage tracker for RAG LLM responses\
&#x20;   3\. the fundamental nodes of Proof of Knowledge's DKG builder

## What is an kEngram?

kEngrams can be defined as a **structured unit or node of knowledge** within our Decentralised Knowledge Graph, the Brain. It's a piece of information that is interconnected within a broader landscape of data, contributing to the broader understanding of a concept or topic. kEngrams can be searched using RAG LLM as their data are vectorised.

kEngrams are modelled after the theoretical stucture of our brains, the engram:

> An engram is a unit of cognitive information imprinted in a physical substance (brain), theorized to be the means by which memories are stored.

{% hint style="info" %}
The "k" in "kEngram" stands for "knowledge" and is silent.&#x20;
{% endhint %}

### kEngram Essentials

In theory, an kEngram can consist of content in any structured form. However, v1 kEngrams must consist of markdown data type.&#x20;

The kE's essential form is determined by the data ontology used during its creation. Data ontologies can be as simple as **Question -> Answer**, or much more complex. We refer to the data ontology as the "Question", and the structured content that results as the "Answer".

An kEngram consists of several integral components that collectively contribute to its formation and execution:

1. **Question**: This encompasses the essential content of the query. and can exist without a reference to other notes.
2. **Answer**: This is the base content of the kEngram, formulated into a set of markdown notes that contains the information added in order to explore the Question. Answers must point to the Question or another Data Node
3. **Metadata**: The Metadata provides critical information about the authorship of the kEngram and its historic record of usage by the PoK protocol, recorded through [attestation](kengrams.md#attestation-framework). It lends context and understanding about the contained knowledge, bolstering its relevance within the Brain.
4. **Unique Identifier**: Every Engram has a unique ID associated with it, allowing for its distinct recognition, tracking, and management within the overall Brain system.
5. **Relationships**: These are connections that a kEngram has among its underlying data. These relationships can be thought of as edges in the graph, defining how pieces of information are interconnected, and enabling the creation of a comprehensive, multi-dimensional structure of knowledge.

## Attestation Framework

The Ethereum Attestation Service lays the groundwork for our provenance mechanism. Each attestation becomes part of the computation determining value attribution and reward distribution.

> EAS ensures a transparent and fair system where contributors of Engrams are rewarded based on actual utility and demand in the ecosystem. You can see more about this here: [https://attest.sh/](https://attest.sh/)

The use of EAS within the PoK protocol forms a trustworthy and secure system for validating knowledge contributions and rewarding contributors. It answers the call for a distributed, transparent, and reliable method to authenticate, validate, and incentivize meaningful engagements in a decentralized knowledge ecosystem.

## kEngram Life Cycle

### Creation

For a full walkthrough of kEngram creation using Obsidian, please read [ke-starter-guide](../ke-starter-guide/ "mention")

kE are primarily created through the Research Collective interface but can be created by many methods. Again, the essential nature of an kEngram is structured data made available through a vector database with ties to the blockchain for provenance and tracking. We believe the toolset made available through Obsidian facilitaites the most comprehensive and powerful kEngram creation.&#x20;

When a kEngram is first created, it is recorded via an attestation to the Question. The creator of the kEngram is also noted through EAS, attesting that they were the original contributor of that knowledge piece.&#x20;

### Updating

As knowledge terrains continue to expand and evolve, so do kEngrams. Along the life-cycle, an kEngram may undergo several evolutions, manifested as updates, revisions, or further value additions. New data may be contributed, older information may be updated or made obsolete, and new connections to different kEngrams may be established. All these changes contribute to the growing lifecycle of an kEngram, helping it remain relevant, useful, and accurate in the dynamic ecosystem of the Knowledge Graph. Each change is also captured through an attestation, creating a trail of evolution and accumulation of intellectual input.

### Value Addition

Once a kEngram has been formed, it can be further enriched and enhanced by other groups or individuals who add their own knowledge and insights to it. They can integrate additional data, revise existing information, or link the kEngram to other related kEngram within the Knowledge Graph. This collaborative process of knowledge amplification adds a multi-dimensional depth of understanding to the kEngram, enhancing its value.

### Utilization & Evolution&#x20;

Engrams, once submitted, are then available for use. They are identified and selected by AI interfaces based on their relevance to specific queries or tasks. The frequency, context, and nature of how these Engrams are utilized play a crucial role in determining their ongoing validation scores and their corresponding value within the knowledge market.

<figure><img src="../../.gitbook/assets/CleanShot 2023-12-17 at 21.22.49@2x.png" alt=""><figcaption></figcaption></figure>
