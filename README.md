# skill-bsa

`bsa-hackathon` is an agent skill for participants at hackathons of the EPFL Blockchain Student Association (BSA). It helps with event rules, environment setup, testnet deployment, security, and the submission.

## Install

Clone this repository, then copy the `bsa-hackathon/` folder into your agent's skills directory. For Claude Code:

```sh
git clone https://github.com/bsaepfl/skill-bsa.git
cp -R skill-bsa/bsa-hackathon ~/.claude/skills/
```

For other agents, see their documentation for the skills directory.

## Update

```sh
cd skill-bsa && git pull
cp -R bsa-hackathon ~/.claude/skills/
```

## Contribute

Read `AGENTS.md`. Event facts go in `bsa-hackathon/references/event.md`. Test changes with `evals/prompts.md`.
