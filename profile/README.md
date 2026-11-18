# Cloud Control Plane

Building blocks for a cloud control plane, written in Rust.

## Projects

| Project | Description | Status |
|---|---|---|
| [cloud-plane-iam](https://github.com/cloud-plane/iam) | Identity and access management: authentication, authorization, tokens, projects and role assignments | Active |
| cloud-plane-kms | Key management service: key storage, encryption and signing | Planned |

`cloud-plane-iam` started as keystone-rs, a Rust implementation of OpenStack Keystone. It is now a general-purpose cloud IAM that can run within or outside OpenStack.

## Principles

- **Secure by default.** Safe Rust, a small attack surface and security-reviewed changes.
- **Distributed by design.** Stateless services that scale horizontally.
- **API first.** Documented, versioned APIs backed by automated API tests.
- **Decisions in the open.** Significant design choices are recorded as ADRs in each repository.

## Contributing

Each repository describes its structure and workflow in `CONTRIBUTING.md`. Please read it first. Open an issue before starting large changes.

Report security issues privately through the repository's security policy, not through public issues.

## License

See the license file in each repository.
