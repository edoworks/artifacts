# Edoworks Artifacts

Versioned, reusable artifacts from Edoworks.

## Catalog

| Artifact | Version | Download | License |
| --- | --- | --- | --- |
| [reusefirst](artifacts/reusefirst/) | 1.2.0 | [Release assets](https://github.com/edoworks/artifacts/releases/tag/reusefirst%2Fv1.2.0) | Apache-2.0 |
| [constitution](artifacts/constitution/) | 1.0.0 | [Release assets](https://github.com/edoworks/artifacts/releases/tag/constitution%2Fv1.0.0) | MIT |
| [asc](artifacts/asc/) | 1.0.0 | [Release assets](https://github.com/edoworks/artifacts/releases/tag/asc%2Fv1.0.0) | MIT |

Each artifact is independently versioned. Releases use immutable SemVer tags
and include checksums and a manifest so consumers can download a specific
version without cloning the repository.

Each artifact directory, manifest, and future release tag uses the same
canonical artifact name. Agent-facing skills remain inside their artifact
directory and do not create a second public source tree.

## Scope

These artifacts are advisory local tools. They do not grant publication,
installation, release, authorization, sandboxing, or security authority.

## Support

Open an issue for bugs or usage questions. See [SECURITY.md](SECURITY.md) for
vulnerability reporting and the support boundary.
