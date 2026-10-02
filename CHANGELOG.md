# Change Log

## [1.1.2] - 2026-10-02

- Variables and identifiers are now white (`#DFE2E7`) instead of violet, so ordinary code stays quiet and only meaningful tokens are highlighted.
- CSS/SCSS/LESS: properties and values are white, classes and ids are violet, element tags and pseudo selectors (including `:root`) are teal.
- JS/TS object literal keys are white to match semantic `property`.

## [1.1.1] - 2026-10-02

- Replaced the yellow constants (`#FBCC43`) with pink (`#F286C4`) so syntax stays within the pink/violet/blue palette.
- Replaced the orange variables (`#DFAB5C`) with soft violet (`#C792EA`).
- Classes (`support.class`) now use the teal type color for consistency with semantic `class`.
- Editor warnings (`editorWarning`, `list.warningForeground`, `inputValidation.warningBorder`) and terminal ANSI yellow stay yellow.
- Added themed bracket pair colorization (`editorBracketHighlight.foreground1-6`) so brackets no longer fall back to VS Code's default yellow/orchid palette.

## [1.1.0] - 2026-10-02

- Added semantic highlighting (`semanticTokenColors`) for consistent coloring across all languages with a language server (Python, C#, Rust, TS/JS, Go, Java, ...).
- Added TextMate rules for Dockerfile.
- Expanded Rust and C# token coverage.
- Added rules for Go, Java, C/C++, PHP, Ruby, Kotlin, Swift, Dart, Lua.
- Added rules for HTML, Vue, Svelte, CSS/SCSS/LESS, YAML, TOML, INI, SQL, Shell, PowerShell, Makefile, Terraform, GraphQL and .env.
- Fixed a trailing comma in `tokenColors` that made the file invalid strict JSON.

## [1.0.0] - 2025-05-15

- Update theme to the latest version of Codesanbox fork Nicolas Gryman.
- Initial release