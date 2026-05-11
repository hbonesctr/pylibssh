# Security Scan Report — Run 5

| Field | Value |
|---|---|
| Repository | hbonesctr/pylibssh |
| Commit | d4dc268e |
| Branch | devel |
| Triggered by | push |
| Scan date | 2026-05-11 16:03:39 UTC |
| Runner OS | ubuntu-latest |

## Tools Executed

| Tool | Purpose | Output File |
|---|---|---|
| Syft | SPDX 2.3 SBOM generation | sbom-spdx.json |
| Grype | SCA vulnerability matching (EPSS + KEV) | grype-results.json |
| Snyk | Manifest-based dependency scanning | snyk-results.json |
| Semgrep | SAST — p/ci ruleset | semgrep-results.json |

## Compliance Controls Addressed

| Control | Tool | Standard |
|---|---|---|
| APSC-DV-002560 | Semgrep | DISA ASD STIG v5 |
| APSC-DV-003235 | Grype + Snyk | DISA ASD STIG v5 |
| SA-11 | Semgrep | NIST SP 800-53 Rev 5 |
| SA-15 | Workflow logs + commit history | NIST SP 800-53 Rev 5 |
| RA-5 | Grype + Snyk | NIST SP 800-53 Rev 5 |
| SR-3 | Syft SBOM | NIST SP 800-53 Rev 5 |
| SR-4 | Syft SBOM (PURL/CPE) | NIST SP 800-53 Rev 5 |

*Generated automatically by DoD Security Scanner v2.3-fork*
