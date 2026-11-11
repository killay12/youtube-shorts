# YouTube Shorts video skill

This repository contains the MoneyPrinterTurbo video-generation skill for
GitHub Copilot and compatible agents.

## Files

- `SKILL.md` describes when and how the agent should use the skill.
- `mpt_agent.py` is the adjacent helper used for setup, generation, and result
  delivery.

Install both files together in a skill directory named
`moneyprinterturbo-video`. For Copilot CLI, a user-level location is
`~/.copilot/skills/moneyprinterturbo-video/`.

The skill uses MoneyPrinterTurbo from its upstream repository:
https://github.com/harry0703/MoneyPrinterTurbo
