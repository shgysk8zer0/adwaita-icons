# Contributing to the project
**Note**: Contributions will not be merged into Gnome Project's Adwaita icons.
While their icons are used here, it is not practical for any merging from one
to the other.

## Guidelines
- All icons **MUST NOT** use the `style` attribute.
- All icons **MUST** set a `viewBox` attribute
- All icons **MUST** set `xmlns` and `version` attributes
- All icons **MUST** be in standard/minified SVG format. No Inkscape SVGs or `.ai`
- Icons **SHOULD NOT** use `fill` attribute and **SHOULD** be intended to be
viewed in a single, designer chosen color
- Icons **MAY** set `fill` color for things such as badges, warnings, or elements
where a specific color has meaning and is not to be changed when used

All pull requests will be tested using `svglint.php`, which requires PHP 7+

The decalred guidelines are to ensure that icons in themselves, as well as when
packed into `<symbol>`s are compatible and allow developers of the projects they
are used in to maintain basic stylistic control.
