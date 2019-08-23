# Argo Navis First Principles

## Principle I: Space-based Sandbox

Argo Navis is a space-based sandbox game, a virtual world where players can choose to engage in any activity.  The primary gameplay is piloting one's starship in the open, continous and persistent world.

Gameplay emerges from the game physics and other generic layers such as manufacturing and deployable modules.

The primary gameplay layers are:

### Exploration

Players can travel through the universe and discover new star systems, planets, moons and other astronomical objects.

Players can navigate to and enter orbit around such objects.

Players can land on planets, moons and other bodies to explorer them further.

Player exploration is how the game world continously grows through procedural generation.

### Mining

Players can extract resources from the world and refine them into raw materials.  Resources are found throughout the world; on and inside planets, moons, asteroids, comets and structures.

Building industrial structures can make retrieving resources easier and more efficient.  Structures may be required to extract some resources but should be optional for most.

### Building

Almost everything players use to interact with the world are built by players.  Raw materials are combined into intermediate materials and final products.

Player-built objects include starships, space stations, their modules and surface structures.

### Combat

Players can engage NPCs (PvE) through exploration and quests.  Players can engage each other (PvP) in less lawful star systems beyond faction space.

Combat is derived from real world military weapons and systems and has a realistic feel to it.  Combat is strongly internally consistent with the game physics and other world aspects.

Combat is inspired by both classical and new games and has a strong "rock-paper-scissors" (but with more dimensions) design to it.

Combat features both classic sci-fi space gameplay and novel mechanisms.  The core of combat is ship defensive mechanisms such as armor, shields and evasive manuvering and weapons such as railguns and lasers.  Game physics have a significant role in combat and ship size, speed and mass are of tactical and strategic importance.

Electronic Warfare (EW), countermeasures (ECM) and counter-countermeasures (ECCM) are inspired by real-world technology and in combination adds complex layers to ship builds, strategy and tactics.

Combat and game design should bring about emergence of a complex "meta game" in PvP where no single strategical or tactical play is optimal in every situation.

### Trade

Players can sell and buy almost any retrievable object.  Fungible objects (e.g. raw materials) can be traded through standard exchange order books and unique items can be traded through auction and escrow mechanisms.

Trade generally takes place inside space stations which provide players with a safe trade environment even in dangerous or lawless star systems.

### Community

Players can form organizations (orgs) such as guilds, corporations and alliances.  These orgs are highly configurable and provide gameplay benefits such as joint ownership of assets such as starships, space stations and industrial structures.

Orgs enable players to configure standings between each other and to conquer space.

### Conquest

Player orgs can conquer space, claiming sovereignty of astronomical bodies and entire star systems.  Sovereignty conveys various benefits at the cost of maintaing it through military installations, logistics and defending territory.

### Skills and Role Playing

Player characters can train time-based skills to become better at game activities and unlock more advanced gameplay.

Each skill can be trained a number of levels, each additional level taking longer and longer to train.

Skills form a skill tree, with some advanced skills requiring training in prerequisite skills.


## Principle II: Epic Scale

### Milky Way Galaxy

The Argo Navis game world is the Milky Way Galaxy.  Star systems close to Earth are based on real-world astronomical observations and recent exoplanet data.  Star systems further out are continously, procedurally generated through player exploration.  The generation algorithm is based on modern Present Day Mass Function (PDFM) research and exoplanet catalogs.

Size, mass and other attributes of stars, planets, moons and other celestial objects, as well as their orbits, are based on real-world observational data and reasonably statistically accurate according to the latest astronomy models.

Nested orbits support game objects such as space stations orbiting moons that orbit planets that orbit host stars.

Planets, moons and many other bodies can be landed upon and explored by foot or flight.

### Faster-Than-Light (FTL) Technology

Some star systems are connected via stargates, forming a "star map" that can be quickly traversed.

All systems can be flown to using hyperdrives and other Faster-Than-Light (FTL) technologies.  FTL allow for fast and fun gameplay - traversing realistic astronomical distances in a reasonable amount of time.  Each FTL technology have unique trade-offs in ship/module mass, cost, complexity and required skills.

Even with the fastest FTL technology, it can take players weeks or even months to traverse vast parts of the galaxy.

### Sol - Earth's solar system

Sol connects several nearby star systems and is at a central location between several star regions.  It is the location of several faction capitals / headquarters and a central trading hub.

While players can trade anywhere, Sol is designed to make it likely to emerge as the major trading port among safe star systems.  This is a unique exception of central design in the otherwise procedurally generated game world.

## Principle III: Real Economy

The Argo Navis in-game economy is player-driven with almost everything manufactured by players from raw materials mined from the world.

The open, laissez-faire economy has no built-in central planning or intervention mechanisms.  Regular game balance updates can be seen as a form of exogenous intervention, but such updates do not implement monetary policy or attempts at central pricing, but rather seek to balance fundamental gameplay and world resources.

### Resource Taps and Sinks

In good economic design, resource destructions (sinks) are as important as resource generations (taps).  Sinks add deflationary forces and are requierd to allow the game economy to reach an equilibrium of supply and demand from player activities.

The most important resource sink is combat, where destroyed starships, space stations and other player structures and objects have to be replenished by player manufacturing.

Combat loot and salvage must be balanced with resource sinks.  A guiding principle is that a random portion of a starship or space station's composition and fitted modules are always destroyed when the parent object is destroyed, with the rest dropping as loot and/or available through salvage mechanisms.

### Blockchain Network Link

Objects in the game should generally be transferable and tradeable.  Fungible objects can be bought/sold through exchange order books available in any space station.  Non-fungible objects can be bought/sold through auction and escrow mechanisms in any space station.

The game is natively linked to a public, decentralized and permissionless blockchain network, enabling players to freely transact between the game world and the connected network.

Crucially, the game will never introduce new cryptocurrencies or token; the primary in-game currency will be a pre-existing cryptocurrency or token from the connected blockchain network.

This allows the in-game economy to become as real as players believe it is.  Value can flow in and out of the game, and player characters and their assets can be transferred to external markets, other connected virtual worlds and even forks of the game world.

### No Pay-To-Win

The game will never feature "pay to win".  All objects that affect gameplay must originate from the game world and be either discovered (procedural generation) or manufactured by players.

Microtransactions (as in the game studio selling to players) are only allowed for cosmetic-only objects such as skins for characters, starships and space stations.

### Open, Free and Fair Markets

While players can transfer arbitrary value into the game, the use of that value is bounded and put to risk through the rules of the game.  This provides balance as the more value players deploy in the world the more they risk losing.

### Exponentially Diminishing Returns

Generally, reward must be proportional to risk.

Generally, linear increase in "power" must require an exponential increase in cost.  For example, a starship weapon module with 10% more damage compared to the "base version" of the module may cost 3X more than the base version.

Market prices are a function of supply and demand in a free market and game object manufacturing should feel realistic in terms of required raw materials.  Game design should thus generally balance more powerful starships, structures and their modules by ensuring their manufacturing requires certain amounts of rarer resources.

### Game Balance Updates

In a complex sandbox with multiple interacting layers, frequent game updates are required to balance gameplay.  For example, the defensive/offensive capabilities of starships and their modules requires continual tuning over the long term, especially when new ships or new gameplay mechanisms are introduced.  Regular updates are also required to balance changes in PvP and alliance warfare meta games.

Modifying a weapon's damage without changing the resources required to manufacture it will most likely cause the in-game markets to price the module lower.

Likewise, changes in the distribution, rarity, spawn mechanisms or other aspects of resources can significantly alter gameplay and lead to dramatic effects on in-game markets.

To prevent in-game economic shocks from game updates, the game developers commit to publishing one or more official "balance warnings" before announcing concrete, upcoming balance changes.  This is similar to profit warnings in traditional markets that give market participants a chance to more gradually adjust to upcoming changes.  More generally, the game developers commit to discuss potential balance changes as openly and transparently as possible, so that even official balance warnings will have a smaller impact on in-game market prices.

However, economic shocks originating from endogenous variables are a natural part of the game.  For example, if a skilled group of players manage to take control over a rare resource, they are explicitly allowed to exploit it, even if it leads to very high market prices.

A key principle is that no one player or group of players should be able to completely dominate a single resource long-term.  Monopolies of resources ranging from days to several weeks can be acceptable, but the game design must ensure that resource monopolies incur costs proportional to profits, and significantly increases the risk of warfare, as other players have a strong incentive to challenge the monopoly.

There is an inherent contradiction in allowing the game economy to evolve on its own while simultaneously ensuring the game has good balance and gameplay.

The guiding principle is that balance changes must improve game-play for the majority of players in the long-term and remain effective and sustainable amid other long-term changes in endogenous variables such as warfare and conquest between player groups and the evolving meta game.

Balance changes must never be made to address short-term market price fluctuations nor to address absolute pricing of goods.