# Card Vault

A free, no-login trading card collection and portfolio tracker. Search cards, add them to your collection, and watch market value over time.

Open the hosted site on your phone, then use Share → Add to Home Screen to use it like an app.

## Live prices

- **Pokémon** — [Pokémon TCG API](https://pokemontcg.io) (TCGplayer market prices). Falls back to [TCGdex](https://tcgdex.dev) if that API is down.
- **Magic: The Gathering** — [Scryfall](https://scryfall.com/docs/api) USD prices.
- **Yu-Gi-Oh!** — [YGOPRODeck](https://ygoprodeck.com/api-guide/) TCGPlayer prices.
- **Anything else** (sports cards, sealed product, etc.) — manual name and price.

Market prices are typically for near-mint copies. No account or API key is required. The Pokémon TCG API may rate-limit heavy use.

## Your data

Everything is stored in this browser's local storage on this device. Clearing the site's data, switching browsers, or using another phone will look like an empty collection.

Use **Export JSON** (full backup) or **Export CSV** from the Backup tab, and **Import JSON** to restore. Keep a copy of the JSON file somewhere safe.

## Running it yourself

This is a static site. Any folder with `index.html` works — no build step.

## License

Source is provided as-is for personal use. This project is not affiliated with Collectr, The Pokémon Company, Wizards of the Coast, Konami, TCGplayer, or Scryfall.
