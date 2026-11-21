# AI Fluency toolkit

Two skills that turn the AI Fluency 4D framework (**Delegation, Description, Discernment, Diligence**) into habits you can run in a chat.

| Skill | When | What it does |
|---|---|---|
| `prompt-4d-review` | Before you send a prompt | Grades it on the 4Ds, asks a few questions to close the gaps, and returns an improved version. |
| `fluency-levels` | Before a task that matters | Asks the right questions first, at three depths (1 Quick, 2 Standard, 3 Deep), shows the finished prompt, then does the task. |

Printable cheat sheets, a live demo and the story of how these were made: **[sirsirio.github.io/MyPortfolio/ai.html](https://sirsirio.github.io/MyPortfolio/ai.html)**

## Install

**Claude Code** (two commands, inside a session):

```
/plugin marketplace add SirSirio/ai-fluency-toolkit
/plugin install ai-fluency@sirio-tools
```

**Claude apps (claude.ai, desktop, Cowork):** go to **Customize > Plugins**, add the marketplace `SirSirio/ai-fluency-toolkit`, and install *ai-fluency*.

**Just one skill, or another tool:** each skill is also a single download on the [page](https://sirsirio.github.io/MyPortfolio/ai.html#toolkit), with install notes for the Claude apps, Claude Code and Google Antigravity.

## Use

Plugin skills carry the plugin's name:

```
/ai-fluency:prompt-4d-review <paste your prompt>
/ai-fluency:fluency-levels 2 write the intro of my lab report
```

Claude also picks a skill on its own when your request matches it. With no level, `fluency-levels` recommends one and waits for your yes.

Update later with `/plugin marketplace update sirio-tools`.

## Credits and licence

Based on the AI Fluency Framework by Rick Dakan and Joseph Feller, taught in Anthropic Academy's [*AI Fluency: Framework and foundations*](https://academy.claude.com/courses/ai-fluency-framework-foundations). Not affiliated with or endorsed by Anthropic.

Made with Claude and Gemini; content chosen and reviewed by Sirio Feltrin. Full AI statement and credits: [the page](https://sirsirio.github.io/MyPortfolio/ai.html).

Licensed under [CC BY-NC-SA 4.0](LICENSE): share and adapt with credit, not for commercial use, under the same licence.
