([home](README.md))


# Codex Xolotl: Microservice

[**Scala CITE Services** (SCS)](https://github.com/cite-architecture/scs-akka) is a collection of “microservices” that accept requests via HTTP and deliver very specific data back, formatted as [JSON](https://en.wikipedia.org/wiki/JSON) objects. The [CITE-JSON](https://cite-architecture.github.io/cite-api-docs/CITE-JSON/api/edu/holycross/shot/citejson/index.html) code library can translate these objects back into useful data for other programs to consume.

We now have an instance of (SCS) running with Codex Xolotl data, *e.g.*: <http://folio2.furman.edu/xolotl/libraryinfo>

## Some Sample Requests

- [About this data](http://folio2.furman.edu/xolotl/libraryinfo)
- [A passage of text](http://folio2.furman.edu/xolotl/texts/urn:cts:xolotl:torquemada.001.offner:25.2)
- [A tokenized edition](http://folio2.furman.edu/xolotl/texts/urn:cts:xolotl:torquemada.001.offner.sent:20.1)
- [Getting precise](http://folio2.furman.edu/xolotl/texts/urn:cts:xolotl:torquemada.001.offner.sent:20.1.1-20.1.2)
- [N-Grams](http://folio2.furman.edu/xolotl/texts/ngram/urn:cts:xolotl:torquemada.001.offner:?n=5)
- [An object in a collection](http://folio2.furman.edu/xolotl/objects/urn:cite2:xolotl:commentary.v1:5)