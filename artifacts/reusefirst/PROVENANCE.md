# Provenance

- Origin: Edoworks reuse and contribution-gate increment.
- Generalization: extracted from an internal ecosystem-compounding increment;
  no product source, secrets, user data, or external artifact was included.
- Review: deterministic contract tests are the current artifact evidence.
  Publication approval remains outstanding for this candidate. Consuming
  factories maintain their own Customer Zero evidence rather than embedding
  private product details in this public artifact.
- Skill surface: `SKILL.md` is a generic procedural wrapper around the same
  decision contract; it contains no private factory paths, product context, or
  external instructions.
- Boundary: the package remains dependency-free and local-only. The candidate
  is independently testable and is not yet a published release.
