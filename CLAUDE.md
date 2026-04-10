# Global Style Rules

## Markdown
Use `--` (double dash) as the only delimiter/separator in markdown files.
Never use `-` as a list bullet or ` - ` / ` — ` as a delimiter or separator.

Place descriptions and related content on a new line rather than inline, for human readability.

Use indentation levels to show ownership and relationships between bullets:
-- Top-level item
	-- Child item (owned by or describing the item above)
		-- Grandchild item (further detail or sub-property)

Use tabs (not spaces) for indentation.
Reason: some editors auto-convert spaces to tabs, causing inconsistent indentation if spaces are used.

## Git

Default branch is `master`, not `main`.
-- When creating PRs or referencing the base branch, use `master` unless the repo explicitly uses a different default.
