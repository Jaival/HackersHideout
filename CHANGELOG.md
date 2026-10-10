# Change Log

## [1.2.0]

### Fixed

- Removed the borders drawn around every error, warning, info and hint squiggle.
- Added lines, added files, passed tests and the terminal's green now use a real green (`#7CFC8A`) instead of salmon.
- Warnings are yellow, so they no longer look like errors. Hints are sky blue.
- The terminal's bright colors are now distinct from the normal ones. Bright black was raised from `#313831` so dim text is readable.
- Replaced the removed `testing.message.error.decorationForeground` and `scm.providerBorder` keys.

### Changed

- Raised contrast on line numbers, inactive tabs, input placeholders and peek view line numbers.
- Comments are brighter (`#7D9161`) and italic.
- Syntax highlighting grew from 18 rules to 45. Functions, types, keywords, `const`/`let`, numbers and constants, properties, parameters, `this`/`self`, decorators, operators, punctuation, regex, escapes, HTML/JSX tags and attributes, CSS and Markdown each get their own color or style.
- Turned on semantic highlighting with colors for parameters, properties, types, enum members and deprecated symbols.

### Added

- Colors for inlay hints, ghost text, sticky scroll, bracket pair guides, the command center, status bar hover and warning items, keybinding labels, terminal command decorations, chat and inline chat.

## [1.1.0]

### Added

- Theme icon.

## [1.0.0]

### Added

- First release of the theme.
