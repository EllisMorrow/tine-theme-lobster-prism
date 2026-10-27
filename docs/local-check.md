# Local check summary

- Theme: Lobster · Prism 0.1.1
- Manifest SHA-256: `fe9e5be105278248da29a469daa71a006bfe0b9190eb661c4206f42545ab7113`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 10.77:1, title 10.77:1, link 5.25:1, tag 5.25:1, code 9.84:1, mark 9.52:1, chosen 9.44:1.
  - Dark: body 13.98:1, title 13.98:1, link 5.86:1, tag 5.86:1, code 12.36:1, mark 12.16:1, chosen 11.97:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
