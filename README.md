# 🥁 Drum Charts

Use this tool to map out the song structure and add notes! Drumeo style!
https://stripesmusic.github.io/chart-maker/

## Sharing

**Share** in the editor shares a chart with people by email, like a shared doc:

- **Viewer** opens and performs it
- **Commenter** also leaves comments (on the whole chart or one section)
- **Editor** also changes it; edits show up live for everyone

Typing a full email fills in that person's name if they have an account; people you've shared with before autofill as you type their name. Charts shared with you appear under **Shared with you** in the library. Email/password accounts need to verify their email first (Google accounts already are).

The rules that enforce these roles are in [`firestore.rules`](firestore.rules). Paste the file into Firebase console → Firestore Database → Rules and publish it.
