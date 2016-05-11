# Contextual Preview
Automatically delegate which preview package to activate based on the active [grammar](https://atom.io/docs/latest/using-atom-grammar) of the current file.

## Behaviour
This package delegates preview events according to the following table.[*](#)

| Type     | Grammar/scope   | Preview package                                                 |
|:--------:|:---------------:|:---------------------------------------------------------------:|
| Markdown | source.gfm      | [markdown-preview](https://atom.io/packages/markdown-preview)   |
| AsciiDoc | source.asciidoc | [asciidoc-preview](https://atom.io/packages/asciidoc-preview)   |
| HTML     | text.html.basic | [atom-html-preview](https://atom.io/packages/atom-html-preview) |
| __*__    | __*__           | [source-preview](https://atom.io/packages/source-preview)       |

\* Currently therefore, this means that `apm install asciidoc-preview atom-html-preview source-preview` is required. Configuration options will be added in future.
