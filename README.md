# SI338_Group_Project

# Cross Country Athlete Results (Semantic HTML)

This project is a semantic, accessibility-focused HTML skeleton for a single cross country athlete’s race results. It is designed from a mobile-first perspective and reflects our group’s layout sketches (two-column desktop, stacked mobile).

## Files

- `index.html`  
  Main page for the site. Shows one athlete’s profile, race results, and team comments.  
  - Athlete profile (photo, grade, SR, PR, bio) in an `<aside>` that can stay visible on large screens.  
  - Search and filter controls for this athlete’s races.  
  - Race cards listed in chronological order (most recent first), with a “More details” section for extra metadata and links.  
  - Team comments area that can act like a side panel or inline section on mobile.

- `reset.css`  
  Shared CSS reset used to normalize browser defaults.  
  No custom styling should be added here for this assignment.

## How to use this skeleton

- Replace all `{{...}}` placeholders (e.g., `{{AthleteName}}`, `{{RaceName}}`) with real data from our spreadsheet.  
- For repeatable sections:
  - `{{RACE_CARD_ITEMS}}`: replace with one `<li>…</li>` race card per race.  
  - `{{COMMENT_ITEMS}}`: replace with one `<li>…</li>` comment per comment.
- Keep the existing semantic structure (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`) and headings (`h1`–`h4`) to support accessibility and screen reader navigation.

## Accessibility notes

- The “Skip to main content” link lets keyboard users jump directly to the main content.  
- All form controls (search and filter) include labels, fieldsets, and legends.  
- Images should have meaningful `alt` text if they convey information, or `alt=""` if purely decorative.  
- `<details>` / `<summary>` are used for progressive disclosure (e.g., “More details”) without requiring JavaScript.



