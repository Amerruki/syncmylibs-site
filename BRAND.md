# SyncMyLibs brand

How SyncMyLibs looks and speaks outside the app. In-app design law lives in the app repo.

## Idea

Everything derives from the app icon: two glass library tiles, pink behind and blue in front, leaning toward each other over a deep navy ground, with one dusk photo where they cross. The site should feel like the icon: glassy, fluid, translucent.

## Color

| Token | Value | Role |
|---|---|---|
| Navy, top / bottom | `#18214A` / `#080B1A` | The page ground, a vertical gradient like the icon's |
| Pink glow | `rgba(214, 96, 160, 0.22)` | The back tile, as a soft wash |
| Blue glow | `rgba(74, 132, 222, 0.24)` | The front tile, as a soft wash |
| Ink | `#F2F3FA` | Text |

Dark only. The sun amber stays in the icon.

## Type

SF Pro (`-apple-system`). No all-caps labels, no tracked-out kickers, no monospace strips.

## Voice

Short and confident. Say what it is, never list what it lacks. Never imply it can be downloaded or bought before it can.

Never use: em dashes, middots or dashes as separators, eyebrows above headings, "supercharge", "seamless", "blazingly", "AI-powered", or a release step dressed as a feature (signing, notarization).

## Icon

`/icon.png` is the icon macOS shows for the installed app: the Liquid Glass render compiled from `Resources/AppIcon.icon` in the app repo, taken with `NSWorkspace.shared.icon(forFile: "/Applications/SyncMyLibs.app")` at 1024px and scaled to 512px. Do not use the flat `Resources/AppIcon.icns`; it is the fallback for older macOS and looks different.
