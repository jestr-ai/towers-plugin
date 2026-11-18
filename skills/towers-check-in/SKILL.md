---
name: towers-check-in
description: Check on the owner's Towers companies. Use when they ask how their business, company or website is doing, what happened since yesterday, how many visitors or sign-ups they got, what is waiting for them, or what to do next on Towers.
---

# Checking on Towers companies

Use the Towers connector's tools, and only the numbers they return: never estimate or round a number into something it isn't.

1. Call `my_sites` to see their companies. `current` is the one the other tools use when `site` isn't given; when they name another company, pass its name or id as `site`.
2. Pick the view that answers the question:
   - "How was yesterday?", a morning check: `today`
   - Trends, "this week", visitors and sign-ups over time: `numbers`
   - One company in full: `company`
   - Their credits: `credits`
3. Call `next` for the company's missions. Say which ones wait for the owner, which are running, and what finished. With `mission`, `next` gives one mission in full.
4. Answer in a few sentences: the one thing that matters most (a jump or a drop, a mission done, a mission waiting for them), then one or two next steps they could take, such as:
   - `improve`, so Towers' research team suggests new missions
   - `run_ads`, to get ads ready (see the towers-ads skill)
   - a change to the site (see the towers-change-site skill)

A mission starts only when the owner starts it in the Towers app. When one waits for them, give them its link from `next`: it opens the mission in Towers with an arrow at its button.
