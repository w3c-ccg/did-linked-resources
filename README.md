# DID-Linked Resources Specification

This is the repository of the [W3C Credentials Community Group's](https://www.w3.org/community/credentials/) specification on DID-Linked Resources.

## Code of Conduct

W3C functions under a [code of conduct](https://www.w3.org/Consortium/cepc/).

## About

Please find the formatted specification at: **https://w3c-ccg.github.io/did-linked-resources/**

This specification defines a standardized way of referencing, dereferencing, and fetching digital resources, including schemas, status lists, trust registries, governance documents, and visual representations of Verifiable Credentials. It associates digital resources with Decentralized Identifiers (DIDs), where each individual resource is identifiable through its own DID URL.

The specification complements the [DID Resolution Specification](https://www.w3.org/TR/did-resolution/), defining a method-agnostic set of query parameters for DID-Linked Resources. It is built using existing, familiar [DID Core](https://www.w3.org/TR/did-core/) patterns:

- Support existing DID Resolvers and principles of [DID URL dereferencing](https://www.w3.org/TR/did-core/#did-url-dereferencing)
- Protect against link-rot for long-term retrieval
- Enable resources to be versioned and organised, with individual versions being fetchable
- Include linkage between DID Documents and associated resources via [DID Document Metadata](https://www.w3.org/TR/did-core/#did-document-metadata)
- Be implementable by any DID method — whether ledger-based, web-based, or peer-to-peer

## Editing the spec

The specification source is `index.html`, a [ReSpec](https://respec.org/docs/) document. To preview locally, serve the repository root over HTTP and open `index.html` in a browser:
```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`. ReSpec runs entirely in the browser: no build step is required.

## Status

This document is a draft technical specification produced by the W3C Credentials Community Group, with the intent of progressing toward a W3C standard. Feedback is welcome via the [issue tracker](https://github.com/w3c-ccg/did-linked-resources/issues) or the [public-credentials mailing list](https://lists.w3.org/Archives/Public/public-credentials/).

## Previous work

- [Trust over IP Draft Specification on DID-Linked Resources](https://wiki.trustoverip.org/display/HOME/DID-Linked+Resources+Specification) — superseded by this W3C CCG work item
- [cheqd DID-Linked Resources Architecture](https://docs.cheqd.io/identity/architecture/adr-list/adr-002-did-linked-resources) — original implementation reference
- [did:cosmos Linked Resources](https://github.com/EarthProgram/did-cosmos#linked-resources)
- [DIF Decentralized Web Node Spec](https://identity.foundation/decentralized-web-node/spec/#did-relative-urls)
