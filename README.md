# DID-Linked Resources Specification v0.1

This is the repository of the [W3C Credential Community Group's](https://www.w3.org/community/credentials/) specification on DID-Linked Resources.

## Code of Conduct

W3C functions under a [code of conduct](https://www.w3.org/Consortium/cepc/).

## About

Please find the formatted specification at this URL: https://w3c-ccg.github.io/did-linked-resources/

This specification intends to create a standardized way of referencing, dereferencing and fetching digital resources (schemas, trust & status lists, visual representations of Verifiable Credentials, governance documents, logos). This includes associating digital resources with Decentralized Identifiers (DIDs) and organizing in DID-Linked Collections, where each individual resource is identifiable through its own DID URL.

This specification will extend the [DID Resolution Specification](https://w3c-ccg.github.io/did-resolution/), creating a set of query parameters for DID-Linked Resources, which are not method specific - including what is required and what is optional. 

This specification aims to be built using existing, familiar [DID Core Spec](https://www.w3.org/TR/did-core/) patterns:

- Support existing DID Resolvers and principles of [DID URL dereferencing](https://www.w3.org/TR/did-core/#did-url-dereferencing)
- Protect against linkrot for long-term retrieval
- Enable resources to be versioned and organised, with individual versions being able to be fetched
- Include linkage between DID Documents and associated resources (via [DID Document Metadata](https://www.w3.org/TR/did-core/#did-document-metadata) or otherwise).

## Previous work

- [cheqd composition of DID-Linked Resources](https://docs.cheqd.io/identity/architecture/adr-list/adr-002-did-linked-resources)
- [Trust over IP Draft Specification on DID-Linked Resources](https://wiki.trustoverip.org/display/HOME/DID-Linked+Resources+Specification), to be superseded by the W3C work item
- [did:cosmos Linked Resources](https://github.com/EarthProgram/did-cosmos#linked-resources)
- [DIF Decentralized Web Node Spec](https://identity.foundation/decentralized-web-node/spec/#did-relative-urls)
