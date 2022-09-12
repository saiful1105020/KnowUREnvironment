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

KnowUREnvironment includes facts about climate change and related environmental issues in the form of <em>Resource Description Framework (RDF)</em> triples. An RDF triple consists of three components: (i) subject, (ii) predicate, and (iii) object. For example, we can express the fact "automobile emits CO2" can be expressed as ("automobile", "emit", "CO2") where "automobile" is the subject, "CO2" is the object, and "emit" is a directional relationship between the subject and the object. The entire set of the RDF triples can be captured by a directed multigraph (there may be multiple relationships between the same subject-object pair) where the subjects and objects are represented using nodes, and the predicate is represented using a directed, labeled edge in the graph.

<figure>
 <img src="main_example.jpg", style="width:90%">
 <figcaption>A snapshot of KnowUREnvironment depicts how "automobile" could be related to climate change and related issues.
Within a few hops, the graph can connect concepts from diverse yet relevant fields like environment, agriculture, and public
health demonstrating how powerful yet so compact a knowledge graph can be.</figcaption>
</figure>


