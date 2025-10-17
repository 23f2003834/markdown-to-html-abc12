-
# Markdown to HTML Client-Side Converter with Tabs

This static webpage allows you to input Markdown content through an editable textarea and view both the raw Markdown and its rendered HTML output in separate tabs. It uses:
- **Bootstrap 5.3.3** for styling and tab navigation.
- **marked** for Markdown parsing.
- **highlight.js** for syntax highlighting within code blocks.

All logic runs client-side in JavaScript, with content synchronized between the editor and preview.

## Features
- Edit Markdown source in real-time.
- Switch effortlessly between Markdown source view and rendered HTML.
- Renders Markdown into HTML with syntax highlighting for code blocks.
- Responsive and styled with Bootstrap, with fallback styles provided.
- Keeps content synchronized seamlessly.

## Usage
Open `index.html` in a web browser. The Markdown textarea is pre-filled with the example text:
```
quick brown fox jumps over the lazy dog
```
As you edit the Markdown, switch to the "Rendered HTML" tab to see the live output. Changes are reflected immediately.

## Dependencies
- Bootstrap 5.3.3 from CDN
- marked (Markdown parser)
- highlight.js (syntax highlighting)

## Notes
- This implementation incorporates tabs for toggling views, maintaining the synchronization of Markdown content.
- You can edit the Markdown in the textarea and see updates in the preview instantly.
- The syntax highlighter supports JavaScript, Python, and Java snippets.