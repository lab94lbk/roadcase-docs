# Documentation project instructions

## About this project

- This is the documentation site for **Roadcase**, a tour management platform for musicians, bands, and crews
- Built on [Mintlify](https://mintlify.com) with MDX pages and YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links
- The Roadcase application codebase lives at `~/code/roadcase` (Rails 8.1 + React 19 + TypeScript)

## Terminology

- Use "artist" not "band" or "act" (artist is the Roadcase term for the entity being managed)
- Use "team member" not "user" when referring to people within an artist
- Use "administrator", "member", or "crew" for the three role types (always lowercase)
- Use "show" not "gig" or "concert"
- Use "deal" not "contract" when referring to financial arrangements for shows
- Use "advance" not "tech pack" for the show advance process
- Use "block date" not "time off" or "unavailable date"
- Use "road crew" not "touring crew"
- Use "EPK" or "Electronic Press Kit" (capitalize both)
- Use "Pro" (capitalized) when referring to the Pro plan tier
- Use "Basic" (capitalized) when referring to the Basic plan tier
- Do NOT reference "routing" or "autorouting" — this feature has been removed

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Use the `<Snippet file="pro-badge.mdx" />` snippet at the top of any Pro-only feature page
- Use tables for field/setting descriptions rather than prose
- Use `<CardGroup>` for navigation links to related pages
- Use `<Steps>` for sequential workflows
- Use `<Tip>`, `<Note>`, `<Warning>` callouts sparingly and only when the information is genuinely important
- Audience is end users (musicians, managers, crew) — not developers
- Assume no technical background; explain music industry concepts where helpful

## Content boundaries

- Do NOT document internal admin/super-admin features
- Do NOT document the REST API (no public API docs at this time)
- Do NOT document routing, autorouting, travel legs, or lodging — these features have been removed
- Do NOT reference specific code, database schemas, or implementation details
- Do document all user-facing features across both web and mobile
- Do mark Pro-only features clearly with the pro-badge snippet
- Do cross-link between related pages where it helps the reader
