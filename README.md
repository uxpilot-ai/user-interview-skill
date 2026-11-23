# User Interview Guide skill for Claude Code, Codex and Cursor

A free agent skill that turns what you need to learn into a neutral 1:1 user interview guide: core questions, optional probes, a moderator card and a debrief. It works in Claude Code, Codex, Cursor and any agent that supports skills.

## Install

```bash
npx skills add uxpilot-ai/user-interview-skill
```

Or copy the `skills/user-interview-guide` folder into your agent's skills folder (for Claude Code, `~/.claude/skills/`).

## What it does

- Asks what you need to learn and how you will use the answers, one question at a time.
- Picks the right kind of interview: problem discovery, retained value, adoption and churn, switching, or concept reaction.
- Writes neutral questions anchored in real past events, and flags leading, hypothetical, double-barrelled or overloaded ones.
- Delivers a timeboxed guide, a compact moderator card and a five-minute debrief.
- Tells you when an interview is the wrong method, for example to measure how common something is or to test what caused a change.

## Example prompts

- "Write a 30-minute interview guide to learn why trial users don't activate."
- "Review these interview questions for leading or hypothetical wording."
- "I'm talking to three churned customers tomorrow. Make me a guide."
- "Help me plan switching interviews with people who moved to a competitor."

## What's inside

| File | What it covers |
|---|---|
| `SKILL.md` | The flow: clarify the goal, choose a path, draft the guide |
| `references/interview-modes.md` | How the guide changes for discovery, retention, churn, switching and concept interviews |
| `references/question-design.md` | Building a guide in seven passes, and 15 kinds of weak question with rewrites |
| `references/moderation.md` | Running the session, common moderator mistakes, remote calls |
| `references/recruiting-and-consent.md` | Participant criteria, screeners, consent and recording |
| `references/evidence-signals.md` | What interviews can and cannot prove, and how to debrief |
| `assets/interview-guide-template.md` | A template for a full research round |

## Made by UX Pilot

[UX Pilot](https://uxpilot.ai/?utm_source=user-interview-guide&utm_medium=readme) is an AI UI design tool. When your interviews point to a product change, it can turn your notes into screens, user flows and clickable prototypes, and predict where people will look with an attention heatmap.

## License

[Apache License 2.0](LICENSE): use, change and share it freely. Keep the [NOTICE](NOTICE) file when you do.
