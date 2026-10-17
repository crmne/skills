# skills

[Agent Skills](https://agentskills.io/specification) I wrote and use, for any agent that reads them: Claude Code, Codex, Cursor, RubyLLM, and more.

| Skill | What it does |
| --- | --- |
| [`bitwig-track`](skills/bitwig-track) | Composes an original track and builds it in Bitwig Studio through a generated controller script, with the presets you have installed |

## Install

With the [`skill`](https://github.com/crmne/skill) gem:

```sh
gem exec skill add crmne/skills@bitwig-track
```

Inside a project it installs into the project's agent folders; anywhere else, globally. Pass `--global` or `--agent claude-code` to choose.

## License

MIT. See [LICENSE](LICENSE).
