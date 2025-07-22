# EA-KNN-Algorithm-Twitter-Profanity-filter

A Chrome extension that filters profanity on Twitter using an Ensemble Approach KNN text classification and categorization algorithm.

## Features

- Filters profane words and phrases on Twitter and other sites.
- Multiple categories for profanity (curse, degrading, humiliating, blasphemy, sexism, racism, homophobia, explicit, immodesty, nudity, triumphalism, elitism, arrogance, isolationism, bullying, drugs).
- Customizable word lists for complete and nested matches.
- Extreme filtering mode to catch obfuscated profanities.
- Option to hide entire sentences or replace words with safe alternatives.
- Badge counter shows number of filtered words.
- Context menu options to add words or exceptions.
- Options page for configuration.

## Installation

1. Clone or download this repository.
2. Go to `chrome://extensions` in your browser.
3. Enable "Developer mode".
4. Click "Load unpacked" and select the `EA-KNN-Algorithm-Twitter-Profanity-filter` folder.

## Usage

- Click the extension icon to open the options page.
- Configure filtering options, word lists, and replacement styles.
- Profanity will be filtered automatically on supported sites.

## File Structure

- `aFilter.js` – Main content script for filtering profanity.
- `anEventPage.js` – Background script for extension events and context menus.
- `anOption.html` / `anOption.js` / `anOption.css` – Options page UI and logic.
- `manifest.json` – Chrome extension manifest.
- `icons/` and `img/` – Extension icons and images.
- `test.html` / `console.test` – Test files for development.

## License

This project is provided for educational purposes.

## Author

Gomez Mike Miguel
