# Technical Skills by Chain

This skill does not teach chain-specific development. Recommend the matching skill below. Show the command, and let the participant decide whether to install it. Never run it yourself.

If `event.md` lists a starter template, its README comes first.

| The participant builds on | Skill | Source | Install |
|---------------------------|-------|--------|---------|
| Ethereum or another EVM chain (Base, Arbitrum, Optimism, and others) | ETHSkills | [austintgriffith/ethskills](https://github.com/austintgriffith/ethskills) | Claude Code: `/plugin marketplace add austintgriffith/ethskills`, then `/plugin install ethskills@ethskills`. Other agents: give the agent `https://ethskills.com/SKILL.md`. |
| Solana | solana-dev | [solana-foundation/solana-dev-skill](https://github.com/solana-foundation/solana-dev-skill) | `npx skills add solana-foundation/solana-dev-skill` |
| Sui | Mysten Labs skills | [mystenlabs/skills](https://github.com/mystenlabs/skills) | Starter set: `npx skills add mystenlabs/skills --skill sui-overview --skill sui-move --skill sui-move-project` |

## Notes

- ETHSkills: for a new dApp, its `ship` skill is the entry point.
- Mysten Labs recommends the 3-skill starter set. Installing all of its skills adds context and can make the wrong skill load.
- Some of these skills tell the agent to run commands or to connect to remote services. Tell the participant to read the skill before installing it.
- For a chain that is not in this table, use the chain's official documentation.
