# ChatHSM

A chatbot in a single HTML file. It runs entirely in your browser, with no server and no account. It understands German and English, works with rules, and can optionally use a small AI model in the browser.

**Live:** https://chathsm.github.io/chathsm/

## Features

- Chat with mood and intent detection, typo tolerance and context memory
- General knowledge, weather and Wikipedia search (online only)
- Learns new words and facts, remembers people, pets and details you tell it
- Jokes, riddles, timer and small games
- Voice input (microphone button) and read-aloud, using your browser's own speech features
- Optional small AI model (Transformers.js), loaded by you from the ＋ menu
- Installable as an app, works offline

## Install as an app

- **iPhone (Safari):** Share → Add to Home Screen
- **Android (Chrome):** Menu → Install app
- **Desktop (Chrome/Edge):** install icon in the address bar

## Privacy

Everything you write is processed on your device. What the bot learns stays in your browser's local storage, not on GitHub or any server. Outside connections happen only when needed: weather, Wikipedia, the AI library (jsdelivr.net) and the one-time model download (huggingface.co).

## Files

`index.html` (the bot), `manifest.webmanifest`, `sw.js` (offline mode) and the icon images.

## Limits

The bot only knows what is in its code and can be wrong. Small AI models make mistakes and large ones can crash phones.
