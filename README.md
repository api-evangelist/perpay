# Perpay (perpay)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Perpay is a buy-now-pay-later and credit-building platform that lets consumers shop and pay via automatic payroll deductions. Its internal REST platform supports marketplace checkout, installment plan creation, payroll direct-deposit switching (via Pinwheel), identity and income verification, and credit-bureau reporting to Experian, TransUnion, and Equifax. Perpay operates a closed marketplace — third-party merchant checkout integration is not publicly available; API access is reserved for Perpay's own products and vetted partners.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/perpay/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/perpay/refs/heads/main/apis.yml)

## Tags

- Fintech
- BNPL
- Buy Now Pay Later
- Credit Building
- Payroll Deduction
- Payments
- Consumer Finance

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Perpay Marketplace Checkout API

Internal REST API that powers checkout on the Perpay Marketplace. Handles product ordering, spending-limit enforcement, and installment plan creation for approved consumers. Access is limited to Perpay's own platform.

- **Human URL:** [https://www.perpay.com](https://www.perpay.com)
- **Base URL:** `https://api.perpay.com`

#### Tags

- Checkout
- Marketplace
- Installments
- BNPL

### Perpay Payroll Direct-Deposit API

REST integration layer built on Pinwheel's payroll connectivity API. Supports direct-deposit switching, income and employment verification, and real-time confirmation of paycheck routing updates for 1.5 M+ employer payroll platforms.

- **Human URL:** [https://help.perpay.com/en/articles/11661160-how-perpay-uses-direct-deposit-for-payments](https://help.perpay.com/en/articles/11661160-how-perpay-uses-direct-deposit-for-payments)
- **Base URL:** `https://api.perpay.com`

#### Tags

- Payroll
- Direct Deposit
- Income Verification
- Employment Verification
- Pinwheel

### Perpay Credit Reporting API

Internal API that submits on-time payment history and spending-limit data to Experian, TransUnion, and Equifax for credit-building purposes. Governed by FCRA requirements.

- **Human URL:** [https://help.perpay.com/en/articles/450206-how-perpay-works](https://help.perpay.com/en/articles/450206-how-perpay-works)
- **Base URL:** `https://api.perpay.com`

#### Tags

- Credit Building
- Credit Bureau
- Experian
- TransUnion
- Equifax
- FCRA

## Common Resources

- **Website:** [https://www.perpay.com](https://www.perpay.com)
- **Help Center:** [https://help.perpay.com/en/](https://help.perpay.com/en/)
- **GitHub:** [https://github.com/Perpay](https://github.com/Perpay)
- **LinkedIn:** [https://www.linkedin.com/company/perpay](https://www.linkedin.com/company/perpay)
- **Terms of Service:** [https://perpay.com/legal/terms-and-conditions](https://perpay.com/legal/terms-and-conditions)
- **Privacy Policy:** [https://perpay.com/legal/privacy-policy](https://perpay.com/legal/privacy-policy)
