
## Techniques
- ZKP enabled credentials
- JSON LD with BBS+ Signatures
- BBS+ Signature requires pairing friendly curves
- BLS12-781 pairing friendly curve can be used
- Benefits of this approach is the ability to derive ZKPs from the signature
- Party generating the proof can choose to partially disclose statement from original signature

## Workflow
- Create a key with type set of BLS12-781
- Keys required to support the BBS+ signatures are generated
- Create a verifiable credential using the DID key as the issuer DID
- MATTR platform will create a ZKP enabled BBS+ credential

## Concepts
- DIDs are generated from the keys referenced in the DID Document
- DIDs can be referenced in credentials to establish the issuer of data
- Verifier can trace the root of trust in a credential from the DIDs

## Actors
- Verifier
- Holder
- Subject
- Issuers

- In this architecture, issuers can create ZKP enabled credentials that allow users to selectively disclose data

