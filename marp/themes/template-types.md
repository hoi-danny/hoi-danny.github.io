# KakaoCloud Marp Template Types

This converter emits Marp only. Every generated slide is backed by a typed
TemplateSlide object and rendered through one of these section classes:

- cover
- contents
- section-divider
- concept
- concept-visual
- visual-focus
- comparison-table
- reference-table
- lab-preview
- procedure
- procedure-shot
- code-terminal
- code-explain
- cleanup
- closing

The converter may split one PPTX slide into multiple Marp slides when content
density would make the slide hard to read. Complex diagrams, console captures,
and UI screenshots are preserved as cropped PNG assets; semantic text, tables,
and code blocks are rendered as Markdown.
