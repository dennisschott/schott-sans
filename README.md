# Schott Sans

Schott Sans is a sans-serif type family designed by Dennis Schott. It includes five weights, each with a matching italic, for a total of ten styles.

## Family

| Weight | Upright | Italic | CSS weight |
| --- | --- | --- | ---: |
| Light | `SchottSans-Light` | `SchottSans-LightItalic` | 300 |
| Regular | `SchottSans-Regular` | `SchottSans-Italic` | 400 |
| Medium | `SchottSans-Medium` | `SchottSans-MediumItalic` | 500 |
| SemiBold | `SchottSans-SemiBold` | `SchottSans-SemiBoldItalic` | 600 |
| Bold | `SchottSans-Bold` | `SchottSans-BoldItalic` | 700 |

The repository contains static fonts in three formats:

- `TTF` for desktop use and broad application compatibility
- `WOFF2` for modern web use
- `WOFF` as a legacy web fallback

The fonts include broad Latin coverage as well as Cyrillic and Hebrew characters, plus common punctuation, symbols, numerals, and currency signs.

## Desktop installation

Install the `.ttf` files through your operating system's font manager. After installation, the family appears as **Schott Sans** in applications, with its weights and italics grouped under the same family name.

## Web use

Add the following declarations to your stylesheet. The paths assume the font files are stored next to the CSS file; adjust them to match your project.

```css
@font-face {
  font-family: "Schott Sans";
  src: url("./SchottSans-Light.woff2") format("woff2"),
       url("./SchottSans-Light.woff") format("woff");
  font-style: normal;
  font-weight: 300;
  font-display: swap;
}

@font-face {
  font-family: "Schott Sans";
  src: url("./SchottSans-LightItalic.woff2") format("woff2"),
       url("./SchottSans-LightItalic.woff") format("woff");
  font-style: italic;
  font-weight: 300;
  font-display: swap;
}

@font-face {
  font-family: "Schott Sans";
  src: url("./SchottSans-Regular.woff2") format("woff2"),
       url("./SchottSans-Regular.woff") format("woff");
  font-style: normal;
  font-weight: 400;
  font-display: swap;
}

@font-face {
  font-family: "Schott Sans";
  src: url("./SchottSans-Italic.woff2") format("woff2"),
       url("./SchottSans-Italic.woff") format("woff");
  font-style: italic;
  font-weight: 400;
  font-display: swap;
}

@font-face {
  font-family: "Schott Sans";
  src: url("./SchottSans-Medium.woff2") format("woff2"),
       url("./SchottSans-Medium.woff") format("woff");
  font-style: normal;
  font-weight: 500;
  font-display: swap;
}

@font-face {
  font-family: "Schott Sans";
  src: url("./SchottSans-MediumItalic.woff2") format("woff2"),
       url("./SchottSans-MediumItalic.woff") format("woff");
  font-style: italic;
  font-weight: 500;
  font-display: swap;
}

@font-face {
  font-family: "Schott Sans";
  src: url("./SchottSans-SemiBold.woff2") format("woff2"),
       url("./SchottSans-SemiBold.woff") format("woff");
  font-style: normal;
  font-weight: 600;
  font-display: swap;
}

@font-face {
  font-family: "Schott Sans";
  src: url("./SchottSans-SemiBoldItalic.woff2") format("woff2"),
       url("./SchottSans-SemiBoldItalic.woff") format("woff");
  font-style: italic;
  font-weight: 600;
  font-display: swap;
}

@font-face {
  font-family: "Schott Sans";
  src: url("./SchottSans-Bold.woff2") format("woff2"),
       url("./SchottSans-Bold.woff") format("woff");
  font-style: normal;
  font-weight: 700;
  font-display: swap;
}

@font-face {
  font-family: "Schott Sans";
  src: url("./SchottSans-BoldItalic.woff2") format("woff2"),
       url("./SchottSans-BoldItalic.woff") format("woff");
  font-style: italic;
  font-weight: 700;
  font-display: swap;
}
```

Then apply the family as usual:

```css
body {
  font-family: "Schott Sans", sans-serif;
}
```

## Version

The included font files are version `1.001`.

## Copyright and licensing

Copyright 2026 The Schott Sans Project Authors
(https://github.com/dennisschott/schott-sans).

Schott Sans is licensed under the [SIL Open Font License, Version 1.1](OFL.txt),
without a Reserved Font Name. You may use, study, modify, embed, and redistribute
the fonts under the terms of that license. Documents and artwork created with
the fonts are not required to use the OFL.
