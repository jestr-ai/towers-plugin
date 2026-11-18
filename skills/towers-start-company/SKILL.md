---
name: towers-start-company
description: Start a new company on Towers from an idea. Use when the owner wants to start a business, launch an idea, open a new company, or turn a project they're working on into a company with its own website.
---

# Starting a company on Towers

1. Get the idea in a sentence or two: what it is, who it's for, and what it does. If it's the project you're working on together, describe that project (and give its address, if it has one).
2. Opening a company costs 300 Towers credits from their balance, and their first company is free. Tell them before you start it, and go on when they agree.
3. Call `start` with the idea in their words. It answers at once with a start id (`st_…`).
   - If it answers `needs_plan`, they don't have the credits: give them the link it returns, as it is, and stop.
   - If a start is already running, follow that one first.
4. Follow it with `status` (run: the `st_…` id) every minute or two, and tell them each new line it says: the name Towers chose, who it's for, its address, the website being built. It takes about 5 to 10 minutes.
5. When it's ready, give them the company's name and address. No ads are made or started when a company opens; offer `run_ads` to get its ads ready (see the towers-ads skill).

To go on with a company that is still at its first steps (one the server lost, or one they left in the app), call `start` with `site` instead of `idea`. It costs nothing.
