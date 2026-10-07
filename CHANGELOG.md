# Changelog

All notable changes to the Adones Theme project will be documented in this file.

## [1.2.0] - [10/7/2026]

### Adones Coffee: readability and contrast pass

**Syntax**
- Comments are lighter and clearer (`#7D6B5C` -> `#A39F85`), still italic
- Variables are lighter and cleaner (`#A6947A` -> `#CEC6BB`)
- Keywords are now yellow (`#D68562` -> `#CBBB4D`) so they separate from HTML tags
- Types, classes and interfaces are now teal (`#C2A15A` -> `#83B9AC`)
- Properties move to a soft salmon (`#D398AC` -> `#D4A58F`), parameters to `#C99C86`
- Functions are a clearer blue (`#8FB0C0` -> `#8AB6C4`)
- Strings are slightly brighter (`#B3C17A` -> `#A6C280`)
- Numbers and booleans: `#E0AD70` -> `#CFA16E`
- Regex now has its own color (`#C792B8`)
- Operators are a sage green (`#9FB38C`), and punctuation sits quieter (`#9C8C7E`)

**HTML and CSS**
- HTML tags: `#D18B7A` -> `#D08C6A`
- HTML attributes: `#D9A566` -> `#D8A55A`
- CSS properties were too dark (`#9C7360`) and are now clearly visible (`#B8AC9C`)
- CSS selectors now match HTML tag color (`#D08C6A`)
- CSS values are lighter (`#D9B98A`)

**UI**
- Main text is brighter (`#DCC9B4` -> `#E6D5C0`) across editor, terminal, menus, inputs and widgets
- Dim UI text (line numbers, inactive tabs, placeholders, ignored files) is much easier to read
- Active tab background now matches the editor, so there's no visible seam
- Selection highlight is slightly stronger
- Terminal: black is no longer invisible against the background, cyan is now teal instead of brown
- Bracket pair colors updated to match the new syntax palette

### Fixed
- Syntax colors and semantic token colors now agree, so colors no longer shift depending on whether semantic highlighting is active

## [1.1.5] - [9/15/2026]

- Fixed issues with themes. 
- Kept ruling consistent across all four theme files.


## [1.1.1] - [9/15/2026]

- Minor fix in Adones Theme

## [1.1.0] — [9/12/2026]

### Added

* Added a new **Adones Coffee** theme variant — a warm, espresso-toned dark theme with a coffee-shop inspired syntax palette (mocha, caramel, terracotta, olive, dusty rose), offering more contrast and clearer syntax hierarchy than the original Adones Theme without leaning into neon or high-saturation colors.

## [1.0.0] — [9/6/2026]

### Added

* Added a new **Adones Theme Darker** theme variant, providing a higher contrast alternative to the original Adones Theme.

### Changed

* Refined the **Adones Theme** color palette.
* Changed the colors of **Adones Theme** and **Adones Cream**.
* Made small adjustments to various UI colors and theme elements.

### Notes

* **Adones Theme** remains the darker variant.
* **Adones Cream** remains a lighter variant.
* Tested with **HTML, CSS, and JavaScript**.