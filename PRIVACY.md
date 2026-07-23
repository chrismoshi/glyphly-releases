# Glyphly Privacy Policy

*Last updated: 23 July 2026*

Glyphly is a local-first desktop app for CJK language learning (Chinese,
Japanese, and Korean). This policy explains what it stores, what stays on your
device, and the few cases where data leaves it.

## What Glyphly does

Glyphly helps you capture text from your screen, read it with OCR, look up
words, save vocabulary, and review what you learn with spaced repetition.

## No account, no tracking

Glyphly has no user accounts and no sign-up. It does not collect analytics, does
not track your usage, and does not build a profile of you.

## What is stored on your device

Glyphly keeps the following in a local database and configuration files on your
PC, under your Windows user profile:

- saved words and their sentence context
- review history and spaced-repetition scheduling data
- capture history and imported text
- app settings and preferences
- license activation status
- the downloaded language engine (OCR models and dictionary data)

This data is not uploaded anywhere. Deleting the app data removes it. You can
export a backup of your own data from within the app.

## Screen captures and recognised text

OCR, word segmentation, and dictionary lookup run entirely on your device, using
a local engine that Glyphly downloads once during setup.

Screenshots and the text recognised from them are **not** uploaded for these
features. They are processed locally and stored locally.

## Optional sentence translation

Glyphly can translate whole sentences using DeepL. This feature is **off by
default** and requires you to add your own DeepL API key in
**Settings → Translation**.

If you enable it, then when you request a translation the sentence you selected
is sent to DeepL's API to be translated, and the result is returned to your
device. Nothing else is sent. Your API key is stored in the Windows credential
store, not in a plain-text file, and it is never sent to us.

DeepL's handling of that text is governed by
[DeepL's own privacy policy](https://www.deepl.com/privacy). If you do not add a
key, no text is ever sent to DeepL.

## License activation

Glyphly Pro uses license-key activation handled by Lemon Squeezy, our payment
provider and merchant of record.

When you activate a key, or when Glyphly periodically re-checks that your
license is still valid, it contacts Lemon Squeezy with your license key and a
device identifier to confirm the license is active and within its device limit.
No learning data, captured text, or personal content is sent as part of this
check.

Your purchase details — name, email, and billing information — are collected and
held by Lemon Squeezy when you buy, under
[Lemon Squeezy's privacy policy](https://www.lemonsqueezy.com/privacy). Glyphly
does not receive or store your payment details.

## Updates

Glyphly checks for new versions by requesting a small update manifest from this
public GitHub repository. That request is an ordinary web request and carries no
personal data beyond what any download involves.

## Children

Glyphly is not directed at children under 13 and does not knowingly collect
personal data from them.

## Changes to this policy

We may update this policy as Glyphly changes. The date at the top reflects the
most recent revision, and the full history is visible in this repository.

## Contact

Privacy questions can be raised on the
[issue tracker](https://github.com/chrismoshi/glyphly-releases/issues). A
dedicated privacy contact address will be published here before it is needed for
anything that should not be discussed in public.
