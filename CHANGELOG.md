# Changelog

## 2026.06.23 — Papirus blue folder colour

### What Changed

Initial repo. The **neo-candy-papirus-blue** folder icons were recoloured to **blue** from the Papirus icon theme
and ship as `neo-candy-papirus-blue-icons-git`, depending on `neo-candy-icons-git`.

### Files Modified

- Initial scaffold + usr/share/icons/neo-candy-papirus-blue/

### Public folder icon (folder-publicshare)

Added `folder-publicshare` to the special-folder set so the **Public** folder no longer
falls back to a generic icon. Copied this variant's own colour-matched
`folder-image-people.svg` (folder + person headshot) to `folder-publicshare.svg` at
sizes 22–64, and `folder.svg` at 16px (headshot is illegible at that size).

### Files Modified

- usr/share/icons/neo-candy-papirus-blue/{16x16,22x22,24x24,32x32,48x48,64x64}/places/folder-publicshare.svg (new)

### Desktop folder icon (user-desktop)

Added `user-desktop` so the **Desktop** folder no longer falls back to a generic icon.
Copied this variant's own colour-matched `folder-desktop.svg` (the tinted monitor) to
`user-desktop.svg` at sizes 22–64, and `folder.svg` at 16px (monitor is illegible at
that size).

### Files Modified

- usr/share/icons/neo-candy-papirus-blue/{16x16,22x22,24x24,32x32,48x48,64x64}/places/user-desktop.svg (new)
