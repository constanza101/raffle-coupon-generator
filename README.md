# 🎟️ Raffle Coupon Generator

A simple, free, browser-based tool to generate print-ready A4 raffle coupon sheets — no signup, no install, no server required.

**[→ Open the app](https://constanza101.github.io/raffle-coupon-generator/)**

---

## What it does

Fill in your event details, pick a color, and generate a printable PDF with numbered coupons ready to hand out. Each coupon includes fields for participants to write their name, last name, ID, phone number, and Instagram handle.

Designed for clubs, schools, small businesses, and community organizations running fundraisers or giveaways.

---

## Features

- **Unique numbered coupons** — auto-incremented with customizable zero-padding (001, 0001, 00001)
- **4, 8, 10 or 12 coupons per A4 page** — choose the size that works for your event
- **Custom color** — match your brand or event theme
- **Optional tear-off stub** — keep the numbered stub, give the main coupon to the participant
- **Adjustable field spacing and font size** — fine-tune the layout to fit more or less info
- **Printer-safe margins** — 8mm safe zone on all sides, zero gap between coupons for clean cutting
- **Bilingual** — full Spanish and English interface
- **Works offline** — once the page loads, no internet needed
- **No data collected** — everything stays in your browser

---

## How to use

1. Open the app at [constanza101.github.io/raffle-coupon-generator](https://constanza101.github.io/raffle-coupon-generator/)
2. Fill in your event name, organization, starting number and total coupon count
3. Choose your color, coupons per page, number format, and spacing preferences
4. Click **Preview** to see your layout
5. Click **Print / Save PDF** — in the print dialog, set margins to **None** and save as PDF

> **Tip:** In Chrome, go to *More settings → Margins → None* before saving to PDF to avoid extra whitespace.

---

## Customization options

| Option | Range | Default |
|---|---|---|
| Coupons per page | 4, 8, 10, 12 | 10 |
| Number format | 3–5 digits | 3 (001) |
| Main color | Any hex color | `#88C1B4` |
| Field gap | 2px – 24px | 14px |
| Font size | 6px – 14px | 8px |
| Tear-off stub | On / Off | Off |

---

## Running locally

No build step needed. Just clone and open:

```bash
git clone https://github.com/constanza101/raffle-coupon-generator.git
cd raffle-coupon-generator
open index.html
```

---

## Contributing

Pull requests are welcome. If you find a bug or have a feature idea, open an issue.

---

## License

MIT — free to use, modify, and share.
