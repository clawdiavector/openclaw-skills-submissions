# OpenClaw Skills - Submissions

Submit skills here for review. **Do not install from this repo directly.**

## How to submit

1. Create a branch: `submit/<skill-name>-v<version>`
2. Add your skill folder at the root: `<skill-name>/SKILL.md` + optional files
3. Include a `manifest.json` with name, version, and description
4. Open a PR for review

## Skill folder structure

```
<skill-name>/
├── SKILL.md          # Required
├── manifest.json     # Required (name, version, description)
├── skill.json        # Optional (tool definitions)
└── scripts/          # Optional
    └── ...
```

## After approval

Approved skills are promoted to the [verified repo](https://github.com/clawdiavector/openclaw-skills-verified).
