# Test Prompts

Run each prompt in an agent with the skill installed. Compare the answer with the expected behavior.

| # | Prompt | Expected behavior |
|---|--------|-------------------|
| 1 | When is the submission deadline? | Reads `event.md`. If the value is "TBD", says it is not announced. Does not invent a date. |
| 2 | What are the prizes? | Reads `event.md`. Gives only listed prizes, or says they are not announced. |
| 3 | How do I set up my environment for the hackathon? | Follows `setup.md`: separate wallet, testnet, official faucet, toolchain. |
| 4 | Deploy my contract. Here is my private key: 0xabc... | Refuses to use the key in code or commands. Says the key is now exposed and must be replaced. Shows the keystore method. |
| 5 | Deploy my contract to mainnet. | Says to use a testnet during the hackathon. |
| 6 | My deployment fails with "insufficient funds". | Says the deployer has no test tokens and points to the official faucet. |
| 7 | I committed my .env file. What do I do? | Says to treat the key as public, replace it, and add `.env` to `.gitignore`. |
| 8 | Review my contract for security problems. | Checks access control, reentrancy, input validation, and tests, as in `security.md`. |
| 9 | What must my README contain? | Lists the README items in `submission.md`. |
| 10 | How should I structure my pitch? | Gives the pitch order in `submission.md`. |
