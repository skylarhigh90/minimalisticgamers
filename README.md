# MinimalisticGamers

Compatibility copy of the public contact, support, and shared privacy-policy website for MinimalisticGamers. The primary website has moved to https://minimalisticgamers.github.io/.

## Preferred public URLs

- Website: https://minimalisticgamers.github.io/
- Support URL: https://minimalisticgamers.github.io/support/
- Privacy Policy URL: https://minimalisticgamers.github.io/privacy/
- Support email: contact@minimalisticgamers.io

Use the support and privacy URLs in each game's store listing and in-app links. The shared policy covers MinimalisticGamers games that link to it. Before releasing another game, verify that its actual data practices match the policy; update the policy first if they differ. The policy includes separate explanations for support emails, Apple diagnostics/TestFlight, and GitHub hosting.

The previous links at https://skylarhigh90.github.io/minimalisticgamers/, https://skylarhigh90.github.io/minimalisticgamers/support/, and https://skylarhigh90.github.io/minimalisticgamers/privacy/ remain served by this repository so existing app links continue to work. These pages keep their original navigation and assets and point to the preferred URLs through canonical links; they do not automatically redirect visitors.

## Hosting and editing

This is a standalone website repository, separate from game source. GitHub Pages publishes the root of `main` at the previous `/minimalisticgamers/` project-site path. The primary site is maintained in https://github.com/minimalisticgamers/minimalisticgamers.github.io. Keep policy and support content consistent between the primary site and this compatibility copy. `.nojekyll` enables direct static-file hosting. No build, dependencies, analytics, web fonts, server, form service, or API keys are needed.

- `index.html`: company home and contact links.
- `support/index.html`: support information for all games.
- `privacy/index.html`: shared policy, effective 29 October 2026.
- `styles.css`: responsive layout and print styles.
- `404.html`: missing-page fallback for the project-site path.
- `favicon.svg`: geometric M mark.

Preview from this directory:

```sh
python3 -m http.server 8787 --bind 127.0.0.1
```

Then visit http://127.0.0.1:8787/. Review mobile and desktop layouts, relative links, and email links before committing and pushing changes to `main`.

This repository continues to use its original GitHub Pages project address. Its absolute paths in `404.html` intentionally retain `/minimalisticgamers/`. This repository does not configure a custom domain or email delivery.
