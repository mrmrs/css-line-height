# css-line-height

Functional CSS for line-height

## Filesize

| File | Size |
|------|------|
| `dist/line-height.css` | 849 bytes |
| `dist/line-height.min.css` | 565 bytes (165 Gzipped) |

## Install

```sh
npm install css-line-height
```

## Usage

### Import

```css
@import "css-line-height";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-line-height/dist/line-height.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-line-height/dist/line-height.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.lh` | `line-height: 1;` |
| `.lh-title` | `line-height: 1.3;` |
| `.lh-copy` | `line-height: 1.5;` |
| `.lh-2` | `line-height: 2;` |
| `.lh-3` | `line-height: 3;` |
| `.lh-s` | `line-height: 1;` |
| `.lh-title-s` | `line-height: 1.3;` |
| `.lh-copy-s` | `line-height: 1.5;` |
| `.lh-2-s` | `line-height: 2;` |
| `.lh-3-s` | `line-height: 3;` |
| `.lh-m` | `line-height: 1;` |
| `.lh-title-m` | `line-height: 1.3;` |
| `.lh-copy-m` | `line-height: 1.5;` |
| `.lh-2-m` | `line-height: 2;` |
| `.lh-3-m` | `line-height: 3;` |
| `.lh-l` | `line-height: 1;` |
| `.lh-title-l` | `line-height: 1.3;` |
| `.lh-copy-l` | `line-height: 1.5;` |
| `.lh-2-l` | `line-height: 2;` |
| `.lh-3-l` | `line-height: 3;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.lh-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/line-height.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/line-height.css` — formatted
- `dist/line-height.min.css` — minified

## License

MIT
