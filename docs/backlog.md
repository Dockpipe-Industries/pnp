# PNP backlog

Start with discovery and a small interoperable foundation. Keep the reference implementation in PipeLang and make the protocol specification and fixtures language-independent.

| Story | Outcome |
| --- | --- |
| NET-101 | Inventory existing networking behavior and record platform evidence, ownership and compatibility risks. |
| NET-102 | Review protocol boundaries and define a staged extraction with compatibility and rollback. |
| NET-201 | Specify identity, pairing, authorization, discovery, version negotiation and structured errors. |
| NET-202 | Specify requests, events and bounded bidirectional streams with cancellation and replay rules. |
| NET-203 | Publish the reference runtime, self-hosted broker and C++ and PipeLang SDKs with interoperability evidence. |
| NET-301 | Prove filtered discovery, directional grants and revocation across broker and resource host. |
| NET-302 | Qualify authenticated direct links and relay fallback under equivalent authorization rules. |
| NET-303 | Define logical target resolution, failover and stable bindings for running work. |
| NET-501 | Specify cross-broker trust after proving the single-broker path. |

Dockpipe's reference application and PipeLang port, ForgePipe adoption, and Cloud hosting integration belong in their respective repositories. The package store can distribute PNP applications while network access is subject to separate PNP authorization.
