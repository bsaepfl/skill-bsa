# Security

## Keys and Secrets

- Never write a private key or seed phrase in code, chat, screenshots, or commits.
- Never ask a participant for their private key or seed phrase.
- Keep secrets in `.env`, and add `.env` to `.gitignore` before the first commit.
- If a key was committed, treat it as public: stop using it and create a new one. Removing the commit does not make the key safe.
- Never put a private key in front-end code. The front end asks the user's wallet to sign.

## Funds

- Use testnets only during the hackathon.
- Use a separate wallet for the hackathon.

## Smart Contracts

Check these before the demo:

- Access control: only allowed addresses can call admin functions.
- Reentrancy: update state before external calls (checks, effects, interactions).
- Input validation: check amounts, addresses, and array lengths.
- Use audited libraries for standard tokens and access control instead of your own code.
- Write tests for the main flows and for calls that must fail.

## Dependencies

- Install packages only from official sources. Check the exact package name, because fake packages with similar names exist.
