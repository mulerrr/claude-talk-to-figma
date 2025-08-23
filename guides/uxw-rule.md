# Voice & Tone Guide

## Meta
- **Version:** 1.0.0
- **Updated at:** 2025-08-16
- **Owner:** Design Lab Â· UX Writing
- **Audience locales:** id-ID, en-US
- **Priority order:** compliance → clarity → actionability → consistency → tone → brand

---

## Voice
**Principles:** Warm, Concise, Trustworthy, Human, not chatty, Conversational, Helpful, encouraging

**Do**
- Use everyday words
- Active voice
- One idea per sentence

**Don’t**
- Jargon
- Shamey/blaming phrasing
- Overpromising outcomes

---

## Tone Ladder
| State | Tone |
|---|---|
| success | brief, appreciative |
| neutral | matter-of-fact, minimal |
| warning | calm, solution-first |
| error_sensitive | empathetic, no blame, clear next step |
| high_risk | reassuring, transparent about limits |

---

## Lexicon
### Preferred terms
| Term | Use |
|---|---|
| PIN | PIN |
| OTP | kode OTP |
| Sign in | Masuk |
| Log out | Keluar |

### Banned terms
Proceed, OK, Password untuk PIN, Gagal total

### Casing
- **Buttons:** Title Case in Indonesian, Sentence case in Indonesian, don't more tha 5 words
- **Labels:** Sentence case

---

## Accessibility & Readability
- **Reading level:** G6-8
- **Inclusive language:** true

### Numeracy & Format
| Locale | Date | Time | Number |
|---|---|---|---|
| id-ID | DD/MM/YYYY | 24h | 1.234,56 |
| en-US | MM/DD/YYYY | 12h | 1,234.56 |

---

## Negative Case Policy
**Steps**
1. Acknowledge briefly
2. Neutral cause (no blame)
3. Offer one next step
4. Set expectation (time/limits)

**Phrasing**
- **Avoid:** Kamu salah memasukkanâ€¦, Gagal karena kamuâ€¦
- **Prefer:** Kode tidak cocok, Tidak dapat diproses saat ini

---

## Compliance
- **Privacy**
  - Do not expose personal data in messages
  - Never confirm sensitive info in errors
- **Legal required clauses:** (none listed)
- **Must not claim:** Guaranteed approval, Instant recovery

---

## Evaluation Requirements
- **Heuristics:** clarity, empathy, actionability, consistency, a11y
- **Output variants:** short, standard, extra_clear
- **Fit checks:** character_limits, tone_match, reading_level, placeholder_safety
- **Edge states:** empty, error, offline, rate_limited, permission, payment_fail

---

## Telemetry
- **Primary:** task_completion, error_recovery_rate
- **Secondary:** resend_click_rate, support_contact_rate
