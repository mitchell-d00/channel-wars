# Channel Wars — TV Station Management Simulator

**Channel Wars** is a detailed, original, offline, single-HTML TV network management game inspired by classic broadcast tycoon games.

> **GitHub About description (copy to repository settings):**
> An offline, single-file TV station tycoon for iPad and desktop. Schedule shows, sell ads, outsmart rival networks, watch animated cutscenes, and customize your station and programs.

## Play

- **Browser (once GitHub Pages is enabled):** https://mitchell-d00.github.io/OpenAI-TV/
- **Offline:** Download `Channel-Wars.html` or `index.html` and open it in Safari, Chrome, or another modern browser.
- **No installation or accounts.** The complete game, graphics, code, data and styles are bundled inside each HTML file.

## Channel Wars gameplay

Manage one independent television station across an eight-room headquarters. Purchase broadcasting licenses for 32 fictional programs, build a seven-hour schedule, sign advertising contracts, commission newsroom packages, invest in upgrades, borrow money and compete against three rival channels. Follow hourly audience ratings, profits, network reputation and an expanding career record.

## New in this edition

- **Channel Wars** branding throughout the game
- Original illustrated SVG **animated story cutscenes** for the city, staff meeting, control room, ratings battle and major milestones; animations respect the reduced-motion preference
- **Random station names** on new games, or enter your own station name in Settings
- **Full Settings menu** with light/dark themes, animated graphics and story toggle, and introduction replay
- **Show-name editor:** rename any or all 32 shows from within the app
- **Text file support:** download your own `.txt` show-name file, edit it, upload it later, or reset the show titles
- **Existing saves kept:** the previous OpenAI TV local save key is preserved and its data migrated in memory as needed
- Touch-friendly responsive UI with no horizontal overflow at 390px testing

### Upload your own show list

Open **⚙ Settings → TV show name editor**. You can edit the name list directly and press **Apply names**, or press **Save as .txt** to download a template. Modify it with any text editor, then press **Upload .txt**.

```text
# The left-hand show IDs must stay unchanged
starlight = Neon House
midnight = Mystery District
cosmos = A Tour of the Universe
```

You can also supply a plain list of 32 titles in catalog order (one per line). Show-name changes persist with game saves and are included in exported JSON save files.

## Files

- `index.html`: the entire game and GitHub Pages entrypoint
- `Channel-Wars.html`: offline standalone with the new brand
- `OpenAI-TV.html`: backwards-compatible filename containing the same current game
- `LICENSE`: MIT license

## Name change and GitHub Pages

The game has been renamed to **Channel Wars**. GitHub repository renaming and its About description must be changed in the repo settings by an administrator. Recommended repository slug: `channel-wars` (GitHub is case-insensitive). Once renamed, GitHub Pages will be expected at `https://mitchell-d00.github.io/channel-wars/` after it is configured and deployed.

## Credits

An original game **inspired by the TV management simulation genre**. This game does not include original *Mad TV* or TVTower artwork, game assets, or source code, and is not officially affiliated with OpenAI or Rainbow Arts.
