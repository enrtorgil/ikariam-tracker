<img src="public/images/readme/ika-logo-tracker.gif" alt="Ikariam Island Tracker" width="100%" />

Unofficial tool to explore and analyze islands across multiple servers in [Ikariam](https://es.ikariam.gameforge.com) — the classic strategy game set in ancient Greece.

Visit the live site at **[ikatracker.com](https://ikatracker.com)**.

---

## Features

**Explore & analyze**

- **Global island ranking** based on combined score, plus dedicated rankings for sawmills and special mines
- **Island table** with filters by world, mine type, wonder, free slots, Helios Tower, and more
- **Detailed island view** with stats, interactive world map, and player distribution chart
- **Mine level distribution charts** by resource type
- **Tracked worlds dashboard** with last scrape time, session status and data freshness per server
- **World bonuses** — the bonuses and maluses of every lobby world, grouped by community, also usable as a filter in the island table
- **Multi-language UI** in 28 languages

**Atlas — search, rankings & maps**

- **Detailed search** — any player or alliance: stats, cities, members and score breakdown, plus a per-player chart of how their scores and states evolved
- **Player ranking** and **Alliance ranking** — cross-server leaderboards
- **Server ranking** — atlas of communities and worlds, with a **transfer eligibility checker** (exact gap to the top-50 cutoff in every world), a **ranking by population** and a **population evolution** chart per world
- **Player comparator** — pick up to 10 players and see who leads in each score, plus a historical chart (absolute or growth %) tracking their score evolution over time
- **Recent inactives** and **Recent vacations** — players inactive or on vacation right now, ranked by time in that state, with total points and alliance
- **Pillory** — every player ever banned, ranked by total days banned, with how many separate bans and their current state
- **Interactive world map** per server with player and alliance filters
- **Inactivity radar** — inactive/banned cities within a map area
- **Pirate radar** — pirate-fortress range coverage on the map
- **Trade map** — branch-office trade ranges across the map

**Agora — calculators**

- **Building calculator** — accumulated building costs and time, with reducers and multi-level upgrades
- **Military calculator** — army and fleet composition, upkeep and general bonuses
- **Units training time** — how long troops and ships take, from your barracks and shipyard level, including world bonus and government form
- **Abyssal Ambush** — damage and estimated rewards for the event, with editable base damage and reward coefficients
- **Wall destruction** — simulate siege attacks against a wall round by round, with ammunition and unit rotation
- **Production calculator** — sawmill and special-mine output, workers and upgrade times
- **Research calculator** — research points earned from researches
- **Unit upgrades** — accumulated per-level upgrade cost for troops and ships
- **Wonder regeneration** — miracle cooldowns from faith and theocracy

---

## Data collection

Each tracked world is scraped from its public Ikariam pages (rankings, world map, island and city views) using authenticated game sessions. The result is stored and served as a read-only dataset, refreshed on a schedule — the public site never scrapes on its own, it only displays the stored data.

Want a world added, or spotted something off? [Open an issue](https://github.com/enrtorgil/ikariam-tracker/issues).

---

## Supporting this project

This project is not affiliated with Gameforge. All in-game data belongs to their respective owners.

If you'd like to support the project:

- **[PayPal](https://paypal.me/enrtorgil)** — direct donation  
- **[Buy me a coffee](https://www.buymeacoffee.com/uEYSGKJaAO)** — no signup required  
- **[Ko-fi](https://ko-fi.com/enrtorgil)** — no platform fees  
- **[GitHub Sponsors](https://github.com/sponsors/enrtorgil)** — support the developer

---

## Community

Found a bug? Spotted a translation error? Have an idea, or a world you'd like added? [Open an issue](https://github.com/enrtorgil/ikariam-tracker/issues).

"Ikariam" is a registered trademark of Gameforge 4D GmbH. This project is not affiliated with, endorsed by, or sponsored by Gameforge.

---

<div align="center">

**Built with ❤️ using Laravel**

⭐ If you find this project useful, consider starring the repository

</div>
