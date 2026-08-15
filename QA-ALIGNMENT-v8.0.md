# QA Alignment Report — Generative AI for 3D Modeling v8.0

Course code: **TGS-2023037544**
Audit date: **15 August 2026**

## Overall verdict

**PASS** — the release set is structurally valid, visually inspected, source-aligned and ready for controlled Drive/TMS/GitHub publication.

## A. PowerPoint quality — PASS

- 224-slide, concept-led deck with a single v8.0 cover version.
- General Trainer and Dr Alfred Ang profile-card slides are present.
- Assessment briefing precedes the assessment summary; WA → PP → LMS → sign-off flow is shown visually.
- Digital Attendance appears near the front and is repeated before the final slide.
- Learner access and LMS download slides use visual cards and readable URL callouts.
- Detailed click-by-click procedures are excluded from the deck and retained in the Learner Guide/activity instructions.
- Every slide has the course title, TGS code, copyright, and slide number footer.
- Native PowerPoint chart retained and labelled; all 224 slides passed strict OOXML validation.
- Practice Exam: not applicable. This is not a certification-exam preparation course, and neither the live course page nor the controlled legacy materials identify an approved practice-exam URL.

## B. Assessment quality — PASS

- Original TMS instrument preserved: 6-question Written Assessment (SAQ), 1 hour; 3-task Practical Performance, 2 hours.
- All questions are open-ended.
- Question papers use cover → candidate instructions/grading → content from page 3.
- Answer keys are trainer copies and contain suggestive answers.
- The assessment PDF verifier passed all four rendered documents.

| Criterion | Instrument item | Course evidence |
|---|---|---|
| K1 | WA Question 1 | Topic 1 · Slides 20–84 |
| K2 | WA Question 2 | Topic 1 · Slides 20–84 |
| K3 | WA Question 3 | Topics 1 and 3 · Slides 20–84, 151–215 |
| K4 | WA Question 4 | Topics 2 and 3 · Slides 85–215 |
| K5 | WA Question 5 | Topics 2 and 3 · Slides 85–215 |
| K6 | WA Question 6 | Topics 1 and 3 · Slides 20–84, 151–215 |
| A1, A2 | PP Task 1 | Activities 1–4 · Slides 68–83 |
| A3, A4 | PP Task 2 | Activities 5–8 · Slides 134–149 |
| A5, A6 | PP Task 3 | Activities 9–12 · Slides 199–214 |

## C. Lesson Plan — PASS

- WSQ cover, version-control record, static page-numbered TOC, Arial body and Page X of Y footer are present.
- Four days run 09:00–18:00 with a one-hour lunch; each day totals eight contact hours.
- The daily schedule and topic/activity breakdown map to the final 224-slide deck.
- Landscape schedule rows and portrait breakdown pages were visually inspected after regeneration.

## D. Learner Guide — PASS

- WSQ cover, version-control record, static page-numbered TOC, Arial body and Page X of Y footer are present.
- Detailed numbered procedures are provided for all 12 activities.
- Acceptance checks, evidence requirements and activity-folder references are included.
- `LEARNER-GUIDE.md` is generated from the same source and mirrors the DOCX/PDF content.
- All 37 rendered pages were inspected, including the TOC, activity pages and Quick Reference.

## E. Activities and alignment — PASS

- 12 individual learner-facing folders exist under `activities/`; no legacy `labs/` folder remains.
- Every folder contains `README.md`, `INSTRUCTIONS.md`, `CHECKLIST.md`, `STARTER.blend`, `EXAMPLE.blend` and `Example-Presentation.pptx`.
- Supplied Blender assets were reused across the progression; the 24 `.blend` files carry valid `BLENDER` headers and 22 distinct checksums.
- Blender itself is not installed in this build environment, so native viewport/open testing was not available; file integrity and source provenance were verified instead.
- Activity sample presentations passed OOXML ZIP integrity checks.

## F. Files, versions and distribution — PASS

- Exactly one current courseware version (v8.0) is present.
- PPTX/PDF, LG DOCX/PDF/Markdown and LP DOCX/PDF are current.
- Assessment contains exactly four DOCX files and is excluded from GitHub by `.gitignore`.
- `.env`, source/reference material, build tooling, generated visuals and QA renders are excluded from GitHub.
- Drive publication must keep answer keys trainer-only; only the WA and PP question papers may be attached to the LMS.

## Source coverage

- Legacy PPT: retained the TSC, technical-drawing, assessment and production-quality coverage as the floor.
- Live course page: retained the four-day structure, three topics and three learning outcomes.
- Linked Blender/AI video: incorporated prompt → script → Blender Scripting workspace → traceback → repair → verification practice.
- Blender documentation and supplied assets: updated terminology and hands-on work from Autodesk Inventor to Blender.
