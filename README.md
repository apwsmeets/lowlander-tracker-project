Lowlander Tracker

A community Discord bot for World of Warcraft: Forever.

Lowlander Tracker helps a small group of players keep track of their characters, find suitable dungeons while levelling, and explore potential gear upgrades.

Current functionality

- Character roster: Displays character levels, classes, races and specializations using public Blizzard character profiles.
- Dungeon recommendations: Suggests suitable dungeons based on the levels of selected characters.
- Character equipment data: Retrieves and caches currently equipped items to support future gear analysis.

Planned functionality: Gear upgrades

The project is being extended with a gear-upgrade recommendation feature.

The intended functionality includes:

- Checking whether an item can be equipped by a character.
- Evaluating item suitability for the character's specialization.
- Comparing candidate items against currently equipped gear.
- Accounting for item effects, relevant stats and set bonuses.

Item information will use World of Warcraft: Forever data sources, including "ForeverDB.net" (https://foreverdb.net), subject to data availability and validation.

Where ForeverDB data is displayed, the bot will provide the required visible attribution and link to ForeverDB.

Project status

Lowlander Tracker is a non-commercial, privately developed community project. Its source code is maintained in a private GitHub repository.

The gear-upgrade functionality is under development. Recommendations will be introduced only when the underlying data and evaluation methods have been sufficiently validated.

Technology

- JavaScript
- Cloudflare Workers
- Discord HTTP Interactions API
- Blizzard Community API
- Cloudflare KV
