# Where to next? information website

Standalone static pages for Google OAuth branding. Intended public repository:
`stephanos-p/where-to-next`. Publish only this directory's files, not the Android
application repository. No build, JavaScript, external fonts, or analytics.

Public contact: papastylianou.stephanos@gmail.com.
The policy pages were reviewed for initial publication on 10 September 2026.

Enable GitHub Pages with source `Deploy from a branch`, branch `main`, folder
`/ (root)`. Once deployment has succeeded, verify these URLs before entering them:

| Branding field | Planned value |
| --- | --- |
| Homepage | https://stephanos-p.github.io/where-to-next/ |
| Privacy policy | https://stephanos-p.github.io/where-to-next/privacy.html |
| Terms | https://stephanos-p.github.io/where-to-next/terms.html |
| Authorized domain | stephanos-p.github.io |

In Google Search Console, use a URL-prefix property for
`https://stephanos-p.github.io/where-to-next/`, with the Google account that owns
or edits the Cloud project. Add Google's HTML verification file at the website
root, or its exact HTML verification meta tag to index.html; retain it after
verification. Do not use a DNS Domain property for github.io, which you do not own.

Search Console ownership verification does not guarantee OAuth branding approval.
Check the actual Branding validation before treating setup as complete.

The privacy page documents current Android behavior, including retained cloud
versions and the distinction between disconnecting, revoking authorization, and
deleting data. Review it whenever those behaviors change. Public website links
have not been added to the Android app in this change.
