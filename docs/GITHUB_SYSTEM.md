# GitHub presentation system

This document is the maintenance contract for repositories owned by `BrierAinz`.

## Identity boundary

- `BrierAinz` is the GitHub owner and canonical account.
- `BrierStudios` is a studio/brand identity, not a GitHub organization.
- `brierstudios.com` is the public studio site.
- Private repositories must not be exposed from the public profile unless intentionally announced.
- Forks must preserve upstream attribution and must not be presented as original BrierAinz projects.

## Visual language

| Token | Value | Role |
|---|---|---|
| Void Black | `#05080D` | primary background |
| Deep Slate | `#0A1119` | secondary background |
| Frost Cyan | `#8FD8E8` | primary technical accent |
| Muted Frost | `#6FAFC1` | secondary accent |
| Ancient Gold | `#D5B96D` | sparse emphasis |
| Bone White | `#F3F6F8` | primary text |
| Ash | `#A8B7C2` | secondary text |

Runes, roots, tree geometry, fine technical lines, and restrained HUD motifs are allowed. Decoration must not obscure project state or technical documentation.

## Repository states

Use one of these semantic states when a repository README needs an explicit lifecycle label:

- `FLAGSHIP`: primary maintained system.
- `ACTIVE`: ongoing implementation or maintenance.
- `EXPERIMENTAL`: intentionally unstable work.
- `INFRASTRUCTURE`: support realm or bounded subsystem.
- `ARCHIVED`: preserved historical material; no normal feature work.
- `UPSTREAM FORK`: derivative workspace preserving upstream authorship.
- `PRIVATE INTERNAL`: operational repository not intended as a public product.

Do not claim a release, test count, maturity level, or implementation status unless it is supported by the repository itself.

## README families

### Product / application

Banner → concise value proposition → verified features → architecture → setup → usage → configuration/security → verification → status → license.

### Yggdrasil realm

Realm banner → purpose → responsibilities → current state → contents → boundaries → related ecosystem links.

### Upstream fork

Upstream identity remains primary. Fork-specific scope belongs in a clearly separated note and must never rewrite upstream authorship.

## Maintenance rules

1. Preserve working documentation before adding decoration.
2. Prefer local or version-controlled assets over third-party image hosts.
3. Badges must communicate verifiable state; decorative badge spam is discouraged.
4. Security-sensitive data never belongs in screenshots, examples, logs, issue templates, or generated assets.
5. `reino-helheim` is audit-only while its README declares the realm read-only.
6. Visibility changes require an explicit decision; presentation work does not imply publication.
7. Broken links, stale organization references, and contradictory versions are defects.
8. Public-profile copy must not reveal private repository inventory accidentally.
