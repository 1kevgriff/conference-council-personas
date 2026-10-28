# Conference council personas

A reusable panel of fictional stakeholders for pressure-testing conference materials: sponsor prospectuses, ticket pages, CFPs, outreach emails, and pricing copy.

These personas started as planning archetypes for a regional one-day developer conference. They are written to be event-agnostic so other organizers can reuse and extend them. They are not real people or organizations.

## Why a council

One organizer voice misses objections. A council of simulated buyers and sponsors will argue with your draft the way a real room would: price, approval lag, list-sharing, ROI, public-benefit rules, unbilled days, and "why this region."

Use them with any LLM. Paste a persona's prompt block, attach your draft, and ask what would make them buy, sign, or walk away.

## Personas

### Ticket buyers

| Persona | Role | File |
| --- | --- | --- |
| Sam | Independent freelancer / solo consultant | [sam-independent.md](personas/sam-independent.md) |
| Dana | Full-time employed developer (nine-to-fiver) | [dana-nine-to-fiver.md](personas/dana-nine-to-fiver.md) |
| Marcus | Developer between jobs | [marcus-between-jobs.md](personas/marcus-between-jobs.md) |
| Aaliyah | Adult college student in a computing program | [aaliyah-college-student.md](personas/aaliyah-college-student.md) |

### Sponsors

| Persona | Role | File |
| --- | --- | --- |
| Connor | Partner at a local consulting firm | [connor-consulting-firm.md](personas/connor-consulting-firm.md) |
| Priya | Engineering lead at a regional product company | [priya-product-company.md](personas/priya-product-company.md) |
| Rick | Technical recruiter at a staffing agency | [rick-staffing-firm.md](personas/rick-staffing-firm.md) |
| Helen | IT director at a regional hospital system | [helen-health-care.md](personas/helen-health-care.md) |
| Mike | Engineering manager at a defense contractor | [mike-defense.md](personas/mike-defense.md) |
| Denise | Economic-development manager (local government) | [denise-local-government.md](personas/denise-local-government.md) |
| Jordan | DevRel manager at a national developer-tool vendor | [jordan-developer-tool-vendor.md](personas/jordan-developer-tool-vendor.md) |
| Grant | Senior eng manager at a large regional employer | [grant-large-employer.md](personas/grant-large-employer.md) |
| Tamara | Outreach coordinator at an education / workforce program | [tamara-education.md](personas/tamara-education.md) |
| Bobby | Small local business owner / community supporter | [bobby-community-supporter.md](personas/bobby-community-supporter.md) |

## Suggested panels

Run a draft past a small panel instead of everyone at once.

### Ticket buyers

Sam · Dana · Marcus · Aaliyah · Tamara

Good for ticket pages, price calendars, scholarship copy, and student offers.

### Small budgets

Connor · Bobby · Tamara · Priya · Jordan

Good for entry and mid-tier sponsor packages, community tiers, and in-kind asks.

### Big-ticket

Denise · Helen · Grant · Mike · Jordan

Good for top-tier prospectus pages, payment terms, and long-approval workflows.

### Hiring

Rick · Priya · Marcus · Mike · Grant

Good for recruiting benefits, opt-in ribbons, list-sharing policy, and "looking for work" copy.

## How to use with any LLM

1. Pick a persona file (or a panel above).
2. Copy the **How to prompt them** block into your chat.
3. Paste the draft you want reviewed (prospectus PDF text, ticket page, email, CFP).
4. Ask a concrete question, for example:
   - What would make you buy or walk away?
   - What is unclear or oversold?
   - What would you need before you take this to your budget holder?
5. Optionally run the same draft through a second persona and compare objections.

Keep answers in character. Discard anything that invents real company or city facts.

## Persona template

New personas should follow [TEMPLATE.md](TEMPLATE.md):

- Role and short background
- Budget and decision power
- What they care about
- Objections
- A ready-to-paste LLM prompt
- Optional organizer notes (privacy, consent, guardrails)

## Contributing

1. Fork the repo (or open a branch).
2. Copy `TEMPLATE.md` to `personas/<slug>.md`.
3. Keep the persona fictional. Do not base a file on a real named person or a real employer's private details.
4. Stay event-agnostic. A short note that the set began at a regional developer conference is fine; do not hard-code one event's prices, package names, or internal deals.
5. No private data: no real emails, phone numbers, home addresses, unpublished sponsor pipelines, or internal repo paths.
6. Open a pull request. Say which panel(s) the persona belongs on, if any.

## License

[MIT](LICENSE) · Copyright (c) 2026 Kevin Griffin
