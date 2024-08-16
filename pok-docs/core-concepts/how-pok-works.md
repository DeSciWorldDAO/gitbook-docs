# How PoK Works

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

## The Primitives

PoK consists of two core primitives:&#x20;

1. [kEngram](kengram.md) (kE) - a novel onchain data primitive optimised for embedding data for [RAG](../further-reading/rag-llm.md) query
2. [Universal Citation Points](universal-citation-points.md) (UCP) - an unopinionated accounting system to track usage of kEngram vectors by RAG search

## The Interactions

and two categories of interaction:

1. Offchain - the creation of kE; the querying of agents; the retrieval of kE and tracking of this action all take place in an offchain environment.
2. Onchain - the created kE are attested to onchain wallet address using [EAS](../further-reading/eas.md). The retrieval tracking of these vectors produce [UCP](universal-citation-points.md) that are attested to the kE upon use. Additonally, subDAO infra through [Research Collectives](research-collectives.md) facilitate and simplify an onchain environment to improve PoK user experience, provide an incentive layer and allow decentralised kE curation.

Together, these aspects provide an infrastructure for the embedding, surfacing and tracking of structured data via [RAG LLM](../further-reading/rag-llm.md), forming a [decentralised vector graph](../further-reading/dkg.md) ecosystem. These vector graphs are formed in isolation - each called a "[Brain](brains.md)" - but exist within a network of Brains, creating the PoK data layer that facilitates inter-graph queries and coordination of disparate data providers, globally.

## The Sources

The PoK data layer aggregates a wide variety of data sources to be embedded into kE.  This enables efficient search across an array of data, provided through a variety of channels including:

* chatstreams from platforms such as Telegram and Discord
* embedded markdown files
* other kE vector graphs in an inter-graph retrieval process
* social graphs obtained from Lens and Farcaster
* integratied&#x20;

## The Middleware

PoK utilises many exsting tools and software, both onchain and offchain, to facilitate the creation of data layer and points distribution.

Below is a brief description of the roles of these tools, for more, visit their linked docs:

* Index Network
* Ceramic
* EAS
* Akash Network
* Llama Index
* ChromaDB
* Lit Protocol
* EthereansOS

