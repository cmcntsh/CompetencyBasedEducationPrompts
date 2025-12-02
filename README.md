# Competency-Based Education Prompts

## Mapping

A useful set of mapping relationships in the Simple Knowledge Organization System (SKOS) are defined by the World Wide Web Consortium (W3C). The SKOS is used for linking knowledge organization systems. Concepts orgainized in different concept schemes can be linked to each other using SKOS mapping properties. See https://www.w3.org/TR/skos-reference/#mapping and https://www.w3.org/TR/2009/NOTE-skos-primer-20090818/

* skos:exactMatch - \<A> skos:exactMatch \<B> indicates an exact equivalence mapping link between \<A> and \<B>
* skos:closeMatch - \<A> skos:closeMatch \<B> indicates a close equivalence mapping link between \<A> and \<B>
* skos:broadMatch - \<A> skos:broadMatch \<B> indicates a hierarchical mapping link between \<A> and <B> where \<B> is broader than \<A> 
* skos:narrowMatch - \<B> skos:narrowMatch \<A> indicates a hierarchical mapping link between \<A> and \<B> where \<A> is narrower than \<B> (skos:broadMatch and skos:narrowMatch have an inverse relationship)
* skos:relatedMatch - \<A> skos:relatedMatch \<B> indicates an associated mapping link between \<A> and \<B> with no hierarchy indicated

Prompt: map concepts to each other using SKOS mapping relationships

```
You are in expert in <Field or Domain> and in knowledge organization systems like thesauri, taxonomies, classification schemes, and subject heading systems. Please use the Simple Knowledge Organization System (SKOS) mapping relationships defined by the World Wide Web Consortium (W3C) to assign a relationship between each item in list 1 with each item in list 2. The mapping relationships are defined and described online: https://www.w3.org/TR/skos-reference/#mapping and https://www.w3.org/TR/2009/NOTE-skos-primer-20090818/ The mapping relationships are skos:exactMatch, skos:closeMatch, skos:broadMatch, skos:narrowMatch, and skos:relatedMatch. Here is a description of the meaning for each mapping relationship: <A> skos:exactMatch <B> indicates an exact equivalence mapping link between <A> and <B>; <A> skos:closeMatch <B> indicates a close equivalence mapping link between <A> and <B>; <A> skos:broadMatch <B> indicates a hierarchical mapping link between <A> and <B> where <B> is broader than <A> (skos:broadMatch and skos:narrowMatch have an inverse relationship); <B> skos:narrowMatch <A> indicates a hierarchical mapping link between <A> and <B> where <A> is narrower than <B>; and <A> skos:relatedMatch <B> indicates an associated mapping link between <A> and <B> with no hierarchy indicated. Here are the items in list 1: "<Paste list 1 here.>" Here are the items in list 2: "<Paste list 2 here.>" Please provide the rationale for the mapping classification you assigned to each concept pairing between list elements.
```
