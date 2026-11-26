# PNP agent guidance

PNP owns the public network protocol, reference runtime and broker, SDKs, and conformance tests. Dockpipe and other consumers own their application behavior, storage, and deployment policy.

- Start from `dev`, work on a feature branch, and open PRs into `dev`. Maintainers promote `dev` to `staging`, then `staging` to `master` by PR.
- Use [the task router](docs/agents/index.yaml) and link the owning GitHub issue. Preserve unrelated changes.
- Prefer PipeLang for the reference implementation. Keep the wire specification and conformance fixtures usable by independently written implementations. Pin published SDK or toolchain versions.
- Specify compatibility, error outcomes, authorization, cancellation, and resource bounds when changing a wire contract. Verify interoperability and negative cases before claiming support.
- Keep secrets, account identifiers, deployment values, and generated outputs out of commits. Follow the [security policy](SECURITY.md) for sensitive findings.
- Report what was tested and any native-platform or interoperability checks still open. Publication and promotion follow [contributor guidance](CONTRIBUTING.md).
