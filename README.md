# Personal Context Portfolio

This repository is the working context layer for Ryan Green's group of businesses and initiatives. It is written for AI tools that need reliable context for strategy, planning, analysis, writing, and technical reasoning.

It is organised around the actual group model rather than around generic profile templates. The aim is to show what sits at the ownership layer, what sits at the operating layer, which businesses drive growth, and where cross-business relationships matter.

## Repository Structure

```text
personal-context-portfolio/
├── README.md
├── identity.md
├── goals-and-priorities.md
├── decision-log.md
├── group-narrative.md
├── group-stack-model.md
├── businesses/
│   ├── green-box-ventures/
│   │   └── context.md
│   ├── tac-operations/
│   │   └── context.md
│   ├── caterlytix/
│   │   ├── context.md
│   │   └── projects.md
│   ├── pebble/
│   │   └── context.md
│   ├── arrocms/
│   │   └── context.md
│   └── agentsdotne/
│       └── context.md
├── templates/
├── examples/
├── wiring/
└── interview-protocol/
```

## Root Files

- `identity.md`
- top-level context on who I am, what I do, and how to reason about the group

- `goals-and-priorities.md`
- current strategic direction and where time, investment, and management attention should go

- `decision-log.md`
- the standing decisions that shape structure, operating logic, and trade-offs

- `group-narrative.md`
- a plain-English explanation of how the group fits together and why the entities exist

- `group-stack-model.md`
- the layered model covering ownership, shared capability, commercial platforms, products, and ecosystem work

## Businesses Folder

Each folder in `businesses/` represents a specific business or initiative.

- `businesses/green-box-ventures/context.md`
- `businesses/tac-operations/context.md`
- `businesses/caterlytix/context.md`
- `businesses/caterlytix/projects.md`
- `businesses/pebble/context.md`
- `businesses/arrocms/context.md`
- `businesses/agentsdotne/context.md`

Each `context.md` explains the role of that entity, how it creates value, and how an AI should reason about it. `businesses/caterlytix/projects.md` holds the more detailed workstream context for the group’s main growth business.

## How To Use This Repository With AI Tools

### ChatGPT and Claude

For general strategic reasoning, start with:

1. `identity.md`
2. `group-narrative.md`
3. `group-stack-model.md`
4. Any relevant business `context.md`
5. `goals-and-priorities.md` when trade-offs matter

If the discussion is specifically about Caterlytix, also include `businesses/caterlytix/projects.md`.

### MCP or File-Aware Tools

If the AI tool can read repository files directly, point it at the repository root and instruct it to read the root files first, then the relevant business folder. This works well for MCP-compatible tools, repository-aware coding agents, or any assistant that can ingest markdown from a local directory.

### Good Prompt Pattern

Use prompts that tell the AI what level of context to load. For example:

> Read `identity.md`, `group-stack-model.md`, and `businesses/caterlytix/context.md`, then help me refine the Caterlytix enterprise growth strategy.

This keeps the context relevant and avoids loading the entire repository into every interaction.

## Keeping Files Updated

- Update `goals-and-priorities.md` when strategic direction changes.
- Update `decision-log.md` when a structural decision becomes stable enough to guide future reasoning.
- Update a business `context.md` when its role, model, or strategic position changes.
- Update `businesses/caterlytix/projects.md` when a major workstream changes scope, status, or importance.
- Review naming, terminology, and business relationships regularly so the repository stays internally consistent.

## Reference Material

The `templates/`, `examples/`, `wiring/`, and `interview-protocol/` directories remain as supporting material. They are useful when extending the portfolio or wiring the markdown into other AI workflows, but the authoritative operating context lives in the root files and `businesses/` folder.
