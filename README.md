# hCaptcha (hcaptcha)

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

hCaptcha, operated by Intuition Machines, is a privacy-focused CAPTCHA
and bot-defense platform used as a drop-in replacement for Google
reCAPTCHA. The free Publisher and Pro tiers offer a JavaScript widget
and a server-side /siteverify endpoint that issue and verify single-use
tokens. The Enterprise tier (hCaptcha Enterprise) adds advanced bot
detection, account defense, MFA, machine-learning fraud signals, and
management APIs. hCaptcha is broadly integrated into web frameworks and
CMS platforms (React, Vue, Angular, Node/Express, WordPress, Magento)
and ships first-party mobile SDKs for iOS and Android.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hcaptcha/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hcaptcha/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Public

## Tags

- CAPTCHA
- Bot Defense
- Privacy
- hCaptcha
- Intuition Machines
- Account Defense
- Enterprise Security

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### hCaptcha Siteverify API

The /siteverify endpoint validates an hCaptcha response token
submitted by a browser. The server POSTs the token, secret key,
and optional remote IP, and receives a JSON response indicating
success, hostname, timestamp, score (Enterprise), and any error
codes. This is the canonical server-side check that gates form
submissions and API calls behind an hCaptcha challenge.

- **Human URL:** [https://docs.hcaptcha.com/](https://docs.hcaptcha.com/)
- **Base URL:** `https://api.hcaptcha.com`

#### Tags

- Siteverify
- Token Verification
- Server-Side

#### Properties

- [Documentation](https://docs.hcaptcha.com/)
- [API Reference](https://docs.hcaptcha.com/#verify-the-user-response-server-side)
- [Postman Collection](collections/hcaptcha.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcaptcha.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### hCaptcha JavaScript Widget

The hCaptcha JS widget renders the visible or invisible challenge
on a page and produces a response token on success. Developers
include a script tag pointing at js.hcaptcha.com/1/api.js and place
a div with data-sitekey, optionally configuring theme, size,
callback, and language. Frontend wrappers exist for React, Vue,
and Angular.

- **Human URL:** [https://docs.hcaptcha.com/configuration](https://docs.hcaptcha.com/configuration)
- **Base URL:** `https://js.hcaptcha.com/1/api.js`

#### Tags

- JavaScript
- Widget
- Frontend
- Challenge

#### Properties

- [Documentation](https://docs.hcaptcha.com/configuration)
- [Script U R L](https://js.hcaptcha.com/1/api.js)
- [S D K React](https://github.com/hCaptcha/react-hcaptcha)
- [S D K Vue](https://github.com/hCaptcha/vue-hcaptcha)
- [S D K Angular](https://github.com/hCaptcha/ng-hcaptcha)
- [Postman Collection](collections/hcaptcha.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcaptcha.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### hCaptcha Invisible

Invisible hCaptcha runs the challenge in the background and only
surfaces a visible puzzle when risk requires it. It is configured
via the same widget script and an additional data-size="invisible"
attribute, enabling no-friction verification on most legitimate
users.

- **Human URL:** [https://docs.hcaptcha.com/invisible](https://docs.hcaptcha.com/invisible)
- **Base URL:** `https://js.hcaptcha.com/1/api.js`

#### Tags

- Invisible
- Frictionless
- Risk-Based

#### Properties

- [Documentation](https://docs.hcaptcha.com/invisible)
- [Postman Collection](collections/hcaptcha.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcaptcha.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### hCaptcha Mobile SDKs

hCaptcha publishes native iOS and Android SDKs (with React Native
and Flutter wrappers) so mobile apps can present the same risk-based
challenges as the web widget and obtain response tokens that the
server verifies via /siteverify.

- **Human URL:** [https://docs.hcaptcha.com/mobile_app_sdks](https://docs.hcaptcha.com/mobile_app_sdks)
- **Base URL:** `https://docs.hcaptcha.com/mobile_app_sdks`

#### Tags

- Mobile
- iOS
- Android
- SDK

#### Properties

- [Documentation](https://docs.hcaptcha.com/mobile_app_sdks)
- [S D Ki O S](https://github.com/hCaptcha/hcaptcha-ios-sdk)
- [S D K Android](https://github.com/hCaptcha/hcaptcha-android-sdk)
- [Postman Collection](collections/hcaptcha.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcaptcha.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### hCaptcha Enterprise

hCaptcha Enterprise extends the core challenge with advanced bot
detection, account defense (ATO and fake-account protection), MFA
and pull-based SMS, fraud signals, and management APIs for
provisioning sitekeys, retrieving analytics, and tuning policies.
Access is gated to Enterprise customers.

- **Human URL:** [https://www.hcaptcha.com/enterprise](https://www.hcaptcha.com/enterprise)
- **Base URL:** `https://api.hcaptcha.com`

#### Tags

- Enterprise
- Account Defense
- Fraud
- Management API

#### Properties

- [Product Page](https://www.hcaptcha.com/enterprise)
- [Documentation](https://docs.hcaptcha.com/enterprise)
- [Postman Collection](collections/hcaptcha.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcaptcha.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.hcaptcha.com/)
- [Documentation](https://docs.hcaptcha.com/)
- [Enterprise](https://www.hcaptcha.com/enterprise)
- [Signup](https://www.hcaptcha.com/signup-interstitial)
- [Pricing](https://www.hcaptcha.com/#pricing)
- [GitHub Organization](https://github.com/hCaptcha)
- [Blog](https://www.hcaptcha.com/post)
- [Privacy](https://www.hcaptcha.com/privacy)
- [Status](https://status.hcaptcha.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
