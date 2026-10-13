# FAQ Assistant Prototype

A beginner-friendly, browser-based FAQ assistant built with **HTML, CSS, and vanilla JavaScript**.

## Features

- Search a small, predefined FAQ knowledge base.
- Suggest answers based on keyword matching.
- Provide clickable example questions.
- Responsive layout for desktop and mobile screens.
- Run locally in a browser without installing dependencies or using an API key.

## Try it

1. Download or clone this repository.
2. Open `index.html` in a web browser.
3. Try questions such as:
   - How long does shipping take?
   - Can I return an item?
   - What payment methods do you accept?
   - How can I track my order?

## How it works

The app compares the words in a question with keywords attached to each FAQ entry, then displays the closest match when the score passes a simple threshold. The example answers are illustrative content and should be replaced with accurate details before using this for a real business.

## Technology

- HTML5
- CSS3
- JavaScript (no framework or external dependency)

## Important limitation

This is a **rule-based prototype, not an AI- or LLM-powered application**. It does not call an AI API, connect to a store, retrieve order data, or contact a support team. It is an initial learning project that can later be extended with an LLM service, a verified knowledge source, and appropriate privacy and security controls.

## Possible next improvements

- Add more FAQs and refine keyword matching.
- Add unit tests for matching behavior.
- Deploy the static page with GitHub Pages.
- Explore an LLM integration without exposing API keys in frontend code.
