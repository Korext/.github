<div align="center">

# Korext

**AI Code Governance. Platform and Open Standards.**

[![Platform](https://img.shields.io/badge/Platform-korext.com-000000?style=for-the-badge&logo=google-chrome&logoColor=white)](https://korext.com)
[![Open Source](https://img.shields.io/badge/Open_Source-oss.korext.com-blue?style=for-the-badge&logo=google-chrome&logoColor=white)](https://oss.korext.com)
[![Specs](https://img.shields.io/badge/Specs-CC0%201.0-green?style=for-the-badge)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Code](https://img.shields.io/badge/Code-Apache%202.0-blue?style=for-the-badge)](https://www.apache.org/licenses/LICENSE-2.0)

</div>

---

AI is rewriting how software gets built. The governance has not caught up.

Korext is closing that gap with two things: a **governance platform** for enterprises and a set of **open standards** for the entire industry.

---

## The Platform

Korext enforces regulatory, security, and engineering standards on AI generated code at the moment it is written. Every scan produces a cryptographically signed proof bundle that attests where the code was processed, where the data was stored, and who signed it.

Runs inside every major IDE, in CI/CD, from the terminal, and directly inside AI coding tools via MCP.

| Surface | Install |
|---------|---------|
| VS Code, Cursor, Windsurf | Extension marketplace |
| JetBrains | Plugin marketplace |
| CLI | `npm install -g korext` |
| GitHub Actions | `korext/enforce-action@v3` |
| Chrome | Chrome Web Store |
| MCP | Built in |

Three data sovereignty regions. Customer managed signing keys. 72 governance packs. 532 rules. 13 language grammars.

**[korext.com →](https://korext.com)**

---

## Open Standards

We believe AI code governance requires open standards that no single vendor controls. Every specification below is **CC0 public domain**. Every tool is **Apache 2.0**. Every dataset is **CC BY 4.0**.

<table>
<tr>
<td width="50%" valign="top">

### Track

**[ai-attestation](https://github.com/korext/ai-attestation)**
Track AI generated code in your repository. Detects 19 AI coding tools from git history. One command install.

```bash
npx @korext/ai-attestation init
```

[![npm](https://img.shields.io/npm/v/@korext/ai-attestation?label=npm&color=CB3837)](https://www.npmjs.com/package/@korext/ai-attestation)

</td>
<td width="50%" valign="top">

### Declare

**[ai-license](https://github.com/korext/ai-license)**
Declare AI provenance in any open source project. Standardized notice that attaches to any existing license.

```bash
npx @korext/ai-license generate
```

[![npm](https://img.shields.io/npm/v/@korext/ai-license?label=npm&color=CB3837)](https://www.npmjs.com/package/@korext/ai-license)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Scan

**[supply-chain-attestation](https://github.com/korext/supply-chain-attestation)**
AI provenance across your entire dependency tree. 14 ecosystems. CycloneDX and SPDX integration.

```bash
npx @korext/supply-check scan
```

[![npm](https://img.shields.io/npm/v/@korext/supply-check?label=npm&color=CB3837)](https://www.npmjs.com/package/@korext/supply-check)

</td>
<td width="50%" valign="top">

### Report

**[ai-incident-registry](https://github.com/korext/ai-incident-registry)**
The public registry for AI code failures. AICI identifiers. Detection rule mapping. Vendor notification.

```bash
npx @korext/incident-report draft
```

[![npm](https://img.shields.io/npm/v/@korext/incident-report?label=npm&color=CB3837)](https://www.npmjs.com/package/@korext/incident-report)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Measure

**[ai-code-radar](https://github.com/korext/ai-code-radar)**
The real-time pulse of AI code adoption. Live data, embeddable charts, public API for journalists and researchers.

[![Dashboard](https://img.shields.io/badge/Live_Dashboard-oss.korext.com%2Fradar-blue)](https://oss.korext.com/radar)

</td>
<td width="50%" valign="top">

### Detect

**[ai-regression-database](https://github.com/korext/ai-regression-database)**
Patterns AI coding tools consistently get wrong. Reproducible. Version tracked. Detection linked.

```bash
npx @korext/regression-submit detect
```

[![npm](https://img.shields.io/npm/v/@korext/regression-submit?label=npm&color=CB3837)](https://www.npmjs.com/package/@korext/regression-submit)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Sustain

**[commit-carbon](https://github.com/korext/commit-carbon)**
Carbon footprint of AI assisted commits. CSRD, SEC, and CDP compatible disclosure. Peer reviewed methodology.

```bash
npx @korext/commit-carbon scan
```

[![npm](https://img.shields.io/npm/v/@korext/commit-carbon?label=npm&color=CB3837)](https://www.npmjs.com/package/@korext/commit-carbon)

</td>
<td width="50%" valign="top">

### Enforce

**[enforce-action](https://github.com/korext/enforce-action)**
GitHub Action for AI code governance in CI/CD. Scan every pull request. Block violations before merge.

```yaml
- uses: korext/enforce-action@v3
```

[![GitHub Action](https://img.shields.io/badge/Marketplace-GitHub%20Actions-blue)](https://github.com/marketplace/actions/korext-enforce)

</td>
</tr>
</table>

---

## How It All Connects

```
Developer writes code with AI tools
         │
         ▼
   ai-attestation          ← Tracks which AI tools, how many commits
         │
    ┌────┼────┐
    │    │    │
    ▼    ▼    ▼
ai-license  commit-carbon  supply-chain-attestation
 Declare     Measure         Scan dependencies
 provenance  emissions       for AI provenance
    │    │    │
    └────┼────┘
         │
         ▼
   KOREXT PLATFORM          ← Govern, scan, sign proof bundles
         │
         ▼
   enforce-action           ← Gate CI/CD on governance policy
         │
         ▼
   ai-code-radar            ← Aggregate live adoption statistics
         │
    ┌────┴────┐
    ▼         ▼
ai-incident   ai-regression
-registry     -database
 Document      Document
 failures      patterns
```

The open standards track, declare, and measure. The platform governs and signs. Together they form the complete AI code governance stack.

---

## Licensing

| Layer | License | Why |
|-------|---------|-----|
| Specifications and schemas | CC0 1.0 (public domain) | Maximum adoption. No friction. |
| Code and tools | Apache 2.0 | Standard permissive license. |
| Data and datasets | CC BY 4.0 | Open with attribution. |

---

## Get Involved

We welcome contributors across every project.

Browse [open issues](https://github.com/orgs/korext/repositories) across all repositories. Read the CONTRIBUTING.md in any project. Reach out at **maintainers@korext.com** to discuss maintainer roles.

**[Meet the team →](https://oss.korext.com/team)**

---

<div align="center">

**[korext.com](https://korext.com)** · **[oss.korext.com](https://oss.korext.com)** · **[Team](https://oss.korext.com/team)**

*AI code governance for the enterprise. Open standards for the industry.*

</div>

## Maintainers

Korext Open Source is created and maintained by [Tom Bruno](https://github.com/tombruno-korext), Founder of [Korext](https://korext.com).

- MEng in AI/ML, Robotics, and Controls (UC Berkeley)
- MS in Innovation and Entrepreneurship (HEC Paris)
- BS in Digital Technology, Design, and Innovation (Technological University Dublin)

Contact: maintainers@korext.com
