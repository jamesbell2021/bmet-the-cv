# The CV

An interactive breakdown of what a junior games-industry CV actually needs to do: take apart five real-shaped CVs (environment artist, gameplay programmer, games designer, 3D animator, QA tester), section by section, then test the judgement with an eight-question quiz and a print-ready checklist for writing your own.

**Live site:** https://jamesbell2021.github.io/bmet-the-cv/

Built for **Unit B1 Phase 3 — creating materials for career progression using technical practice** (B1.3, assessed under AC3) at Belfast Met. The CV and personal statement are named evidence in the specification's list of promotional materials.

## What's on the page

- **Take a CV apart** — switch between five full, realistically-detailed CVs and tap any section (header, statement, skills, projects, education, employment, interests, references) to see what it's for, what a strong one does, the mistake that gets made most often, and a question to check your own against.
- **Spot the stronger line** — an eight-question quiz pairing a weak and a strong version of the same CV line (a skills entry, a project description, an opening statement, an interests section, an email address, a portfolio link placement, a filename) with feedback on why one survives a twenty-second read and the other doesn't.
- **Rules and myths** — a do/do-not reference list specific to games hiring, including places it deliberately contradicts generic careers advice.
- **Where to read more** — eight free, UK-focused, checked links (Grads in Games, Skillsearch, Into Games, ScreenSkills ×2, Prospects, National Careers Service, Ukie) for CV writing and role research.
- **Your checklist** — ten concrete things to bring to the next lesson before writing an own CV, each with a note on why it has to be prepared in advance rather than written from memory.

As with the companion page [Breaking In](https://github.com/jamesbell2021/bmet-breaking-in), dotted-underline terms are tappable jargon explanations.

## Using it in class

Works as a lead-in to a CV-writing lesson: students explore the worked examples and take the quiz first, then use the checklist as homework to bring the specifics (real advert, real software list, real project numbers, references already asked) they'll need before they can write anything worthwhile. Both the CV view and the checklist have a print button, styled for a clean printout with the interactive chrome hidden.

## Running it

No build step, no dependencies beyond two Google Fonts. No audio on this page.

- **Online:** use the GitHub Pages link above.
- **Offline:** download `index.html` and open it in any browser.

## Updating the content

Everything lives in `<script>` at the bottom of `index.html`:

- `TERMS` — the jargon glossary, same `{{key|display text}}` pattern as the companion page.
- `NOTES` — the explainer shown for each CV section when tapped.
- `ROLES` — the five worked CVs. Copy the shape of an existing entry to add a sixth discipline.
- `QUIZ` — the eight weak/strong comparison questions.
- `CHECKS` — the ten-item pre-lesson checklist.

---

🤖 Built with [Claude Code](https://claude.com/claude-code)
