# 🎡 Theme Park

> A plug-and-play CSS theme library. Pick a theme, drop in a `<link>` tag, done.

**[Live Theme Builder →](https://tranjcs.github.io/Theme-Park/builder)**

---

## Get started in 30 seconds

Pick a theme and paste the CDN link into your `<head>`:

```html
<!-- Modern — clean, blue accent -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/theme-park/themes/theme-modern.css">

<!-- Editorial — warm serif, newspaper feel -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/theme-park/themes/theme-editorial.css">

<!-- Terminal — dark monospace, hacker green -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/theme-park/themes/theme-terminal.css">
```

That's it. No build step, no JavaScript, no config.

---

## Themes

| Theme | Vibe | Font | Accent |
|---|---|---|---|
| `theme-modern.css` | Clean, geometric | System UI | Blue `#2563eb` |
| `theme-editorial.css` | Warm, newspaper | Georgia | Crimson `#8b1a1a` |
| `theme-terminal.css` | Dark, monospace | Courier New | Green `#3fb950` |

---

## What's included

Every theme styles these out of the box:

- **Typography** — `.title`, `h1`–`h3`, body text, muted text
- **Buttons** — `.btn-primary`, `.btn-secondary`, `.btn-ghost`
- **Images** — `.img-base`, `.img-card`, `figure`, `.img-caption`
- **Code** — inline `<code>` and `<pre>` blocks

All themes are **WCAG 2.1 AA compliant** — contrast ratios verified, `:focus-visible` styles included, and `prefers-reduced-motion` respected.

---

## Build your own

Don't like any of the presets? Use the **[live theme builder](https://tranjcs.github.io/Theme-Park/builder)** to adjust colors, fonts, border radius, and button style — then copy the generated CSS variables into your project.

---

## Use with npm

```bash
npm install theme-park
```

```css
@import 'theme-park/themes/theme-modern.css';
```

---

## Customize

Every theme is built on CSS custom properties. Override any variable in your own stylesheet:

```css
:root {
  --color-accent: #7c3aed;   /* swap the accent to purple */
  --radius-md:    12px;      /* rounder corners */
}
```

---

## Roadmap

- [ ] Components: tabs, accordion, modal
- [ ] Zero-JS component variants (CSS-only with `:has()`)
- [ ] RTL support (logical properties)
- [ ] More themes

---

## License

MIT
