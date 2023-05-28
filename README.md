# Inter font for Hugo

This module provides CSS and web fonts for [Inter](https://github.com/rsms/inter/).

By default, only Latin and Latin Extended character sets are included.
Optionally, Cyrillic, Greek and Vietnamese are available in addition to Latin.

To use, import this module from your `config.toml`.

## Latin only

```toml
[module]
[[module.imports]]
path = "github.com/hugo-fonts/inter"
```

To enable the font in a template, use `/css/inter-latin.css`.

## Cyrillic
```toml
[module]
[[module.imports]]
path = "github.com/hugo-fonts/inter/cyrillic"
```

To enable the font in a template, use `/css/inter-cyrillic.css`.

## Greek
```toml
[module]
[[module.imports]]
path = "github.com/hugo-fonts/inter/greek"
```

To enable the font in a template, use `/css/inter-greek.css`.

## Vietnamese
```toml
[module]
[[module.imports]]
path = "github.com/hugo-fonts/inter/vietnamese"
```

To enable the font in a template, use `/css/inter-vietnamese.css`.
