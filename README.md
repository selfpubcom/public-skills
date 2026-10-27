# AI skills by selfpublishing.com

Skills you install once in your AI so it follows them every time. Each skill lives in its own folder under `skills/`, with its own README and FAQ.

Works in Claude (desktop app and Cowork), Codex, Grok Bot, Grok Build, and Claude Code.

## Skills

| Skill | What it does |
| --- | --- |
| [Brand Builder](skills/brand-builder/) | Reads your website, asks a few questions, and builds a complete brand skill for your business. |

## How to install a skill

Open your AI, start a new chat, and paste the install line from the skill's README. For example:

> Install the brand-builder skill from https://github.com/selfpubcom/public-skills/tree/main/skills/brand-builder, then run it.

## FAQ

**Which AI should I use?**
Any of the 4 works. If you're not sure, start with the Claude, Codex, or Grok Bot desktop app. Grok Build runs in your computer's Terminal, which takes more setup.

**My AI says it can't install skills.**
Make sure you're in the Claude, Codex, or Grok Bot desktop app, or in Grok Build, not a browser chat. Then start a new conversation and paste the install line again.

**My AI asked permission to save a file. Is that okay?**
Yes. Installing a skill means saving it on your computer, so say yes when your AI asks.

**How do I get the latest version of a skill?**
Paste the skill's install line again and tell your AI to replace the version you have.

## For technical users

Install with the skills CLI:

```bash
npx skills add selfpubcom/public-skills --skill brand-builder
```

Or copy any folder under `skills/` into your tool's skills folder:

| Tool | Folder |
| --- | --- |
| Claude Code | `~/.claude/skills/` |
| Codex | `~/.agents/skills/` |
| Grok Build | `~/.grok/skills/` |
