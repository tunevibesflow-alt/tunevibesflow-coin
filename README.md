
# TuneVibesFlow Coin Website - v7

This bundle contains a responsive landing page for TuneVibesFlow Coin ($TVF) with:
- Galaxy-style dark theme
- CSS pink–orange soundwave animation
- Banner + coin images
- Live price tracker (client-side, uses CoinGecko contract API)
- Buy button linking to your Pump.Fun page

## Files
- `index.html` - Main responsive landing page
- `A_digital_rendering_of_a_coin_features_the_TuneVib.png` - Coin image
- `A_digital_graphic_design_banner_for_TuneVibesFlow_.png` - Banner image

## How to enable live price
1. Open `index.html` in a text editor.
2. Find the JS section near the bottom and set:
   - `CONTRACT_ADDRESS` to your token contract (example: `0x...`).
   - `PLATFORM` to either `binance-smart-chain` or `ethereum` depending on the chain.
3. Save and open `index.html` in a browser. The price will load from CoinGecko (client-side).

## Deploy
Use GitHub Pages / Netlify / Vercel as in earlier README instructions.

Notes:
- If CoinGecko doesn't have your token, the live price will be unavailable.
- The buy button links to Pump.Fun as provided.
