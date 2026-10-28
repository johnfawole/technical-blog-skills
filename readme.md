# Agent Skills

Agent skills for developer-focused content. Install one command, and your coding agent writes like a senior engineer talking to peers.

## Skills

| Skill | What it does |
| --- | --- |
| [`technical-blog-writing`](engineering-blog-skills.md) | Writes technical blog posts and tutorials with a punchy topic, a problem-first introduction, runnable code, and a short FAQ. |

## Install

```bash
npx skills add johnfawole/agent-skills
```

List the skills in this repo before installing:

```bash
npx skills add johnfawole/agent-skills --list
```

Works with Claude Code, Cursor, Codex, GitHub Copilot, Windsurf, and other agents that support skills.

## What `technical-blog-writing` gives you

Ask your agent for a blog post, tutorial, how-to, or comparison aimed at developers. The skill takes over and enforces:

- **A topic that earns the click.** Active, direct, and written last. It must score at least 73% in the MonsterInsights Headline Analyzer.
- **A tight introduction.** Four paragraphs at most. Problem first, then the solution hint, then what to expect.
- **A TL;DR.** Five bullets at most.
- **Code that runs.** Fenced, linted, with prerequisites listed and the full block shown at the end.
- **A short FAQ.** Five questions at most, answer first.
- **A confident engineer voice.** Second person, strong opinions, short sentences, no filler like "seamless" or "platforms".

## Try it

After installing, prompt your agent:

```text
Write a tutorial on building a rate-limited scraper with Node.js. Use the technical-blog-writing skill.
```

You can also point it at an existing draft:

```text
Review this draft against the technical-blog-writing checklist and rewrite what fails.
```

## Repo structure

```text
technical-blog-skills/
└── skills/
    └── technical-blog-writing/
    ├── engineering-blog-skills.md
    └── readme.md
```

Each skill lives in its own folder under `skills/`.

## Contributing

Found a rule that's too loose or a gap in the checklist? Open an issue or a pull request. Keep changes small and keep the voice rules intact.

## Author

Built by [John](https://johnfawole.dev), a technical content marketer and developer relations professional.

## License

MIT