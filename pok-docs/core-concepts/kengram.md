# kEngram ⧖

**kEngram** \
/ˈɛnɡram/\
_noun_\
&#x20;   _1._ a novel onchain data primitive\
&#x20;   2\. data structure optimised for vector embedding and RAG query\
&#x20;   3\. the primary knowledge unit in the Proof of Knowledge protocol\
_notation_\
⧖ - \[unicode 29d6]

The Proof of Knowledge (Pok) protocol is built around the [attestation](https://docs.attest.sh/docs/core--concepts/attestations) of kEngrams (kE). kEngrams are designed as a blockchain-based primitive aimed to incentivize and reward knowledge contributions within a _decentralized architecture._&#x20;

## Question -> Claim

An kEngram consists of a **Question** and an associated **Claim**. This is symbolised with unicode notation 29d6, two interlocking triangles, illustrated below.  We assert that storing the data kE in Question -> Claim format produces the most performant RAG search results.

The question is the basis of inquiry that the AI agent uses during its RAG search.  As such, when new data is embedded into an index, it is either:&#x20;

a) related to an existing Question as a Claim;&#x20;

b) becomes the basis of a new Question.



<figure><img src="../.gitbook/assets/July Deck (4).png" alt=""><figcaption></figcaption></figure>

## Haikuification

Each kEngram, when stored in PoK, is first structured in the Question -> Claim format. Next, the entire data unit is passed through a query to create a Haiku of that data. This uses "poetic encoding" to maintain strong semantic value representation of the data, yet compresses the data into a small line of text - a Haiku. Not only does this compress the amount of text stored, but it also creates a unified ontology for the RAG query to utilise in its first-stage search. This improves [coherence](coherence.md) of search results.



<figure><img src="../.gitbook/assets/HaikukE (1).png" alt=""><figcaption></figcaption></figure>

## Attestation

Using EAS, we can create an unbreakable link between the Author and the kEngram. When users submit to the Brain, the kEngram that is created is attested to their wallet address or UserID. Whenever that kEngram is used as context in future RAG queries, PoK creates another attestation of that query happening. This allows PoK to effectively track provenance of data and usage of that same data, which provides the basis of the PoK [Universal Citation Points](universal-citation-points.md) (UCP) system.
