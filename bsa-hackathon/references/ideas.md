# Choosing and Scoping an Idea

BSA hackathons last 30 to 36 hours. These rules come from projects that won prizes (see `winning-projects.md`).

## Choose

1. **Pick the track first, then the idea.** Most prizes are track prizes. Read the sponsor's track description in `event.md` and build on the sponsor's newest or most specific feature. A generic app that touches the sponsor's chain rarely wins its track.
2. **Start from a real, specific problem.** Name who has the problem and show evidence: an incident, a number, a regulation. A project that starts with "on 25 August, $37M of debt became eligible for liquidation because..." is stronger than one that starts with "DeFi is risky".
3. **Answer "why a blockchain?"** Judges ask it. Good answers: no trusted intermediary, open settlement, verifiable state, programmable money. If a database does the same job, change the idea.
4. **Check that it is new.** Search the sponsor's past hackathon winners and their ecosystem. If it already exists, add the part that is missing, or choose another idea.

## Scope

1. **Build one flow end to end.** One user action that works fully, from front end to chain, is better than five features that half work.
2. **Fix the demo first.** Write the 2-minute demo script before you write code. Build only what the demo shows.
3. **Use the starter template** if `event.md` lists one. It saves the first hours of setup.
4. **Cut at the halfway point.** At half of the hacking time, remove every feature that is not on the demo path.
5. **Leave the last hours for the submission:** deployment, README, video, and pitch practice (see `submission.md`).

## Patterns That Won

- **Hide the blockchain from the user:** passkeys instead of seed phrases, human-readable names instead of addresses, sponsored gas.
- **Regulation and identity:** credential-gated access, EU digital identity wallets, selective disclosure of attributes, MiCA compliance.
- **AI agents with hard limits:** the model only interprets the request, and fixed code, a smart contract or a hardware wallet decides whether funds move.
- **Privacy for finance:** hidden bets, confidential strategy execution, zero-knowledge deposits.
- **Payments for machines:** pay-per-call APIs (for example x402) that AI agents can use without an account.
