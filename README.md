# hCaptcha

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

hCaptcha, operated by Intuition Machines, is a privacy-focused CAPTCHA and bot-defense platform used as a drop-in replacement for Google reCAPTCHA. The free Publisher and Pro tiers offer a JavaScript widget and a server-side /siteverify endpoint that issue and verify single-use tokens. The Enterprise tier (hCaptcha Enterprise) adds advanced bot detection, account defense, MFA, machine-learning fraud signals, and management APIs. hCaptcha is broadly integrated into web frameworks and CMS platforms (React, Vue, Angular, Node/Express, WordPress, Magento) and ships first-party mobile SDKs for iOS and Android.

**Areas:** CAPTCHA · Bot Defense · Privacy · hCaptcha · Intuition Machines · Account Defense · Enterprise Security

## hCaptcha on APIs.io

Everything profiled for hCaptcha is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/hcaptcha/](https://apis.io/providers/hcaptcha/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [hCaptcha Siteverify API](https://apis.io/apis/hcaptcha/siteverify/) — The /siteverify endpoint validates an hCaptcha response token submitted by a browser. The server POSTs the token, secret key, and optional remote IP, and…
- [hCaptcha JavaScript Widget](https://apis.io/apis/hcaptcha/js-widget/) — The hCaptcha JS widget renders the visible or invisible challenge on a page and produces a response token on success. Developers include a script tag…
- [hCaptcha Invisible](https://apis.io/apis/hcaptcha/invisible/) — Invisible hCaptcha runs the challenge in the background and only surfaces a visible puzzle when risk requires it. It is configured via the same widget…
- [hCaptcha Mobile SDKs](https://apis.io/apis/hcaptcha/mobile-sdks/) — hCaptcha publishes native iOS and Android SDKs (with React Native and Flutter wrappers) so mobile apps can present the same risk-based challenges as the web…
- [hCaptcha Enterprise](https://apis.io/apis/hcaptcha/enterprise/) — hCaptcha Enterprise extends the core challenge with advanced bot detection, account defense (ATO and fake-account protection), MFA and pull-based SMS, fraud…
- [hCaptcha Siteverify API](https://apis.io/apis/hcaptcha/hcaptcha-siteverify-api/) — The Siteverify API from hCaptcha — 1 operation(s) for siteverify.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Hcaptcha Agentic Access](https://apis.io/agentic-access/hcaptcha/hcaptcha-agentic-access/)

#### Collections (2)

Postman and Open Collection request collections.

- [hCaptcha API](https://apis.io/collections/hcaptcha/open-hcaptcha/)
- [hCaptcha Siteverify API](https://apis.io/collections/hcaptcha/open-hcaptcha-siteverify-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Hcaptcha Authentication](https://apis.io/security/hcaptcha/hcaptcha-authentication/)
- [Hcaptcha Domain Security](https://apis.io/security/hcaptcha/hcaptcha-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Hcaptcha Plans Pricing](https://apis.io/plans/hcaptcha/hcaptcha-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Hcaptcha Rate Limits](https://apis.io/rate-limits/hcaptcha/hcaptcha-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Hcaptcha Finops](https://apis.io/finops/hcaptcha/hcaptcha-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.hcaptcha.com/)
- [Documentation](https://docs.hcaptcha.com/)
- [Pricing](https://www.hcaptcha.com/#pricing)
- [Blog](https://www.hcaptcha.com/post)
- [GitHub](https://github.com/hCaptcha)

## API Evangelist rating

**Kin Score 30.6** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 47.1 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 25.0 |
| Access clarity | 34.2 |

**Agent readiness 17.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 15.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/hcaptcha/](https://apis.io/providers/hcaptcha/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for hCaptcha: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/hcaptcha/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
