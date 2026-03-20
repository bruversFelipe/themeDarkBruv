# Changelog

## [2.0.0] — 2026

### Dark Bruv Neo — Major Redesign

Complete evolution of the original Dark Bruv theme. Same DNA, significantly upgraded.

**Core**
- Renamed to Dark Bruv Neo
- Bumped minimum VS Code engine to `^1.80.0`
- Enabled `semanticHighlighting: true` for language-server-aware colorization
- Updated gallery banner to match new deep navy background `#1a1a2e`

**New: Semantic Token Colors**
- Added `semanticTokenColors` block covering: `type`, `interface`, `class`, `enum`, `typeParameter`, `function`, `method`, `variable`, `parameter`, `property`, `enumMember`, `decorator`, `namespace`, `keyword`
- Added modifier rules: `variable.readonly`, `property.readonly`, `variable.static`

**Improved: TypeScript / JavaScript**
- Types and interfaces now render in cyan `#56d4e8` — distinct from variables
- Generic type parameters highlighted separately
- Decorators get dedicated gold `#d7ba7d` color
- Imported symbols (`variable.other.readwrite.alias`) use variable yellow
- Keywords and storage modifiers unified under pink primary `#fa57d7`

**New: JSX / TSX**
- Tag names → cyan
- Attribute names → yellow
- Expression containers `{}` → pink-soft
- Tag punctuation → muted gray

**New: CSS / SCSS**
- Property names → cyan
- Selectors → pink primary
- At-rules → pink primary
- SCSS variables → yellow
- Units and numeric values → constant blue

**New: Python**
- Decorators → gold
- Built-in functions → cyan
- Type hint annotations → cyan
- `self` / `cls` → muted gray

**New: Go**
- Built-in types → cyan
- Function declarations → pink primary italic
- Package names → muted gray

**New: JSON**
- Object keys → purple `#b791ff`
- Booleans / null → constant blue
- Numbers → constant blue

**New: Markdown**
- Headings → pink primary bold
- Inline code → cyan
- Links → cyan
- Blockquotes → gray italic

**New: Shell**
- Built-in commands → pink primary italic
- Variables → yellow
- Flags → muted gray
- String interpolation → pink soft

**New: SQL**
- DML / DDL keywords → pink primary
- Aggregate functions → pink primary italic

**Global**
- Comments → gray italic across all languages
- Strings → orange `#e29c63` across all languages
- Numbers → constant blue `#569cd6` across all languages
- Language constants (`true`, `false`, `null`) → constant blue

---

## [0.9.0] — 2018

- Initial release
