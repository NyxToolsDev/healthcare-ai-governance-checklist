# Healthcare AI Governance Readiness Checklist

**A free resource from NyxTools by NyxTools**

Use this checklist to assess whether your healthcare organization is ready to govern AI tools safely and compliantly. Work through each section honestly — the goal is to identify gaps before regulators, auditors, or a breach does it for you.

---

## How to Use This Checklist

Score each item: **Yes** (in place), **Partial** (started but incomplete), or **No** (not addressed).

- **80%+ Yes:** You're ahead of most healthcare organizations. Focus on closing remaining gaps.
- **50-79% Yes:** Significant foundation, but critical gaps likely exist. Prioritize sections with the most "No" answers.
- **Below 50%:** You need a governance program before expanding AI use. The good news: you're assessing now, not after an incident.

---

## Section 1: Policy and Leadership

| # | Item | Yes | Partial | No |
|---|------|:---:|:-------:|:--:|
| 1.1 | Your organization has a written AI Acceptable Use Policy | | | |
| 1.2 | The policy defines approved vs. prohibited AI use cases | | | |
| 1.3 | An executive sponsor (CIO, CISO, or equivalent) owns AI governance | | | |
| 1.4 | A cross-functional AI Governance Committee exists or is planned | | | |
| 1.5 | AI governance has been discussed at the board or senior leadership level | | | |
| 1.6 | The policy is reviewed and updated at least annually | | | |

**Why this matters:** 58% of healthcare organizations using AI tools have no formal governance policy. The Colorado AI Act (effective Feb 2026), White House AI framework, and the HIPAA Security Rule update (2025-2026) all assume you have one.

---

## Section 2: HIPAA and PHI Protections

| # | Item | Yes | Partial | No |
|---|------|:---:|:-------:|:--:|
| 2.1 | Staff know which AI tools are approved for use with PHI | | | |
| 2.2 | PHI is never entered into consumer-grade AI tools (ChatGPT free tier, Gemini, etc.) | | | |
| 2.3 | Business Associate Agreements (BAAs) are in place for all AI tools that process PHI | | | |
| 2.4 | You have verified that approved AI vendors do NOT use your data for model training | | | |
| 2.5 | PHI is never included in AI prompts without de-identification or an approved tool | | | |
| 2.6 | AI-generated outputs containing PHI are treated with the same protections as any PHI | | | |
| 2.7 | Audit logs exist for all AI tool access involving patient data | | | |

**Why this matters:** The average healthcare data breach costs $10.93M (IBM, 2023). An employee pasting patient notes into an unapproved AI tool is a breach — and it's happening at organizations that think they're compliant.

---

## Section 3: Vendor Evaluation

| # | Item | Yes | Partial | No |
|---|------|:---:|:-------:|:--:|
| 3.1 | You have a formal process for evaluating AI vendors before approval | | | |
| 3.2 | Vendor evaluations include HIPAA compliance, security controls, and data handling | | | |
| 3.3 | You verify vendor certifications (SOC 2 Type II, HITRUST, ISO 27001) | | | |
| 3.4 | You confirm data residency (US-only processing for PHI) | | | |
| 3.5 | Contract terms include breach notification, data deletion, and right to audit | | | |
| 3.6 | You have evaluated ALL currently used AI tools — not just newly requested ones | | | |

**Why this matters:** Most organizations evaluate new AI tools but grandfather existing ones. The tools adopted earliest — before governance existed — are often the highest risk.

---

## Section 4: Training and Awareness

| # | Item | Yes | Partial | No |
|---|------|:---:|:-------:|:--:|
| 4.1 | All staff complete AI-specific training before accessing AI tools | | | |
| 4.2 | Training covers HIPAA implications of AI use (not just general HIPAA) | | | |
| 4.3 | Training includes real scenarios: what to do and what not to do | | | |
| 4.4 | Training completion is tracked and tied to AI tool access | | | |
| 4.5 | Role-specific training exists (clinical vs. administrative vs. IT) | | | |
| 4.6 | Training is refreshed at least annually | | | |

**Why this matters:** A policy without training is a policy nobody follows. Organizations that gate AI access on training completion see 70%+ reduction in shadow AI incidents.

---

## Section 5: Shadow AI and Monitoring

| # | Item | Yes | Partial | No |
|---|------|:---:|:-------:|:--:|
| 5.1 | You have assessed whether staff are using unauthorized AI tools | | | |
| 5.2 | Network monitoring or DLP detects traffic to known AI platforms | | | |
| 5.3 | Staff have a clear, non-punitive channel to report AI tool use or request new tools | | | |
| 5.4 | You provide approved AI alternatives so staff don't resort to consumer tools | | | |
| 5.5 | Shadow AI findings are reported to the Governance Committee | | | |

**Why this matters:** Blocking AI without providing alternatives drives use underground. The organizations with the lowest shadow AI rates are the ones that say "yes, use these approved tools" — not the ones that say "no AI."

---

## Section 6: Incident Response

| # | Item | Yes | Partial | No |
|---|------|:---:|:-------:|:--:|
| 6.1 | Your incident response plan includes AI-specific scenarios | | | |
| 6.2 | Staff know how to report an AI-related incident (PHI in prompts, wrong output used clinically) | | | |
| 6.3 | You have conducted a tabletop exercise with an AI-specific scenario | | | |
| 6.4 | Incident response roles are assigned and documented | | | |
| 6.5 | AI incidents are tracked separately for trend analysis | | | |

**Why this matters:** When (not if) an AI incident occurs, the response time and quality determine whether it's a contained event or a reportable breach. Organizations that rehearse respond faster.

---

## Section 7: Regulatory Awareness

| # | Item | Yes | Partial | No |
|---|------|:---:|:-------:|:--:|
| 7.1 | You are tracking the Colorado AI Act (SB 24-205, enforcement June 30, 2026) and the proposed replacement bill | | | |
| 7.2 | You are aware of the HIPAA Security Rule update timeline (2026) | | | |
| 7.3 | You understand whether the EU AI Act applies to your organization | | | |
| 7.4 | You have assessed whether any current AI tools qualify as "high-risk" under emerging regulations | | | |
| 7.5 | Legal counsel has reviewed your AI governance program for regulatory alignment | | | |
| 7.6 | You have a plan for BOTH Colorado AI Act outcomes (original act stands OR replacement bill passes) | | | |
| 7.7 | You are tracking the HHS AI governance reorganization (March 2026) as a model for your own structure | | | |

**Why this matters:** The Colorado AI Act faces a potential repeal-and-replace — but the transparency requirements survive either outcome, and HIPAA, Joint Commission, and malpractice liability don't care which version passes. Organizations that build governance for both scenarios are prepared. Organizations betting on one outcome are gambling.

---

## Scoring Summary

| Section | Total Items | Yes | Partial | No |
|---------|:-----------:|:---:|:-------:|:--:|
| 1. Policy and Leadership | 6 | | | |
| 2. HIPAA and PHI Protections | 7 | | | |
| 3. Vendor Evaluation | 6 | | | |
| 4. Training and Awareness | 6 | | | |
| 5. Shadow AI and Monitoring | 5 | | | |
| 6. Incident Response | 5 | | | |
| 7. Regulatory Awareness | 7 | | | |
| **Total** | **42** | | | |

### Your Readiness Level

| Score | Level | What It Means |
|-------|-------|---------------|
| 34-42 Yes | **Advanced** | Strong foundation. Close remaining gaps and maintain. |
| 21-33 Yes | **Developing** | Good start, but critical gaps exist. Prioritize Sections 2 and 6. |
| 10-20 Yes | **Early Stage** | Significant work needed. Start with policy (Section 1) and PHI protections (Section 2). |
| 0-9 Yes | **Pre-Governance** | Your organization needs a governance program before expanding AI use. |

---

## What To Do Next

This checklist tells you where you stand. Closing the gaps requires:

- **Customizable policy templates** covering acceptable use, HIPAA prompt safety, vendor evaluation, incident response, board presentation, training curriculum, and implementation planning
- **A structured implementation guide** with week-by-week rollout steps
- **A vendor evaluation scorecard** with weighted criteria and automatic disqualifiers

The **Healthcare AI Governance Kit** from NyxTools includes all of these — 11 templates built by a healthcare IT professional with 19 years of experience, designed for organizations navigating AI adoption under HIPAA. Includes Colorado AI Act scenario planning for both legislative outcomes, a maturity model self-assessment, and a governance org chart based on the March 2026 HHS reorganization.

Learn more: [NyxTools on Gumroad](https://nyxtools.gumroad.com)

---

*Copyright 2026 NyxTools. This checklist is free to use and distribute with attribution.*
