# Dojo

Small native macOS apps for study. Each folder holds a ready-to-run app as a zip.

| App | What it does |
|---|---|
| [Kana Dojo](KanaDojo/) | Learn hiragana and katakana: a clickable sound chart, a typed rōmaji drill that re-queues your misses, and flashcards. Speaks with the Mac's Japanese voices. |

## Installing

1. Download the zip from the app's folder and unzip it.
2. Drag the `.app` into your Applications folder.
3. The first time, **right-click the app and choose Open**, then click Open in the dialog.
   The apps are signed locally, not notarized by Apple, so a plain double-click is blocked by Gatekeeper on the first launch only.

Requires macOS 13 or later on Apple Silicon.

## Kana Dojo notes

- The app lists every Japanese voice installed on the Mac. Kyoko ships with macOS. For better ones (Otoya, O-Ren, Hattori), use **More voices…** in the toolbar, or System Settings → Accessibility → Read & Speak → the ⓘ button next to System Voice → Japanese.
- Progress (group selection, toggles, per-kana miss counts) is stored locally in the app and persists between launches.

## Fonts

Bundles [IBM Plex](https://github.com/IBM/plex) and [Klee One](https://github.com/fontworks-fonts/Klee), both under the SIL Open Font License 1.1.
