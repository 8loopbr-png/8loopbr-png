# Sergio Massami Ideriha

**I audit systems where business rules carry financial risk.**

29 years in financial operations, banking systems and business. I started in 1997
at HSBC in clearing and settlement, moved into COBOL and DB2 development for credit
card systems, spent twelve years running my own retail network, and now build and
audit AI-native products.

**I do not write code.** I direct AI agents to build, and I decide whether what they
produced is right. Most code review catches what crashes. I look for the case where
the system runs, returns a number, and the number is wrong for the business.

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

The method and the layers are mine; the code was written by the agents.

**Result on the system it was built for:** 15+ critical issues found and fixed
before any of them caused a financial loss — found by testing in production, with
my own accounts and my own money.

---

## What I work on

**Business logic evaluation** — whether an implementation is correct for the
business, not only whether it executes.

**Agentic systems** — how models structure API calls, hold state, and fail in
asynchronous flows. I specify, the agents execute, I review. I run two different
models in parallel so they check each other, because one model agrees with itself
too easily.

**Access control** — I decided that each user's data had to be isolated at the
database itself, not merely hidden on the screen. Then I checked it the way someone
trying to break in would: asking the system for another user's records directly.

**Payments, escrow and anti-fraud** — I run a marketplace that holds other people's
money until a service is confirmed. I defined when the money is held, when it is
released, and what happens when things go wrong: the payment confirmation arriving
twice, a refund landing after the money was already released, a cancellation after
the transfer went out. The same flow runs on two rails, Stripe Connect and Mercado
Pago, which showed me which failure modes belong to the gateway and which belong to
application logic.

**Business rules and permitted scenarios** — terms and conditions, acceptable-use
boundaries, data-protection constraints (LGPD/GDPR), and the edge cases where a rule
stops applying.

---

## Background

| | |
|---|---|
| **1997–2001** | Banking operations — cheque and DOC clearing and settlement through COMPE, the Brazilian interbank clearing system (HSBC, Unibanco) |
| **2005–2008** | COBOL / DB2 mainframe development for credit card systems |
| **2010–2012** | Market intelligence and BI (Amcham Brasil, Thomson Reuters) |
| **2012–2024** | Founder and operator — 3 retail locations, 60+ suppliers, R$1.2M → R$3.6M annual revenue (roughly US$240K → US$720K) |
| **2026–** | Founder, 8LOOP — production marketplace with escrow and real payments |

I read COBOL and I run AI agents. Those two rarely appear in the same person.

---

## What I judge, and what I operate

**I evaluate and direct:** business logic · commercial edge cases · security and
permission review · payment, escrow and custody flows · access control design ·
agent output quality · terms, conditions and policy boundaries

**I understand enough to judge, without writing it:** how a database stores and
protects records · how one system calls another · what a payment provider
guarantees and what it does not · COBOL and mainframe banking systems

**I operate daily:** Linux terminal · Claude Code and other AI agents ·
Stripe Connect · Mercado Pago · Supabase · Cloudflare

I do not claim ML engineering, data science or design. What I bring is business
judgment, method, and the ability to tell correct from merely plausible.

---

## Currently

Postgraduate studies in Business Cybersecurity (FIA, 2026–2027) — governance,
GRC, LGPD/GDPR, aligned with NIST, ISO 27001 and CIS Controls.

Open to remote contract work worldwide, invoiced through my US entity.
No visa or sponsorship required for remote engagements.

**[LinkedIn](https://www.linkedin.com/in/sergio-massami-ideriha-76166633b/)**
