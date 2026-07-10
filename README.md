# SkillProof Skills

Skills built and bench-tested by [SkillProof](https://skillproof.dev) — the tested Claude skills directory. We test other people's skills for a living ([public methodology](https://skillproof.dev/methodology)); ours go through the same protocol, and every skill ships with a measured benchmark, not marketing claims.

Each skill lives in its own repo — one `git clone` installs it.

## Skills

| Skill | What it does | Measured result | Install |
|---|---|---|---|
| [seo-translator](https://github.com/Skillproofdev/seo-translator) | SEO-aware, human-sounding translation: per-market registers, never-translate list, anti-AI pass | 76k tokens / 4m53s per language (2,900-word article) | `git clone https://github.com/Skillproofdev/seo-translator ~/.claude/skills/seo-translator` |
| [token-discipline](https://github.com/Skillproofdev/token-discipline) | Input-side token savings: search-before-read, batched tool calls, no redundant re-reads — 9 enforceable rules | −19–20% tokens on multi-step work (5 controlled task pairs); a wash on one-shots | `git clone https://github.com/Skillproofdev/token-discipline ~/.claude/skills/token-discipline` |
| [research-discipline](https://github.com/Skillproofdev/research-discipline) | Verifiable research: live sources over memory, per-claim citations, independent 2-source check, [unverified] flags, adversarial pass — 8 enforceable rules | −59% wrong claims (13.0%→5.4%, 110 claims judged against live primary sources) at ~+10% tokens | `git clone https://github.com/Skillproofdev/research-discipline ~/.claude/skills/research-discipline` |
| [review-discipline](https://github.com/Skillproofdev/review-discipline) | Code review that proves every finding (demonstrated failure path or [suspicion]), breadth-before-depth | 18.5/21 seeded bugs caught vs 17 baseline, 0 false positives vs 1, ~100% demonstrated failure paths | `git clone https://github.com/Skillproofdev/review-discipline ~/.claude/skills/review-discipline` |
| [email-discipline](https://github.com/Skillproofdev/email-discipline) | Emails people answer: one goal, subject-as-ask, word budgets, no AI fluff | 'would reply now' 9/12 vs 3/12 baseline; mechanical pass 12/12 vs 2/12 | `git clone https://github.com/Skillproofdev/email-discipline ~/.claude/skills/email-discipline` |
| [commit-discipline](https://github.com/Skillproofdev/commit-discipline) | Commit messages that match the diff: Conventional Commits, why-not-what, breaking footers | diff coverage 97% vs 83%, 0 fabrications vs 1, split-detect 2/2 vs 0/2 | `git clone https://github.com/Skillproofdev/commit-discipline ~/.claude/skills/commit-discipline` |
| [api-discipline](https://github.com/Skillproofdev/api-discipline) | REST/OpenAPI design that stays validator-clean and audits its own consistency | 0 validator errors vs 18 baseline, 0 consistency violations vs 6 | `git clone https://github.com/Skillproofdev/api-discipline ~/.claude/skills/api-discipline` |
| [summary-discipline](https://github.com/Skillproofdev/summary-discipline) | Faithful summaries: numbers verbatim, contradictions flagged not silently resolved | 3/3 planted contradictions caught vs 0/3; 2 critical omissions vs 10 | `git clone https://github.com/Skillproofdev/summary-discipline ~/.claude/skills/summary-discipline` |
| [readme-discipline](https://github.com/Skillproofdev/readme-discipline) | READMEs grounded in the code: every claim traces to a file, every command runs | section completeness 18/18 vs 14, blind preference 3/3 repos, trust 4.67 vs 3.67 | `git clone https://github.com/Skillproofdev/readme-discipline ~/.claude/skills/readme-discipline` |
| [changelog-discipline](https://github.com/Skillproofdev/changelog-discipline) | Changelogs traceable to real commits: nothing invented, breaking changes kept | commit traceability 87% vs 6%, format 30/36 vs 13/36 (fabrication a tie — both honest) | `git clone https://github.com/Skillproofdev/changelog-discipline ~/.claude/skills/changelog-discipline` |
| [prompt-discipline](https://github.com/Skillproofdev/prompt-discipline) | Prompt improvement that diagnoses before rewriting: minimal-diff + A/B test plan | task success 0.90 vs 0.70 original, half the prompt bloat (n=1, honest caveat) | `git clone https://github.com/Skillproofdev/prompt-discipline ~/.claude/skills/prompt-discipline` |
| [text-humanizer](https://github.com/Skillproofdev/text-humanizer) | Remove AI tells while freezing every fact: rebuild the prose in a human voice, claim set immutable | beat the raw baseline on blind preference 8–4 (published 3 honest failures first); tells 2 vs 4, facts 129/130 | `git clone https://github.com/Skillproofdev/text-humanizer ~/.claude/skills/text-humanizer` |

## Free tools for skill authors

[SKILL.md validator, token calculator, Rules⇄SKILL.md converter](https://skillproof.dev/tools) — all client-side, no signup.

## License

MIT.
