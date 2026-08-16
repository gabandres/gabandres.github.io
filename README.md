# gabandres.github.io

Serves `/.well-known/apple-app-site-association` so iOS can associate a private
app with this domain, which is what allows a passphrase to be offered to and
saved in the iCloud Keychain.

`.nojekyll` is required: Jekyll skips dot-directories, so without it
`.well-known/` is never published.

Nothing here is secret. An association file only names an app that is allowed to
claim the domain; it grants nothing to anyone else.
