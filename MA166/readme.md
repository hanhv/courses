# MA 16600 — Calculus II

This folder contains the Fall 2026 MA 16600 course website.

## Structure

- `index.html` — Main course homepage and complete lesson list.
- `schedule.html` — Course schedule.
- `groundrules.html` — Course ground rules.
- `QuickStudentGuide.html` — Quick Student Guide.

### Shared Components

The `components/` folder contains HTML shared across the lesson pages:

- `header.html` — Shared header and navigation.
- `footer.html` — Shared accessibility notice and footer.

Changes to these shared files should automatically apply to all lesson pages.

### Lessons

The `lessons/` folder contains the individual lesson pages:

- `lesson01.html` through `lesson35.html`

Each lesson file should contain the lesson-specific content only. Shared header/navigation and footer content should not be duplicated in each lesson.

## Styling

The site uses the global stylesheet:

`https://hanhv.github.io/style.css`

The MA166 lesson pages use JavaScript to load the shared components from `components/header.html` and `components/footer.html`.