# QSC repository branding and README guide

This lightweight guide helps Quantum Science Center (QSC) Software Ecosystem
repositories communicate clearly without turning branding into a release
certification process.

The practical test is simple: in about one minute, can a reader discover:

1. What is this project?
2. Why does it matter to QSC?
3. What works today?
4. Where can I see evidence or a demonstration?

Use the [minimal README template](../templates/README.template.md) as a starting
point. Adapt it to the repository rather than filling every possible section.

## Minimum standard for a branded pilot

A repository needs only these elements:

| Element | Minimum expectation |
| --- | --- |
| Identity | Project name as a Markdown level-one heading |
| Outcome | A short statement understandable outside the immediate development team |
| Status | Honest maturity plus a distinction between current, experimental, and planned work |
| Ownership | An accountable team or owner and a practical contact path |
| Evidence | One useful result, screenshot, example, benchmark, test report, or demonstration link |
| Access | The shortest usable path, or a clear statement that the project is not yet available |
| Accessibility | Meaningful image text and current, canonical links |

Meeting this list means the repository is ready as a **branding pilot**. It does
not imply scientific approval, release readiness, or production support.

## Recommended enhancements

Add only what improves the repository:

- A project-specific banner from the shared QSC visual family
- Up to five real, maintained badges
- An “At a glance” table for contribution, users, maturity, milestone, owner,
  and review date
- A workflow or architecture visual when it clarifies responsibility
- A tested quick start and links to deeper documentation
- A roadmap, contribution guide, repository layout, or editable visual sources

These are recommendations, not branding gates.

## Optional banner guidance

| Property | Preferred default |
| --- | --- |
| Canvas | 1600 × 400 px (4:1), adjusted when another ratio works better |
| Delivery | Optimized PNG for predictable GitHub rendering |
| Editable source | SVG, Figma, or another documented source when practical |
| Target size | Aim for 600 KB or less |
| Safe area | Approximately 80 px; verify legibility at narrow widths |
| Text | Project name plus a descriptor of roughly eight words or fewer |
| Logo | Unmodified QSC mark with its aspect ratio preserved |
| Accessibility | Descriptive alt text |

The dimensions, size, safe area, and editable source are design defaults, not
pass/fail requirements. Logo integrity and meaningful alt text are required.

Use the working ecosystem palette consistently:

| Role | Color |
| --- | --- |
| Ink / dark background | `#101D2D` |
| QSC red accent | `#AE1935` |
| QSC blue accent | `#306A91` |
| Warm light background | `#F4F1E9` |
| White | `#FFFDF8` |

The technical motif should communicate the project's function. For example, a
compiler can show a transformation path, a workflow can show connected stages,
and a data project can show a structured record.

## Writing the opening

A useful outcome sentence is:

> **[Project] helps [primary user] achieve [scientific or operational outcome]
> by [distinct capability].**

Prefer the result over internal implementation language. A short status line or
link near the opening can tell the reader what works and where to see evidence;
all four one-minute questions do not need to fit in one literal viewport.

## Evidence and media

Choose one proof point in the format that best fits the repository:

- A scientific result or before/after image
- A cropped screenshot of an interactive tool
- A reproducible example, benchmark, or test report
- A short WebP or GIF for one interaction
- A linked video poster for a multi-step story

A repository does not need several media formats. Caption visuals with the
conclusion the reader should notice, use relative links for repository-owned
media, and provide captions or transcripts for video.

## Common maturity vocabulary

| Maturity | Meaning |
| --- | --- |
| Concept | Scope is defined; no dependable artifact yet |
| Prototype | Demonstrates the idea; interfaces may change |
| Research preview | Collaborators can use it; validation is still growing |
| Pilot | Exercised in representative workflows; hardening continues |
| Supported release | Versioned, tested, documented, and actively maintained |
| Archived | Preserved for reference; no active development promised |

Do not call a research prototype “production ready” unless the team has defined
and met the support obligation that phrase implies.

## Editorial defaults

- Expand an acronym on first use.
- Prefer active voice and observable outcomes.
- Keep the opening summary to two or three sentences.
- Date time-sensitive status claims.
- Separate current capability from future plans.
- Use maintained badges only.
- Do not use an aspirational diagram as evidence of implemented behavior.

## Definition of done for the branding pilot

- The one-minute questions are easy to answer.
- Current capability and future plans are clearly separated.
- Ownership and a contact path are visible.
- At least one useful example, result, or evidence link is available.
- Media is accessible and links use canonical locations.
- The project team has reviewed the narrative for accuracy.

Release-readiness items may remain open if the README says so honestly. Use the
separate [release-readiness checklist](RELEASE_READINESS.md) when a project is
preparing for public distribution or supported use.
