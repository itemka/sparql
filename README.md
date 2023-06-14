# SPARQL

## 1. Introduction:

- Resource Description Framework (`PDF`): https://en.wikipedia.org/wiki/Resource_Description_Framework
- [SPARQL](https://en.wikipedia.org/wiki/SPARQL)

***

## 2. Building blocks of an RDF graph

- RDF graph at a glance: https://prezi.com/p/9mh5iy8664e1/looney-tunes-graph/
- Semantic triple: https://en.wikipedia.org/wiki/Semantic_triple
- Internationalized Resource Identifier: https://en.wikipedia.org/wiki/Internationalized_Resource_Identifier
- Blank node: https://en.wikipedia.org/wiki/Blank_node

***

## 3. Authoring RDF graph data

* RDF graph at a glance: https://prezi.com/view/BKhuOQHjSzEpMUvtNnWe
* Add the `solution-looney-tunes.ttl` file 

***

## 4. Querying with SPARQL: The essentials

Code example:
```
SELECT *
WHERE {
  ?s ?p ?o
}
LIMIT 20
```

> a = rdf:type

* SPARQL 1.1 Query Language: https://www.w3.org/TR/sparql11-query/
* For more queries look at the `get.sparqlbook` file.

***

## 5. Querying with SPARQL: Property Paths

* SPARQL 1.1 Property Paths: https://www.w3.org/TR/sparql11-query/#propertypaths
* For more queries look at the `propertyPaths.sparqlbook` file.

***

## 6. SPARQL Update

* SPARQL 1.1 Update: https://www.w3.org/TR/sparql11-update/
* For more queries look at the `update.sparqlbook` file.

***