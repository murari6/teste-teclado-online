# Teste de Teclado Online

A free, instant keyboard testing tool built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies, no installation required.

🌐 **Live Site:** [testeteclado.online](https://testeteclado.online)

## Features

- **Real-time key testing** — Press any key and see it light up instantly
- **ABNT2 & ANSI support** — Proper Brazilian layout with Ç key
- **Chatter detection** — Flags keys that register double-presses
- **Dark/Light mode** — Click the title to toggle themes
- **Mobile-friendly** — Works on PC, laptop, and phone
- **6 languages** — Portuguese, English, Spanish, French, German, Italian
- **Zero dependencies** — ~15KB total page weight
- **SEO optimized** — JSON-LD, Open Graph, Twitter Cards, hreflang

## Articles & Guides

The site includes comprehensive keyboard troubleshooting guides:

- [ABNT2 vs ANSI: How to Identify Your Keyboard Layout](https://testeteclado.online/abnt2-ou-ansi/)
- [Keyboard Chatter: What It Is, How to Detect and Fix](https://testeteclado.online/teclado-com-chatter/)
- [How to Test a Mechanical Keyboard: Complete Step-by-Step Guide](https://testeteclado.online/como-testar-teclado-mecanico/)
- [Anti-Ghosting Test: How to Detect and Fix Ghosting](https://testeteclado.online/teste-anti-ghosting/)
- [How to Test Notebook Keyboard: Complete Guide](https://testeteclado.online/teste-teclado-notebook/)
- [Free Mouse Click Test Online — Check Double Click and Buttons](https://testeteclado.online/teste-de-mouse/)

## Tech Stack

- **HTML5** — Semantic markup with JSON-LD structured data
- **CSS3** — Self-hosted utility classes (Tailwind-like, 5KB gzipped)
- **Vanilla JavaScript** — Zero dependencies, runs in all modern browsers
- **Cloudflare Pages** — Global CDN, instant deployments

## Performance

- **LCP:** < 0.5s (self-hosted CSS, no external requests)
- **CLS:** 0 (no layout shifts)
- **Total size:** ~15KB HTML + CSS combined
- **No tracking cookies** — Privacy-first design

## Deployment

```bash
npm install
npm run deploy
```

Requires [Cloudflare Wrangler CLI](https://developers.cloudflare.com/pages/functions/wrangler/).

## License

MIT License — feel free to fork and modify.

## Built With ❤️ for Brazilian Keyboard Users

Created because existing keyboard testers didn't properly support the ABNT2 layout. Now you can test every key on your Brazilian keyboard instantly.

---

⭐ **Star this repo** if you find it useful!

[Report an issue](https://github.com/issues) | [Suggest a feature](https://github.com/issues)
