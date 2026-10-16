# Channel Wars 📺

**Channel Wars** is an original, single-file TV-station management game made for iPad, phone, and desktop browsers. Build your channel, schedule programs, attract viewers, run advertising campaigns, and compete against rival networks.

## Play

**[Play Channel Wars](https://mitchell-d00.github.io/channel-wars/)** *(available when GitHub Pages is enabled)*

Or download [`index.html`](index.html) and open it in a modern browser. The entire game—art, styling, logic, and data—is in **one HTML file**. No installation, external assets, account, or build step is needed.

## Features

- **Run a TV station:** Seven nightly broadcast slots, show licensing, ratings, advertising contracts, news programming, upgrades, and loans.
- **Outsmart rival channels:** Compete for audience share and track nightly reports.
- **Choose your station name:** Pick a custom network name or generate one randomly.
- **Rename the shows:** Edit the names of 32 programs individually or bulk-import a `.txt` file.
- **Original animated cutscenes:** Illustrated scenes introduce your station and celebrate milestones. Toggle cutscenes and effects in Settings.
- **Settings:** Station identity, light/dark mode, animations, story scenes, and show-title editor.
- **Play offline:** The game saves locally in your browser; use the in-game export/import tools to move your save between devices.

## Rename shows using a text file

Go to **⚙ Settings → TV show name editor**. Download your custom title list as a `.txt`, edit it, then upload it back into the game. You can edit titles directly in Settings, too.

Example:

```text
starlight = Neon House
midnight = Mystery District
cosmos = A Tour of the Universe
```

Keep the IDs to the left of `=` unchanged. You can rename only the shows you want. Alternatively, upload 32 titles, one per line, in the catalog's order.

**Note:** The show-title `.txt` file changes only program names. Your actual game progress is exported/imported separately as JSON.

## Files

| File | Purpose |
| --- | --- |
| [`index.html`](index.html) | **The one and only game file** — playable offline and served by GitHub Pages |
| [`LICENSE`](LICENSE) | MIT license |
| `.nojekyll` | Keeps GitHub Pages deployment simple |

There are no separate older-game or duplicate standalone HTML builds in this repository.

## Save compatibility

Channel Wars continues using the earlier browser save-storage identifier to keep existing players' progress and customizations. Despite the internal compatibility identifier, this repository contains **only Channel Wars**.

## Project status

A browser-first, offline simulation inspired by the classic TV management genre. All shows, channel brands, dialogue, and illustrations are original. This is not a release of *Mad TV*, TVTower, or their assets, and it is not an official OpenAI product.

## License

MIT; see [LICENSE](LICENSE).
