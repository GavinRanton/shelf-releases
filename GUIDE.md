# Shelf — how to use it

Your Mac forgets everything you copy the moment you copy the next thing. Shelf
remembers the last 500, keeps them encrypted on your own machine, and gets any
of them back with one keystroke.

Version 1.0.1. Requires macOS 14 or later. Apple silicon and Intel.

---

## Install

1. Open the disk image and drag **Shelf** into **Applications**.
2. Launch it from Applications. Nothing opens, and that is correct: Shelf lives in the menu bar and has no window of its own.
3. Press **⌃⇧Space**. A panel slides up from the bottom of the screen. That is Shelf.
4. The first time you paste from it, macOS asks for **Accessibility**. Allow it. Without it Shelf can still copy to your clipboard, it just cannot press ⌘V for you.

It is signed with an Apple Developer ID and notarised by Apple, so there are no
security warnings and no right-click workaround.

---

## The one thing to remember

**⌃⇧Space** opens and closes the panel from anywhere, in any app.

---

## Your first five minutes

Do these in order. About a minute each, and they cover most of daily use.

| # | Do this | Why |
|---|---|---|
| 1 | Copy three or four different things: text, a link, an image, a file | Give Shelf something to hold |
| 2 | Open the panel and press **3** | Entries are numbered. Pressing a number pastes that one straight into the app you came from. Fastest way to use Shelf, and most people never find it |
| 3 | Open it again and just start typing | Search covers everything, including text recognised inside screenshots |
| 4 | Press **Tab** a few times | Cycles the filter: Text, Image, File, Link, Email, Colour, Code |
| 5 | Select a messy paragraph and press **⌘T** | Paste recipes. Rejoin lines broken by a PDF, strip tracking off a link, turn CSV into a real table. Changes what gets pasted, leaves the saved copy alone |
| 6 | Press **⌘K** and ask a question | Try "the link I copied yesterday" or "summarise what I just copied". Plain English, runs on your Mac |

---

## Keys worth knowing

### From anywhere

| Keys | Does |
|---|---|
| **⌃⇧Space** | Open or close the panel |
| **⌃⇧V** | Paste the next entry down. Press repeatedly to fill a form from several copies in order |
| **⌃⇧R** | Start that sequence again from the newest entry |

### Inside the panel

| Keys | Does |
|---|---|
| **Return** | Paste into the app you came from |
| **⇧Return** | Paste as plain text, dropping the formatting |
| **⌘Return** | Copy only, do not paste |
| **1** to **9** | Paste that numbered entry |
| **Tab** | Filter by type |
| **⌘E** | Edit the text before it pastes |
| **⌘P** | Pin it, so it stays at the top |
| **⌘R** | Rename it, so you can find it by a word you chose |
| **⌘M** | Switch between the two layouts |
| **⌘⌫** | Delete the entry |
| **Esc** | Close |

Double-click an entry to paste it, or drag one straight out of the panel into any app.

---

## The less obvious half

| Feature | What it is |
|---|---|
| **Snippets** (⌘S) | Give a block of text a keyword like `;;sig`. Type that keyword in any app and Shelf swaps in the text. Snippets can carry today's date, your last copy, or a calculation |
| **Collect and merge** (⌘G) | Mark several entries in order, then paste them as one block. Gather from three apps and drop the lot in at once |
| **Screenshots** | New screenshots land in your history on their own, whether or not you copied them. The text inside them becomes searchable |
| **Spaces** | Colour-coded groups such as Work or Home. Copies sort themselves by the app or website they came from |
| **Read aloud** (⌘L) | Reads an entry out loud in a large reader, highlighting each word. Works on text found inside an image too |
| **Presenting mode** (⌘⇧P) | Blurs every preview before you share your screen. You can still paste normally, but nobody watching sees what you copied |

---

## Two layouts

Both dock to the edge of the screen and never float over your work. Swap with **⌘M**.

| Layout | Shape | Better for |
|---|---|---|
| **Bottom Shelf** | Full width along the bottom, big cards with a preview panel | Images, links and colours, anything you want to see before pasting |
| **Side Ledge** | Narrow strip down the right edge, tight rows | Grabbing text quickly while you work |

---

## What it does with your data

- **Everything stays on your Mac.** History lives in an encrypted database in your own Library folder. No account, no server, no sync, no analytics.
- **It refuses to record from password managers.** 1Password, Bitwarden, LastPass, Dashlane, KeePassXC, Keychain Access and macOS password prompts are ignored out of the box. So is anything an app marks as a password, in any app.
- **Nothing is uploaded, including the clever bits.** Searching text inside images, reading aloud and the plain-English questions all run on your own machine.
- **Pause Recording** in the menu turns it off whenever you want.

Full statement: [PRIVACY.md](PRIVACY.md)

---

## Three things that look like bugs

| Looks like | Actually |
|---|---|
| The menu bar icon is missing | If your menu bar is full, or you have a MacBook with a notch, macOS drops the icon and an app cannot claim a spot. Shelf still works. Use the hotkey, and the **⋯** button in the panel gives you the same menu |
| The panel opened on the wrong screen | It opens on whichever display your pointer is on. With two monitors it will not always be where you were looking |
| Screenshots are not appearing | The first time Shelf reads a folder inside Documents, Desktop or Downloads, macOS asks permission. If you missed it: System Settings → Privacy & Security → Files & Folders |

---

## Updates

Shelf checks once a day and offers you new versions. You click once.

---

## Feedback

Rough notes are fine. The annoying details are the useful ones.

- Anything that made you stop and think, even for a second
- A moment you expected something to happen and it did not
- Anything you tried to do that Shelf would not let you
- Whether you kept using it after the first day, and honestly why not if you did not
- Any wording that reads oddly or sounds like it was written by a developer

gavin.ranton@gmail.com
