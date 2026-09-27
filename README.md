# WarmWinterOS public site

This repository contains only the static, public-facing website for WarmWinterOS. It is intended for `warmwinteros.com` after a separate publishing review. The website source is MIT-licensed; ResearchOS, Foveliem, installers, scientific data, credentials, and private documentation are **not** part of this repository or its license.

The previous PRE-ALPHA / LEGACY landing page and disabled Pages configuration are historical context. The founder authorized reusing this repository for the new public site on 2026-09-27. Pages remains disabled until the revised content, domain, DNS, and HTTPS are explicitly checked and publication is approved. Adding files here does not publish an installer.

## Current public claims

- ResearchOS is a local-first scientific workbench.
- An internal Windows FTIR candidate passed clean-Sandbox first-install, offline analysis, and A-to-B upgrade/uninstall data-retention tests. This is not an invited or public release.
- A frozen XPS science probe passed a clean-Sandbox test, but installed XPS UI/workflow qualification is still open; XPS is not presented as available.
- Foveliem integration and additional scientific modules are roadmap work, not implemented Alpha promises.
- Access requests go by email to `limiaodong6@gmail.com`; there is no online registration or public download.

## Local preview

Open `index.html` in a browser. The page uses plain HTML and CSS with no package manager, API, analytics, tracking, or externally hosted assets.

## Publishing checklist

1. Confirm claims against accepted release evidence and update the date/status text.
2. Review the public diff for secrets, private paths, personal/research data, and unlicensed assets.
3. Push only after explicit approval. Configure GitHub Pages from the reviewed branch/root; it is currently disabled.
4. Verify ownership of `warmwinteros.com`, then configure the custom domain, DNS, HTTPS, and redirects. Do not leave DNS pointed at a disabled Pages site.
5. Inspect the deployed page on desktop and mobile, check all links and the contact address, and verify no installer or private source is exposed.

The private binary download channel will be a separate organization-owned repository with read-only invitations, and only after its own Go/No-Go review.
