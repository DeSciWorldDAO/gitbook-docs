# How PoK Works

PoK consists of two core primitives:&#x20;

1. [kEngram](kengram.md) (kE) - a novel onchain data primitive optimised for embedding data for [RAG](../further-reading/rag-llm.md) query
2. [Universal Citation Points](universal-citation-points.md) (UCP) - an unopinionated accounting system to track usage of kEngram vectors by RAG search

Together, these two primitives provide an infrastructure for the embedding, surfacing and tracking of structured data, forming a [decentralised vector graph](../further-reading/dkg.md) ecosystem. These vector graphs are formed in isolation - we call them [Brains](brains.md) - but exist within a network of Brains, creating the PoK data layer that facilitates inter-graph queries and coordination of disparate data providers using [RAG LLM](../further-reading/rag-llm.md).

The kE vector graph enables efficient search across an array of data, provided through a variety of channels including:

* chatstreams from platforms such as Telegram and Discord
* embedded markdown files
* other kE vector graphs in an inter-graph retrieval process
