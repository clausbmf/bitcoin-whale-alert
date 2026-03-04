 # 🐋 Bitcoin Humpback Whale Alert

  A real-time, single-file Bitcoin whale transaction tracker built with
  vanilla HTML, CSS, and JavaScript. No backend. No framework. Just open
  it in a browser.

  ## Features
  - Detects live Bitcoin transactions above 100 BTC (Whale) and
    1,000 BTC (Humpback Whale)

  - Exchange detection — identifies Binance, Coinbase, Kraken,
    Bitfinex, OKX and more

  - Transfer direction indicator — Wallet → Exchange, Exchange →
    Exchange, and more

  - Dormant whale detection — flags coins inactive for 1, 3, or 5+ years

  - 🔊 Synthesized whale sound alerts via Web Audio API (toggle ON/OFF)
  - 📊 Live stats bar — Whales Today, Biggest Move, Total BTC Moved
  - ⚡ Auto-refreshes every 15 seconds via mempool.space public API
  - 💾 24-hour transaction cache using localStorage
  - 📱 Fully responsive dark theme UI

  ## How to use
  Just open index.html in any modern browser. No install needed.

  Data source: mempool.space
