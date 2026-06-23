# CLAUDE.md — neo-candy-numixs

## Project overview

Standalone repo for the **neo-candy-numixs** folder-icon theme — the same folder set as
`erikdubois/surfn-numixs` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-numixs/` — folders only. Packaged as `neo-candy-numixs-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-numixs/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
