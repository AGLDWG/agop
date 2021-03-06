
### NOTE: this profile is not yet complete nor approved by the AGLDWG for use or release

![](agldwg-logo-ochre-150.png)

# Australian Government Ontology Profile
A profile of OWL for the purposes of [Australian Government Linked Data Working Group](https://www.linked.data.gov.au).

This is a *profile*, that is a specification that constrains, extends, combines, or provides guidance or explanation about the usage of another specifications. In this case, this profile constrains the [OWL 2 Web Ontology Language
RDF-Based Semantics](https://www.w3.org/TR/owl2-rdf-based-semantics/) to ensure that the ontology, and things it defines, contain properties for cataloguing and documentation purposes.

Future versions of this profile may include requirements for modelling patterns too, but currently requirements are only for certain forms of annotation.

This profile is formally described using the [Profiles Vocabulary](https://www.w3.org/TR/dx-prof/) and a machine-redable ([RDF](https://www.w3.org/RDF/)) and human-readable (HTML) form of it are available:

* [agop.ttl](profile.ttl) - RDF (turtle serialization)
* [agop.html](profile.html) - HTML
  * see this rendered at [here](https://rawcdn.githack.com/AGLDWG/agop/a9e85a31a53985375f908d17875695005c207367/agop.html)

his profile's persistent URI:

* <https://linked.data.gov.au/def/agop>


## Profile Resources
This Profile contains several different resources.

### Specification
The set of Requirements for ontologies that this Profile defines, in human-readable (web page) form are given in the [specification document](specification.html), a rendered version of which you can see here:

* [specification](https://rawcdn.githack.com/AGLDWG/agop/a9e85a31a53985375f908d17875695005c207367/specification.html)

### Validator
The machine-actionable form of the same Requirements is given in the [validator resource](validator.shacl.ttl) which is a [SHACL](https://www.w3.org/TR/shacl/) Shapes file used to validate RDF documents.


### Examples
Four examples of ontologies - two valid, two invalid - are given in this repository's top-level folder:

1. [example.valid-1.ttl](example.valid-1.ttl)
1. [example.valid-2.ttl](example.valid-2.ttl)
1. [example.invalid-1.ttl](example.invalid-1.ttl)
1. [example.invalid-2.ttl](example.invalid-2.ttl)


## License
This repository's content is licensed using the [Creative Commons *Attribution 4.0 International* license](https://creativecommons.org/licenses/by/4.0/). See the [LICENSE file](LICENSE) for the deed.


## Contacts
This profile was created by members of the Australian Government Linked Data Working Group.

Please see the profile source file itself ([agop.ttl](agop.ttl)) for particular contributors' details and please see the AGLDWG's website, <http://www.linked.data.gov.au>, for AGLDWG contact details.
