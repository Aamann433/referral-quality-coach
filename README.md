# Referral Quality Coach

A beginner-friendly, browser-only Talent Acquisition prototype. It checks the
completeness of referral evidence, not candidates or hiring decisions.

## Open the app

Visit https://aamann433.github.io/referral-quality-coach/ once GitHub Pages has
finished publishing.

To run entirely offline, download this repository as a ZIP, extract it, and
double-click `index.html`. No installation, build, server, or dependencies.

## Use it

Choose one of three sample roles, or choose **Paste another role**. For a pasted
role, enter a title, paste the job description, and copy its requirements into the
requirements box, one per line. Each line becomes a checklist item. Requirements
are not extracted by AI. Editing the role clears the role-relevance explanation;
changing a requirement clears its selection.

Describe your relationship, firsthand work example, observed outcome, connection
to at least one role requirement, and the limits of your knowledge. Select
**Check my referral** for reasons and, for Red or Yellow, one follow-up question.

## Transparent rules

- **Red:** No confirmed firsthand example with a situation and an observed action.
- **Yellow:** A firsthand example is supplied, but one or more other evidence
  details are missing.
- **Green:** All evidence fields are supplied and at least one requirement is
  selected. The number of selected requirements does not affect the result.

Blank entries and common placeholders are treated as missing. These simple rules
cannot verify truth, substantive specificity, or whether the claimed role
connection is correct. Green describes a completed evidence structure, not an
assessment or endorsement of the person.

**This checks the quality of your referral evidence. It does not assess the
candidate or determine whether they should progress.**

## Privacy and hosting

The app uses plain HTML, CSS, and JavaScript. No APIs, database, authentication,
analytics, browser storage, or external dependencies. Job descriptions and
referral text stay in the current tab and are not submitted. Refreshing, closing,
or clearing the draft discards them. Use sample information for this prototype.

GitHub Pages serves the public files over HTTPS and may keep standard website
request logs; it does not receive the text entered into this app. The source code
and anything committed to this repository are public. Do not commit referral
information or internal job descriptions.

GitHub Pages publishes `main` from the repository root. Changes to `index.html`
on that branch are published automatically.
