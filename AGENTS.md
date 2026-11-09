# unfloat site: instructions for agents

Read `../ops/AGENTS.md` first when it exists: the project's records, policy and session routine live there. This repository is unfloat's public front door, github.com/unfloat-org/unfloat.

- Everything here is public the moment it is pushed. Push only files Daniil approved (D-020, D-024).
- Text is in Daniil's voice (`../ops/voice.md`) and goes through the humanizer skill before Daniil sees it. Keep the safety line wherever health comes up: sudden new floaters, flashes, or a shadow or curtain over vision need a same-day eye exam.
- No person or draft IDs, no names of people or institutions who have not agreed to be named, no links into private repositories. `uo check --repo .` (pre-commit hook and CI) checks IDs, links and files; `brand/*.png` are the only images allowed (`.unfloat.toml`).
- After a push, record it in ops (`uo log post - "..."`) and commit there.
