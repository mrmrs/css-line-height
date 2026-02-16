# css-line-height

Functional CSS for line-height

## Filesize

| File | Size |
|------|------|
| `dist/line-height.css` | 821 bytes |
| `dist/line-height.min.css` | 537 bytes (161 Gzipped) |

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
| `.lh1` | `line-height: 1;` |
| `.lh2` | `line-height: 1.25;` |
| `.lh3` | `line-height: 1.5;` |
| `.lh4` | `line-height: 2;` |
| `.lh5` | `line-height: .85;` |
| `.lh1-s` | `line-height: 1;` |
| `.lh2-s` | `line-height: 1.25;` |
| `.lh3-s` | `line-height: 1.5;` |
| `.lh4-s` | `line-height: 2;` |
| `.lh5-s` | `line-height: .85;` |
| `.lh1-m` | `line-height: 1;` |
| `.lh2-m` | `line-height: 1.25;` |
| `.lh3-m` | `line-height: 1.5;` |
| `.lh4-m` | `line-height: 2;` |
| `.lh5-m` | `line-height: .85;` |
| `.lh1-l` | `line-height: 1;` |
| `.lh2-l` | `line-height: 1.25;` |
| `.lh3-l` | `line-height: 1.5;` |
| `.lh4-l` | `line-height: 2;` |
| `.lh5-l` | `line-height: .85;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.lh1-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/line-height.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/line-height.css` — formatted
- `dist/line-height.min.css` — minified

## License

MIT
