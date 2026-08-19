# Instructional Materials and GitHub Plan

_Developer-facing plan for building adaptable classroom materials and preparing them for public release._

## Purpose

This plan turns the project's broad material categories into an initial, Markdown-first working model. It also prepares for public, open-source publication without treating drafts as classroom-ready curriculum or creating a remote repository before the course developer chooses its owner and license.

## Initial Material Model

### Course-Level Materials

- Course overview and rationale
- Nine-week course map
- Course-level learning outcomes and essential content strands
- Assessment overview and adaptation guidance

### Unit-Level Materials

- Unit overview: phenomenon or driving question, outcomes, vocabulary, materials, timing, and safety/accessibility notes
- Teacher lesson plans: agenda, preparation, facilitation notes, likely misconceptions, and adaptation choices
- Student activity materials: readings, evidence cards, models, data sheets, prompts, and reflection or submission directions
- Presentation content: Markdown source or slide outline by default; a slide deck only when visuals materially improve teaching
- Assessment materials: student task, success criteria or rubric, and teacher look-fors

### Format Principles

- Use Markdown as the source format whenever practical.
- Write teacher-facing guidance as adaptable facilitation notes, not word-for-word teaching scripts by default.
- Keep teacher-facing, student-facing, and developer-facing content separate.
- Use accessible language, descriptive image text, clear source attribution, and formats educators can revise.
- Add non-Markdown files only when they provide a real functional advantage, such as an editable slide deck or structured data workbook.

## Proposed Local Repository Layout

This is a planned structure, not a claim that a Git repository already exists:

```text
README.md
LICENSE                         # added after license selection
CONTRIBUTING.md                 # added before outside contributions are invited
docs/
  development/                  # proposals, research, decisions, project brief
    prototypes/                 # draft materials awaiting educator review/testing
  educator-guide/               # reviewed course-level guidance
curriculum/
  units/
    <unit-name>/
      unit-overview.md
      teacher/
      student/
      assessments/
      presentations/
assets/
  images/
  diagrams/
```

`docs/development/` makes the planning status visible. `curriculum/` should contain only materials that have completed the relevant educator review.

The current draft prototypes are [Heat-Flow Launch](prototypes/heat-flow-launch/README.md), [Moisture Pathways](prototypes/moisture-pathways/README.md), [Climate-Context Design Cases](prototypes/climate-context-design-cases/README.md), and [Materials Life-Cycle Tradeoffs](prototypes/materials-life-cycle-tradeoffs/README.md). The companion [Systems-Model Evidence Progression](systems-model-evidence-progression-proposal.md) is developer-facing rather than student-facing. All stay in `docs/development/` until they have been reviewed and tested.

## Staged Public-GitHub Plan

### Stage 1 — Prepare Locally

- Maintain clear status labels for proposals, reviewed curriculum, and source materials.
- Attribute external sources and record the license or permission status of every reusable asset.
- Keep student information, school-specific private information, credentials, and copyrighted materials that cannot be redistributed out of the project.

### Stage 2 — Establish the Repository

Before creating or publishing a GitHub repository, the course developer should choose:

1. Repository owner or organization and repository name
2. License for curriculum text and original visual assets
3. Whether development drafts will be public immediately or only reviewed materials will be public
4. Contribution policy, including educator feedback, issue reporting, and review expectations
5. Versioning and release convention

### Stage 3 — First Public Release

- Create a clear `README.md` describing the course's intended audience, status, use, and adaptation boundaries.
- Add the selected license, attribution guidance, and contribution guidance.
- Publish reviewed course-planning documents and classroom materials with their status plainly labeled.
- Create a versioned release only after a documented curriculum review.

## Pending Decisions

- **License:** No license has been selected. A Creative Commons license may fit curriculum materials, but the course developer must choose the exact terms before publication.
- **Working in public:** The project intends to publish openly, but whether unreviewed development drafts will be public remains undecided.
- **Repository:** No Git repository or remote GitHub repository exists in this workspace yet.
- **Asset policy:** The project needs a final rule for photographs, diagrams, presentation templates, and other media before public release.

---

_Last updated: 2026-08-19_
