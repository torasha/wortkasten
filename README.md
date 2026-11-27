# Wortkasten

A free vocabulary trainer that runs in the browser and works offline. You learn with exercises instead of flashcards: choosing, matching, writing, dictation, building words from letters, filling gaps in sentences, building sentences and picking der/die/das. Spaced repetition then brings every learned word back after 2, 5, 8, 15 and 30 days.

**Open the app:** https://torasha.github.io/wortkasten/
**News, new dictionaries and tips:** Telegram channel [@wortkasten](https://t.me/wortkasten) (in Russian)

No account, no ads, no tracking. Your words and progress stay on your device.

---

## 1. Put Wortkasten on your home screen

Once installed, Wortkasten opens like an ordinary app in its own window and keeps working without internet.

**iPhone / iPad (Safari)**
1. Open https://torasha.github.io/wortkasten/ in **Safari** (other browsers on iPhone cannot install web apps).
2. Tap the **Share** button (the square with an arrow).
3. Scroll down and tap **Add to Home Screen**, then **Add**.

**Android (Chrome)**
1. Open the link in **Chrome**.
2. Tap the **⋮** menu in the top right corner.
3. Tap **Install app** (or **Add to Home screen**) and confirm.

**Computer**
- **Chrome or Edge:** click the install icon at the right end of the address bar (a small screen with an arrow), or open the **⋮** menu → **Cast, save and share** → **Install page as app**.
- **Safari on Mac (macOS Sonoma or later):** **File** → **Add to Dock**.

> **Important:** progress is stored in the browser on this one device. The app on your phone and the app on your computer do not share progress. Before clearing Safari data or changing your phone, make a backup: **Settings → Data and backup → Make a backup**. You can restore it on any device.

---

## 2. Load a dictionary

### A ready-made dictionary
1. Open **Dictionaries** → **Load dictionary**.
2. Under **Ready-made dictionaries**, pick one for your level and tap **Choose**.
3. Make sure the dictionary is switched on (the toggle next to its name), then go to **Learn**.

### Your own dictionary
You can load an **Excel file (.xlsx)**, a **CSV or TSV file**, or simply **paste a list** (a Quizlet export works as it is).

1. Open **Dictionaries** → **Load dictionary**.
2. Give the dictionary a name, then choose a file or paste your list.
3. Tap **Next**, check which column is which (word, translation, example …) and load.

**Columns, in this order:**

| Column | Required | Example |
|---|---|---|
| Word (in the language you are learning) | yes | `die Entscheidung` |
| Translation | yes | `decision` |
| Example | no | `Das war eine schwere {Entscheidung}.` |
| Example translation | no | `That was a hard decision.` |
| Example 2, translation 2, example 3, translation 3 | no | |

The separator can be a tab, a semicolon, a comma or a dash. A pasted list can be as simple as one word per line:

```
die Stelle — position, place
reliable [rɪˈlaɪəbl] — dependable
sich erinnern an A — to remember
```

**A few tips**
- **Gap exercise:** put the word as it appears in the example in curly braces: `Ich {nehme} an einem Kongress {teil}.` Often the app finds the word by itself, but braces are always safe.
- **der/die/das exercise:** write nouns with their article: `das Haus`.
- **Transcription:** add it in square brackets after the word, e.g. `cat [kæt]`. It is shown next to the word and never has to be typed.
- **Language and voice:** each dictionary can have its own language (**Dictionaries → Language**). It sets the voice for pronunciation and the keyboard layout.
- **A few words after a lesson:** tap **+** next to the app name to add words one by one or as a list.

The full manual is built into the app: **Help**, available in English, German and Belarusian.

---

## Licence and credits

- Code: MIT licence (see `LICENSE`).
- Ready-made dictionaries in the `dict` folder: CC BY 4.0 (see `dict/README.md`).
- Excel files are read with SheetJS (Apache 2.0). Fonts: Golos Text and Literata (SIL Open Font License).
- Wortkasten is inspired by BX Language acquisition (bxmemo.com).
- Built with Claude (Anthropic) as an AI-assisted development project: product design, rules and testing by the author, code generated with AI.

© 2026 Wortkasten
