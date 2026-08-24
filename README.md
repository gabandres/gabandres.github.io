# gabandres.github.io

Serves `/.well-known/apple-app-site-association` so iOS can associate a private
app with this domain, which is what allows a passphrase to be offered to and
saved in the iCloud Keychain.

`.nojekyll` is required: Jekyll skips dot-directories, so without it
`.well-known/` is never published.

Nothing here is secret. An association file only names an app that is allowed to
claim the domain; it grants nothing to anyone else.

It also hosts the two public pages the App Store requires for the **Agenda** app:

| Path | Purpose |
| --- | --- |
| [`/agenda-privacy/`](agenda-privacy/) | Privacy Policy URL — and, for version 1.0, the Support URL too |
| [`/agenda-support/`](agenda-support/) | Support page (Guideline 1.5); the Support URL to use from the next version on |
