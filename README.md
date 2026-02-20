# Groww Weekly Review Automation

## Overview
This project demonstrates a lightweight workflow automation that generates a weekly product sentiment pulse from app store reviews.

Built using Zapier scheduling + JavaScript processing, the system simulates ingestion → summarization → reporting → email drafting.

This showcases workflow automation, prompt structuring, and product insight generation.

---

## Working Prototype
Live Link:
https://zapier.com/editor/350276958/published

---

## Automation Flow
1. Scheduled trigger runs every Monday
2. JavaScript step:
   - Computes week range
   - Generates insight note
   - Produces email draft
3. Output available in Zap history

---

## Deliverables
- Weekly note → `weekly-note.md`
- Email draft → `email-draft.txt`
- Sample reviews dataset → `reviews_sample.csv`

---

## How to Re-Run for New Week
1. Open Zapier
2. Run Zap manually or wait for schedule
3. Retrieve output from Zap History
4. Replace weekly-note contents if using live data

---

## Theme Legend
| Theme | Meaning |
|------|--------|
| Onboarding | Signup UX issues |
| KYC | Verification delays |
| Payments | Transaction failures |
| UI | Navigation/usability |
| Performance | Speed/crashes |

(Max 5 themes enforced)

---

## Future Improvements
- Real review ingestion
- LLM clustering
- Auto email sending
- Historical tracking
- Dashboard visualization
