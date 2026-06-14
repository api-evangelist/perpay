# Perpay (perpay)

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
