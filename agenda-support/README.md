# Agenda — Support

The published support page for the **Agenda** iOS app.

📄 **<https://gabandres.github.io/agenda-support/>**

Contact is a single address, `support@bermudezsystems.com`, answered by the developer. There is no
ticketing system and no form — the app has no server, and neither does its support.

Spanish comes first and English second, because the App Store listing ships `es-MX` only and the
people who use the app are Spanish-speaking. The page is one file with no build step and no
dependencies.

## Why this exists separately from the privacy policy

App Store Connect asks for a *Support URL* (Guideline 1.5) and a *Privacy Policy URL*. Version 1.0
was submitted with both fields pointing at `/agenda-privacy/`, and version metadata cannot be edited
while a version sits in review — so `/agenda-privacy/` carries a support section of its own, and
this page is the dedicated destination the **next** version's Support URL should point at.

## What may go on this page

Only behaviour that exists in the build currently on the App Store. Describing a feature that has
not shipped yet turns the support page into a bug report from the reviewer. In particular: the page
describes the app as **not syncing between devices**, and must not claim otherwise until a build
with iCloud sync is actually approved and released.

Screen names are quoted from `src/i18n/strings.ts` in the app repo, in both languages, so that what
the page says to tap matches what the user sees.
