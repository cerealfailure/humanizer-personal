# Humanizer: Personal Voice Edition

A Claude Code skill that strips AI writing patterns and rewrites text in a specific human voice — an intellectually hungry, ambitious guy in his early 20s who connects hedge funds to Epicurean philosophy to evolutionary biology in one breath.

Based on [blader/humanizer](https://github.com/blader/humanizer) (which uses Wikipedia's [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) guide), extended with a personal voice profile trained on real writing samples.

## What it does

1. **Detects 25 AI writing patterns** — significance inflation, AI vocabulary, superficial -ing analyses, promotional language, em dash overuse, rule of three, etc.
2. **Rewrites in a trained voice** — not generic "human-sounding" but a specific person's voice with stream-of-consciousness thinking, cross-domain connections, rhetorical questions, aphoristic punches, and casual-intellectual register.
3. **Self-audits** — asks "what makes this obviously AI generated?" and revises.

## Install

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/thenameszinski/humanizer-personal.git ~/.claude/skills/humanizer
```

## Usage

In Claude Code:

```
/humanizer [paste your text]
```

Or conversationally: "humanize this text" / "rewrite this in my voice" and paste the content.

## Voice characteristics

- Stream of consciousness, thinks on paper
- Cross-domain connections (finance, biology, philosophy, tech)
- Rhetorical questions as genuine thinking tools
- Arrow notation (->) for logical chains
- Short punchy sentences mixed with long flowing ones
- Self-deprecating honesty about failures
- Casual register with intellectual density
- Comfortable with uncertainty and incomplete thoughts
- British/international English spelling

## Customising

Edit `SKILL.md` to adjust:
- **Voice Profile section** — update writing samples and style descriptions
- **AI Pattern Detection** — add or remove patterns
- **Voice Calibration Checks** — adjust what "sounds right"

## Credits

AI pattern detection from [blader/humanizer](https://github.com/blader/humanizer).
Voice profile and calibration are original.
