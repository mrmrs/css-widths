# css-widths

Functional CSS for widths

## Filesize

| File | Size |
|------|------|
| `dist/widths.css` | 1333 bytes |
| `dist/widths.min.css` | 887 bytes (220 Gzipped) |

## Install

```sh
npm install css-widths
```

## Usage

### Import

```css
@import "css-widths";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-widths/dist/widths.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-widths/dist/widths.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.wi-bb` | `width: border-box;` |
| `.wi-cb` | `width: content-box;` |
| `.wi-mx` | `width: max-content;` |
| `.wi-mn` | `width: min-content;` |
| `.wi-av` | `width: available;` |
| `.wi-fc` | `width: fit-content;` |
| `.wi-at` | `width: auto;` |
| `.wi-i` | `width: inherit;` |
| `.wi-bb-s` | `width: border-box;` |
| `.wi-cb-s` | `width: content-box;` |
| `.wi-mx-s` | `width: max-content;` |
| `.wi-mn-s` | `width: min-content;` |
| `.wi-av-s` | `width: available;` |
| `.wi-fc-s` | `width: fit-content;` |
| `.wi-at-s` | `width: auto;` |
| `.wi-i-s` | `width: inherit;` |
| `.wi-bb-m` | `width: border-box;` |
| `.wi-cb-m` | `width: content-box;` |
| `.wi-mx-m` | `width: max-content;` |
| `.wi-mn-m` | `width: min-content;` |
| `.wi-av-m` | `width: available;` |
| `.wi-fc-m` | `width: fit-content;` |
| `.wi-at-m` | `width: auto;` |
| `.wi-i-m` | `width: inherit;` |
| `.wi-bb-l` | `width: border-box;` |
| `.wi-cb-l` | `width: content-box;` |
| `.wi-mx-l` | `width: max-content;` |
| `.wi-mn-l` | `width: min-content;` |
| `.wi-av-l` | `width: available;` |
| `.wi-fc-l` | `width: fit-content;` |
| `.wi-at-l` | `width: auto;` |
| `.wi-i-l` | `width: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.wi-bb-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/widths.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/widths.css` — formatted
- `dist/widths.min.css` — minified

## License

MIT
