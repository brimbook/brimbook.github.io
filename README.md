# Brim Book

Make Valorant Brimstone lineup posters and keep them in your own lineup book.

**Use it:** https://henry-bonikowsky.github.io/brim-book/

1. Hit **+ New lineup**. Add 4 screenshots: location, minimap, reference (where to aim), land spot. Snip them and paste with Ctrl+V, drop them, or pick files.
2. Fill in the land time. For post-plant lineups the poster gets a beep box: how many spike beeps after the speed-up to wait before you shoot, so a full defuse, a half defuse, or a tanked defuse can't finish. For anti-Phoenix lineups it shows when to shoot after he ults.
3. **Save to book** or **Download PNG**.

## Your data stays in your browser

There is no server and no account. Lineups are stored in this browser only (IndexedDB). Clearing site data or switching browsers/devices means they're not there.

**Export book** saves everything to one `.json` file: use it to back up, move to another device, or trade books with a friend. **Import book** merges a file into your book; it never deletes anything and skips lineups you already have.

One `index.html`, no build step, no dependencies.
