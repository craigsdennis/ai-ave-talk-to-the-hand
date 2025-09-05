# Update Background — Session Log (2025-09-05)

## What you asked for
- Use `public/talk-to-the-hand.jpg` as the website background image.
- Create a `truth-window` folder and keep markdown logs of what we build, showing what you asked for and what I did. Make one for this session.

## What I did
- Reviewed the project structure and opened `public/index.html`.
- Added a `<style>` block in `public/index.html:6` to set the page background:
  - Applied `background: url('talk-to-the-hand.jpg') no-repeat center center fixed;`
  - Used `background-size: cover` for full-viewport coverage.
  - Set `margin: 0` on `body` and added light text contrast (white + subtle shadow).
- Created this log at `truth-window/2025-09-05.md` to document the session.

## File changes
- Modified: `public/index.html`
- Added: `truth-window/2025-09-05.md`

## Notes / Next options
- I can add an overlay (e.g., semi-transparent dark layer) for improved text readability.
- I can keep or remove the current text styling depending on your preference.
