# Super Websites demo v2

Design concept for the Super Websites site (Patrick and Dave). Static HTML: open `index.html` in a browser, no build step.

- `index.html` is the whole page: styles, the chain-break opening animation and the brief form are inline.
- `assets/` holds the glossy logo, the hero illustrations and the two work screenshots.

Not a live site. Pricing, timings, inclusions and contact details are placeholders until agreed.

## Codex and DC collaboration — notes v1.0.0

2026-10-14 (Pacific/Auckland). Patrick has authorised Patrick's Codex and Dave's Claude (DC) to work together on Super Websites. Use this README for asynchronous handovers; neither assistant automatically receives the other's chat messages.

- Before starting, read this README, the current source, recent commits, branches and open pull requests. GitHub's latest committed files are the source of truth.
- Keep SWdemo1 and SWdemo2 as separate design alternatives unless Patrick or Dave requests a combination. Reuse useful ideas deliberately; do not replace either site wholesale with the other.
- For website code changes, use a task branch such as `codex/<task>` or `dc/<task>`, with a pull request explaining the change, validation and remaining questions.
- Before merging, fetch the latest target branch and reconcile changes. Preserve the other assistant's work; do not force-push shared branches or resolve conflicts by blindly taking one whole file.
- Scope tasks clearly. If both tasks touch the same file or section, agree the handover through notes or Patrick/Dave before making overlapping edits. README notes are coordination aids, not an automatic lock.
- Keep version numbers and code version notes current for website changes. This README-only handover is notes v1.0.0 and does not change the website's version.
- When handing over, append a dated note with assistant name, task/branch, files changed, checks performed, unfinished items and decisions needed. Preserve existing notes and clearly mark proposals.
- Keep unagreed prices, inclusions, delivery times, hosting assumptions and client claims labelled as proposals. Do not make commitments on behalf of Patrick or Dave.
- Super Websites uses this GitHub account.

### Codex review — 2026-10-14

Reviewed design concept v2 at commit `c4a6436`, whose commit credits Claude. The page keeps HTML, CSS and JavaScript in `index.html`. It includes a chain-break intro, new hero illustrations, a keys/ownership section, a four-step path, six logo treatments, portfolio screenshots and preview notes. Google Fonts are external.

Draft proposals shown on the page: one-page site NZ$1,500 + GST; five-page site NZ$2,500 + GST; two review rounds; contact-form delivery; Google-related setup; and Day 1 / Day 2 / Weeks 1–2 / Week 3 timings. Preserve their draft status until agreed with Patrick and Dave.

The NZ$79/month care-plan comparison, NZ$40–100/month market range and approximate domain cost have not been independently verified in this review. Confirm the free-hosting/only-domain-renewal claims against the final hosting and form-delivery design. FanCast and CamerAcademy are presented as real work; confirm attribution and permission before public launch.

Open items: third portfolio slot, email/phone/location TBC, and real form delivery. The form currently reveals a preview message only and has no contact-name/email field, so a production enquiry flow needs a way to reply. Social preview image currently uses a relative URL; configure and test it against the eventual public site URL before launch. The page is marked `noindex`.

Source checks found no missing local HTML assets, missing fragment targets or duplicate IDs. Responsive and reduced-motion code is present. This was a source review, not a fresh visual/browser test or a verified production deployment.

No website source or assets changed in this review.
