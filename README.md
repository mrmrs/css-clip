# css-clip

Functional CSS for clip

## Filesize

| File | Size |
|------|------|
| `dist/clip.css` | 401 bytes |
| `dist/clip.min.css` | 279 bytes (118 Gzipped) |

## Install

```sh
npm install css-clip
```

## Usage

### Import

```css
@import "css-clip";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-clip/dist/clip.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-clip/dist/clip.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.clip-auto` | `clip: auto;` |
| `.clip-i` | `clip: inherit;` |
| `.clip-auto-s` | `clip: auto;` |
| `.clip-i-s` | `clip: inherit;` |
| `.clip-auto-m` | `clip: auto;` |
| `.clip-i-m` | `clip: inherit;` |
| `.clip-auto-l` | `clip: auto;` |
| `.clip-i-l` | `clip: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.clip-auto-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/clip.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/clip.css` — formatted
- `dist/clip.min.css` — minified

## License

MIT
