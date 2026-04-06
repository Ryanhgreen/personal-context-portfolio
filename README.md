# Personal Context Portfolio

This repository is the working context layer for Ryan Green's group of businesses and initiatives. It is designed to give ChatGPT and other AI tools the context they need to reason accurately about strategy, operations, structure, products, and cross-business decisions.

It is organised around the real group model rather than around generic profile templates. The aim is to make clear:

- what sits at the ownership layer
- what sits at the shared operating layer
- which businesses drive growth
- how the businesses relate to one another
- which files an AI should read for a given task

## Purpose

This repository exists to reduce repeated explanation and improve the quality of AI-assisted work.

Used properly, it should help an AI:

- understand the structure of the group before making recommendations
- distinguish between ownership, shared capability, and customer-facing delivery
- reason about Caterlytix, Pebble, ArroCMS, TAC Operations, Green Box Ventures, and AGENTSdotNE in the right context
- produce outputs that are more strategically useful and less generic

It is not a marketing site or a public company profile. It is working context for analysis and decision support.

## Repository Structure

```text
personal-context-portfolio/
├── README.md
├── identity.md
├── communication-style.md
├── goals-and-priorities.md
├── decision-log.md
├── group-narrative.md
├── group-stack-model.md
├── group-strategy-deck.md
├── businesses/
│   ├── green-box-ventures/
│   │   ├── context.md
│   │   └── sales-pitch.md
│   ├── tac-operations/
│   │   ├── context.md
│   │   └── sales-pitch.md
│   ├── caterlytix/
│   │   ├── context.md
│   │   ├── projects.md
│   │   └── sales-pitch.md
│   ├── pebble/
│   │   ├── context.md
│   │   └── sales-pitch.md
│   ├── arrocms/
│   │   ├── context.md
│   │   └── sales-pitch.md
│   └── agentsdotne/
│       ├── context.md
│       └── sales-pitch.md
├── prompts/
│   └── update-business-files.md
├── templates/
│   └── business-sales-pitch-template.md
├── examples/
├── wiring/
└── interview-protocol/
```

## Root Files

- `identity.md`: top-level context on who I am, what I do, and how an AI should reason about the group
- `communication-style.md`: guidance on tone, structure, and output style for AI-assisted writing and analysis
- `goals-and-priorities.md`: current strategic direction and where time, investment, and management attention should go
- `decision-log.md`: standing decisions that shape structure, operating logic, and trade-offs
- `group-narrative.md`: plain-English explanation of how the group fits together and why the entities exist
- `group-stack-model.md`: layered view of ownership, shared capability, commercial platforms, products, and ecosystem work
- `group-strategy-deck.md`: markdown version of the core strategy-deck storyline for planning and summary work

If an AI can only read a few files, these should be the default starting point.

## Businesses Folder

Each folder in `businesses/` represents a specific business or initiative.

- `context.md`
- `projects.md` where relevant
- `sales-pitch.md`

Each `context.md` explains:

- the role of that entity in the wider group
- how it creates value
- how it relates to the other businesses
- what an AI should keep in mind when reasoning about it

`businesses/caterlytix/projects.md` adds more detailed workstream context for the group’s main growth business.

Each `sales-pitch.md` is used for:

- brand positioning
- sales and marketing messages
- ideal customer profiles
- customer personas
- qualification questions
- objections and buying triggers
- cross-sell and group synergies

## How To Read The Repository

Use the files in layers rather than reading everything by default.

### Start Here for Most Tasks

1. `identity.md`
2. `group-narrative.md`
3. `group-stack-model.md`

### Add These When the Task Is Strategic

- `goals-and-priorities.md`
- `decision-log.md`
- `group-strategy-deck.md`

### Add These When the Task Is Business-Specific

- the relevant `businesses/<name>/context.md`
- the relevant `businesses/<name>/sales-pitch.md` for positioning, messaging, or qualification work
- `businesses/caterlytix/projects.md` if the task involves Caterlytix delivery, platform strategy, or growth planning

This keeps the context set focused and reduces noise.

## How To Use This Repository With AI Tools

### ChatGPT and Claude

For general strategic reasoning, start with:

1. `identity.md`
2. `communication-style.md`
3. `group-narrative.md`
4. `group-stack-model.md`
5. the relevant business `context.md`
6. the relevant business `sales-pitch.md` for sales, messaging, or commercial work
7. `goals-and-priorities.md` when trade-offs matter

If the discussion is specifically about Caterlytix, also include `businesses/caterlytix/projects.md`.

### Best Practice for ChatGPT

- Do not paste the whole repository unless the task genuinely spans the whole group.
- Tell ChatGPT which files to use before asking the main question.
- Ask it to state assumptions when context is incomplete.
- Ask it to distinguish between group-level decisions and business-level decisions.
- Ask it to reference specific files when making a recommendation.

Example:

> Read `identity.md`, `communication-style.md`, `group-narrative.md`, `group-stack-model.md`, `businesses/pebble/context.md`, and `businesses/pebble/sales-pitch.md`. Then recommend how Pebble should relate to Caterlytix without weakening Pebble's direct-to-school focus.

### MCP or File-Aware Tools

If the AI tool can read repository files directly, point it at the repository root and instruct it to read the root files first, then the relevant business folder. This works well for MCP-compatible tools, repository-aware coding agents, or any assistant that can ingest markdown from a local directory.

### Good Prompt Pattern

Use prompts that tell the AI what level of context to load. For example:

> Read `identity.md`, `group-stack-model.md`, `group-strategy-deck.md`, and `businesses/caterlytix/context.md`, then help me refine the Caterlytix enterprise growth strategy.

This keeps the context relevant and avoids loading the entire repository into every interaction.

## Best Practices

- Keep files factual, current, and specific.
- Write for decision support, not for presentation polish.
- Prefer clear distinctions between ownership, influence, and direct control.
- Update terminology consistently across files when a business model or relationship changes.
- Add new files only when they improve reasoning clarity; avoid creating context sprawl.
- Where a topic is active but unstable, capture the stable logic in the root files and the changing detail in the relevant business file.

## Keeping Files Updated

- Update `goals-and-priorities.md` when strategic direction changes.
- Update `decision-log.md` when a structural decision becomes stable enough to guide future reasoning.
- Update a business `context.md` when its role, model, or strategic position changes.
- Update `businesses/caterlytix/projects.md` when a major workstream changes scope, status, or importance.
- Update a business `sales-pitch.md` when positioning, customer profiles, objections, or buying triggers change.
- Review naming, terminology, and business relationships regularly so the repository stays internally consistent.

## Reference Material

The `templates/`, `examples/`, `wiring/`, and `interview-protocol/` directories remain as supporting material. They are useful when extending the portfolio or wiring the markdown into other AI workflows, but the authoritative operating context lives in the root files and `businesses/` folder.
