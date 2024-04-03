![Qworum logo and name](https://raw.githubusercontent.com/doga/qworum-website/master/build/assets/images/logos/Qworum-logo-and-name.svg "Qworum logo and name")

# Qworum ontology

An RDF ontology for use within the [Qworum platform](https://qworum.net) and the larger RDF ecosystem.

## Classes and interfaces

Description of Qworum classes and the interfaces they implement:

- Interfaces can extend zero, one, or many other interfaces.
- A Qworum class implements exactly one interface.
- For their properties and method parameters, Qworum classes can indicate which actual interface implementations they are using.

## Various terms

- `qrmv:end` — end-of-document indicator, used for ensuring the completeness of RDF documents that are being read, particularly in streaming scenarios.
- `qrmv:anyIRI` — an IRI that should not be dereferenced, either because it points to non-RDF content, or because it points to RDF content that is not relevant for the current RDF dataset.
- `qrmv:comment` — a comment written in Markdown.

∎
