# SkillProof Skills

Skills built and bench-tested by [SkillProof](https://skillproof.dev) — the tested Claude skills directory. We test other people's skills for a living ([public methodology](https://skillproof.dev/methodology)); ours go through the same protocol, and every skill ships with a measured benchmark, not marketing claims.

Each skill lives in its own repo — one `git clone` installs it.

## Skills

| Skill | What it does | Measured cost | Install |
|---|---|---|---|
| [seo-translator](https://github.com/Skillproofdev/seo-translator) | SEO-aware, human-sounding translation: per-market registers, never-translate list, anti-AI pass | 76k tokens / 4m53s per language (2,900-word article) | `git clone https://github.com/Skillproofdev/seo-translator ~/.claude/skills/seo-translator` |
| [token-discipline](https://github.com/Skillproofdev/token-discipline) | Input-side token savings: search-before-read, batched tool calls, no redundant re-reads — 9 enforceable rules | −19–20% tokens on multi-step work (5 controlled task pairs); a wash on one-shots | `git clone https://github.com/Skillproofdev/token-discipline ~/.claude/skills/token-discipline` |
| [research-discipline](https://github.com/Skillproofdev/research-discipline) | Verifiable research: live sources over memory, per-claim citations, independent 2-source check, [unverified] flags, adversarial pass — 8 enforceable rules | −59% wrong claims (13.0%→5.4%, 110 claims judged against live primary sources) at ~+10% tokens | `git clone https://github.com/Skillproofdev/research-discipline ~/.claude/skills/research-discipline` |

## Free tools for skill authors

[SKILL.md validator, token calculator, Rules⇄SKILL.md converter](https://skillproof.dev/tools) — all client-side, no signup.

## License

MIT.
