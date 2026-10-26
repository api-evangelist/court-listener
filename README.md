# CourtListener

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

CourtListener is a free legal research platform operated by the [Free Law Project](https://free.law/), a nonprofit working to make the legal ecosystem more equitable and competitive. It provides a comprehensive REST API for accessing US court opinions, PACER docket data, oral arguments, judge biographical data, financial disclosures, and citation networks from federal and state courts.

## What the API Covers

- **Case Law** — Over 9 million court opinions from federal and state courts dating back to 2009
- **PACER Data** — Approximately 500 million items from the federal PACER court filing system via the RECAP Archive
- **Oral Arguments** — 3.4+ million minutes of oral argument audio, the largest internet collection
- **Judge Data** — Biographical records for 16,000+ federal and state judges
- **Financial Disclosures** — Judge financial disclosure documents
- **Citation Analysis** — Citation lookup and citation network visualization
- **Search and Alerts** — Full-text search API and email/webhook alerts for cases and search terms

## API Details

- **Base URL:** `https://www.courtlistener.com/api/rest/v4/`
- **Version:** v4.4
- **Authentication:** Token (recommended), Cookie/Session, or HTTP Basic
- **Formats:** JSON (default), HTML, XML

## Membership Plans

| Tier | Price | Rate Limits |
|------|-------|-------------|
| Free | $0 | 5/min, 50/hr, 125/day |
| Tier 1 | $10/mo or $100/yr | 10/min, 75/hr, 300/day |
| Tier 2 | $25/mo or $250/yr | 15/min, 150/hr, 600/day |
| Tier 3 | $50/mo or $500/yr | 20/min, 250/hr, 1,000/day |
| Tier 4 | $100/mo or $1,000/yr | 25/min, 300/hr, 1,400/day |
| EDU | Free (.edu email) | Tier 1 limits |

## Resources

- [CourtListener Website](https://www.courtlistener.com/)
- [API Documentation](https://wiki.free.law/c/courtlistener/help/api/rest/v4/overview)
- [Membership & Pricing](https://free.law/membership)
- [GitHub Organization](https://github.com/freelawproject)
- [Python SDK](https://github.com/freelawproject/courtlistener-api-client)
- [Free Law Project Blog](https://free.law/blog/)

## Repository Contents

- `apis.yml` — APIs.json 0.19 profile for CourtListener
- `plans/court-listener-plans-pricing.yml` — Detailed membership plan and pricing information
- `rate-limits/court-listener-rate-limits.yml` — API rate limit specifications per tier
- `finops/court-listener-finops.yml` — FinOps guidance for managing API costs

---

Maintained by [Kin Lane](mailto:kin@apievangelist.com) / [API Evangelist](https://apievangelist.com)
