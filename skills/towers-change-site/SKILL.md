---
name: towers-change-site
description: Change a Towers company's website. Use when the owner asks to edit, fix or update their Towers site, change its text, prices or images, add a page or a feature, or redesign it.
---

# Changing a Towers website

Choose the way by the size of the change.

**A few lines** (a word, a price, a link, a heading):
1. `files` to find the file, `read_file` to read it.
2. `edit_file` with an `old` text that appears exactly once, or `write_files` for whole files. The version before is kept.
3. `deploy` to publish `site/`. Towers checks the pages on a phone and a computer first. It answers with a deploy id (`dp_…`): follow it with `status` until it's live.

**Anything bigger** (a page, a feature, a redesign, server code under `code/`):
1. Call `code` with a clear brief: what to build, where it goes, and how it should look and work when it's done. Add a short `title`.
2. Each coder run uses the owner's mission credits, and an account's first 3 runs are free: tell them before the first paid one.
3. Follow the run with `status` (`tm_…`). It usually takes under half an hour.

When a change is live, `site_preview` shows the site as a phone does, so they can see it.
