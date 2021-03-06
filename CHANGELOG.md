# Language-Idris Changelog

## Next version

### Added

- `print-definition` to show the definition of the selected word

### Fixed

## v0.2.0

### Added

- status indicator that shows if a file is loaded or dirty
- metavariables are now called holes

### Fixed

- fixed bug in the parser when there where backslashes in the answer [#32](https://github.com/idris-hackers/atom-language-idris/issues/32) (@david-christiansen)
- Program not loaded before running interactive editing commands [#34](https://github.com/idris-hackers/atom-language-idris/issues/34)
- faster startup [#28](https://github.com/idris-hackers/atom-language-idris/issues/28)

## v0.1.4

### Added

- new metavariable view (`Language Idris: Metavariables`)
- a tutorial that explains how to use this package
- context menu for `Language Idris: Type Of` and `Language Idris: Docs For`

### Fixed

- `Language Idris: Proof Search` and `Language Idris: Add Clause`
- deprecations that now broke the editor because of the dropped API methods

## v0.1.3

### Added

### Fixed

- Better syntax highlighting
- fixed the parser for the ide-mode lisp
- fixed [#18](https://github.com/idris-hackers/atom-language-idris/issues/18)
- fixed [#19](https://github.com/idris-hackers/atom-language-idris/issues/19)
- fixed an issue with the error lines not being clickable in the error panel

## v0.1.1

### Added

- Type and doc info highlighting https://github.com/idris-hackers/atom-language-idris/pull/9 (@archaeron)

### Fixed

- Ensure that keybindings only work on Idris files (#2)
- Syntax highlighting for infix functions
- Fixed a crash when idris was not installed

## v0.1.0

### Added

- Shortcut to Show the doc of a variable (ctrl-alt-d)

### Fixed

- updated for the new version of Atom (@archaeron)
- new parser for the ide-mode commands (@archaeron)
- new serializer for the ide-mode commands (@archaeron)
- various fixes (@ulidtko)

## v0.0.1

### Added

- Case-splitting (ctrl-alt-c) (@fangel)
- Clause-adding (ctrl-alt-a) (@fangel)
- Proof-search (ctrl-alt-s) (@fangel)
- Showing the types of meta-variables (ctrl-alt-t) (@fangel)
- Show the doc of a variable (@fangel)
