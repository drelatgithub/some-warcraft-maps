# 3.0.0

From now on this map will be using sematic versioning!

- Balancing
    - Glyph of Fortification: Duration increased from 8s to 9s.
    - Human upgrade Improved Spotting: Attack range bonus increased from 700/1000 to 1000/1400.
    - Human base defense Guardian Spirit: Cooldown reduced from 95s to 80s.
    - Orc base defense True Art: Cooldown reduced from 100s to 80s.
    - Undead base defense Soul Release: Cooldown reduced from 95s to 80s.
    - Night Elf base defense Overgrowth: Cooldown reduced from 85s to 80s.
    - Relatively Fat Naga Siren: Initial Agi inceased from 25 to 30. Str increase per level increased from 1.8 to 2.0.
    - Immolation Panzer: Base HP reduced from 1250 to 1100.
    - Relatively Fat Immolation Panzer: Initial strength reduced from 100 to 80.
    - Relatively Fat Immolation Panzer's Inferno Blast: Blast damage reduced from 200 to 180.
    - Alchemist's Healing Spary: Level 4 healing per wave reduced from 85 to 75.
    - Beastmaster's Stampede
        - Beasts per second reduced from 2/5/8 to 2/4/6.
        - Damage per beast reduced from 60/85/110 to 60/80/100.
        - Cooldown increased from 180/150/120s to 180/160/140s.
    - The Elder's Weixiao Work: Attribute bonus per unit kill increased from 0.025/0.05/0.075/0.1 to 0.05/0.1/0.15/0.2. The hero kill multiplier reduced from 10 to 5. [ *Note:* The hero kill attribute bonus is still 0.25/0.5/0.75/1 *--end note* ]

- Chaotic troops
    - Relatively Fat Naga Siren now drops Glyph of Enhanced Fortification on death.
        - Item Glyph of Enhanced Fortification: Gives your team 5s boost on fortification duration on picking up.
    - Immolation Panzer now has a chance to drop Panzer Parts on death.
        - Item Panzer Parts: Increases 8 strength and 14 attack damage for the carrier.
    - New troops on wave 5: Hero Relatively Fat Shadow Fiend accompanied by Shadow Fiends. Killing the hero grants the heroes of the killing player with 2 skill points (or 700G and 700L for the player for each skill point not applicable). The Relatively Fat Shadow Fiend will drop Glyph of Invisibility on death.
        - Relatively Fat Shadow Fiend: Permanently invisible hero, has slow poison ability.
        - Shadow Fiend: Permanently invisible creature.
        - Item Glyph of Invisibility: Acquiring the item will enable the player to use Glyph of Invisibility via `-i` command, which makes all non-working buildings of the player becoming invisible for a period of time.

- AI
    - Now AI players will be able to cast Fortification, Defense Frenzy and Glyph of Invisibility on their structures in certain conditions.
    - Slight adjustment of AI base defense decision.

- Bug fixes
    - Fixed Goblin Rubber Duck Store not reacting to item selling/pawning events.
    - Fixed Defense Frenzy creating a peasant at the center of the map.
    - Fixed Fortification and Defense Frenzy ready information not correctly displayed.

- Miscellaneous
    - Slight improvement of Goblin Rubber Duck Store menu display.

# 2.99q

- Balancing
    - Human upgrade Improved Spotting (Level 1): Sight range bonus reduced from 800 to 700. Attack speed bonus increased from 20% to 25%. Now the Magic Sentry ability range will match this upgrade.
    - Human upgrade Enhanced Spotting (Level 2): Attack range bonus increased from 900 to 1000. Attack speed bonus increased from 40% to 50%. Now the Magic Sentry ability range will match this upgrade.
    - Night Elf upgrade Tree Essence Stronghold (Level 2): Increased restore potency decreased from 40% to 30%.
    - Mountain King's Devotion Aura: Level 4 armor boost increased from 6 to 6.5.
    - Tauren Chieftain's War Stomp: Level 4 damage increased from 100 to 120.
    - Lich's Death And Decay: Cooldown increased from 150/120/90s to 150/130/110s, mana cost increased from 250 to 250/275/300.
    - Keeper of the Grove's Tranquility: Level 2 healing amount increased from 55 to 65.
    - Relatively Fat Immolation Panzer's Inferno Blast: Projectile speed increased from 360 to 400.
    - Item Missile: Launch Missile cooldown reduced from 10s to 5s, mana cost reduced from 40 to 30.
    - Item Missile Vault: Launch Missile cooldown reduced from 120s to 110s.

- Goblin Rubber Duck Store
    - Now there are 2 rubber duck stores in the field.
    - Movement speed of the store increased from 460 to 470, and the stores will change their destinations more frequently.
    - Remade call handling processes. Now the stores may answer to calls simultaneously from multiple players.

# 2.99p

- Balancing
    - Relatively Fat Naga Siren's Devotion Aura: Armor boost increased from 12 to 20.
    - Relatively Fat Naga Siren's Parasite: Cooldown reduced from 2.5s to 2s.
    - The Elder's Xuming cooldown reduced from 120/110/100s to 100s.
    - Human upgrade Enhanced Spotting (Level 2): Gold cost increased from 200 to 300, lumber cost increased from 150 to 250.
    - Human upgrade Enhanced Spotting (Level 2): Sight range and attack range further increased by 200.
    - Orc upgrade Rupture focus (Level 2): Gold cost increased from 200 to 300, lumber cost increased from 150 to 250.
    - True Art (Orc base defense): Slow duration increased from 0.5s to 0.8s.
    - Night Elf upgrade Tree Essence Stronghold (Level 2): Gold cost increased from 200 to 300, lumber cost increased from 150 to 250.
    - Night Elf upgrade Tree Essence Stronghold (Level 2): Increased restore potency increased from 20% to 40%.
    - Undead upgrade Chaotic Rift (Level 2): Gold cost increased from 200 to 300, lumber cost increased from 150 to 250.
    - Undead upgrade Chaotic Rift (Level 2): Mini Frost Wyrm base movement speed reduced from 420 to 400, and base HP reduced from 350 to 250.

- Miscellaneous
    - Slight display improvement for Goblin Rubber Duck Store.
    - True Art (Orc base defense) is refactored.

# 2.99o

- Items
    - Missile
        - Launch mana cost reduced from 50 to 40.
        - Mana pool increase increased from 100 to 130.
    - Missile Vault
        - Full Salvo cooldown increased from 80s to 120s.
        - Mana pool increase increased from 180 to 260.

- Balancing
    - Relatively Fat Phoenix egg morphing time increased from 15s to 25s.
    - Relatively Fat Phoenix base attack reduced from 42 - 70 to 42 - 60.
    - Relatively Fat Phoenix passive AOE DPS reduced from 12 to 10.
    - Remade Overgrowth (Night Elf base defense):
        - Now both air and ground units will be ensnared and doomed.
        - Doom time: 12s
        - Ensnare time: 25s

- Slight modification on Goblin Rubber Duck Store.

# 2.99n

- Added a Goblin Rubber Duck Store that lives in the rivers
    - Currently it sells one item: Missile
        - Item: Missile (600G)
            - Increase Agility by 7
            - Increase Max Mana by 100
            - Ability: launch a missile globally to deal small damage to a small area. (Mana cost: 50, Cooldown: 10s)
    - Call `114514` in game to contact the store!
    - There might be more surprise if you tip the store a lot!

- New Item: Missile Vault
    - Increases agility, attack speed and maximum mana.
    - Has the ability of launching full salvo of missiles to strike the enemies.
    - Model credits: "Mass Dispel Area" by stan0033 @Hive, "Rocket Rain" by ILH @Hive.

- Changes
    - Slight modification on the terrain to make the rivers connected for water transports.

- Balancing
    - The Night Elf base ult Overgrowth ground unit entangle time increased from 8s to 11s.
    - The Night Elf base ult Overgrowth air unit ensnare time increased from 16s to 30s.
    - Night Elf upgrade Tree Structure Stronghold (Level 1) attack speed increase increased from 110% to 120%.
    - Night Elf upgrade Tree Essence Stronghold (Level 2) will only activate when accumulated damage on an ancient reaches 50, but the restoring potency is increased by 20%.

# 2.99m

- Changes
    - Changed Night Elf fortification effect to "Power Infusion" by Shyster @Hive.
    - Added a "Scanner Sweep" effect by Shyster @Hive to The Elder when entering the extended life (Xuming).

- Fixes
    - Fixed Airship Store not belonging to the neutral passive player.

- Credits
    - A "Goblin Rubber Duck" model is used in this version, thanks to MiniMage, Pvt.Toma and Red @Hive.

# 2.99l

- Remade Xuming for The Elder
    - Now Xuming will extract in total 60 seconds from a unit and kill it when the extraction finishes. The time extracted will keep The Elder from dying when taking more damage than current HP. However, if this time runs out, The Elder dies.
    - Extracts 1s from the unit every 3/2/1 seconds.
    - Cooldown: 120/110/100 seconds.

- Balancing
    - Warden's Blink distance scaled from 1000/1075/1150/3225 to 1000/1200/1400/1600.
    - Warden's Blink cooldown at level 4 reduced from 4s to 1s.

# 2.99i

- Minor fixes.
