# MaterialBridge - technical plan

**Planning document, not an implementation report.**

## Product objective

Open, inspectable mapping between product material lists and export schemas rather than an enterprise sourcing platform.

## Intended system boundary

- **Input:** Synthetic furniture and textiles with fictional factories and materials.
- **Processing stages:** Material and component tree schema; Column mapping and import pipeline; Provenance/coverage score engine; Local editor and export adapters.
- **Output:** A sample material spreadsheet becomes validated structured output with explicit provenance.
- **Runtime / build stack (tentative):** Python 3.12+, FastAPI, SQLite, SQLModel, Svelte, pytest
- **Explicitly excluded:** Legal attestation, verified real supply-chain claims, collection of proprietary supplier data, or real personal information.

## Functional modules

- Build a component-to-material tree with unit and quantity validation
- Map CSV supplier-field names to a transparent canonical schema
- Track data provenance and unresolved fields in a local project
- Export generic product-information JSON with a declared schema version
- Compare successive material bills for omissions and unit changes

## Demonstration and acceptance cases

**Test 1:** Import a fabricated upholstery bill of materials

**Test 2:** Mark uncertain material fields and show export blockers

**Test 3:** Compare two synthetic component lists and explain differences

## Safety, privacy, and provenance

1. Keep example datasets fictional, self-created, or appropriately licensed.
2. Run locally for the initial prototype; do not collect data on actual third parties.
3. Document origin and versions of external specifications and dependencies.
4. Exclude production credentials; put environment variable *names* only in `.env.example` if required later.
5. Do not make certification, legal compliance, professional safety, or performance guarantees without independent validation.

## Engineering unknowns and constraints

Sector-specific DPP requirements may not yet be finalized; product should separate generic data preparation from official compliance.

## Release definition

A first release requires a runnable prototype, verified README instructions, automated tests tied to the three demonstrations, the full LICENSE file, and an honest public GitHub development history. The roadmap estimates are hypotheses until reviewed during implementation.
