# Seibi Production Reminder — Presentation

Follow-up presentation slides for the "生産リマインド" (Production Reminder) feature added to Seibi (設備管理システム), a companion update to the main [seibi-app-presentation](https://github.com/markjosephdsgatdula-dotcom/seibi-app-presentation) deck.

This feature lets shop-floor staff "watch" a specific production process code and get notified automatically (new order detected / 3 days before / day of), browse the daily production schedule across 4 screens (Watch List, Search, SHOP Calendar, Customer Lookup), receive a daily admin digest via LINE WORKS, and subscribe the schedule to their device's native calendar app.

## Project Structure

- `index.html` — the 8-slide interactive web presentation.
- `styles.css` — shared deck theme (same visual style as the main Seibi presentation).
- `mockup.css` — styling for the real-app UI mockups shown on the feature slides.
- `slides.js` — slide navigation logic (keyboard, click, bullet dots).
- `japanese_speech_script.md` — a Japanese speech script to present alongside the slides.

## How to View

Double-click `index.html` or open it in any web browser.

- Use **Left/Right Arrow keys**, **Spacebar**, or click anywhere on a slide to advance.
- Click the bullet dots in the navigation bar to jump directly to any slide.

## Note on the screenshots

The app screens shown on slides 4–6 are not raw screenshots — they're built from the real app's own CSS classes with real data captured live from the production system, so they render crisply at presentation size instead of as a compressed image capture. The LINE WORKS report on slide 7 is the actual message text delivered to the real channel.
