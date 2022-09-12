# KnowUREnvironment
 
Despite climate change being one of the greatest threats to humanity, many people are still in denial or lack motivation for appropriate action. A structured source of knowledge can help increase public awareness while also helping crucial natural language understanding tasks such as information retrieval, question answering, and recommendation systems. We introduce <em>KnowUREnvironment</em> -- a knowledge graph for climate change and related environmental issues, extracted from the scientific literature. We automatically identify 210,230 domain-specific entities/concepts and encode how these concepts are interrelated with 411,860 RDF triples backed up with evidence from the literature, without using any supervision or human intervention. Human evaluation shows our extracted triples are syntactically and factually correct (81.69% syntactic correctness and 75.85% precision). The proposed framework can be easily extended to any domain that can benefit from such a knowledge graph.

## Climate Change Abstracts

We extracted 228,860 abstracts related to climate change and environmental issues, by mining articles published before 2020. The following keywords were matched against author provided keywords to find the relevant articles:

<ul>
<li>climate change</li>
<li>sustainability</li>
<li>pollution</li>
<li>global warming</li>
<li>sea-level rise</li>
<li>climate</li>
<li>water stress</li>
<li>coastal flooding</li>
</ul>

<a href="#"> Download the extracted abstracts with author-provided keywords</a>

## About the Knowledge Graph

<figure>
 <img src="main_example.jpg", style="width:90%">
 <figcaption>A snapshot of KnowUREnvironment depicts how `automobile` could be related to climate change and related issues.
Within a few hops, the graph can connect concepts from diverse yet relevant fields like environment, agriculture, and public
health demonstrating how powerful yet so compact a knowledge graph can be. Additionally, each of the links in the graph is
backed up by a scientific evidence</figcaption>
</figure>
