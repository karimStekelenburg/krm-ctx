# KRM Context Templates

A structured template repository for managing project context through markdown files. This repository provides a framework for documenting and organizing project knowledge across different phases of development.

## Structure

- `prompts/` - Protocol documents defining the process for each phase
  - `brainstorm.protocol.md` - Protocol for the brainstorming phase
  - `design.protocol.md` - Protocol for the design phase
  - `implementation.protocol.md` - Protocol for the implementation phase

- `templates/` - Template markdown files for each phase
  - `entrypoint.template.md` - Main entry point template
  - `brainstorm/` - Templates for brainstorming phase
    - `functional-requirements.template.md`
    - `project-context.template.md`
    - `technical-requirements.template.md`
  - `design/` - Templates for design phase
    - `architectural-design.template.md`
    - `implementation-plan.template.md`
  - `implementation/` - Templates for implementation phase
    - `progress-log.template.md`
    - `scratchpad.template.md`

## Usage

1. Click "Use this template" to create a new repository based on these templates
2. Follow the protocols in the `prompts/` directory for each development phase
3. Use the corresponding templates from the `templates/` directory to document your project context

## License

MIT