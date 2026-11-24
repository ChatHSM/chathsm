# ChatHSM

A small chatbot in a single HTML file. Written in German, with an English mode in the settings.

Try it: https://chathsm.github.io/chathsm/

## Features
- Recognises mood and feelings (sad, stressed, angry, happy, and more), including emojis
- Answers simple questions on German cities, countries, rivers, mountains, planets, elements, history up to 2026 and famous people
- Built-in calculator (with step-by-step maths), timers with alarm, riddles, jokes, poems, stories, vocabulary trainer and a country quiz
- Optional small AI models that run inside your browser (via Transformers.js, downloaded on demand, with folders and an optional thinking mode)
- Optional cloud AI using your own API key (e.g. Gemini, OpenAI, Anthropic, OpenRouter, Groq, Mistral or a custom provider)
- Optional web search via Wikipedia, weather lookup via Open-Meteo and voice input / read aloud (if supported by your browser)
- Small self-learning memory and knowledge updates in your browser, with export and import

## Install as an app
Once hosted on `https://` (like the link above), you can add ChatHSM to your home screen:
- iPhone (Safari): Share -> Add to Home Screen
- Android (Chrome): Menu -> Install app
- Desktop (Chrome / Edge): install icon in the address bar

## Privacy
By default, everything you write is processed on your device. What the bot learns and any loaded knowledge updates stay in your browser's local storage, not on GitHub or any server. Outside connections happen only when needed: weather (open-meteo.com), Wikipedia, knowledge-update links you enter, the AI library (jsdelivr.net) and the one-time model download (huggingface.co).

If you turn on Cloud AI with your own API key (off by default, with an extra confirmation box), your messages, recent chat turns and short knowledge notes are sent to the provider you chose, under that provider's privacy rules. The key stays in your browser only (only saved permanently if you tick the box on your own device) and is never part of backups.

## Files
- `index.html`: the whole chatbot
- `manifest.webmanifest`, `sw.js`, icons: needed so it can be installed as an app and work offline

## Limits
This is a rule-based project with optional small browser AI or your own cloud API key. Built-in facts currently reach up to mid-2026 unless you load updates, and both rules and AI models can make mistakes. It does not replace real advice, especially for serious topics or health questions.
