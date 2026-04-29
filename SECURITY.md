# Security Policy

## Scope

This is a **static document repository** — it contains PDFs and markdown files, not executable software. However, security considerations still apply:

- Malicious or modified documents (PDFs with embedded scripts)
- Repository access credential leaks
- Harmful content submitted via pull requests

---

## Reporting a Security Issue

If you discover a security issue related to this repository (e.g., a PDF containing malicious embedded content, a compromised file, or a credential/token accidentally committed), please report it responsibly.

**Do not open a public GitHub Issue for security vulnerabilities.**

Instead, please report via:

1. **GitHub's Private Vulnerability Reporting** (preferred):
   > Repository → Security tab → "Report a vulnerability"

2. **Email:** `[YOUR EMAIL HERE]`
   - Use the subject line: `[SECURITY] Aviation PDF Repo - [Brief Description]`
   - If the content is sensitive, please use PGP encryption (key available on request)

---

## What to Include in Your Report

- Description of the issue
- Steps to reproduce or verify
- The specific file(s) involved (path or URL)
- Any relevant screenshots or analysis output
- Your suggested severity (Low / Medium / High / Critical)

---

## Response Timeline

| Step | Target Time |
|------|-------------|
| Acknowledgement of report | 48 hours |
| Initial assessment | 5 business days |
| Remediation (file removal/replacement) | 7 business days |
| Disclosure (if applicable) | After remediation |

---

## Document Integrity

To help verify document integrity, contributors are encouraged to provide **SHA-256 checksums** for submitted files in the pull request description or in `index.md`.

You can generate a checksum with:

```bash
# Linux / macOS
sha256sum document.pdf

# Windows (PowerShell)
Get-FileHash document.pdf -Algorithm SHA256
```

---

## Out of Scope

The following are **not** security vulnerabilities for this repository:

- Copyright/DMCA concerns → see [DMCA.md](./DMCA.md)
- Outdated document versions → open a regular Issue
- Missing documents → open a regular Issue or Pull Request

---

## Supported Versions

This is a living repository. Only the current state of the `main` branch is actively maintained.
