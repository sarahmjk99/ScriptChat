# ScriptChat
# 🎭 ScriptDeck

A browser-based line study tool for actors. Upload your script, pick your character, and run your lines in a chat interface — like texting your scene partners.

## Features

- **PDF upload** — drop in your script directly, no reformatting needed
- **Chat UI** — lines appear as a conversation, your character on the right in red
- **Run Lines mode** — your lines are hidden until you type them or reveal them
- **80% match** — type enough of your line and it auto-advances
- **Hint system** — reveals your line one word at a time if you get stuck
- **Beat breakdown** — write your "where you're coming from" and "where you're going" notes for each beat, pinned at the top of the chat
- **Beat navigation** — jump to any beat, switch characters mid-session
- **Korean language support** — works with mixed English/Korean scripts
- **Everything runs in your browser** — no account, no server, your scripts never leave your device

## How to use

1. Open the app
2. Click **File → New Script**
3. Upload your PDF
4. Type the character names from the script (separated by commas)
5. Optionally add beat breakdown notes
6. Hit **Save & Open**
7. Pick your character → pick your starting beat → run your lines

## Built with

HTML, CSS, vanilla JavaScript, and [PDF.js](https://mozilla.github.io/pdf.js/) for PDF extraction. No frameworks, no backend, no dependencies to install.

---

*Built for actors, by an actor.*

One thing to know
Everything runs in the user's browser — the PDF never leaves their device, scripts save to their local browser storage. So each person gets their own private copy of their scripts. Nothing is shared between users.
