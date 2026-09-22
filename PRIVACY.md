# Shelf and your privacy

Short version: everything stays on your Mac. Nothing is uploaded, ever.

## What Shelf records

Shelf watches the system clipboard. When you copy something, it saves a copy so
you can get it back later. That includes text, links, images, files and colours.

## Where it goes

Into a single encrypted database at
`~/Library/Application Support/Shelf/history.db`, encrypted with SQLCipher. The
32-byte key sits beside it in `history.key`, readable only by your user account,
in a folder locked to your account.

What that protects you from: another user account on the same Mac, a stolen or
copied database file, and anything that ends up in a backup or on a cloud drive.

What it does not protect you from: a program already running as you, on your
Mac. Nothing short of a per-use password would, and this is a clipboard manager,
so that would make it useless.

No copy leaves the machine. There is no account, no server, no sync, no
telemetry and no analytics.

## What Shelf refuses to record

| Source | Behaviour |
|---|---|
| Password managers and Keychain Access | Ignored, always |
| macOS authentication prompts | Ignored, always |
| Secure text fields | Ignored while focused |
| Apps marked "concealed" on the clipboard | Ignored, always |
| Any app you add to the ignore list | Ignored |

## AI search

Asking Shelf a question runs Apple's on-device language model, which is part of
macOS. Your clipboard content is passed to that model locally. It does not touch
a network. If your Mac does not support it, Shelf falls back to plain keyword
search and tells you so.

## Screenshots

If you turn on screenshot importing, Shelf reads image files from the folders you
choose so captures land in your history automatically. It reads nothing else in
those folders, and macOS asks your permission before it can read them at all.

## How long things stay

As long as you tell it to, in Settings. Retention runs hourly and on every new
entry. Clear History deletes everything immediately and permanently.

## Updates

Shelf checks for new versions over HTTPS. That request carries no identifying
information beyond what any download needs.

## Removing it

Delete Shelf.app, then delete `~/Library/Application Support/Shelf`. That removes
the database and the key together, and the history is gone for good.

Questions: gavin.ranton@gmail.com
