# Brand assets

| File | Use |
|------|-----|
| `app-icon-1024.png` | Full-resolution app icon (Teal, light), rendered from the same vector as the iOS icon. |

Everything else on the site draws the mark as inline SVG (`src/components/brand/app-mark.tsx`), so it stays sharp
and follows light and dark mode. The favicon (`src/app/icon.svg`, `src/app/favicon.ico`), the Apple touch icon
(`src/app/apple-icon.png`) and the Open Graph image (`src/app/opengraph-image.tsx`) use the same path.

**Source of truth:** `TrayTrack/AppIcon.icon/Assets/arch-upper.svg` and `arch-lower.svg` (icon background `#0B5F52`,
upper arch white at 40%, lower arch white; dark icon: arches `#3DD9C0` on a `#2A2C2E` to `#0F1011` gradient).
The same path is in `TrayTrackWidget/AlignersOutStyle.swift` (`AppMarkShape`). Regenerate these files if the icon changes.
