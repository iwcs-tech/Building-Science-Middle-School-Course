# Instructional Materials and GitHub Plan

_Developer-facing plan for building adaptable classroom materials and preparing them for public release._

## Purpose

This plan turns the project's broad material categories into an initial, Markdown-first working model. Project documents are published to the tracked GitHub repository as they are created or modified, without treating development drafts as classroom-ready curriculum. A license has not yet been selected.

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

## Intended Repository Layout

This is the intended structure for the existing repository. Publishing a document does not authorize moving an unreviewed draft into `curriculum/`.

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

The current draft prototypes are [Heat-Flow Launch](prototypes/heat-flow-launch/README.md), [Moisture Pathways](prototypes/moisture-pathways/README.md), [Climate-Context Design Cases](prototypes/climate-context-design-cases/README.md), [Materials Life-Cycle Tradeoffs](prototypes/materials-life-cycle-tradeoffs/README.md), [Air and Ventilation Systems](prototypes/air-and-ventilation-systems/README.md), [Water-Use Systems](prototypes/water-use-systems/README.md), and [Feedback-and-Controls Systems](prototypes/feedback-and-controls-systems/README.md). The companion [Systems-Model Evidence Progression](systems-model-evidence-progression-proposal.md) and [Culminating Task Comparison Packet](prototypes/culminating-task-comparison/README.md) are developer-facing rather than selected student assessments. All stay in `docs/development/` until they have been reviewed and tested.

## Staged Public-GitHub Plan

### Stage 1 — Prepare Locally

- Maintain clear status labels for proposals, reviewed curriculum, and source materials.
- Attribute external sources and record the license or permission status of every reusable asset.
- Keep student information, school-specific private information, credentials, and copyrighted materials that cannot be redistributed out of the project.

### Stage 2 — Maintain the Public Working Repository

When a project document is created or modified:

1. Keep its development, review, and classroom-testing status explicit.
2. Validate links, formatting, and the absence of private information or credentials.
3. Commit the completed document change and push it to the tracked GitHub repository.
4. Keep unreviewed work under `docs/development/`; move materials into `curriculum/` only after the relevant educator approval.

The course developer still needs to choose the license, contribution policy, and versioning or release convention.

### Stage 3 — First Public Release

- Create a clear `README.md` describing the course's intended audience, status, use, and adaptation boundaries.
- Add the selected license, attribution guidance, and contribution guidance.
- Publish reviewed course-planning documents and classroom materials with their status plainly labeled.
- Create a versioned release only after a documented curriculum review.

## Pending Decisions

- **License:** No license has been selected. A Creative Commons license may fit curriculum materials, but the course developer must choose the exact terms before publication.
- **Working in public:** New and modified project documents are pushed to the tracked GitHub repository while retaining explicit draft and review-only labels.
- **Repository:** The local workspace tracks `origin` at `https://github.com/iwcs-tech/Building-Science-Middle-School-Course.git`.
- **Asset policy:** The project needs a final rule for photographs, diagrams, presentation templates, and other media before public release.

---

_Last updated: 2026-09-24_
