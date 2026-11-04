# DOM live

Un singur fișier HTML (`index.html`), fără build și fără npm: order book live de pe Binance (futures și spot), cu tape, delta și separarea ordinelor executate de cele retrase.

- Date: WebSocket public Binance, direct din browser. Nu există cont, cheie sau server.
- Doar citire. Nu plasează ordine.
- Hosting: GitHub Pages (branch `main`, rădăcina). `_headers` e pregătit pentru Cloudflare Pages, dacă se mută acolo.
- Pe futures, cartea vine de pe `/public` și tranzacțiile de pe `/market`; pe spot, o singură conexiune.

Nu e sfat financiar.
