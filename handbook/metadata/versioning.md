# Versioning Policy

## Compatibility Matrix

| Handbook Version | Python | CUWALID | DRYP | Status |
|---|---|---|---|---|
| 0.1.0-draft | 3.11 | 1.x | 2.x | Draft scaffold |

## Policy

- Increment patch version for typo and editorial updates.
- Increment minor version for chapter-level content additions.
- Increment major version for structural overhauls or new software major compatibility.
- Update compatibility matrix with every release.

## Release Checklist

- Confirm software compatibility targets.
- Validate `handbook/metadata/constraints-py311.txt` against a clean Python 3.11 environment.
- Verify chapter links and appendix references.
- Confirm citations and license statements.
- Export and test PDF, Word, and HTML outputs.
