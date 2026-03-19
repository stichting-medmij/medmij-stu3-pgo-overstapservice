# MedMij-STU3-Portability
This repository contains HL7 FHIR STU3 compliant conformance materials for MedMij STU3 Portability. This project is currently in a pre-publication status and can therefore not be considered stable.

The implementation guide for this project, also in a pre-publication status, can be found on [Simplifier](link Simplifier).

This repository is maintained by MedMij.

### Examples

In 1.0.0-alpha.8 a redesign was put in place, removing vocabulary and structure definitions from this repository. These may well return in later stage, for now we're basing functionalitity on the use of examples in gegevensdienst Verzamelen Documenten 3.0 (PDF/A).

Examples given are part of the Interoplab test suite in a proof of concept with participants. The [simulator test data](examples/testdata-simulator) is based on [BgZ 3.0](https://github.com/Nictiz/Nictiz-testscripts/tree/main/output/STU3/BgZ-3-0) and the matching test scenarios.

The following resources are used as test material for [use case 1](https://changemanagement.medmij.nl/ontwerp-pgo-koppelvlak/actueel/bijlage-testscripts-2025-pgok):

- DocumentReference resource [_port-DocumentReference-XXX-Rijn.json](examples/_port-DocumentReference-XXX-Rijn.json) which represents a reference entry with metadata on a MedMij portability report available for retrieval.
- Binary resource, containing the actual document [_port-Binary-XXX-Rijn.json](examples/_port-Binary-XXX-Rijn.json), a generated PDF/A file.

Note that the two DocumentReference resources (and the referenced Binary resource) are used in both use case [1.1](https://changemanagement.medmij.nl/ontwerp-pgo-koppelvlak/actueel/bijlage-testscripts-2025-pgok#id-(v0.8)Bijlagetestscripts(2025-PGOK)-Usecase1.1Overstapservice:verzamelendocumentenoverPGO-koppelvlak) and [1.2](https://changemanagement.medmij.nl/ontwerp-pgo-koppelvlak/actueel/bijlage-testscripts-2025-pgok#id-(v0.8)Bijlagetestscripts(2025-PGOK)-Usecase1.2Overstapservice:beschikbaarstellendocumentenoverPGO-koppelvlak).