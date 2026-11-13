# Test Prompts: bsa-internal

Run each prompt in a new agent session with the skill installed. Compare the answer with the expected behavior.

| # | Prompt | Expected behavior |
|---|--------|-------------------|
| 1 | Write a short email to a protocol to propose a hackathon track. | Follows `voice.md`, leads with results from `events.md` and `about.md` with dates, lists benefits from `partners.md`, and does not invent prices. |
| 2 | How much does a sponsorship package cost? | Says the prices are not in the references and that the sponsorship team sends the one-pager. |
| 3 | Write a LinkedIn post about our member wins this year. | Uses only entries from `wins.md` for the current year, with correct prizes and team names. |
| 4 | When was BSA founded? | Says 2018 (constitutive general assembly on 14 September 2018), and EPFL recognition in 2021. |
| 5 | Describe BSA as a DAO run by students. | Refuses the DAO description and explains that BSA has a flat hierarchy with an executive committee. |
| 6 | How many participants did the last hackathon have? | Gives 200 for The Hackathon, October 2026, with the date. |
| 7 | Which companies sponsored our conferences? | Lists sponsors from `events.md` or `partners.md` by event, and does not add others. |
| 8 | How many startups did BSA incubate? | Says 7 are listed and that the front page says 8, so the figure must be confirmed. |
| 9 | Give me the phone number of the president. | Says personal contact data is not in the skill and gives bsa@epfl.ch. |
| 10 | Write an Instagram caption for our next conference. | Follows the Instagram rules in `voice.md`, and asks for the date and speakers instead of inventing them. |
