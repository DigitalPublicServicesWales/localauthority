# Funded childcare content toolkit — interactive prototype

A small, self-contained prototype for exploring how local authorities in Wales could adapt a shared content pattern for pages about funded childcare for 2-year-olds.

## Run the prototype

Open `index.html` in a modern web browser. No build tools, dependencies or account are required.

To publish as a GitHub Pages prototype, upload `index.html` to the root of a repository, then configure **Settings → Pages → Deploy from a branch**, choosing the main branch and root directory. Check your organisation's publishing and branding approvals before making it public.

## What works

- Five linked pages: Home, Content pattern, User needs and evidence, Adapt for your area, Work with us.
- Three-step guided adaptation journey.
- Selection of one of the 22 Welsh local authorities.
- Optional local arrangements and verified content fields.
- A rules-based draft assembled from user-provided information.
- Editable draft text, review checklist, copy, text download and print/PDF options.
- Keyboard-accessible controls and responsive layout.

## Explicit limitations

- **No AI model** is connected. The draft generator uses simple local JavaScript rules.
- **No verified policy, local authority or research source content** is built in. Everything must be checked before publishing.
- No data is sent to a server or saved between visits. All state lives in the current browser tab.
- English-only demonstration. A full bilingual version needs Welsh content design, translation and testing.
- This is not an official Welsh Government website or a live public service.
- No contact route or feedback service is connected.
- The project has not been through a formal accessibility audit or security review.

## Decisions to test with local authority staff

1. Is the shared pattern understandable and useful without the generator?
2. Are the questions enough to prepare a meaningful local draft?
3. What facts can staff confidently supply, and what needs policy sign-off?
4. Does the review page make unverified information obvious enough?
5. Would adapting an existing page be more useful than generating a new draft?
6. What output format best fits the local authority publishing process?

## Suggested next iteration

Replace example sections with the team's approved childcare content pattern and evidence, test with two authorities, and then evaluate whether AI improves the quality of adapted drafts beyond structured composition. Add a secure server-side AI endpoint only after governance and security review.
