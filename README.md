# hCaptcha (hcaptcha)

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
