# Asset credits

Every file in this folder is a **placeholder for prototyping**, except `art/`. Milestone 4 replaces the art with original Aseprite work (see `docs/technical.md`, Assets).

`art/` holds that original work, drawn for this game and exported from the Aseprite sources in the repo's `art/` folder. It uses the [Resurrect 64](https://lospec.com/palette-list/resurrect-64) palette by Kerrie Lake. So far it holds the mouse heroes, Chompies (eight looks), all nine heroes' weapons, the items, the effects, the UI icons, the card panels, the touch icons, and every enemy and boss of Cheddar Keep and Muenster's Den; the 0x72 pack still supplies TynoDynoRhyno.

Every pack below is **CC0 1.0** ([public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/)). Commercial use is allowed and credit is not required, but we give it anyway. Each pack keeps its original licence file next to its files where it shipped with one.

Downloaded 2026-11-20. Only the files the game loads are kept here, with each pack's licence file. Everything in this folder is copied into the web build, so the original zips live in the git-ignored `downloads/` folder at the repo root, never in here.

## Sprites

| Folder | Pack | Author | Source | Contents |
| --- | --- | --- | --- | --- |
| `sprites/0x72-dungeontileset-ii/` | 16x16 DungeonTileset II (v1.7) | 0x72 | [itch.io](https://0x72.itch.io/dungeontileset-ii) | Animated characters (4-frame idle and run, a hit frame for heroes), bomb, flasks. Its weapons are no longer used. No licence file shipped; CC0 per the source page ("use this tileset for whatever you like (CC-0)"). `atlas.json` is generated from the pack's `tile_list_v1.7` for Phaser. Downloaded 2026-11-20 |

## Fonts

| Folder | Font | Author | Source | Contents |
| --- | --- | --- | --- | --- |
| `fonts/m5x7/` | m5x7 | Daniel Linssen | [itch.io](https://managore.itch.io/m5x7) | Pixel TTF, 16 px line height; draw at 16 px or whole multiples. Fetched from the CC0 [m5x7 crate](https://crates.io/crates/m5x7) because itch.io was rate-limiting; same file size as the itch.io upload |

## Audio

| Folder | Pack | Author | Source | Contents |
| --- | --- | --- | --- | --- |
| `audio/sfx/kenney-interface-sounds/` | Interface Sounds | Kenney | [kenney.nl](https://kenney.nl/assets/interface-sounds) | Four of the 100 menu sounds kept: `tick_001`, `confirmation_001`, `back_001`, `error_001`. Licence file kept |
| `audio/sfx/kenney-rpg-sounds/` | 50 RPG Sound Effects | Kenney | [OpenGameArt](https://opengameart.org/content/50-rpg-sound-effects) | Ten of the 50 kept: `knifeSlice`, `chop`, `metalPot2`, `metalLatch`, `cloth3`, `bookFlip1`, `handleCoins`, `drawKnife1` to `drawKnife3`. Licence file kept |
| `audio/sfx/kenney-music-jingles/` | Music Jingles | Kenney | [kenney.nl](https://kenney.nl/assets/music-jingles) | Four files loaded, all Steel jingles: `jingles_STEEL09.ogg`, the "You fell" sting (`sfx.fall`); `jingles_STEEL08.ogg`, floor cleared (`jingle.floor`); `jingles_STEEL07.ogg`, rescue fanfare (`jingle.rescue`); `jingles_STEEL02.ogg`, dungeon cleared and the win screen (`jingle.victory`). Licence file kept. Downloaded 2026-11-21; `jingles_STEEL02.ogg` on 2026-11-26 from [OpenGameArt](https://opengameart.org/content/85-short-music-jingles) (Kenney's CC0 upload; its copies of the other three match byte for byte) |
| `audio/sfx/kenney-impact-sounds/` | Impact Sounds | Kenney | [kenney.nl](https://kenney.nl/assets/impact-sounds) | Two files loaded: `impactSoft_heavy_000.ogg`, the enemy-defeated thud (`sfx.defeat`), and `impactPunch_heavy_000.ogg`, the hit of 3 or more damage (`sfx.hit.heavy`). Licence file kept. Downloaded 2026-11-21 |
| `audio/music/juhani-junkala-chiptune-adventures/` | Chiptune Adventures | Juhani Junkala | [OpenGameArt](https://opengameart.org/comment/70103) | Three OGG loops: `stage-select.ogg` (`music.hub`), `stage-1.ogg` (`music.battle`), `boss-fight.ogg` (`music.boss`). `INFO.txt` kept (CC0: "released under CC0 creative commons license"). Downloaded 2026-11-21 |
| `audio/music/juhani-junkala-action-chiptunes/` | 5 Chiptunes (Action) | Juhani Junkala | [OpenGameArt](https://opengameart.org/comment/97025) | One file loaded: `title-screen.wav` (`music.title`; the pack ships WAV only). `INFO.txt` kept (CC0). Downloaded 2026-11-21 |

## Credits line for the game

> Placeholder art and audio by 0x72, Kenney (kenney.nl) and Juhani Junkala; m5x7 font by Daniel Linssen. All CC0.

A pack trimmed here can be downloaded again from its source link into `downloads/` when a new sound or sprite is needed.

## Install icons

`icons/` holds the home-screen icons (192, 512 and the 180 px apple-touch-icon): the original app icon, a cheese wedge with a heart-shaped hole, exported from `art/ui/appIcon.aseprite` by `npm run art:export`. `manifest.webmanifest` is the web app manifest.
