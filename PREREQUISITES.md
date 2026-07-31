# Prerequisites

## Required

- Git
- Java 17 or later
- Bash, zsh, or compatible shell
- A code editor or IDE

## Recommended

- Maven 3.9+
- Claude Code
- GitHub account
- Mermaid-compatible Markdown viewer
- ZIP utility

## Verify installation

```bash
git --version
java -version
javac -version
mvn -version
claude --version
```

Some acts use dependency-free Java scripts, while others use Maven. Read the README inside each act before running commands.

## Claude Code safety

- Start with plan mode for analysis exercises.
- Review project `CLAUDE.md` and `.claude/settings.json`.
- Do not use `--dangerously-skip-permissions`.
- Do not expose secrets or production credentials.
- Display write-tool arguments before execution.
