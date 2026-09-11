# TARGET: today's build

Choose the idea, person, interaction, and visual direction. The agent can help phrase and save your decisions after you approve them. The provided scope and review safeguards stay in place.

- **Thing:** A one-page Fantasy Football Trade Analyzer where players choose who they give and receive, select a scoring mode, get a fairness grade, and see suggestions to balance the deal.
- **Audience:** Fantasy football players deciding whether a proposed trade is fair and worth accepting.
- **Requirements:** One working primary interaction; players can select a PPR, half-PPR, or standard scoring mode; selected trade sides, fairness grade, player values, and balancing suggestions are understandable; honor my approved standing rule in AGENTS.md.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Use a locally bundled, clearly dated player-value snapshot; label sample or illustrative data. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** A clean, easy-to-understand comparison page with Giving and Receiving player selections beside a prominent trade grade and concise explanation.
- **Test:** I can select players for both sides, choose a scoring mode, receive a trade grade and suggested adjustment, check that an incomplete trade is handled clearly, and point to my standing rule's effect in the actual preview. After I approve and merge, the same registered Pages URL works.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
