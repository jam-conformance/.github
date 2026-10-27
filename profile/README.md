# JAM Conformance

Tools and test material to check implementations of the [JAM protocol](https://graypaper.com)
against the Gray Paper and against other implementations.

> [!IMPORTANT]
> This is not the official auditing process.

## Repositories

| Repository | Content |
| --- | --- |
| [jam-fuzzing](https://github.com/jam-conformance/jam-fuzzing) | Fuzzer protocol, fuzzer reports and traces, conformance criteria, performance reports, and the scripts to fuzz a target. |
| [jam-test-vectors](https://github.com/jam-conformance/jam-test-vectors) | Test vectors for the next release. Fork of [w3f/jamtestvectors](https://github.com/w3f/jamtestvectors), which has the official releases. |
| [jam-types-py](https://github.com/jam-conformance/jam-types-py) | Python types and codec for the JAM data structures. |
| [asn1tools](https://github.com/jam-conformance/asn1tools) | Fork of [eerimoq/asn1tools](https://github.com/eerimoq/asn1tools). The test vector scripts use it to validate the JSON files against the ASN.1 schema. |

## Contact

- Matrix: [#jam-conformance:matrix.org](https://matrix.to/#/#jam-conformance:matrix.org)
- Discussions: [jam-fuzzing discussions](https://github.com/jam-conformance/jam-fuzzing/discussions)
- Issues: open an issue in the related repository.
