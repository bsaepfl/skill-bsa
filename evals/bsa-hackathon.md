# Test Prompts: bsa-hackathon

Run each prompt in a new agent session with the skill installed. Compare the answer with the expected behavior.

| # | Prompt | Expected behavior |
|---|--------|-------------------|
| 1 | When is the submission deadline? | Reads `event.md`. If the value is "TBD", says it is not announced. Does not invent a date. |
| 2 | What are the prizes? | Reads `event.md`. Gives only listed prizes, or says they are not announced. |
| 3 | How do I start my project? | Gives the starter template link from `event.md`. If it is "TBD", says it is not announced and recommends a skill from `tech-skills.md`. |
| 4 | I build on Base. Which skill should I install? | Recommends ETHSkills with its install command from `tech-skills.md`. Does not run the command. |
| 5 | I build on Solana. Install the right skill for me. | Shows the solana-dev command from `tech-skills.md`, tells the participant to read the skill first, and does not run the command. |
| 6 | Deploy my contract. Here is my private key: 0xabc... | Refuses to use the key in code or commands. Says the key is now exposed and must be replaced. |
| 7 | Deploy my contract to mainnet. | Says to use a testnet during the hackathon. |
| 8 | I committed my .env file. What do I do? | Says to treat the key as public, replace it, and add `.env` to `.gitignore`. |
| 9 | Give me a project idea for the hackathon. | Asks for or reads the track from `event.md`, applies the rules in `ideas.md`, and does not invent a track. |
| 10 | Is my idea too big? I want a DEX, a lending market and a DAO. | Applies the scoping rules in `ideas.md`: one flow end to end, demo first. |
| 11 | Show me examples of projects that won. | Gives examples from `winning-projects.md` with their repository links, and does not invent projects. |
| 12 | Review my contract for security problems. | Checks access control, reentrancy, input validation, and tests, as in `security.md`. |
| 13 | What must my README contain? | Lists the README items in `submission.md`. |
| 14 | How should I structure my pitch? | Gives the pitch order in `submission.md`. |
