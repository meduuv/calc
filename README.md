# Calc

> A clean, keyboard-friendly calculator built for the browser.

Calc is a lightweight client-side calculator with a focused interface, basic arithmetic, percentage support, calculation history, and keyboard controls.

## Features

- Addition, subtraction, multiplication and division
- Percentage calculations
- Decimal input
- Backspace and clear controls
- Calculation history
- Full keyboard support
- No backend required

## Run locally

Clone the repository and open `index.html` in a browser.

```bash
git clone https://github.com/meduuv/calc.git
cd calc
```

No build step or package installation is required.

## Controls

| Action | Input |
|---|---|
| Numbers | `0-9` |
| Operators | `+ - * / %` |
| Calculate | `Enter` / `=` |
| Delete | `Backspace` |
| Clear | `Escape` |

## How it works

```text
keyboard / buttons
        ↓
 expression state
        ↓
 validated arithmetic
        ↓
 result + history
```

Everything runs locally in the browser. There is no server-side calculation layer.

## Tech

- HTML
- CSS
- Vanilla JavaScript
- Browser DOM APIs

## License

MIT

Built by **Meduuv**.

[More projects](https://github.com/meduuv?tab=repositories) · [guns.lol/meduu](https://guns.lol/meduu)
