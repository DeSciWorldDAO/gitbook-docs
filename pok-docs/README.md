# Introduction to PoK

## Welcome!

PoK, Proof of Knowledge, is an open source infrastructure public good for creating a unified embedding space for general AI usage, onchain and offchain.

PoK provides an unopinionated data layer optimised for RAG LLM query, resulting in an advanced AI-based search system. PoK tracks the usage of individual vectors and issues points to the authors of those vectors when queried. This allows for decentralised contribution to a [collective knowledge base](core-concepts/brains.md), optimised for efficient communication of context via intra-graph query (within one knowledge base) and inter-graph query (different knowledge bases communicating with each other).&#x20;

## Why does this exist?

#### Onchain Association

The convergence of technologies in the fields of blockchain, AI, compute, storage and communication provide new avenues for coordinating people in the digital space. For the first time in history, we have the tools available at an economic scale suitable for mass usage to allow for the creation and empowerment of truly soveriegn communities.

{% content-ref url="vision/onchain-association.md" %}
[onchain-association.md](vision/onchain-association.md)
{% endcontent-ref %}

#### Knowledge-Backed Economy

We strongly believe that data - the lifeblood of AI - should provide both provenance and value back to the author. The knowledge and context that is created by our information is what makes AI useful; without our input, AI would cease to provide meaningful results. As such, we should own our fair share of the AI-driven future. We must create mechanisms that allow for the open, decentralised contribution to and utilisation of AI technologies while ensuring the sovereign individual is not taken advantage of.

{% content-ref url="vision/knowledge-backed-economy.md" %}
[knowledge-backed-economy.md](vision/knowledge-backed-economy.md)
{% endcontent-ref %}

#### Network Coordination

As these AI agents can represent the view point of one or many people, through the embedding and retrieval of their data, we can utilise agents as an interactive and adaptive mouthpiece for our onchain associations. It is a large task to coordinate a group of people internally to an association, a much larger one still to coordinate between associations. Multi-Agent Systems (MAS) allow our personalised agents to seamlessly communicate between each other, providing unprecedented coordination.

{% content-ref url="vision/network-coordination.md" %}
[network-coordination.md](vision/network-coordination.md)
{% endcontent-ref %}

## What are the use-cases?

The unopinionated nature of PoK allows for infinte use-cases to be created by the community. It is our ambition to support and inspire a library of "plugins" for PoK to proliferate over the coming years.

Some exciting potential and existing use-cases:

* **Representatives**\
  Associations of people may allow an agent to consume their chatstreams and existing documentation to create a representative intelligence in an agent. This agent can then be used as an external-facing product for people to interact with that represents the association 24/7.
* **Coordinators**\
  Agents imbued with an association's intelligence can then coordinate members of said association. For example, if members have a question about the state of a task, or want to make a new plan, they can query the Coordinator to get an instant answer from their embeddings, that delivers a direct reference to the original author of that data.
* **Research Assistant**\
  Agents connected to PoK are aware of the state of embeddings of all other agents in the network. When researching a topic, users can speak with the PoK agent to determine the state of research that exists, providing links and recommendations to research or researchers that may assist in their work.
* **Trading Bots**\
  Intelligences can keep an aggregated sentiment analysis of PoK authors, determining the volatility index of the market and executing onchain trades for an association that loads a wallet for them. This can be alternative income streams for users.

## How does it work?

PoK utilises multiple offchain and onchain middleware tools to facilitate its data layer and points distribution. PoK's novel contribution to the deAI stack is the [kEngram](core-concepts/kengram.md), an onchain data primitive optimised for embedding data for [RAG](further-reading/rag-llm.md) query.
