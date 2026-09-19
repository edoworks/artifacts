# Contributing

Keep artifacts independently versioned, dependency-minimal, documented, and
separated from private factory, product, customer, and historical data.

Changes require tests, provenance updates, license review, and a release note.
Do not add credentials, private paths, generated caches, or unsupported claims.

## Change workflow

All changes must be made on a feature branch and submitted as a pull request
to `main`. Direct pushes to `main` are not part of the supported workflow.

Every pull request must include the repository pull-request template and a
rubber-duck review by a human reviewer other than the author. The reviewer must
walk through the changed files and record either each finding with its
disposition or an explicit statement that no issues were found. A green CI
check does not replace this review.

Maintainers merge only after the required review is approved, CI is green, the
branch is current, and the artifact tests, provenance, license review, and
release-note requirements are satisfied. A merged pull request is the only
supported path to `main`.

After merge, the merged feature branch is deleted. The cleanup automation only
deletes a non-default branch whose pull request was merged and whose head is in
this repository; fork branches remain the contributor's responsibility.
