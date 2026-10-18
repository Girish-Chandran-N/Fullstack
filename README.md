# Operation Full Stack — Kerala Edition

Three files, one plan: intern → full-stack developer in ~32 weeks, tuned for the Kerala / South India market (and the big Indian IT hubs).

## What's in here

| File | What it is | How to use it |
|---|---|---|
| **Full-Stack-Roadmap-Kerala.html** | The visual roadmap: 9 seasons, 148 checkpoints, verified YouTube courses, projects, schedule, job-hunt playbook, interview bank, cheat sheets, motivational art & memes. | Open it in any browser (double-click). Tick boxes as you finish topics — progress saves in your browser. Buttons: hide completed, collapse checklists, save as PDF, reset. Works offline. |
| **Full-Stack-Study-Tracker.xlsx** | The working tracker: Dashboard, 148-row Study Tracker, 32-week Weekly Log (pre-dated from Mon 19 Oct 2026), Projects, DSA Log (150 slots), Job Applications (200 rows), Interview Prep (40 questions), Resources, Cheat Sheet, Skills. | Open in Excel / LibreOffice / Google Sheets. Only fill the white cells — the dashboard is formula-driven. |
| **assets/** | The motivational artwork (hero, boss, victory) plus the anime meme images (DBZ, Naruto/Rock Lee, Solo Leveling, My Hero Academia, Attack on Titan). | Optional — every image is already embedded in the HTML, so the page works offline. |
| **image-search/** | Original downloaded meme files before cropping. | Safe to delete. |

## The plan in one paragraph

**Season 1 (W1–2)** Git + HTML/CSS pro → **Season 2 (W3–7)** JavaScript deep dive → **Season 3 (W8–11)** React + TypeScript + Tailwind → **Season 4 (W12–16)** Node + Express + MongoDB (JWT auth, deployed API) → **Season 5 (W17–18)** SQL + Python/Django → **Season 6 (W19–22)** capstone + Docker + CI/CD → **Season 7 (ongoing)** 45 min DSA daily → **Season 8 (W23–24)** Power BI → **Season 9 (W25–32)** portfolio, resume, 300 targeted applications, referrals, mock interviews.

Weekly load: **6 h × 4 weekdays + 1 project day = ~30 h/week.**

## Three rules that decide whether this works

1. **70/30 rule** — 70% of study time is building, 30% watching. Every video ends with the tab closed.
2. **One boss per season** — no new phase until the current deliverable is deployed with a live URL.
3. **Apply wider than Kerala** — 70% Kerala (Infopark/Technopark/Cyberpark) + 30% Bengaluru/Chennai/Hyderabad/remote.

## Anime motivation checkpoints

The page now opens with a **Training Arc** ribbon (DBZ / Naruto / Solo Leveling), then keeps the energy going:

- **Naruto "nindō" divider** before the roadmap — *never skip two days in a row*
- **My Hero Academia "PLUS ULTRA"** mid-boss card after Season 4, at the point where most people quit
- **Solo Leveling "ARISE"** banner over the project ladder
- **Attack on Titan (Levi)** banner in the job-hunt section
- **Anime meme wall** in the motivation section (Goku, Rock Lee, All Might, Levi, Solo Leveling)

## Upgraded in this version

- **Fixed Phase Progress Bar Bug**: Individual phase card progress bars previously failed to fill because the percentage unit (`%`) was missing in the CSS width calculation (`fillEl.style.width = p + '%'`).
- **Responsive Sticky Glassmorphic Navbar**: Single-row, fixed-height (66px desktop / 60px mobile) sticky header that never wraps or clips. Includes glowing logo, Kerala '26 badge, desktop pill links, RPG Hunter Rank indicator (`🌱 E-Rank` → `👑 S-Rank`), and real-time interactive gradient progress line at the header bottom.
- **Mobile & Tablet Navigation Drawer**: On screens ≤ 960px, desktop links seamlessly collapse into an animated hamburger button that reveals a frosted glass drawer with section navigation, live progress card, and quick action toolbar.
- **ScrollSpy Navigation**: Section links dynamically highlight as you scroll through the page on both desktop and mobile drawer.
- **Comprehensive Mobile & Tablet Layout**: Optimized grids and touch targets across all viewports (Hero, Anime ribbons, Arc dividers, Stats, Schedule, Projects, Job hunt, Cheat sheet tables, and Motivation memes). Checkboxes have comfortable 44px+ tap targets.
- **Modern Typography**: Integrated Google Fonts (`Outfit` for bold display headings, `Plus Jakarta Sans` for clean body text, `JetBrains Mono` for code/shortcuts).
- **Checklist clicks no longer jump the page**: Scroll guard on every checkbox and clean element IDs.

## Note on accuracy

All YouTube videos, playlists and PDF cheat sheets were verified to exist when this was built (Oct 2026). Salary and demand figures come from 2026 hiring reports, live Infopark listings and salary aggregators — treat them as directional, not guarantees.
