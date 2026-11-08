# MaterialBridge

> Material-data normalization for passport-readiness workflows.

**Current state:** Documentation starter / proposed product. The presence of this README does **not** mean the software has been implemented, deployed, used. Update this status to reflect real work.

## What it is

MaterialBridge is a proposed specialist software tool for Small furniture makers, textile producers, and material-information specialists. Material attributes, origins, and component relationships often reside in incompatible local tables. The intended differentiation is: Open, inspectable mapping between product material lists and export schemas rather than an enterprise sourcing platform.

## Intended users and use cases

- Import a fabricated upholstery bill of materials
- Mark uncertain material fields and show export blockers
- Compare two synthetic component lists and explain differences

## Planned features

- Build a component-to-material tree with unit and quantity validation
- Map CSV supplier-field names to a transparent canonical schema
- Track data provenance and unresolved fields in a local project
- Export generic product-information JSON with a declared schema version
- Compare successive material bills for omissions and unit changes

## Proposed technology

Python 3.12+, FastAPI, SQLite, SQLModel, Svelte, pytest

These technologies are *planned*, not a claim that dependencies have already been installed or code has been written. Revise this section when actual implementation decisions are made.

## Proposed architecture

- Material and component tree schema
- Column mapping and import pipeline
- Provenance/coverage score engine
- Local editor and export adapters

See [TECHNICAL_PLAN.md](TECHNICAL_PLAN.md) for technical boundaries and acceptance tests.

## Running locally

**Not yet runnable.** This package contains documentation templates, not software. When a functioning implementation is available, replace this paragraph with tested prerequisites, install instructions, a verified executable command, and a reproducible example using `Synthetic furniture and textiles with fictional factories and materials.`

## Data boundaries and exclusions

Legal attestation, verified real supply-chain claims, collection of proprietary supplier data, or real personal information. All public examples should use Synthetic furniture and textiles with fictional factories and materials.

## Known limitations / validation risks

Sector-specific DPP requirements may not yet be finalized; product should separate generic data preparation from official compliance.

## Development roadmap

Work is broken into estimated, not-yet-completed milestones in [ROADMAP.md](ROADMAP.md). They are *planning estimates*, not an assertion that development has begun or that work will definitely be performed.

## Business direction

Potential commercial extensions: Paid data connectors and team collaboration tools. 

## Contributing and licensing

License: [Mozilla Public License 2.0](LICENSE) (`MPL-2.0`). The distribution contains the complete license text. Any future source files can include the SPDX identifier `MPL-2.0` and the Exhibit A notice where appropriate. Rights in contributions and project ownership must be verified before licensing.

