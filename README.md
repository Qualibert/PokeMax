# PokeMax

PokeMax is a Discord bot designed to help build and manage a Pokémon Go community. 
Most of its features required PokeNav bot: https://pokenavbot.com/

## Planned features

This list consists in no-way a engagement on my part to develops in any timeframe, or at all, the mentionned features. This is merely to give an idea on where PokeMax is going to be.
Modules tagged as ``TBC`` are more in a proof-of-concept state than the others. Those tagged as ``Plus`` requires a lot of work and might be feature enable for patreon supporters.

### Welcome module
- Ability to have a welcome channel where new users can easily setup their pokenav trainer profile.
- Provides a step-by-step guide with each section trigerred after the previous is done.
- The module will checks for invalid inputs (like xp with spaces).

### Raid module
- ``flare`` command which will enable notifying the server about raids looking for help and when.
- ``go`` command to send a role-tag in the chat, after making sure every participant is on-site.
- Advanced statistics for each member, including alternatives to count ``raids joined`` and ``raid party created``.
- Odds of winning with the current group command and display in the channel description.
- ``tiers`` command which display the current boss list infographic.
- On egg hatched, support for selecting the boss with a reaction from a list.
- Exploring a way to split "active-raids" channel.
- Exploring a way to advertise ex-raid pass sharing.
- Exploring a way to display a mini-map in "active-raids" (Plus)

### General-Chat module
- Ability to cherry-pick copycat "PokeNav" commands in specific channels (``gtc`` / ``map`` /compact ``dex`` etc).

### POI module
- Batch import from a IITC (PoGo plugin) JSON file.
- Partial matching "Did you mean?" for invalid reports.

### Embed module
- ``announce`` command which can build a nice-looking embed piece-by-piece instead of a long single command. (ex: ``announce title Mewtwo is back in ex-raids!`` then ``announce thumbnail www.something.com/mewtwo.png`` )
- Each embed command will display the current preview of the embed you are working on.
- A simple reaction can then send it to your preset "news" channel or another channel of your choice.

### Nest module (TBC)
- Synchronisation from TSR Atlas.
- User nest reporting supporting partial match.
- New POI similar to others PokeNav pois (nests).
- Self-cleaning active-nests channel with optionnal notifications for migration.

### Wild reporting module (TBC)
- To be announced.

### Gym takedown module (TBC)
- To be announced.

### Event module (TBC)
- To be announced.

### Badge module (TBC - Plus)
- Autogranting PokeNav badges on certain criterias.

### Notifications module (TBC - Plus)
- Self-updated notifications list and roles using the current boss list.
- Displayed as a "reaction role" type message that users can press to get notifications for some raids.
- Support for a "schedule" which could disable all notifications for "busy" timeframe.

### PVP module (TBC - Plus)
- PVP channel supporting PVP challenges or "looking for opponent".
- Score given using reactions to declared the winner (similar to silph.gg).
- Leaderboards for PVP stats.

### Android Tasker Overlay (Plus)
- Synthetic Google voice notifications for new raid reports.
- Raid, research and wild reporting by screenshots with single button press from the game.
- Ability to use some of the raid commands to some extend (including ``go`` and ``here``).
- Informations on the current raid viewable without leaving the game (odds of winning, boss max CP).

### Enhanced Trade module (TBC - Plus)
- To be announced.
- Possibly an alternate way of sorting trade requests.

### Misc Infographics module (TBC)
- ``set-field`` and ``set-eggs`` commands to have the commands display a chosen infographic.
- Possibilty to eventually have automatic field, counters and egg infographics (Plus).

### Real-Life Weather module (TBC - Plus)
- To be announced.
- Not for ingame weather (this is not figured out yet).

### Pokestop Submission module (TBC - Plus)
- Considered only, might not be relevant.

### Multilanguages module (TBC - Plus)
- Considered only, might not be relevant.
