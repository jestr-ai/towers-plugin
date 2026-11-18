# Towers for Claude

Towers runs companies for their owners: each one has its own website, its numbers, its missions (work Towers' agents do for it) and its ads. This plugin lets you run your Towers companies from Claude.

## What's in it

- **The Towers connector** at `https://towers.app/mcp/claude`: the same connector as the Towers listing in Claude's connector directory. You sign in to Towers and allow it once.
- **Four skills** that teach Claude how to work with it:
  - `towers-check-in`: how your companies are doing, what happened since yesterday, what waits for you
  - `towers-start-company`: start a new company from an idea (its name, who it's for, its price, its address and its website)
  - `towers-change-site`: change and publish your website, or hand a bigger change to Towers' coder
  - `towers-ads`: get your Facebook and Instagram ads ready as a mission you start in the Towers app

## Use it

Install it from Claude's directory (**Customize → Plugins**, search for Towers), or in Claude Code load this repository with `claude --plugin-dir`. Connect Towers from the plugin's Connectors tab (or let Claude Code connect it), sign in to Towers and select **Allow**. Then ask, for example:

- "How did my Towers companies do this week?"
- "Start a company that helps landlords collect rent."
- "Add a pricing page with three plans to my site and put it live."
- "Get ads ready for my company."

You need a Towers account, free to start at [towers.app](https://towers.app). Opening a company costs 300 Towers credits (your first is free), and each change by Towers' coder uses mission credits (your first 3 are free).

## What it doesn't do

Missions, ads included, start only when you start them yourself in the Towers app; Claude gives you the link. The plugin doesn't make images, video or audio, doesn't run ads, and doesn't move money.

## Data

The plugin runs nothing on your computer. Its skills are instructions for Claude, and its connector sends Claude's requests (which tool, and what it asked) to Towers at towers.app over HTTPS, with the access you allowed. Towers keeps a record of those requests to run the service and fix problems; it never gets your conversations with Claude. See the [Towers privacy policy](https://towers.app/privacy) and the [connector docs](https://towers.app/docs/claude). Disconnect any time in the Towers app or in Claude.

## Help

Write to matan@towers.app.

## License

MIT, see [LICENSE](LICENSE).
