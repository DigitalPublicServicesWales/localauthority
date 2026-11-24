# Funded childcare for 2-year-olds: content toolkit

**Digital Public Services Wales – working prototype v0.7**


A small static website that helps local authorities adapt a shared content pattern for funded childcare for 2-year-olds.

## Try it

Open `index.html` in a web browser, or publish it through GitHub Pages. No build step or server is required.

## What works

- About the pattern and suggested position in a council website
- User needs: six concise needs mapped to sections of the supplied content pattern, plus scope boundaries and validation questions
- Local authority setup: council and area names, application and Family Information Service contacts, provider search and application links, processing time, system name, and provider-choice variant
- Live save of local answers in the browser via localStorage
- Preview using the supplied content pattern
- Clear placeholders for missing local information and the as-yet-unsupplied 'provider chosen after applying' copy
- Text download, copy and print/save as PDF

## Boundaries

This is a working prototype, not a published public service. The current supplied content is a working pattern and must be checked against approved scheme guidance before publication. The site now contains a working Welsh translation drafted for prototype testing. It has not been approved or professionally reviewed. Local answers remain in the browser, not a shared database. The setup includes processing time and online system name for future content decisions, but these are deliberately *not* inserted into the public-facing page yet because the source pattern does not specify where or how to use them.

Do not enter personal information about families. Do not present this prototype as an officially approved Welsh Government website.

## Suggested feedback workflow

Keep one GitHub repository. Use Issues for each proposed improvement, with a screenshot, expected behaviour, who raised it, and whether it affects the shared pattern or a local variation. Use a branch and pull request for each approved change. Tag releases (v0.2, v0.3) and keep a short changelog.

## Next iteration

1. Review with the content designer: exact copy, place in website hierarchy, provider-choice variants, and what is protected vs locally adaptable.
2. Test with 2–3 local authorities and record questions and changes.
3. Review all Welsh copy, terminology, grammar, local names and links with Welsh-speaking content specialists, then test the bilingual journey with users.
4. Consider downloadable Word, structured change history and contributions after the journey is validated.

## Visual design and naming (v0.3)

The prototype has a DPSW-inspired publisher header, a clearer service title and interaction styling informed by the GOV.UK Design System (including form fields, focus states, button treatment, content widths and prototype identification). The geometric publisher mark is an **illustrative placeholder**, not the official DPSW logo.

This is **not** a production-ready application of the GOV.WALES Global Experience Language (GEL). Confirm official branding, design system requirements and publishing approval with the relevant Welsh Government teams before public release.

Suggested public-facing name: **Funded childcare for 2-year-olds: content toolkit**. Attribution: **Digital Public Services Wales**, with the context **Welsh Government funded childcare**.

### Feedback workflow

Use GitHub Issues to record a concrete problem, the page or step affected, evidence from a colleague or local authority, and a proposed change. Agree changes to the shared pattern with the content owner before changing public-facing wording.

## User needs (v0.4)

The User needs section contains six **candidate needs inferred from the supplied draft pattern**: understanding the offer, timing, finding a provider, applying, what happens next, and getting help. They are not claimed as research-validated user needs. They should be tested with families and local authorities, and then updated with evidence. This section intentionally limits scope to the page and links to related services instead of duplicating them.

## Changes in v0.5

- Official combined Welsh Government and Digital Public Services Wales logo, referenced from the Welsh Government Digital and Data blog. **The logo loads from an external website:** if external images are blocked or the blog URL changes, the site displays a bilingual text fallback. Before formal publication, get the approved brand asset and host a local copy with permission.
- DPSW dark teal, white and mint styling, retaining accessible GOV.UK-style forms and focus states. The palette is visually informed by official branding, not a verified brand-token specification.
- Six user needs presented as three distinct lines: As a…, I need to…, So that I can…
- Related links to the DPSW Apply service pattern, Service Manual and fundamental user needs.
- Renamed setup navigation to **Adapt for your local authority**.
- Fixed **Preview your page** button to use the same explicit client-side navigation as the tabs and save entered values first.

No AI, backend or API connection is used.

## v0.6 changes

- Restores the welcoming homepage: mint hero, simple parent-and-child illustration and four linked cards.
- Removes decorative uppercase eyebrow text above the hero heading.
- Adds a Work with us page and navigation entry, linking to the official DPSW contact route. Replace with an agreed project-specific address when available.
- Keeps v0.5 branding, user needs, form, preview, export and guidance links.
- Fixes a duplicated phrase in one candidate user need.

## Changes in v0.7 — English and Welsh

- Added a visible **Cymraeg / English** switch in the publisher header. It preserves the current toolkit section on switching.
- Added Welsh versions of the homepage, user needs, collaborative contact page, local authority form and content preview.
- The local information entered is shared between the two languages and stored in the browser; the language preference is also saved locally.
- The copy and download actions now export the currently selected language.
- Changed the HTML document language on switching to support assistive technology.
- The Welsh wording is an **unreviewed working translation**. It is explicitly marked as such. It must be reviewed by Welsh-speaking content professionals and approved policy owners before publication or use as a public-facing template.
- Authority names and locally entered organisation names are not automatically translated. Teams should enter the appropriate names for the intended language, or the form should be extended to store separate Welsh and English versions.
- There is no AI, external translation service, server or submission of local details.

### Known limitations

- The Welsh copy has not had professional language or policy review.
- Links point to the resources supplied for the English prototype; verify or replace with Welsh equivalents where available.
- The language switch is client-side. For a production website, consider separate `/en/` and `/cy/` URLs to make each language independently accessible and indexable.
- The PDF/print view and exported text require bilingual usability and accessibility testing.
