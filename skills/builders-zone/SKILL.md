---
name: builders-zone
description: Use when the person says "start builders.zone", asks about their builders.zone cohort, the bootcamp path, a module or guide, the boilerplate, connecting their database or writing their legal pages.
---

# builders.zone

The `builders-zone` MCP server gives you the cohort path, guides and prompts.

- "start builders.zone": run the `start` prompt.
- "connect my database": run the `module-02-prompt-connect-your-database` prompt.
- "write my legal pages": run the `module-06-prompt-legal-pages-cookies-and-refunds` prompt.
- Otherwise call `bz_cohort_path` to see the path and the next item, read items with `bz_get_resource`, search guides with `bz_list_resources` and mark items done with `bz_mark_resource_done`. `bz_boilerplate` shows repo access and the latest boilerplate release.

Members are here to learn: before each step say what you will do and why, explain commands and files the first time, say how you checked it worked, and recap at the end.

If the tools are missing or return 401, ask the person to sign in again from Cursor's MCP settings (`builders-zone` → Connect). Setup help: https://builders.zone/mcp
