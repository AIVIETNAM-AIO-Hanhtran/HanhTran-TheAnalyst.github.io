# Resume Advice — Jeff Su's "5 Golden Rules" (notes for our CV work)

> **Source:** Jeff Su, *"Write an Incredible Resume: 5 Golden Rules!"*
> YouTube: https://www.youtube.com/watch?v=Tt08KmFfIYQ
> Written companion: https://www.jeffsu.org/5-golden-rules-for-an-incredible-resume/
>
> The video is built on **Austin Belcak's analysis of 125,484 resumes** — every rule is backed by what the data showed actually works (not subjective opinion).
>
> Captured 2026-06-09 while drafting `cv_harvard.md`.

---

## Rule 1 — Include a LinkedIn profile

- **The data:** Only **48%** of the 125,484 resumes included a LinkedIn link. Those that did saw higher interview rates.
- **What to do:**
  - Put the LinkedIn URL in the header alongside email and phone.
  - Make sure the linked profile is actually presentable: professional headshot, banner, full work history matching the resume, real connections.
- **Why it matters:** Recruiters search LinkedIn for context the one-page resume can't carry — recommendations, mutual connections, longer-form post history.

## Rule 2 — Use the right keywords and skills (hard AND soft)

- **The data:** Candidates only included **51%** of the important keywords from the job description. Soft skills were heavily under-represented.
- **What to do:**
  - Paste the job description into a free word-cloud tool. The biggest words are the keywords the ATS and the recruiter are scanning for.
  - Mirror those keywords into your resume — in the Skills section AND inside bullet points (more credible than a chip list alone).
  - **Don't skip soft skills.** Communication, stakeholder management, prioritisation, mentorship, etc. carry weight even on technical CVs. Reference Udemy's and CNBC's "in-demand soft skills" lists if stuck.
- **Tactic note:** Keywords belong in the bullet that proves them. "Stakeholder management" in a chip list is weak; "Aligned PM, CS, and Marketing on a shared merchant mental model" is strong.

## Rule 3 — Include measurable results

- **The data:** Only **26%** of resumes had five or more metrics. Resumes with measurable outcomes performed materially better.
- **The formula — XYZ bullet:**
  > **"Accomplished [X] as measured by [Y], by doing [Z]."**
  - **X** = the outcome (what changed)
  - **Y** = the metric that proves it
  - **Z** = the specific actions you took
- **Example given in the video / article:**
  > *"Drove 2,500 organic sign-ups to our monthly newsletter by A/B testing content layout and collaborating with co-marketing partners, representing a 43% quarter-on-quarter increase."*
- **Push every internal metric to a business outcome.** Don't stop at "33% productivity increase by sales team" — close the loop with "translating to X incremental sales." Internal efficiency wins are weaker without the dollars/users/conversions they unlock.
- **Target:** at least **5 quantified bullets** across the resume.

## Rule 4 — Keep length 475–600 words

- **The data:** The ideal resume length is **475–600 words**. **77%** of resumes were outside that range.
- **What to do:**
  - Paste the resume into Word or Google Docs → check the word count.
  - Under 475 → you're under-selling, add depth (more XYZ bullets, more metrics).
  - Over 600 → you're padding, cut. Common cuts: redundant adjectives, restated job descriptions, soft-skill chips not backed by a bullet, very early roles that no longer matter.
- **Why this range:** long enough to prove substance, short enough that a recruiter actually reads it in the 6–10 seconds they spend on first pass.

## Rule 5 — Cut buzzwords and clichés

- **The data:** **51%** of resumes included buzzwords, clichés, or incorrect pronouns. Fluff dilutes the signal.
- **What to do:**
  - Search *"resume clichés and buzzwords"* for a current list and systematically delete matches.
  - Replace each cliché with the **specific thing you did**.
- **The principle (the line worth tattooing):**
  > **"Your writing should always be selling your experience, not summarising it."**
- **Common offenders to scan for:** *results-driven, team player, hard-working, go-getter, passionate, self-motivated, strategic thinker, dynamic, synergy, leverage (as a verb), think outside the box, detail-oriented, proven track record, responsible for, helped to, assisted with.* Most can be deleted or rewritten as a concrete action.
- **Pronoun trap:** never use "I" / "we" / "my" in a resume bullet — Harvard / standard convention is implied subject ("Built…", "Led…", "Designed…").

---

## How our `cv_harvard.md` draft scores against the 5 rules

| Rule | Status in current draft | Action |
|---|---|---|
| **1. LinkedIn** | ✓ Included in header (`linkedin.com/in/hoang-anh-tran-435195255`) | Done. |
| **2. Keywords + soft skills** | Hard skills are strong; soft skills are thin (one mention of "cross-functional", no explicit communication / mentorship / stakeholder-management chips) | **Add a soft-skills line** to Technical Skills section (stakeholder alignment, cross-functional collaboration, written/visual communication, mentoring junior analysts if applicable). Also weave soft-skill keywords into existing bullets where they belong. |
| **3. Measurable results — ≥5 quantified bullets** | ✓ Already strong: ~75% time-to-setup reduction (M1a), 12 MRR types reconciled (M1b), ~5pp churn drop + ~$3K MRR/month (M4), Day 2–3 → ~60 min + +3pp trial-to-paid (M6), 5-team adoption (M7), 1,660 trial merchants analysed (M6) | Already meets the 5-metric bar. **Tighten the XYZ structure** on any bullet that has X (outcome) but is missing Z (the specific action) — e.g. some M7 / M8 bullets could be tightened. |
| **4. Length 475–600 words** | Current draft is closer to **~1,100 words** (2-page full-detail format the user chose) | **Decision point.** Jeff Su's 475–600 target is for a strict 1-page US resume. The 2-page Harvard format the user chose will run longer by design. If targeting US-style 1-pagers later → cut roughly in half, keep Chatty milestones M1a/M4/M6/M7 only, collapse earlier roles to one-liners. If sticking with 2 pages → no change needed but stay disciplined on padding. |
| **5. Buzzwords / clichés** | Mostly clean — but a few candidates to scan: *"end-to-end"* (×2), *"deep-dive"*, *"sole data analyst"*, *"systems-level"*, *"foregrounded"*, *"vague PM questions"*, *"production analytics systems"* | **Sweep pass.** Replace "vague PM questions" with the actual translation work; trim "end-to-end" if the bullet already names the steps; check no "I" / "we" pronouns slipped in. |

---

## Most important single takeaway

Rule 3 (the **XYZ formula**) plus Rule 5 (**sell, don't summarise**) together do most of the work.
A bullet that says "Built a dashboard" summarises.
A bullet that says "Built a Power BI dashboard that gave PM monthly cash-flow visibility across 12 MRR contribution types, reconciled to ΔMRR every month" sells.
The current Chatty bullets in our draft mostly already follow this — they're the strongest part of the CV. The weakest blocks (Bess & Company, ENUY) are where the XYZ tightening will pay off most.
