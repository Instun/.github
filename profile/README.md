# About Instun

Instun is a technology company specializing in next-generation identity and credentialing technologies. We focus on building secure, standards-compliant solutions for digital identity management and verifiable credentials.

## Standards

### Identity & Credentials

#### W3C Standards
- [Verifiable Credentials Data Model v2.0](https://www.w3.org/TR/vc-data-model-2.0/) - Credential issuance, verification and selective disclosure
- [Decentralized Identifiers (DID Core) v1.0](https://www.w3.org/TR/did-core/) - Decentralized identifier syntax, operations, methods and resolution
- [Data Integrity 1.0](https://www.w3.org/TR/vc-data-integrity/) - Proof creation, verification and document canonicalization
- [RDF Dataset Normalization 1.0](https://www.w3.org/TR/rdf-canon/) - URDNA2015 algorithm and deterministic graph canonicalization
- [DID Specification Registries](https://w3c.github.io/did-spec-registries/) - DID method and parameter registration
- [Verifiable Credential Implementation Guidelines 1.0](https://www.w3.org/TR/vc-imp-guide/) - Best practices for VC implementations

#### Community Standards
- [W3C CCG Verifiable Credentials API](https://w3c-ccg.github.io/vc-api/) - Issuance, verification and status checking endpoints
- [W3C CCG did:key Method v0.7](https://w3c-ccg.github.io/did-method-key/) - Key format specifications and multicodec support
- [W3C CCG did:web Method](https://w3c-ccg.github.io/did-method-web/) - Web-based DID resolution and domain verification
- [W3C Security Vocabulary](https://w3c-ccg.github.io/security-vocab/) - Security terminology and cryptographic concepts

#### Signature Suites
- [SM2 Signature 2023](https://github.com/Instun/lds-sm2-2023) - SM2 signature suite for verifiable credentials
- [BBS+ Signature Suite 2020](https://w3c-ccg.github.io/ldp-bbs2020/) - Zero-knowledge proof selective disclosure
- [Ed25519 Signature 2020](https://w3c-ccg.github.io/lds-ed25519-2020/) - Ed25519 signature suite specification
- [ECDSA Signature 2019](https://w3c-ccg.github.io/lds-ecdsa-secp256k1-2019/) - ECDSA secp256k1 signature suite
- [Data Integrity Proof Suite Registry](https://w3c.github.io/vc-di-eddsa/) - Registry of proof suites for data integrity

### Cryptography

#### International Standards
- [BBS+ Signatures](https://identity.foundation/bbs-signature/draft-irtf-cfrg-bbs-signatures.html) - BLS12-381 curve and zero-knowledge proofs
- [EdDSA (RFC 8032)](https://datatracker.ietf.org/doc/html/rfc8032) - Ed25519 curve and pure signing function
- [FIPS 186-4](https://csrc.nist.gov/publications/detail/fips/186/4/final) - Digital signature standard and key generation
- [NIST SP 800-56A](https://csrc.nist.gov/publications/detail/sp/800-56a/rev-3/final) - Key establishment and domain parameters
- [SHA-2 (FIPS 180-4)](https://csrc.nist.gov/publications/detail/fips/180/4/final) - SHA-256/384/512 hash functions
- [ITU-T X.690](https://www.itu.int/rec/T-REC-X.690) - ASN.1 DER encoding rules and type definitions
- [SEC 1](https://www.secg.org/sec1-v2.pdf) - Elliptic curve parameters and key generation
- [ANSI X9.62](https://webstore.ansi.org/standards/ascx9/ansix9621998) - Public key cryptography and EC domain parameters
- [RFC 5480](https://datatracker.ietf.org/doc/html/rfc5480) - ECC public key format and algorithm identifiers
- [RFC 5915](https://datatracker.ietf.org/doc/html/rfc5915) - EC private key structure and PKCS #8 format
- [RFC 7517](https://datatracker.ietf.org/doc/html/rfc7517) - JSON Web Key format and operations
- [PKCS#8](https://tools.ietf.org/html/rfc5208) - Private-Key Information Syntax
- [X.509/SPKI](https://tools.ietf.org/html/rfc5280) - Public key infrastructure

#### Chinese National Standards
- [GB/T 32918.1-2016](http://www.gmbz.org.cn/main/viewfile/20180108023812835219.html) - SM2 elliptic curve parameters and key generation
- [GB/T 32905-2016](http://www.gmbz.org.cn/main/viewfile/20180108015954226939.html) - SM3 cryptographic hash algorithm
- [GB/T 35276-2017](http://www.gmbz.org.cn/main/viewfile/20180108023459013744.html) - SM2 in TLS protocol and cipher suites
- [GM/T 0009-2012](http://www.gmbz.org.cn/main/viewfile/20180108023617172563.html) - SM2 digital signature and verification
- [GM/T 0003.1-2012](http://www.gmbz.org.cn/main/viewfile/2018011001400692565.html) - SM2 point compression and encoding rules

### Data Formats & Protocols

#### Core Formats
- [JSON-LD 1.1](https://www.w3.org/TR/json-ld11/) - Context processing and graph representation
- [CBOR RFC 8949](https://datatracker.ietf.org/doc/html/rfc8949) - Binary object representation and streaming encoding
- [RDF 1.1](https://www.w3.org/TR/rdf11-concepts/) - Resource description framework
- [Multicodec v1.0](https://github.com/multiformats/multicodec) - Self-describing values and format registry
- [Multibase v1.0](https://github.com/multiformats/multibase) - Binary encoding and base encodings
- [JSON Schema](https://json-schema.org/specification.html) - JSON data validation and documentation

#### Communication Protocols
- [JSON-RPC 2.0](https://www.jsonrpc.org/specification) - Remote procedure calls and message format
- [WebSocket (RFC 6455)](https://datatracker.ietf.org/doc/html/rfc6455) - WebSocket protocol and frame format
- [WebRTC 1.0](https://www.w3.org/TR/webrtc/) - Peer connections and data channels
- [RFC 4648](https://datatracker.ietf.org/doc/html/rfc4648) - Base64URL encoding and padding rules
