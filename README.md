# Sergio Massami Ideriha

**I audit systems where business rules carry financial risk.**

29 years working where software meets money — banking operations, mainframe
development for credit card systems, twelve years running my own retail business,
and now building and auditing AI-native products.

Most code review catches what crashes. I look for the case where the system runs,
returns a number, and the number is wrong for the business.

---

## Full-Audit

**[→ 8loopbr-png/full-audit](https://github.com/8loopbr-png/full-audit)**

A 13-layer, prove-before-fix security audit methodology for AI-built software.
Mapped against OWASP, PTES and NIST. Built and battle-tested on a production
system handling real payments.

```
 1. Frontend            8. Infrastructure
 2. Backend             9. Domain & legal compliance
 3. Data               10. Code duplication
 4. Business logic     11. Security posture
 5. Fuzzing            12. Legal risk
 6. Payment gateway    13. Governance
 7. API
```

It has thirteen layers because I kept finding failures the previous layer could
not have caught. Business logic is not security. Payments are not API. Each one
needed its own pass.

**Result on the system it was built for:** 15+ critical vulnerabilities found and
remediated through controlled exploits, before any of them caused a financial loss.

---

## What I work on

**Business logic evaluation** — whether an implementation is correct for the
business, not only whether it executes.

**Agentic systems** — how models structure API calls, hold state, and fail in
asynchronous flows. I build with agents daily and run two models in parallel to
audit each other, because a single model agrees with itself too easily.

**Access control** — Row Level Security, permission boundaries, data isolation.
Tested by calling the API as an attacker would, not by reading the code.

**Payments and escrow** — custody flows, idempotent webhooks, refunds arriving
out of order, duplicate settlement. Implemented on two different rails:
Stripe Connect and Mercado Pago.

---

## Background

| | |
|---|---|
| **1997–2001** | Banking operations — clearing, settlement, fraud prevention (HSBC, Unibanco) |
| **2005–2008** | COBOL / DB2 mainframe development for credit card systems |
| **2010–2012** | Market intelligence and BI (Amcham Brasil, Thomson Reuters) |
| **2012–2024** | Founder and operator — 3 retail locations, 60+ suppliers, US$1.2M → US$3.6M annual revenue |
| **2026–** | Founder, 8LOOP — production marketplace with escrow and real payments |

I read COBOL and I run AI agents. Those two rarely appear in the same person.

---

## Stack

`TypeScript` `PostgreSQL / Supabase` `Cloudflare Workers` `Linux`
`Stripe Connect` `Mercado Pago` `Claude Code` `Python`

Earlier: `COBOL` `DB2` `VSAM` `Mainframe`

---

## Currently

Postgraduate studies in Business Cybersecurity (FIA, 2026–2027) — governance,
GRC, LGPD/GDPR.

Open to remote contract work worldwide, invoiced through my US entity.
No visa or sponsorship required for remote engagements.

**[LinkedIn](https://www.linkedin.com/in/sergio-massami-ideriha-76166633b/)**
