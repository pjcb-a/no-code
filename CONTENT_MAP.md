# Content map — portfolio

## Through-line and goal

**One-line claim:** I turn complex workflows into clear, responsive digital experiences.  
**Primary visitor action:** contact JP about a frontend opportunity.  
**Supporting action:** inspect a real project, then return to contact.

The map below is content-first. The named paths can be adapted to the already chosen site stack and Vercel deployment without changing the story.

| Page / suggested path | Sections in order | Case placement and proof | Named call to action |
| --- | --- | --- | --- |
| Home `/` | 1. Name, role, and one-line claim. 2. Short intro. 3. Featured work. 4. Brief approach/credibility. 5. Contact invitation. | Feature **CARES** first, then **SubTrack**. Use real UI captures. Link to the AI experiment as a smaller third item. | **View CARES case study** near featured work; **Email JP about a frontend role** at the end. |
| Projects `/projects` | 1. Page intro. 2. Featured project cards. 3. Other work or experiments. 4. Contact prompt. | Order: CARES, SubTrack, AI-assisted contact form. Each card needs role, one-sentence problem, year, capture, and detail link. | **Read CARES case study**; **Email JP about a frontend role** at the end. |
| CARES `/projects/cares` | 1. Title and summary. 2. Role/team/tools. 3. Problem. 4. User flows and design decisions. 5. Real captures. 6. Current state and evidence. 7. Reflection. | Student concern submission/status and appointment booking; include only screens JP can credit. | **See SubTrack** and **Email JP about a frontend role**. |
| SubTrack `/projects/subtrack` | 1. Title and summary. 2. Role/tools. 3. Renewal problem. 4. Dashboard and reminder flow. 5. Real captures. 6. Current state. 7. Reflection. | Replace the current sign-in-only capture with dashboard and renewal screens once gathered. | **See AI-assisted contact form** and **Email JP about a frontend role**. |
| AI experiment `/projects/ai-assisted-contact-form` | 1. Question tested. 2. Vague prompt result. 3. Precise brief and result. 4. Test/debugging evidence. 5. Lessons. | Side-by-side form captures and the four test cases; link to workflow documentation and branches. | **View all projects** and **Email JP about a frontend role**. |
| Experience `/experience` | 1. Short intro. 2. Experience timeline. 3. Skills used in featured cases. 4. Resume link. 5. Contact prompt. | Existing portfolio lists BS IT at Ateneo de Naga University, ThePillars Publication, BITS creatives, and Liderato kan Nueva Atenista. Confirm dates and wording. | **Download resume**; **Email JP about a frontend role**. |
| About `/about` | 1. Two-paragraph bio. 2. How JP approaches frontend and visual work. 3. Learning and collaboration. 4. Optional real portrait. 5. Contact prompt. | Tie the approach to CARES, SubTrack, and the AI experiment rather than a generic tool list. | **See my work**; **Email JP about a frontend role**. |
| Contact `/contact` | 1. Short invitation. 2. Direct email. 3. LinkedIn, GitHub, Behance. 4. Response expectations if JP wants to state them. | Existing contact links are listed in the personal portfolio. Start with a direct mail link; add a form only when its delivery path is real. | **Email JP about a frontend role** (primary). |

Suggested primary contact link: `mailto:jacob.johnpaul15@gmail.com`. Other existing channels: [LinkedIn](https://www.linkedin.com/in/john-paul-jacob-12b064407/), [GitHub](https://github.com/pjcb-a), and [Behance](https://www.behance.net/johnpauljacob). Verify that JP still wants each public.

## Proof to gather before the build

| Priority | Needed item | Why |
| --- | --- | --- |
| 1 | CARES screenshots of a full concern flow and an appointment flow, plus a list of JP-owned screens/components | The existing capture shows only sign-in. |
| 2 | SubTrack dashboard and renewal screenshots, plus the exact personal contribution | The existing capture shows only sign-in. |
| 3 | Side-by-side contact-form screenshots and links to the exact FE-03 branch commits | Makes the AI workflow comparison visually verifiable. |
| 4 | Working demo URLs and public repo links for each case | Lets visitors inspect proof directly; current listed demo URLs need a fresh check. |
| 5 | Current resume and confirmed experience dates | Prevents outdated role and timeline claims. |
| 6 | Any real evaluation notes, test results, or measured outcomes | Enables stronger results sections without invented numbers. |
| 7 | Real portrait, if wanted | Avoids using an AI-generated stand-in for JP. |

## Image set and navigation notes

The initial image set is [CARES](assets/cares-ui.png), [SubTrack](assets/subtrack-ui.png), and the [JP mark](assets/jp-mark.svg). These two project images are existing UI captures, not generated replacements. Use descriptive alt text that identifies the screen and product. The homepage should link straight into the strongest case, and each case should provide an obvious next project and contact link. Keep the technical health-check route, if the site has one, out of the main portfolio navigation.
