# omniskill

Call with `$omniskill`.

I usually tell Codex the same things:

- use ASD-STE100 English
- use Luna subagents
- make it simple
- ask if unsure

so i made a skill.

## Install

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/Devetak/omniskill.git ~/.codex/skills/omniskill
mkdir -p ~/.codex/skills/writing
cp ~/.codex/skills/omniskill/writing/SKILL.md ~/.codex/skills/writing/SKILL.md
```

## Update

After installation, update the skill with:

```bash
cd ~/.codex/skills/omniskill
git pull --ff-only
mkdir -p ~/.codex/skills/writing
cp ~/.codex/skills/omniskill/writing/SKILL.md ~/.codex/skills/writing/SKILL.md
```

Codex can select the companion `writing` skill for drafting and editing tasks.

Best used with [Ponytail](https://github.com/DietrichGebert/ponytail) for coding-heavy work.
