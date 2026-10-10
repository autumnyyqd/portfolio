# Design brief

Source: Stitch HTML
Mood: clean, industrial, precise. Technical and structured like an executive code / data dashboard, with crisp monospace metadata and a dot-grid surface.

## Style

- Style: Technical.
- Feel: clean, industrial, precise.
- Personal detail: mountain contour line divider between hero and experience.
- Motion: crisp and functional: state changes, no decoration. When the visitor prefers reduced motion, nothing moves.

## Colours

| Token | Light | Dark | Used for |
|---|---|---|---|
| background | #f8f9fb | #0d1117 | page background: cool technical white with faint dot grid |
| surface | #f2f4f6 | #161b22 | cards, code container background |
| text | #191c1e | #e6edf3 | headings and body text |
| muted | #57606a | #9198a1 | dates, metadata, section indices, borders |
| accent | #1a7f37 | #3fb950 | links, focus ring, status indicators: syntax green |
| on-accent | #ffffff | #0d1117 | text on an accent-coloured button |

## Type

| Role | Font | Size | Weight |
|---|---|---|---|
| headings | "JetBrains Mono", ui-monospace, Menlo, Consolas, monospace | name 2rem, section 1.25rem, role 1rem | 600 |
| body | "IBM Plex Sans", system-ui, sans-serif | 1rem, line height 1.6 | 400 |
| details | "JetBrains Mono", ui-monospace, Menlo, Consolas, monospace | dates, status, code metadata 0.875rem | 400 |

## Shapes

- Corner radius: square corners (0rem) across all cards, tags and containers.
- Borders: 1px subtle border in the muted/outline token around cards and code blocks.
- Shadows: none.

## Layout

- One column layout, maximum width 52rem, centred, with 1.5rem padding at the sides on phones; faint 16px dot-grid background.
- 2.5rem between sections, 1rem between items in a list.
- Experience and education formatted in clean, bordered data cards with monospace index prefixes.

## Components

- Links: syntax green (#1a7f37), underlined or boxed as monospace action tags; focus ring in accent colour.
- Projects: none currently; styled with surface background, 1px border, and monospace tags when present.
- Skills: represented as a formatted array/JSON block with syntax-coloured strings.
- Section headings: prefixed with numeric indices and slashes (e.g., "01 / PROFILE_SUMMARY").

## Signature

- Move: Other cards step back on hover and focus
- Guide: guides/css/child-state-based-styling.md
- Where: experience and credential cards: while one is pointed at or focused, the others step back.

## Sections

1. `bio`: the name, credentials, headline, status box, and bio summary.
2. `links`: LinkedIn and email action links.
3. `cv`: experience timeline, education, and skills array.
4. `certifications`: professional courses and certifications.
5. `events`: workshops and industry conferences.
