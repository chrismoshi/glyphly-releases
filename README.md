<p align="center">
  <img src="assets/glyphly.png" alt="Glyphly" width="96" height="96">
</p>

<h1 align="center">Glyphly</h1>

<p align="center"><strong>Turn Mandarin text on your screen into language learning.</strong></p>

<p align="center">
  <a href="https://github.com/chrismoshi/glyphly-releases/releases/latest"><strong>Download for Windows</strong></a>
  ·
  <a href="https://chrismoshi.github.io/glyphly-releases/">Product page</a>
  ·
  <a href="./PRIVACY.md">Privacy</a>
  ·
  <a href="./TERMS.md">Terms</a>
  ·
  <a href="./REFUND.md">Refunds</a>
</p>

---

Glyphly is a local-first Windows desktop app for Mandarin learners. Capture text
from your screen, read it with on-device OCR, look up words instantly, save
vocabulary, and review what you learn.

It is built for learners who study from the Mandarin text already in front of
them — study PDFs, reading apps, websites, and their own learning materials —
rather than from a fixed course deck.

**Windows · Mandarin Chinese · Free to try**

---

## What Glyphly does

- **Capture** Mandarin text from screen content you have access to, with a
  region selection or a global hotkey.
- **Read** it with on-device OCR — no screenshot leaves your machine.
- **Look up** words as you go: pinyin, definitions, and word segmentation.
- **Save** words and their sentence context to a personal lexicon.
- **Review** what you saved with spaced repetition (FSRS scheduling).
- **Translate** whole sentences with DeepL — optional, and only if you add
  your own API key.

---

## Privacy-first by design

Glyphly is local-first. The core loop is built to run on your machine.

- OCR, word segmentation, and dictionary lookup all run on your device.
- Captured images and recognised text are not uploaded for OCR or lookup.
- Your saved words, sentences, and review history live in a local database on
  your PC. There is no account, and no cloud sync.
- Sentence translation is off until you enable it. It is the one feature that
  sends text off your machine, and only the sentence you asked about.
- Once the language engine is installed, capture, lookup, and review work with
  no internet connection.

Full details in the [Privacy Policy](./PRIVACY.md).

---

## Download

Get the latest Windows installer from the
**[Releases page](https://github.com/chrismoshi/glyphly-releases/releases/latest)**.

On first launch, Glyphly downloads its language engine once (about 300 MB) and
installs it locally. After that the core capture-and-review loop works offline.
The app checks for its own updates and can install them for you.

> **A note on the SmartScreen warning:** Glyphly's installer is not yet
> code-signed, so Windows may show a "Windows protected your PC" prompt. Choose
> **More info → Run anyway**. Code signing is in progress; until it is done, only
> download Glyphly from the Releases page linked above.

---

## Screenshots

Screenshots coming soon.

---

## Glyphly Pro

Glyphly is free to download and use. The whole core loop — capture, OCR, lookup,
saving, and spaced-repetition review — is free, with a cap of **150 saved
words**. Words you have already saved are never locked or taken away, and your
review history stays yours.

**Pro removes the cap and adds study tools:**

- Unlimited saved words
- Clipboard watch — look up Mandarin text as you copy it
- File import — bring in text files to study
- Sentence quiz

| Plan | Price |
|------|-------|
| **Founder Lifetime** — limited launch offer | **$89.99** one-time |
| **Yearly** | **$49.99 / year** |
| **Monthly** | **$8.99 / month** |

Prices in USD. Payments are processed by Lemon Squeezy, our merchant of record.

**How to buy and activate:** open Glyphly, go to **Settings → License**, and
choose a plan. After purchase you receive a license key by email — paste it into
that same card and press **Activate**.

One key works on up to 3 devices. Glyphly re-checks your license periodically
and keeps Pro unlocked for 14 days offline, so a flight or a dead connection
never locks you out of your own vocabulary.

Founder Lifetime is an early-supporter offer to fund development, and may be
limited by time or quantity. Features that depend on third-party cloud services
may carry fair-use limits.

---

## System requirements

- Windows 10 or Windows 11 (64-bit)
- At least 1 GB free disk space (the language engine is a ~300 MB download that
  unpacks locally)
- An internet connection for first-time setup, updates, and license activation
- Core capture, lookup, and review work offline once setup is complete

---

## Language support

**Available now**

- Mandarin Chinese

**Planned**

- Japanese
- Korean

Planned languages are on the roadmap without a committed date. Each one needs
its own dictionary and text-analysis work, so they ship when they are genuinely
good rather than on a schedule.

Explanations and translations can target English, French, German, Spanish, or
Portuguese.

---

## Support

Found a bug, or something not working as described? Open an issue on the
[issue tracker](https://github.com/chrismoshi/glyphly-releases/issues).

For billing, license, and refund questions, see the
[Refund Policy](./REFUND.md).

---

## Policies

- [Privacy Policy](./PRIVACY.md)
- [Terms of Use](./TERMS.md)
- [Refund Policy](./REFUND.md)

---

## Credits

Chinese dictionary data from [CC-CEDICT](https://www.mdbg.net/chinese/dictionary?page=cc-cedict),
© MDBG, licensed under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

---

*This repository hosts Glyphly's public downloads and update files.*
