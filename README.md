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

Item and game data will use World of Warcraft: Forever data sources, including the ForeverDB API (https://foreverdb.net), subject to data availability and validation.

Planned ForeverDB API integration

The project intends to use the ForeverDB API to retrieve item, item-set and dungeon information for its gear-upgrade recommendation feature.

API requests will be handled server-side through the Cloudflare Worker. API credentials will be stored securely as server-side secrets, and retrieved data may be cached to limit unnecessary requests and comply with API usage limits.

ForeverDB data will be used within the bot's functionality and will not be redistributed as a standalone dataset.

Where ForeverDB data is displayed, the bot will provide the required visible attribution and a link to ForeverDB.

Project status

Lowlander Tracker is a non-commercial, privately developed community project. Its source code is maintained in a private GitHub repository.

The gear-upgrade functionality is under development. Recommendations will be introduced only when the underlying data and evaluation methods have been sufficiently validated.

Technology

- JavaScript
- Cloudflare Workers
- Discord HTTP Interactions API
- Blizzard Community API
- Cloudflare KV
