# 🏙️ Founder City

A startup real-time strategy game inspired by the [Acquired](https://www.acquired.fm/) podcast.

- **Chapter 1: The Garage** (1998) — found Nimbus, hire devs and sales, watch your burn rate, and take on the incumbent MacroCorp.
- **Chapter 2: The Bubble** (1999–2000) — after your IPO, a VC-fueled clone called Dotbomb outspends you everywhere. They grow faster than you, but they have no revenue: survive until March 10, 2000, and the crash will do the rest.

## Play locally

```bash
npm start        # serves on http://localhost:3000
```

Or just open `index.html` in a browser — the whole game is a single file.

## Deploy to Railway

```bash
railway init
railway up
```

Railway detects the Node app automatically (`npm start`). No dependencies, no build step.

## How to play

- **Select** units with click or drag-box; **right-click** to move, attack, or give context orders.
- **Devs** 👩‍💻: right-click your garage to write code (fills the Product bar); they also construct buildings.
- **Sales** 🤵: right-click a wandering customer to pitch them; they auto-fight MacroCorp sales at close range.
- **Buildings**: Servers speed up development, Coffee Shops restore nearby morale.
- **Economy**: every employee costs salary per second; every signed customer pays revenue per second.
- **Win**: Product 100% + 6 customers (IPO), or destroy MacroCorp Tower.
- **Lose**: run out of cash, MacroCorp corners the market, or your garage is razed.

*"Is this the greatest business of all time?"*
