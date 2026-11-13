# skill-bsa

Agent skills of the EPFL Blockchain Student Association (BSA).

| Skill | For | Content |
|-------|-----|---------|
| `bsa-hackathon` | Participants at BSA hackathons | Event facts, idea scoping, winning projects, links to chain-specific skills, security, submission. |
| `bsa-internal` | BSA members, mainly communication and sponsorship | History, events, partners, member wins, startups, research, brand voice. |

This repository is public, but `bsa-internal` is meant for internal use.

## Install

Clone this repository, then copy the skill folder into your agent's skills directory. For Claude Code:

```sh
git clone https://github.com/bsaepfl/skill-bsa.git
cp -R skill-bsa/bsa-hackathon ~/.claude/skills/
cp -R skill-bsa/bsa-internal ~/.claude/skills/
```

For other agents, see their documentation for the skills directory.

## Update

```sh
cd skill-bsa && git pull
cp -R bsa-hackathon bsa-internal ~/.claude/skills/
```

## Contribute

Read `AGENTS.md`. Event facts go in `bsa-hackathon/references/event.md`. Test changes with the prompts in `evals/`.
