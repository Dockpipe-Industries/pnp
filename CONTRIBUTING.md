# Contributing to PNP

Create a feature branch from `dev` and open a pull request into `dev`. Link the issue, explain behavior changes, and list the verification you ran. Maintainers promote by pull request from `dev` to `staging` and from `staging` to `master`.

Use this repository for protocol specification, reference runtime and broker, SDKs, and conformance. Keep Dockpipe integration and Cloud operations in their owning repositories. Track a story once in its owning repo and link it to related work or the shared GitHub Project.

Wire changes should describe compatibility and failure handling. Review identity and grants, replay behavior, version negotiation, and resource limits where relevant. Treat sensitive bugs under the [security policy](SECURITY.md).
