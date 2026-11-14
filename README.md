# OSV Scanner — TrillionAI Engineering Reference

**Research-only source archive for TrillionAI Audit. Not a production TrillionAI service.**

## Official upstream provenance

- Official upstream: https://github.com/google/osv-scanner
- Pinned upstream source commit: `80fe50567a5d6e0ec408353e2ceacca1561b91be`
- Expected original upstream Git tree: `2cd4812fc60cbf895076672f255426e9321a70ec`
- Snapshot branch: `osv-scanner-upstream-snapshot`
- Source directory after import: `upstream/`
- Root upstream licence: **Apache License 2.0** (preserved inside `upstream/LICENSE`)
- Pinned upstream tree inventory: **1,413 entries**, including **1,155 tracked file blobs** (~42.9 MB).
- Snapshot import and verification: **PASSED — imported exact pinned upstream tracked Git tree**.

## Source import and verification

### Verified source snapshot

- **GitHub Actions run:** [successful source import and integrity check](https://github.com/Anselm04/OSV-Scanner-Source-Code-Reference/actions/runs/43645160882)
- **Original upstream commit:** `80fe50567a5d6e0ec408353e2ceacca1561b91be`
- **Original upstream root tree:** `2cd4812fc60cbf895076672f255426e9321a70ec`
- **Verified destination `upstream/` tree:** `2cd4812fc60cbf895076672f255426e9321a70ec`
- **Tracked blobs:** 1,155 (42,916,491 bytes total), with 1,413 Git entries including directories
- **Excluded tracked files:** None
- **Licence verified:** Original Apache License 2.0 file present in imported `upstream/LICENSE`

**This is an exact Git-tree match to the pinned tracked source.** It is not proof of a passing OSV Scanner build, completed tests or commercial product readiness.

The [pinned-source import workflow](.github/workflows/import-osv-scanner-source.yml) fetches exactly the pinned upstream Git commit, copies its tracked source tree under `upstream/` on a dedicated branch, checks the exact Git tree hash, and verifies the source tree on the pushed remote branch. It does **not** execute upstream code.

- [Browse source snapshot after successful import](https://github.com/Anselm04/OSV-Scanner-Source-Code-Reference/tree/osv-scanner-upstream-snapshot/upstream)
- [Workflow runs](https://github.com/Anselm04/OSV-Scanner-Source-Code-Reference/actions/workflows/import-osv-scanner-source.yml)

If GitHub push protection finds credential-shaped fixture data, the workflow must fail. Do not bypass protection. Instead document a precisely scoped exclusion and separately verify the filtered tree. Do not call a filtered snapshot an identical upstream tree.

The Git archive excludes any separately hosted submodule contents and externally managed Git LFS data, if present. A matching Git tree establishes source-byte integrity relative to the pinned revision; it does not certify runtime correctness or supply-chain safety.

## Research goals for TrillionAI Audit

- Dependency manifest and lockfile parsing
- Software vulnerability intelligence and package risk classification
- Advisory provenance and repeatable vulnerability evidence
- Supported language and package ecosystem mapping
- CLI result parsing, bounded execution and finding normalization
- Correct handling of vulnerability database availability, unknowns, and offline conditions

All source copyright remains with Google and the original contributors under their applicable licence notices. This research repository does not relicense upstream code or authorise wholesale transfer to proprietary products. Evaluate exact file and dependency licences before incorporating code. Keep the proprietary TrillionAI Audit implementation in its own **private** repository.

No paid infrastructure or production services are activated by this source import.
