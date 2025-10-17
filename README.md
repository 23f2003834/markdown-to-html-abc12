# Markdown to HTML Client-Side Converter

This static webpage allows you to input Markdown content (simulated here as an attachment) and renders it as HTML with syntax-highlighting code blocks. It uses `marked` for Markdown parsing and `highlight.js` for syntax highlighting, all loaded dynamically via CDN. The app ensures all scripts are loaded correctly and the output includes headers.

## Features
- Parses Markdown content into HTML
- Highlights code syntax inside code blocks
- Embedded styling fallback if Bootstrap fails to load
- No server-side processing; all logic is client-side

## Usage
Open the `index.html` in a browser. The page automatically renders the embedded Markdown content.

## Dependencies
- Bootstrap 5.3.3
- marked (for Markdown parsing)
- highlight.js (for syntax highlighting)

## Notes
- This is a minimal example simulating Markdown input as an attachment.
- For dynamic input, replace `mdContent` with user input or file loading logic.