# NEUBRUTALISM.

### The definitive guide to the design movement that refuses to be invisible.

**[neubrutalism.com](https://neubrutalism.com)** -- A comprehensive, authoritative, single-page reference on neubrutalist web design. History, visual anatomy, typography, code patterns, accessibility, and implementation strategy. The page doesn't just describe neubrutalism -- it *is* neubrutalism.

---

## What's Inside

| Section | What You'll Learn |
|---|---|
| **Definition** | What neubrutalism actually is, its philosophy, and how it differs from architectural brutalism and web brutalism |
| **Visual DNA** | The full anatomy -- color theory, borders, hard shadows, typography, and layout principles with live demos |
| **The Type System** | 10 curated fonts across 4 roles (display, heading, body, mono) with specimens and 3 recommended pairings |
| **History** | Timeline from 1950s New Brutalism through Memphis, web brutalism, the Figma effect, to present day |
| **Implementation** | CSS token system, canonical button/card patterns, interactive playground with live sliders |
| **Usage Guide** | Sector-by-sector analysis, WCAG accessibility table, and implementation best practices |
| **Ecosystem** | The four layers (showcase, education, productization, implementation), key platforms, brand adoption |
| **Future** | Durability analysis, competing movements, emerging subtypes |

---

## The Stack

```
border:        3px solid #000;
box-shadow:    5px 5px 0 0 #000;
border-radius: 0;
frameworks:    0;
build-steps:   0;
dependencies:  0;
```

Vanilla HTML + CSS + JS. Google Fonts. That's it. No React, no Tailwind, no webpack, no npm. Opens in any browser, loads instantly, works down to 250px viewport width.

---

## Design Tokens

The entire aesthetic compresses into a handful of CSS custom properties:

```css
:root {
  --border:     3px solid #000;
  --shadow-sm:  3px 3px 0 0 #000;
  --shadow:     5px 5px 0 0 #000;
  --shadow-lg:  8px 8px 0 0 #000;
  --radius:     0;

  --yellow:     #FFD23F;
  --pink:       #FF6B6B;
  --blue:       #74B9FF;
  --green:      #88D498;
}
```

---

## Contributing

This is a community resource. Found an error? Have deeper knowledge? Want to add a section?

1. Fork this repo
2. Create a branch (`git checkout -b my-improvement`)
3. Make your changes
4. Submit a pull request

**Rules:** Vanilla only. Mobile-first. WCAG AA minimum. Practice what we preach. See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

---

## Run Locally

```bash
git clone https://github.com/neubrutalism/neubrutalism.com.git
cd neubrutalism.com
python3 -m http.server 8000
# open http://localhost:8000
```

---

## License

MIT -- see [LICENSE](LICENSE).

---

**`border: 3px solid #000; box-shadow: 5px 5px 0 0 #000;`**
