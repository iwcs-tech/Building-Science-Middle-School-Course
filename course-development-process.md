# Middle School Building Science Course Development Process

_A working plan for researching, designing, testing, and publishing the course._

## Purpose

This document describes how the course will be developed. It covers the developer's AI-assisted workflow, project decisions, partnerships, file organization, testing, and open-source distribution.

It is separate from the [Middle School Building Science Course Concept](middle-school-building-science-course-concept.md), which describes the intended student and teacher experience.

## Development Goals

- Develop an engaging and scientifically sound building science course for middle school students.
- Begin with a realistic nine-week classroom course before creating additional formats.
- Keep educators responsible for curriculum decisions and quality control.
- Use AI as a practical research, brainstorming, drafting, and project-management aid.
- Create adaptable materials that educators can revise for their students and local context.
- Publish the curriculum and supporting resources openly on GitHub.
- Explore how connected tools, data, and local partnerships can support curriculum development.

## AI-Supported Development Workflow

The following activities are for the course developer. They are not student activities or teacher requirements:

1. Schedule AI-assisted research on building science education every Monday morning.
   - Ask the AI to identify three actionable suggestions from that research.
   - Select one suggestion for the AI to develop further.
2. Ask the AI to pose questions that clarify and improve the course concept.
3. Review, revise, and approve all consequential curriculum decisions as the human course developer.
4. Explore possible connections with Hermes and OpenClaw where they can improve the development workflow.

The weekly schedule is intended to maintain steady progress on course development. It does not determine the schedule or structure of student lessons.

## Current Development Artifacts

The following developer-facing documents record the current direction and should be read as planning artifacts, not classroom-ready curriculum:

- [Project Brief](docs/development/project-brief.md) — the confirmed setting, current status, and decisions still needed.
- [Heat-Flow Thread Proposal](docs/development/heat-flow-thread-proposal.md) — the approved direction to develop heat flow as a recurring explanatory idea, without making it the course's sole organizer.
- [Heat-Flow Launch Prototype](docs/development/prototypes/heat-flow-launch/README.md) — three draft lessons and supporting materials prepared for review before classroom testing.
- [Moisture Pathways Strand Proposal](docs/development/moisture-pathways-strand-proposal.md) — a candidate moisture strand and its boundaries; the essential-strand decision remains under review.
- [Moisture Pathways Prototype](docs/development/prototypes/moisture-pathways/README.md) — two draft lessons and supporting materials prepared for educator review before classroom testing.
- [Systems-Model Evidence Progression](docs/development/systems-model-evidence-progression-proposal.md) — a review packet for comparing candidate course-level outcomes and evidence across the developing strands.
- [Climate-Context Design Cases Prototype](docs/development/prototypes/climate-context-design-cases/README.md) — two draft lessons that use fictional climate contexts and modeled design comparisons.
- [Materials Life-Cycle Tradeoffs Prototype](docs/development/prototypes/materials-life-cycle-tradeoffs/README.md) — two draft lessons that use fictional life-cycle and material-choice comparisons.
- [Instructional Materials and GitHub Plan](docs/development/instructional-materials-and-github-plan.md) — the planned material types, repository structure, and decisions required before public release.

## Confirmed Project Decisions

- The initial audience is seventh- and eighth-grade students.
- Typical enrollment is approximately 15 students but may vary.
- The initial course will run for nine weeks.
- Classes will meet three days per week for 40 minutes, producing 27 meetings and 18 instructional hours.
- The initial version will be designed for a standard classroom rather than a workshop.
- The teacher has a laptop and presentation board, and each student has a laptop.
- The course should assume no more than one field trip.
- The teacher-led classroom version will be developed before the fully online version.
- Files and artifacts will be stored in Markdown by default unless another format is necessary.

## Proposed Development Phases

### Phase 1: Define the Course

- Refine the course purpose and central idea.
- Develop a concise set of course-level learning outcomes.
- Select the essential content strands.
- Choose the questions or phenomena that will organize the course.
- Decide on an appropriate culminating task and assessment approach.

### Phase 2: Build the Course Map

- Draft the nine-week scope and sequence.
- Allocate the 27 class meetings across units, transitions, assessment, and schedule flexibility.
- Identify which lessons use explanation, discussion, observation, investigation, digital work, or collaborative problem-solving.
- Identify an optional field trip and a classroom alternative.

### Phase 3: Prototype One Unit

- Develop one representative unit in full.
- Create teacher notes, student materials, presentation content, activity instructions, and assessment materials.
- Check that activities fit a 40-minute period and a standard classroom.
- Review the unit for scientific accuracy, accessibility, safety, cost, and ease of use.

### Phase 4: Test and Revise

- Pilot the representative unit with students if possible.
- Gather feedback from students and the teacher.
- Record timing problems, misconceptions, engagement, material needs, and technology issues.
- Revise the course model before producing the remaining units.

### Phase 5: Complete and Publish the Classroom Course

- Develop the remaining units using the tested model.
- Conduct a final curriculum review.
- Organize the repository so educators can understand, use, and adapt the materials.
- Add licensing, attribution, contribution, and versioning information.
- Publish the classroom course openly on GitHub.

### Phase 6: Develop Additional Versions

- Adapt the tested classroom materials for self-paced online learning.
- Consider optional teacher- or student-facing AI features only when they support a defined educational purpose.
- Develop localization guidance so other educators can adapt examples, climate information, building types, and partnerships.

## Partnerships

Potential partners may contribute expertise, learning opportunities, examples, data, materials, feedback, or access to a field-trip location. Possibilities include:

- Schools and educators
- Building scientists, architects, engineers, contractors, and facility managers
- Community organizations
- Local government departments
- Colleges, universities, trade programs, and workforce-development organizations
- Energy, weatherization, housing, sustainability, and public-health organizations

Partnership development should follow the course's learning goals rather than determine them prematurely.

## File and Artifact Guidelines

- Use Markdown by default.
- Use another format only when it provides a clear functional advantage, such as a spreadsheet for structured planning or data.
- Keep student-facing, teacher-facing, and developer-facing materials clearly separated.
- Record important project decisions and the reasons behind them.
- Use clear filenames and relative links so the project works well in a GitHub repository.
- Keep draft research distinct from reviewed curriculum content.

### Initial Material Model

The first classroom version will use a Markdown-first set of materials. A representative unit will normally include a unit overview, teacher-facing lesson plans and facilitation notes, student-facing activity materials, presentation content where visuals provide a clear advantage, and assessment materials. Detailed teaching scripts are not the default; educators should be able to adapt the materials to their students and local context.

The detailed output model and a staged public-GitHub plan are maintained in the [Instructional Materials and GitHub Plan](docs/development/instructional-materials-and-github-plan.md). This plan does not authorize creation or publication of a remote repository; repository ownership and licensing remain decisions for the course developer.

## Immediate Next Decisions

1. Define and compare possible course-level learning outcomes.
2. Select the course's essential content strands.
3. Choose the central questions or phenomena that will connect the nine weeks.
4. Identify several possible culminating tasks.
5. Draft the first version of the 27-session course map.

---

_Last updated: 2026-08-19_
