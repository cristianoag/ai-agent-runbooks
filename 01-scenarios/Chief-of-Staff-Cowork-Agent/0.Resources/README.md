# Resources and Source Basis - Chief of Staff

## Published Archives

| File | Contents | Intended use |
|---|---|---|
| [Chief-of-staff Cowork Plugin.zip](Chief-of-staff%20Cowork%20Plugin.zip) | Cowork plugin package: root `manifest.json`, `color.png`, `outline.png`, `README.md`, and five expanded skill folders under `skills/`. Each skill includes `SKILL.md` and `reference.md` (14 files total). | Upload the complete ZIP through the supported Cowork plugin surface, subject to tenant policy. This variant uses the skill names documented in the scenario. |
| [Chief-of-staff.zip](Chief-of-staff.zip) | Skills-only bundle: a `Chief-of-staff/` wrapper containing a README and five skill folders, each with `SKILL.md` and `reference.md` (11 files total). No app manifest or icons. | Inspect/customise individual skills for the supported per-user skill installation route. Resolve the communications-skill routing mismatch below before use. |

The plugin manifest declares package version **1.0.0** and manifest version **devPreview**.
The skills declare version **1.0.0** and `verified: false`. These are package metadata, not
evidence of tenant approval or completed acceptance testing.

## Included Skills

| Plugin skill | Skills-only folder / declared name | Purpose |
|---|---|---|
| `leader-concierge` | `leader-concierge` | Clarify intent and route to one leadership workflow |
| `leader-360` | `leader-360` | Weekly operating brief: dashboard, leadership update, risk lens and first moves |
| `executive-drafts` | `leader-comms` | Executive emails, Teams updates, stakeholder notes and delegation drafts |
| `leadership-pack` | `leadership-pack` | Leadership briefs and board, steering, QBR or operating-review pack outlines |
| `team-pulse` | `team-pulse` | Observable work, blockers and visibility gaps; no employee ranking or evaluation |

**Naming difference:** in the published skills-only bundle, both the communications folder
and its declared skill name are `leader-comms`. However, its concierge instructions and
reference tables target `executive-drafts`. The plugin consistently uses `executive-drafts`.
The archives are therefore not interchangeable without checking routing. For the skills-only
route, align the declared name and all routing references in an approved working copy, then
test discovery and routing in a new session. Do not change only the folder name.

## Choosing and Using a Package

1. Select one installation route; do not install both variants blindly and create duplicate
   skills. Inspect the manifest, instructions and companion references before approval.
2. **Plugin:** retain the ZIP's root layout when uploading. Do not add an outer folder or
   replace the expanded `skills/` directories with nested ZIPs. Confirm the tenant supports
   the package's preview manifest.
3. **Skills-only:** extract the bundle and use the individual skill folders inside
   `Chief-of-staff/`, not the wrapper itself. For the documented OneDrive route, each skill
   must have `SKILL.md` directly under its folder in `Documents\Cowork\skills`, with its
   `reference.md` alongside it. Resolve the naming mismatch before enabling the concierge.
4. Start a new Cowork session and complete the [scenario acceptance tests](../3.Runbook.md).
   Check source permissions, grounding, people safety and approval controls before scheduling.

These ZIPs supply skill definitions and references, with app packaging in the plugin variant.
They do not supply a separately hosted agent runtime, grant source access, or provision schedules.
Review-ready output and explicit approval remain required before consequential actions.

## Delivery Assets

| Asset to obtain or produce | Purpose |
|---|---|
| Approved selection of the published plugin or skills-only bundle | Record the chosen version, any routing/configuration changes and tenant approval |
| Pilot scope, evidence windows and priority/RAG rules | Reviewed source and output contract |
| Existing document/deck templates | Artifact validation; no new brand-system design |
| Sanitised routing, permission, safety and output test cases | Repeatable evaluation |
| Schedule inventory and approved prompt versions | Lifecycle and rollback |
| Baseline/pilot scorecard and handover record | Value, cost and ownership evidence |

## Validation Status

Archive integrity, file inventory, manifest metadata and declared skill names were inspected
locally on September 25, 2026. The ZIPs were not modified. Upload compatibility, actual source
access, runtime approval enforcement and live-tenant acceptance have not been validated.

See the [overview](../1.Overview.md), [runbook](../3.Runbook.md) and
[Cowork skill delivery pattern](../../../02-patterns/Cowork-Skill-Delivery-and-Scheduled-Reviews/Cowork-Skill-Delivery-and-Scheduled-Reviews.md).
