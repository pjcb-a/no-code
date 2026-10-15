# Case studies — working copy

These are publishable drafts once the **verify before publishing** items are resolved. The order puts the strongest product work first, then a second frontend project, then a compact example of AI-assisted development judgment.

## 1. CARES — making university concerns easier to follow

**Project:** Centralized Ateneo Response and Engagement System (2026 academic project)  
**Recorded role:** Frontend Developer and UI/UX Designer  
**Tools listed in existing portfolio:** Figma, TypeScript, React  
**Suggested route:** `/projects/cares`  
**Initial visual:** [CARES UI capture](assets/cares-ui.png)

### Draft site copy

CARES brings concern reporting and appointment scheduling into one university workflow. Students need a clear way to submit an issue, follow its status, and arrange a meeting; offices and academic staff need views that fit their own responsibilities. As a frontend developer and UI/UX designer on this collaborative project, I worked on the interface that presents those workflows to users. The repository contains separate student and staff screens, and the project documentation describes role-based concern queues, status changes, and appointment booking. The case study should show how the interface helps each role understand what to do next.

**What this demonstrates:** role-aware interface design, multi-step workflows, React and TypeScript implementation, and collaboration across a larger application.

**Evidence available:** the real UI capture above; the local CARES codebase and README; an [existing portfolio listing](https://github.com/pjcb-a/personal-portfolio); a [demo URL listed there](https://adnucares.vercel.app/).

**Verify before publishing:** identify the specific screens/components and design decisions JP personally owned; capture the student concern flow and an appointment flow; check whether the demo is currently accessible and whether any test or user feedback can be cited. Do not claim adoption, time savings, or a quantified result without evidence. Credit the wider team.

## 2. SubTrack — making recurring payments visible

**Project:** Subscription tracking web app (2026 academic project)  
**Recorded role:** Frontend Developer and UI/UX Designer  
**Tools listed in existing portfolio:** Figma, Vue  
**Suggested route:** `/projects/subtrack`  
**Initial visual:** [SubTrack UI capture](assets/subtrack-ui.png)

### Draft site copy

Subscriptions are easy to forget when renewal dates and costs live in different places. SubTrack was designed to bring them into one dashboard, show upcoming payments, and help users review recurring spending. My recorded role was frontend development and UI/UX design. The first available capture shows the sign-in experience and the visual direction; the full case study should connect that entry point to the dashboard and renewal reminders, using real screens and an explanation of the decisions behind them.

**What this demonstrates:** frontend implementation in Vue, information hierarchy for financial data, and translating a practical user need into a focused product flow.

**Evidence available:** the real UI capture above; the project description and role in JP's existing personal portfolio; a [demo URL listed there](https://sub-track-frontend.vercel.app/).

**Verify before publishing:** capture the actual dashboard and renewal flow; confirm which Vue components and design decisions JP made; check the demo URL; add a repo link if public. No savings, retention, or reminder-delivery claims are supported yet.

## 3. AI-assisted contact form — testing the quality of the brief

**Project:** FE-03 portfolio contact form workflow comparison  
**Role:** Prompt author, reviewer, and verifier  
**Tools:** React, TypeScript, AI-assisted coding, Vitest/React Testing Library in the precise version  
**Suggested route:** `/projects/ai-assisted-contact-form`

### Draft site copy

I built the same portfolio contact-form feature twice with AI assistance to see how the quality of my instructions changed the result. A vague prompt produced a functional form and useful validation, but it made visual and structural decisions I had not specified. A second, precise brief stated the fields, accessibility requirements, visual direction, component boundaries, and test paths. That version aligned more closely with the intended design and made review easier. When the first test run exposed configuration and test-isolation problems, I investigated the failures and got the four requested validation and submission paths passing. The lesson was practical: AI can generate capable code, but I still need to define the acceptance criteria and verify the result.

**What this demonstrates:** requirements writing, accessibility review, test debugging, and judgment about AI-generated work.

**Evidence available:** [workflow comparison in the capstone repository](https://github.com/pjcb-a/capstone/blob/main/WORKFLOW.md) and its `fe03-vague` and `fe03-precise` branches. The local source of the written comparison is `INTERNSHIP/capstone/WORKFLOW.md`.

**Verify before publishing:** add side-by-side screenshots and direct links to the exact branch commits; confirm the public Markdown link resolves after the relevant branch is merged. This was an experiment, so describe it as a tested feature rather than a production contact service.

## Shared case-study format for the site

1. One-sentence result or purpose.
2. Problem and audience.
3. Personal role, team context, and constraints.
4. Two or three concrete decisions, paired with real captures.
5. What exists now and how it was verified.
6. What changed in JP's approach, plus a link to the next case.

Keep the “result” section factual even when metrics are unavailable. A shipped screen, a working workflow, or a passing test is useful evidence on its own.
