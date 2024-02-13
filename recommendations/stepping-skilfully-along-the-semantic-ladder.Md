# Introduction

The semantic ladder is a metaphor for the progression from less expressive semantic artifacts (e.g. term lists, vocabularies) to highly expressive artifacts (e.g. formal ontologies). Here, expressiveness is concerned with how well a machine agent (e.g. a reasoner, a natural language processing agent) can discover how any given term relates to another. Some semantic artifacts will indicate loose associations of terms, while others will use precisely defined relationships, themselves arranged in a semantic structure (e.g. expressing different kinds of spatial relations, "adjacent to", "dorsal to", "anterior to", etc). 
  * In a simple vocabulary, like a term list, a machine agent can look up whether a term is present and lexically aligned to a collection. There is little to no semantic content in such lists, beyond defining a universe of expected terminology.
  * In a structured vocabulary, the terms are embedded in some form of relational framework, expressed through a format like RDF (e.g. "term 1" is_child_of "term 2"). The relations may have arbitrary meaning, and the structures may or may not have formal or consistent semantics. 
  * In a (typical) dictionary, terms are associated with human-readable definitions. This may or may not be of interest to a machine agent, depending on its ability to process natural language.
  * In a thesaurus, terms are related to other terms through relations that express synonymy, antonymy, loose semantic relatedness, exact matches, and similar relations. The Simple Knowledge Organization System (SKOS) is a prominent format for rendering a thesaurus. 
  * In an ontology, formal relationships (axioms) are used to precisely interrelate terms arranged in a superclass-subclass hierarchy, where each subclass inherits all the properties of its superclass. Ontologies are typically "reasoned" (processed through software called a "reasoner") to assess whether the asserted relations are logically coherent and satisfiable. Ontologies are often expressed in the Web Ontology Language (OWL) and its variations.

Choosing what level of the semantic ladder is useful for your application is a critical choice, and sometimes a mix of artifacts are needed to accomplish an initiatives aims. The recommendations below aim to offer implementation guidance across a range of scenarios.


# Recommendations

## Balancing machine- and human-friendliness  



# ... Further sections / examples 
