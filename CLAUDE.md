# CLAUDE.md — neo-candy-papirus-blue

## Project overview

Standalone repo for the **neo-candy-papirus-blue** folder-icon theme — the same folder set as
`erikdubois/surfn-papirus-blue` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-papirus-blue/` — folders only. Packaged as `neo-candy-papirus-blue-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-papirus-blue/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
