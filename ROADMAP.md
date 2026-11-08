# MaterialBridge - development roadmap

**Status:** Planned work only. None of the boxes are marked completed. Estimates are rough.

## Product-level acceptance criterion

A sample material spreadsheet becomes validated structured output with explicit provenance.

## Estimated work breakdown

| Step | Milestone | Estimated hours | Observable outcome |
|---|---|---:|---|
| 1 | Design material tree and data contract | 8 | Documented canonical schema |
| 2 | Create mapping and CSV import | 10 | User-defined column mapping works on fixtures |
| 3 | Implement provenance and missingness tracking | 10 | Every exported value has a known origin or unresolved flag |
| 4 | Develop export and diff tools | 8 | Stable JSON exports and revision comparisons |
| 5 | Build local editor | 10 | A user can complete the synthetic tutorial |
| 6 | Tests, docs, and packaging | 10 | Fully reproducible demo project |
| | **Total estimated** | **56** | |

## Detailed milestones

### 1. Design material tree and data contract (8 estimated hours)

- [ ] Deliverable: Documented canonical schema.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 2. Create mapping and CSV import (10 estimated hours)

- [ ] Deliverable: User-defined column mapping works on fixtures.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 3. Implement provenance and missingness tracking (10 estimated hours)

- [ ] Deliverable: Every exported value has a known origin or unresolved flag.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 4. Develop export and diff tools (8 estimated hours)

- [ ] Deliverable: Stable JSON exports and revision comparisons.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 5. Build local editor (10 estimated hours)

- [ ] Deliverable: A user can complete the synthetic tutorial.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 6. Tests, docs, and packaging (10 estimated hours)

- [ ] Deliverable: Fully reproducible demo project.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

## QA and release gates

- [ ] A real runnable implementation exists, with verified setup commands in `README.md`.
- [ ] Automated tests pass in a clean environment and failures are actionable.
- [ ] Only fabricated, original, openly licensed, or otherwise authorized sample data is published.
- [ ] No passwords, API keys, secrets, customer records, or employer/client confidential artifacts appear in repository history.
- [ ] A source-linked change log and actual progress notes distinguish finished work from plans.
- [ ] The GitHub history preserves authentic work and authorship; do **not** manufacture or backdate commits.

## Parking lot and risks

- Technical: Sector-specific DPP requirements may not yet be finalized; product should separate generic data preparation from official compliance.
- Commercial hypothesis (not validated): Paid data connectors and team collaboration tools.
- Beyond MVP: defer paid extensions and hosted features until the underlying product works.
