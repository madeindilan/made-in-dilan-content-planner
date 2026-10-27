# Made in Dilan Content Planner

A reusable agent skill for turning a creative idea into a practical content-production plan. Built around Dilan Sünbül's work in art direction, brand identity, design and creative technology.

It helps connect the reason behind a creative decision with what to say, what to show and what to do next. Use your own project, material and voice.

[Download ZIP](https://github.com/madeindilan/made-in-dilan-content-planner/archive/refs/heads/main.zip)

## Get started

1. Download and extract the ZIP, or clone this repository.
2. Open the extracted folder in Codex or an agent that supports repository-local skills.
3. Describe your idea, available material, chosen platform and preferred language.

Try:

> $made-in-dilan-content Help me explain one decision in my own project. Use the facts and material I provide. Keep my voice natural, match the spoken points to visuals, and show the next production task. Ask for my actual reasoning when it is missing.

No API key, package installation or background service is required by this repository. The compatible agent is a separate tool with its own account and usage requirements.

Documentation and examples are in English. New content follows the language requested in the brief, or the brief's language when unspecified.

## Choose a useful scope

| Mode | Suitable request | Output |
|---|---|---|
| Quick recording | Explain one observation or design choice | Talking points, essential visuals and the next task |
| Content package | Develop an idea for selected platforms | Platform-specific angles, a production table and ordered tasks |
| Project story | Explain a longer process or case study | Story sections, evidence, narration and editing notes |

Choose only the platforms and formats the idea needs. Durations remain estimates until the actual narration is timed.

## What is inside

- [Agent skill](.agents/skills/made-in-dilan-content/SKILL.md)
- [Production and task template](.agents/skills/made-in-dilan-content/assets/production-template.md)
- [Production decision guide](.agents/skills/made-in-dilan-content/references/methods.md)
- [Platform adaptation guide](.agents/skills/made-in-dilan-content/references/platforms.md)
- [Research policy](.agents/skills/made-in-dilan-content/references/sources.md)
- [Quick on-camera practice](examples/quick-camera.md)

## Worked example: AuraTouch

The [example plan](examples/auratouch/production-plan.md), [draft copy](examples/auratouch/platform-copy.md) and [tasks](examples/auratouch/tasks.md) show how to discuss a real packaging design decision. Its [brief](examples/auratouch/brief.md) separates established facts from missing reasoning. Replace example details when working on another project.

The example is a production plan. It does not claim that filming or publishing has been completed.

## Limits

The skill prepares plans and drafts when invoked. It does not independently produce finished videos, publish to accounts or schedule inspiration scans. [Verification and release notes](docs/verification.md) explain what has been checked.

## Reuse

The original planning instructions, documentation and text templates are available under the [MIT License](LICENSE). The AuraTouch artwork and brand assets are excluded from that license and remain reserved to their rights holders. See [NOTICE.md](NOTICE.md).

This public package contains no third-party lesson transcripts, video extracts, creator-specific teaching summaries, music or copied example scripts.
