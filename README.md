# Amani Secondary — School Management System

A lightweight, browser-based school management system built with plain **HTML, CSS, and JavaScript** — no frameworks, no build step, no backend required to run.

## Features

- **Dashboard** — live totals for students, staff, fees collected, and outstanding balances
- **Students** — admit, edit, remove, search and filter by form
- **Teachers** — manage staff records and class-teacher assignments
- **Attendance** — mark and save a daily register by form
- **Fee Ledger** — record payments, track balances, block over-payment

## Tech Stack

- HTML5
- CSS3 (custom properties, flexbox, grid)
- Vanilla JavaScript (ES6+, no dependencies)

## Getting Started

No installation needed — it's a single static file.

```bash
git clone https://github.com/<your-username>/school-management-system.git
cd school-management-system
```

Then just open `index.html` in a browser, or serve it locally:

```bash
# Python
python3 -m http.server 8000

# Node (http-server)
npx http-server .
```

Visit `http://localhost:8000`.

## Project Structure

```
school-management-system/
├── index.html     # entire app: markup, styles, and logic
└── README.md
```

## Notes

- Data is held in memory for the session only (no `localStorage` / backend) — refreshing resets it to the sample data.
- To persist data in production, add a backend (e.g. Node/Express + MySQL) and wire the CRUD functions in `index.html` to API calls.

## License

MIT