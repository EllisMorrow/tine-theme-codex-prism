# Local check summary

- Theme: Codex · Prism 0.1.1
- Manifest SHA-256: `892a48a2ccefa61944116e6e5f6b23285695a034cbe95761ae20f2a23a16cf62`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 19.44:1, title 19.44:1, link 5.65:1, tag 5.65:1, code 17.36:1, mark 16.37:1, chosen 16.16:1.
  - Dark: body 18.41:1, title 18.41:1, link 5.18:1, tag 5.18:1, code 16.25:1, mark 16.84:1, chosen 16.8:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
