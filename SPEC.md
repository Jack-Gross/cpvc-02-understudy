# TARGET

Before choosing a layout, say what this reader cannot understand from the raw
profile. Fill the brackets; keep the useful defaults. Six lines, not a feature list.

- **Thing:** Showcase using profile-consumer.json to answer "Which project should this recruiter ask about to see growth/GTM thinking, not just code?"
- **Audience:** A hiring manager at an early-stage startup, reviewing my GitHub for 5 minutes before a Growth/GTM interview, deciding what to ask about. Raw JSON shows 5 repos with stars and languages but nothing about which one shows growth thinking versus pure engineering.
- **Requirements:** One supported claim, its exact source fields, and one useful next action. Claim: cart-abandon should lead for a Growth/GTM interview because its description ("Recovery email timing experiments") is the only repo tied to a growth lever (conversion recovery), even though it has fewer stars than storefront-kit (repos[].name, description, stargazers_count, topics; reference date 2026-09-11). Next action: ask "What did you test in the recovery email timing, and what did you learn about when to send?"
- **Guardrails:** Fictional data only; unchanged fixtures; one HTML file; no frameworks, external assets, live APIs, keys or invented outcomes.
- **Experience:** First, one sentence naming cart-abandon as the lead and the growth-relevant question to ask. Next, why it's the pick despite fewer stars, with exact fields beside the claim. Last, the other 4 repos in one plain line each, for context, flagging shopify-theme-fork as a fork with no description. One muted green accent on the lead project only; single ~720px column, reads like a one-page interview prep note. Readable on a laptop; mobile is not required for this session.
- **Test:** A neighbor can explain the answer and next action in ten seconds; I can trace the claim to JSON, see my AGENTS rule followed, use the page in Codex's desktop side-browser preview, and check the page before approving a merge.
