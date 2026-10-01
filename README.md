# Inside the Quant Desk

An interactive field guide to what quants do: the four common roles, the
pipeline from idea to trade, and six live simulations you can play with.

- **Randomness**: Monte Carlo price paths and volatility
- **Backtesting**: a moving-average rule, in-sample vs out-of-sample, overfitting
- **Diversifying**: correlation and the risk/return curve of a two-asset mix
- **Options**: Black–Scholes value, payoff, delta
- **Market making**: spreads, inventory and informed traders, with a live order book
- **Speed**: latency from CPU cycles to transatlantic fibre

Everything is one file, `index.html`, with no build step and no dependencies
(fonts come from Google Fonts and fall back to system fonts). All markets are
simulated from seeded random numbers, so nothing here is real data or advice.

## Run it

    python3 -m http.server 8000

Then open http://localhost:8000.

## Earlier project

The 20/10 Vietsoc Dundee invitation that used to live here is kept unchanged in
`archive/envelope-2024/`.
