# Sovereign

An offline-first document assistant prototype for regulated sectors (law, healthcare, government). Documents stay in the browser tab: nothing is uploaded or sent anywhere.

## Features

- PIN-locked vault (demo PIN: `1234`)
- Upload or paste documents (text files)
- Ask questions and get answers with source citations
- Automatic summary and key facts (dates, amounts, people, contacts)
- Redaction of names, emails, phones, IDs, amounts and dates
- Audit log of every action

## Run it

Download the files, keep them in one folder, and open `index.html` in any modern browser. No server or internet connection needed.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Page structure |
| `styles.css` | Look and layout |
| `app.js` | All app logic |

## Status

This is a version 1 prototype. Answers come from an on-device search-and-summary engine, not a real language model. Data is held in memory only, so refreshing the page resets the vault. Planned next: a real local model (WebLLM or Ollama), PDF and Word support, and user roles.