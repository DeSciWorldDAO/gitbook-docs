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

### Attestation Framework

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

## Validation and Value Attribution

Validation within the PoK protocol operates as an emergent property of a <mark style="color:green;">free market of knowledge</mark>. RAG usage metrics, combined with other continously updating feedbacks, determine the validity and value of the knowledge in a market-based model.&#x20;

The Research Collective ecosystem facilitates groups to gather around specific types of knowledge. Each Research Collective (RC) may begin deploying kEngrams from the RC's interface. They may also aggregate the kEngrams of others, into their "accepted list", that acts as a de-facto ratification of the kEngram. When an kEngram is aggregated into the "accepted list" of an RC, that kE receives a tag in its metadata to show that its been ratified by that Collective. This allows permissionless ratification of knowledge, in a decentralised manner. The kEngrams can then be filtered by levels of ratification, including amount of ratified support and also where that ratification came from. Want to filter kEngrams by those that have been ratified by the Oxford University Research Collective, or by the University of Ethereum RC? Now you can!

In essence, within the Proof of Knowledge model, validation isn't a one-time stamp of approval but a continuous process of adaptation, adjustment, and evolution — a dynamic reflection of a knowledge unit's continuous performance in the marketplace of ideas and information, that simultaneously helps to determine its value.

## Composability

Composability is akin to building with LEGO bricks. Web3 is known for building an interoperable stack: components with a specific usecase that can be combined with others to create entirely new products. This concept is what drives the standardisation of EVM infrastructures.

In the PoK system we have two types of composabilty:

1. **Compasable Knowledge Units**: The kEngram unit itself can be considered as a part of the "DeSci stack"; designed so that it can be incorporated with other DeSci projects as a data input.
2. **Composable Knowledge**: Each piece of knowledge, or more precisely, each [attestation](kengrams.md#attestations), can stand alone but, when combined, they form a more complex and intricate structure to the benefit of the research.&#x20;

### Composable with:

#### AI Services

As the kEngram continues to be used among a global network of AI interfaces, each interaction and usage is also documented. These records contribute to an kEngram's ongoing validation in our ecosystem. This evidence-based approach ensures that each kEngram's relevance, accuracy, and utility are continuously verified, evaluated, and updated.&#x20;

#### The DeSci stack

We anticipate the kEngram will be a widely used primitive for containerising, transferring and attributing knowledge to Authors onchain. The burdegoning DeSci stack may adopt the kE as a fundamental building block for knowledge creation.

## Coherence

{% hint style="info" %}
#### Instead of accuracy as the defining factor of kEngrams, we optimise for coherence.
{% endhint %}

Coherence ensures that the kEngrams contain logically consistent and well-structured information; a clear, homogeneous narrative between the Question and the Answer. This helps to ensure that the kEngram not only makes sense but also can be efficiently queried by AI services.

This process is thought of at two levels:

1. **Local Coherence**: This refers to the cohesion and connectivity within a single kEngram. It involves ensuring each addition to a kEngram is internally consistent and logically connected with the others. This helps to improve the comprehension and interpretation of the individual kEngram.
   * One method to maintain local coherence is to develop focused kEngrams, centred around specific Study Questions or queries.&#x20;
2. **Global Coherence**: Global coherence extends beyond individual kEngrams. It includes the logical connection and relationships between different kEngrams within the Knowledge Graph. Therefore, it not only focuses on the intra-kEngram relationships but also on the inter-kEngram connections. This helps create a globally coherent embedding space, crucial for developing Knowledge Graphs.
   * To improve global coherence, related kEngrams can be cross-referenced. This helps to create a network of related knowledge, thus adding depth and breadth to the overall knowledge representation.

## Coherence Engineering

There are a variety of strategies to enhance coherence in both local and global perspectives. We anticipate whole schools of thought dedicated to understanding and optimising for coherence will emerge in response to this protocol.

User interactions also play an essential role in maintaining and enhancing coherence. Feedback from users can be a powerful tool to refine and update the information in the kEngram, making it more coherent over time. This user-led learning and updating process helps to create a dynamic, interconnected hub of collective knowledge, which is the heart of the PoK mechanism.

In conclusion, optimizing coherence in the PoK system is key to creating an effective and useful knowledge-based ecosystem. It involves a continuous process of learning, adaptation, and evolution with a focus on nurturing the most relevant, coherent, and valuable knowledge.



<figure><img src="../../../.gitbook/assets/CleanShot 2023-12-17 at 21.22.49@2x.png" alt=""><figcaption></figcaption></figure>
