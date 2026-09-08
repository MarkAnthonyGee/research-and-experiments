# Research & Experiments

## Community Problem Radar: a reusable AI research skill

Give your assistant a set of instructions for reviewing community discussions: separate product promotion from firsthand problems, check conflicting evidence, and decide what deserves further investigation.

The skill is written in Markdown, with a guide, output template and fictional practice case. I'm sharing the instructions so you can use or adapt them without developing the workflow from scratch.

## Use the skill

Download this repository using **Code → Download ZIP**, unzip it, and find `skills/community-problem-radar`. Keep that whole folder together; [SKILL.md](skills/community-problem-radar/SKILL.md) contains the main instructions.

For local skill installation, copy the folder to the location for your assistant:

| Assistant | Personal skill folder | Setup documentation |
|---|---|---|
| Codex | `~/.agents/skills/community-problem-radar/` | [Codex skills](https://learn.chatgpt.com/docs/build-skills) |
| Claude Code | `~/.claude/skills/community-problem-radar/` | [Claude Code skills](https://code.claude.com/docs/en/skills) |

Then ask your assistant to use Community Problem Radar on discussions you supply. If it cannot find the skill, check its setup documentation above.

**Without installation:** attach or paste `SKILL.md`, `references/guide.md` and `assets/research-template.md` into a Claude, ChatGPT or other AI chat, along with your discussions. Supplying a web link alone may not give the assistant access to every file.

Example request:

> Use Community Problem Radar on these discussions. Answer its five questions, cite the source IDs, and explain what deserves investigation and what would make us stop. Keep missing information unknown.

## Try it first

The [practice input](skills/community-problem-radar/assets/practice-input.md) has eight fictional records and a self-contained prompt. Copy the page into an AI chat, or give the records to your installed skill. Compare with the [worked answer](skills/community-problem-radar/references/worked-example.md) afterward.

## Where it came from

My background is in operations, project management and process improvement. I directed an AI-assisted scan of 17 Reddit communities for startup and app ideas. It revealed what builders were making and where they got stuck, with much less evidence of what buyers needed. This skill grew from that distinction; the original dataset and scripts remain separate.

AI drafted the skill under my direction. Agent reviews informed revisions; human usability, setup across products and improved outcomes remain unverified. This is a personal collection without ongoing support or a request for contributions.

Version 0.3. Reuse and adapt with credit under [CC BY 4.0](LICENSE.md). [Provenance](PROVENANCE.md) · [Changes](CHANGELOG.md).
