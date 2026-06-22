# Documentation project instructions

This is the public Mintlify documentation site for getbased.

## Public-content boundary

- Do not commit real credentials, tokens, private keys, or unredacted environment files.
- Do not include personal names, local machine paths, private chat/channel IDs, private health context, or internal deployment notes.
- Use inert placeholders such as `your-token-here`, `https://your-host.example`, and `***` for examples.
- Keep internal agent handoff notes out of this repo unless they are deliberately public-safe.

## Project shape

- Pages are MDX files with YAML frontmatter.
- Navigation lives in `docs.json`.
- Use sentence-case headings and plain language.
- Use bold text for UI labels, and code formatting for commands, files, paths, and env var names.

## Verification

Before publishing, check JSON syntax, internal links/navigation, MDX parse safety, and public-data hygiene. After pushing, verify the Mintlify check run and live route.
