# builders.zone plugin for Cursor

Connects Cursor (desktop, CLI and cloud agents) to the [builders.zone](https://builders.zone) MCP server: the cohort path, guides and prompts for the 5-day Athens bootcamp, and the boilerplate.

## What you get

- **MCP server** `builders-zone` at `https://builders.zone/api/mcp` (remote HTTP, OAuth).
- **Skill** `builders-zone`, which tells the agent which prompt or tool to use.

Tools include `bz_cohort_path`, `bz_get_resource`, `bz_list_resources`, `bz_mark_resource_done` and `bz_boilerplate`. Prompts include `start`.

## Setup

1. Install the plugin from the Cursor Marketplace.
2. Click **Connect** next to `builders-zone`, sign in with your builders.zone account and click **Allow**. No API key or token is stored in this repo.
3. In the chat, say **"start builders.zone"**.

You need a builders.zone account. Cohort resources need a cohort seat.

## Troubleshooting

| Problem | Fix |
| --- | --- |
| "Resources are for cohort members" or a 403 | Sign in with the account that has your cohort seat. |
| "Complete onboarding first" | Finish onboarding on builders.zone, then connect again. |
| Tools stopped working | Disconnect and connect again. |

More: https://builders.zone/mcp

## License

MIT
