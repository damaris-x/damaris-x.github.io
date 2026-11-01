# Damaris X: the site

The public site for Damaris X, an AI contractor for small offices. The home page opens in plain words for the office
(how hiring us works, a real example, two illustrative offices), then goes under the hood for technical readers and
investors: carafe, skilldecant, the Fleet operator and the carafe box, and how an engineer sets them up.

- **Live:** https://damaris-x.ai/ (custom domain, set in the repository's Pages settings; https://damaris-x.github.io/ redirects there)
- **The home page** is one HTML file that is also a 15-slide deck: press **P** or **Present**; ← → to move, Esc to
  leave. Opening `…/#present` starts in the deck. ⌘P prints one slide per page (16:9).
- **`fleet-operator/`** is the full Fleet operator page and deck, moved here from
  `damaris-x/carafe-fleet-operator`, whose old address now forwards here.
- **Two styles.** The default is plain HTML (Cheng, 2026-10-29: 「用 GNU 风格」), because people hand pages to their
  agents. `human/` holds the same pages in a designed "human style" (Apple-inspired, Cheng: 「call human style」) as
  the alternative; each page links to its twin ("Style: plain, human style"). Wording changes go into both.
- **`llms.txt`** is the plain-text copy for agents; keep it in step with the home page.

This repository holds the pages and their figures only, no product source. Everything here is public: no
client names, people, machines or private repository links. The internal notes, with the sources for every claim,
are in the carafe repository under `docs/marketing/` and `docs/research/`.

No build step: edit the HTML and open a pull request (the organization requires one for `main`). Merging it
republishes the site within a minute or two.

© 2026 Cheng Cheng. All rights reserved.
