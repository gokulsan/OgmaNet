
## Techniques
- JSON LD with BBS+ Signatures
- BBS+ Signature requires pairing friendly curves
- BLS12-781 pairing friendly curve can be used
- Benefits of this approach is the ability to derive ZKPs from the signature
- Party generating the proof can choose to partially disclose statement from original signature

## Workflow
- Keys required to support the BBS+ signatures are generated
- DIDs are generated from the keys referenced in the DID Document

## Components
- Verifier
- Holder
- Subject
- Issuers

- In this architecture, issuers can create ZKP enabled credentials that allow users to selectively disclose data

