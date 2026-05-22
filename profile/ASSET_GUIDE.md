# Ninobyte CloudOps Lab — Organization Profile Asset Guide

Visual direction and policy for the public GitHub surface (the org profile and the public showcase repositories). This guide is intentionally text-only: it documents intent and rules, not binary assets.

## Principles

- **Markdown-native clarity first.** Prefer clean structure, tables, and restrained markers over imagery.
- **Premium and institutional, not flashy.** No hype, no bootcamp tone.
- **Restraint over decoration.** A few meaningful markers beat many.
- **Public is overview-only.** Public surfaces orient and link; private repositories hold the real materials.

## Icon and emoji system

Use a small, consistent marker set as light orientation cues — never as decoration:

| Marker | Meaning |
|---|---|
| 🧭 | Platform / overview |
| 🧪 | Labs / practice |
| 🛡️ | Security / governance |
| 📦 | Repository map |
| 🧾 | Proof packs / evidence |
| 🔒 | Private / gated |
| ✅ | Ready / complete |
| 🚫 | Boundaries / not included |
| ⚙️ | Operations |
| 📚 | Learning path |

Aim for a handful per page. If a heading reads clearly without a marker, leave it off.

## Mermaid diagram policy

- Use Mermaid only where a diagram makes a concept faster to grasp than prose (an ecosystem map, a workflow, a learner journey).
- Keep diagrams small and legible; prefer left-to-right (`flowchart LR`) for short pipelines.
- One diagram per page is usually enough. If a diagram makes a page too tall or cluttered, use a table instead and note the decision.
- Diagrams must not encode secrets, account identifiers, ARNs, or private URLs.

## Badge and shield policy

- Minimal badges only. A badge must communicate something true and useful (for example, status), never decoration.
- No certification, partnership, or outcome badges.
- No badge implying AWS partnership or official status.
- No fabricated or vanity badges.

## Screenshot policy

- No private screenshots or internal interface captures on any public surface.
- No screenshots containing account identifiers, ARNs, secrets, or real data.
- Prefer Markdown and Mermaid over screenshots; if a screenshot is ever needed, it must be synthetic and reviewed first.

## Public / private visual boundary

- Public surfaces use overview language and link outward to public repositories.
- Private repositories are referenced by name and purpose only — never by exposing their contents.
- Public pages should make the private/public boundary obvious (e.g., a 🔒 marker and a short "private by design" note).

## What this repository will not include

- No custom or downloaded font files.
- No proprietary or licensed brand assets.
- No AWS logos or third-party marks unless usage rights have been reviewed and approved.
- No private screenshots or internal interface captures.
- No secrets, account identifiers, ARNs, or private URLs.
- No implication of AWS partnership, endorsement, or official status.

## Future cover banner (concept only)

- A future banner could carry the wordmark **Ninobyte CloudOps Lab** with the line *Build. Operate. Secure. Govern AWS AI systems.*
- Direction: dark, calm, technical; generous whitespace; a single accent color; no stock imagery.
- Not yet implemented — no banner image is committed to this repository.

## Future visual assets

- Add any future visual asset deliberately, reviewed for licensing and leakage, and kept consistent with this guide.
- When in doubt, stay Markdown-native.
