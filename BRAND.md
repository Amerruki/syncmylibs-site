# SyncMyLibs brand

How SyncMyLibs looks and speaks outside the app. In-app design law lives in the app repo.

## Idea

Everything derives from the app icon: two library tiles, pink behind and blue in front, leaning toward each other over a deep navy ground, with one dusk photo where they cross. Two libraries, one photo.

## Color

| Token | Value | Role |
|---|---|---|
| Pink | `#8E4A7C` | The back tile. Paired with blue, never alone |
| Blue | `#3D64AA` | The front tile. Text selection and any accent |
| Light bg / ink | `#F7F6F9` / `#15192E` | Page base, light |
| Dark bg / ink | `#0D1124` / `#ECEEF6` | Page base, dark |

The sun amber in the icon stays in the icon. Success and error follow macOS system colors.

## Type

- Headlines: New York (`ui-serif`), weight 600, tight leading. Fallback Georgia.
- Body: SF Pro (`-apple-system`), 18px base.
- No all-caps labels, no tracked-out kickers, no monospace "fact" strips.

Every reader is on an Apple device, so Apple's own faces cost nothing to load.

## Layout and motion

One narrow column. No glass cards, grain, fake app windows or icon grids. One entrance on load, off under `prefers-reduced-motion`.

## Voice

Say what the app does in plain sentences, then say where it falls short. Claim only what the app does today, and never imply it can be downloaded or bought before it can.

Never use: em dashes, middots or dashes as separators between phrases, eyebrows above headings, "supercharge", "seamless", "blazingly", "AI-powered", or a feature that is really a release step (signing, notarization).

## Icon

Drawn from geometry by `Tools/IconGen/icon.py` in the app repo, which writes `Resources/AppIcon.icns`. The site's `/icon.png` is the 512px rendition from that file (`iconutil -c iconset`). Regenerate there and re-export; never hand-edit.
