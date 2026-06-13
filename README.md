# CourtListener

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
