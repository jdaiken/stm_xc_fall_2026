# STM Cross Country: Running Royals

Practice schedule for St. Thomas More Cathedral School cross country, fall 2026.

- `index.html` is the full practice plan and calendar. Three age groups (Jackrabbits 3rd–4th, Cheetahs 5th–6th, Falcons 7th–8th), color-coded by workout type, with a group filter and a calendar view.
- `running-royals-family-schedule.pdf` is the two-page handout for parents.

## Publishing

The site is a single static file with no build step. To serve it at
`https://jdaiken.github.io/stm_xc/`, go to **Settings → Pages** in the repo,
set **Source** to *Deploy from a branch*, and choose `main` / `/ (root)`.

The `.nojekyll` file is there to stop GitHub from running the page through Jekyll.

## Editing

Practice content lives in the HTML itself. Each day is a `<div class="day k-TYPE">`
with a warm-up line, the workout, and the cool-down. Workout types are
`k-hills`, `k-tempo`, `k-track`, `k-distance`, `k-shake`, `k-recovery`;
each one drives the stripe color and the chip label.
