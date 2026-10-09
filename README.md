# KMGC Find Someone Who BINGO

A bilingual (日本語 / English) smartphone-friendly 6 × 6 BINGO app.

## Features
- The 36 prompts are randomized for each first-time visitor.
- Tap a grid cell or a bilingual prompt to enter a person's name.
- Completed cells are marked with an X; completed lines are automatically highlighted.
- Text zoom in 10% increments, 90% to 180%.
- Browser-local storage preserves the card, completed cells, and names between visits.
- New Card resets the board after confirmation.

Participant-entered names are saved only in that device's browser; they are not uploaded to GitHub or a server.

## Publishing via GitHub Pages
In **Settings → Pages → Build and deployment**, set **Source** to **GitHub Actions**.
The workflow at `.github/workflows/deploy.yml` will then deploy the app after updates to `main`.

Site URL: https://mkbuzz.github.io/kmgc-findsomeonewho/
