# Borozdov Cabin

A theme from the Borozdov collection. Two faces — light **Postcard**, a cabin journal on
cream paper, and dark **Campfire**, the same journal by the fire. Whisper-light headlines,
pine-green ink for titles and links, marigold tags and an ember caret.

![Borozdov Cabin in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/cabin/main/screenshots/light.png)

![Borozdov Cabin in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/cabin/main/screenshots/dark.png)

## Principles

- **A whispered voice.** IBM Plex Sans Light for the title and headings, at weight 300
  with negative tracking and tight leading, so a headline reads as one shape; it is never
  bolded up. The platform's own sans for the text.
- **Pine green, calm authority.** The title, the largest heading, the open file and links
  are pine green; it never fills a button.
- **One bright punctuation.** Marigold for tags, the highlighter and the plain note;
  morning sky for the info callout; ember for the caret, like firelight against the cream.
- **Cream on cream.** Cards sit one tone above the paper with 20px corners; nothing casts
  a shadow. The main button is charcoal with 20px corners, plain buttons are pill links.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts as cream cards with the title in the type's colour; the plain note in marigold
- Pull quotes in the light headline face, a size up, behind a pine rule
- Tables as cream cards with 20px corners
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory:** Settings → Appearance → Themes → Manage, search for
**Borozdov Cabin**, then **Install and use**.

**By hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/cabin/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Cabin/`, then choose Borozdov Cabin under
Settings → Appearance → Themes.

## Font

IBM Plex Sans Light (© 2018 IBM Corp.) is embedded in `theme.css` as base64 WOFF2 under the
SIL Open Font License 1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). One weight, Latin and
Cyrillic, for the title, headings and pull quotes only.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Открытка» — журнал лесного
домика на кремовой бумаге, и тёмный «Костёр» — тот же журнал у огня. Лёгкие заголовки
(IBM Plex Sans Light), хвойно-зелёные чернила для названий и ссылок, золотистые метки и
огненная каретка. Устанавливается из каталога: Настройки → Оформление → Темы → Настроить →
Borozdov Cabin → Установить и применить.
