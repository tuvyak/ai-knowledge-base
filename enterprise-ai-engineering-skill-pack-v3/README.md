# Enterprise AI Engineering Skill Pack v3

## Purpose

- Provide a normalized, token-efficient engineering standard for AI-assisted development.
- Use one shared structure, workflow, severity model, validation model, and completion format.
- Keep every skill self-contained so it can be loaded independently.
- Reduce repeated instructions while preserving the material requirements of the source skills.

## Included Skills

- `secure-sdlc/secure-sdlc.md`
- `architecture/senior-software-architect.md`
- `clean-code/clean-code-engineer.md`

## Shared Standard

Each skill uses the same sections:

- Purpose
- Role
- Core Principles
- Workflow
  - Before
  - During
  - After
- Requirements
- Validation
- Review Checklist
- Gates
- Completion Output
- References

## Usage

- Load the skill most relevant to the task.
- Load multiple skills for cross-domain work.
- For architecture-sensitive secure coding, load all three.
- Repository instructions apply unless they conflict with higher-priority security or organizational policy.
- Replace `<OWNER>` in each skill front matter with the responsible team or organization.

## Token Optimization

- Shared concepts use identical compact wording.
- Repeated examples and explanatory prose were reduced.
- Lists replace long narrative paragraphs.
- Overlapping requirements were consolidated.
- Each skill remains self-contained to avoid runtime dependency on shared files.

## Version

- Version: 3.0.0
- Status: Active
