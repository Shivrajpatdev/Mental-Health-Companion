# MindfulChat 🌿

A simple, offline, rule-based mental health support chatbot — built as a single self-contained HTML file. No backend, no API keys, no dependencies. Just open it in a browser.

## What it does
- Lets you check in with a quick mood button (great / okay / meh / down / anxious / angry)
- Responds to typed messages with supportive, pre-written replies matched by keyword (e.g. "anxious", "sad", "tired", "lonely")
- Detects crisis-related language (e.g. mentions of suicide or self-harm) and immediately surfaces crisis hotline resources instead of a generic reply

## What it is NOT
- **Not therapy.** All responses are pre-written and pattern-matched — there is no real understanding or AI model behind it.
- **Not a crisis service.** The built-in crisis response points to real hotlines (988 in the US, findahelpline.com internationally), but this app itself cannot help someone in immediate danger.
- **Not a diagnostic tool.** It doesn't assess, label, or track any mental health condition.

Please keep this disclaimer visible in any deployment or fork.

## Running it
Open `mental-health-companion.html` (or `index.html` if renamed) in any modern browser — no installation needed.

To host it publicly with GitHub Pages:
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set the source branch (e.g. `main`) and root folder
4. Your chatbot will be live at `https://<username>.github.io/<repo-name>/`
