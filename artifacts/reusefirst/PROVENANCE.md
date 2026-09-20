# Provenance

- Origin: Edoworks reuse and contribution-gate increment.
- Generalization: extracted from an internal ecosystem-compounding increment;
  no product source, secrets, user data, or external artifact was included.
- Review: deterministic contract tests, artifact validation, and Customer Zero
  dogfood by the factory and its product workflows are the current evidence.
  Human publication approval is recorded for this release.
- Skill surface: `SKILL.md` is a generic procedural wrapper around the same
  decision contract; it contains no private factory paths, product context, or
  external instructions.
- Boundary: the package remains dependency-free and local-only. Its pinned
  public entrypoint was executed by the factory and product workflows during
  release dogfood; no external instructions or network service are required by
  the contract.
