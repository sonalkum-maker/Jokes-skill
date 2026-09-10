# Laugh Skill

`laugh` is a simple GitHub Copilot agent skill that generates one short joke tailored to an optional topic or style.

## Use

Invoke the skill in Copilot Chat:

```text
/laugh databases
```

The skill may also load automatically when you ask Copilot to tell a joke or make you laugh.

## Install

Copy [`.github/skills/laugh`](./.github/skills/laugh) into the same path in your repository. VS Code detects the skill from its `SKILL.md` file.

## Customize

Edit the procedure and quality checks in [`SKILL.md`](./.github/skills/laugh/SKILL.md) to change the humor style, audience, or output format.