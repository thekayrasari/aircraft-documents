# Contributing Guidelines

Thank you for helping build this aviation document repository! Please read these guidelines carefully before submitting anything.

---

## What We Accept

### Always Welcome
- **Public domain regulatory documents**: FAA ACs, Orders, NOTAMs, EASA CSs, AMCs, ICAO Annexes (where legally distributable)
- **Links** to official sources (manufacturer portals, regulatory agency websites)
- **Index improvements**: better metadata, searchable tags, corrected document info
- **Original content**: study guides, summaries, annotations *written by you*

### Case-by-Case
- OEM documents (FCOMs, QRHs, FCTMs): please document the source and your basis for believing redistribution is acceptable (e.g., the document was published publicly by the manufacturer)

### Never Submit
- Documents you obtained under an NDA or confidentiality agreement
- Internal airline operations manuals (SOPs, OM-A/B/C/D) unless explicitly public
- Documents with a visible "Proprietary", "Confidential", or "Not for Distribution" marking
- Anything you don't have the right to distribute

**When in doubt, link to the source instead of uploading the file.**

---

## Submitting a Document

1. **Fork** this repository
2. Place the file in the correct folder (`/fcom/`, `/qrh/`, etc.)
3. Use a clear, consistent filename:
   ```
   [manufacturer]-[aircraft-type]-[doc-type]-[revision]-[date].pdf
   # Example: airbus-a320-fcom-rev45-2019.pdf
   ```
4. Add an entry to `index.md` with:
   - Document title
   - Manufacturer / issuing authority
   - Revision / date
   - Source URL (where you obtained it)
   - SHA-256 checksum
   - Copyright status (Public Domain / OEM / Unknown)
5. Open a **Pull Request** with a description including:
   - What the document is
   - Where it came from
   - Why you believe it's appropriate to include

---

## Code of Conduct

Be respectful. Aviation is a safety-critical field — accuracy and honesty matter more than opinions.

---

## Questions?

Open an Issue or start a Discussion.
