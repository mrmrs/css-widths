# css-widths

Functional CSS for widths

## Filesize

| File | Size |
|------|------|
| `dist/widths.css` | 1537 bytes |
| `dist/widths.min.css` | 1091 bytes (231 Gzipped) |

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
| `.w-border-box` | `width: border-box;` |
| `.w-content-box` | `width: content-box;` |
| `.w-max-content` | `width: max-content;` |
| `.w-min-content` | `width: min-content;` |
| `.w-available` | `width: available;` |
| `.w-fit-content` | `width: fit-content;` |
| `.w-auto` | `width: auto;` |
| `.w-inherit` | `width: inherit;` |
| `.w-border-box-s` | `width: border-box;` |
| `.w-content-box-s` | `width: content-box;` |
| `.w-max-content-s` | `width: max-content;` |
| `.w-min-content-s` | `width: min-content;` |
| `.w-available-s` | `width: available;` |
| `.w-fit-content-s` | `width: fit-content;` |
| `.w-auto-s` | `width: auto;` |
| `.w-inherit-s` | `width: inherit;` |
| `.w-border-box-m` | `width: border-box;` |
| `.w-content-box-m` | `width: content-box;` |
| `.w-max-content-m` | `width: max-content;` |
| `.w-min-content-m` | `width: min-content;` |
| `.w-available-m` | `width: available;` |
| `.w-fit-content-m` | `width: fit-content;` |
| `.w-auto-m` | `width: auto;` |
| `.w-inherit-m` | `width: inherit;` |
| `.w-border-box-l` | `width: border-box;` |
| `.w-content-box-l` | `width: content-box;` |
| `.w-max-content-l` | `width: max-content;` |
| `.w-min-content-l` | `width: min-content;` |
| `.w-available-l` | `width: available;` |
| `.w-fit-content-l` | `width: fit-content;` |
| `.w-auto-l` | `width: auto;` |
| `.w-inherit-l` | `width: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.w-border-box-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/widths.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/widths.css` — formatted
- `dist/widths.min.css` — minified

## License

MIT
