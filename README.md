# elijr

Explain Like I'm Junior.

```
/elijr how does JWT authentication work
```

elijr explains any technical topic to a junior developer: someone who knows the basics (variables, functions, HTTP, git) but is new to the topic. Instead of toy analogies, it builds on what the reader already knows and produces an HTML explainer with:

1. A one-sentence summary of what it is and what problem it solves
2. A diagram of the real mechanism: components, data flow, sequence of steps
3. A short step-by-step explanation tied to the diagram
4. A minimal, runnable, commented code example
5. Common mistakes juniors make, and how to avoid them
6. Key jargon they will hear from senior developers
7. Next steps: what to learn after this

The explanation is written in the language you ask in.

## Writing style

The prose follows about 80% of [ASD-STE100](https://www.asd-ste100.org/) (Simplified Technical English), the controlled language from aerospace maintenance documentation. That means short sentences, active voice, one instruction per step and one word for one meaning. Technical terms are allowed, but each one gets a definition when it first appears. This softened version of the spec was suggested by Andrej Karpathy. For the full spec, add "strict STE" to your request.

## Install

```
/plugin marketplace add emirhansilsupur/elijr
/plugin install elijr@elijr
```

## What it runs

elijr is a single skill (`skills/elijr/SKILL.md`) containing instructions for Claude. It has no scripts, hooks, MCP servers or dependencies, and it does not send or store any data itself.

## License

MIT
