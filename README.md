# 🧠 Brain Dump

A quick-capture notepad for ADHD thoughts: get it out of your head now, sort it later.

**Open / install:** https://frontiersmanfinished.github.io/brain-dump/

## Install on Android
1. Open the link above in **Chrome**.
2. Tap **⋮ → Install app** (or **Add to Home screen → Install**).
3. It appears in your app drawer with the brain icon and opens full screen, even offline.

Each phone keeps its **own** notes. Nothing is sent to a server. The app's code is public, but your notes never leave the device.

## Using it
- Type and press **Enter** to save (Shift+Enter for a new line). Start with `!` to mark it important.
- Optional labels: To-do, Follow up, Idea, Question, Remember. Add `#tags` anywhere.
- Tick the checkbox when you've dealt with something. Undo is available for a few seconds.
- 🎲 **Pick one for me** chooses a single open item when the list feels like too much.
- Anything open for 7+ days gets a gentle "sitting X days" note.

## Backups
Notes live only on the device, so use **Back up** (bottom of the page) now and then. On Android it opens the share sheet. Save it to Google Drive or email it to yourself. **Restore** merges a backup back in without creating duplicates, which also works for moving notes to another phone or computer.

If you uninstall the app or clear Chrome's site data, notes are deleted unless you have a backup.

## Files
| File | Purpose |
|---|---|
| `index.html` | The whole app (HTML, CSS, JS in one file) |
| `manifest.webmanifest` | Makes it installable: name, colours, icons |
| `sw.js` | Service worker: lets the app open offline and pick up updates |
| `icons/` | App icons (`icon.svg` is the source) |

To release a change: edit the files, then bump `VERSION` in `sw.js` so phones refresh their saved copy.
