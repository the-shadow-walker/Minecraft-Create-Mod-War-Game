# The Great Industrial War: Server Rulebook

---
## TL;DR
Three teams fight over an industrial map. You mine and haul debris back to your factory to process into scrap currency, which you spend at the market on materials. Weekends open up war windows where you fight to capture neutral extractors across the map for more income, and during specific hours you can raid and blow up enemy factories for a cut of their weekly output. Upgrading your extractors and factory requires Create mod power and Netherite, so building good mechanical infrastructure matters as much as fighting. No single team can snowball — the more extractors you own the less efficient they get, and destroyed factories respawn the next Friday with upgrades intact. Season ends when one team controls everything or the last surviving team surrenders.
--

## 1. Team Setup and Territory

Three teams compete: **Blue**, **Red**, and **Green**, each starting in a separate biome.

Each team's home territory contains:
- 2 home extractor slots (pre-defined build zones)
- 1 Factory Zone — the only location where a furnace can be built and scrap processed

Home territory is always safe during Peace Time. It cannot be permanently captured, but the factory and extractors can be destroyed during Total War windows.

**The Merge Rule:** If a team loses all territory and their factory is destroyed, they must merge with the weakest surviving team to keep the war going. Once one empire achieves total map control, the season ends.

---

## 2. The Scrap Economy

### Overview

There are three equal-value scrap currencies, each tied to a biome. No single scrap is superior — all three are required for full industrial progression.

| Scrap | Biome | Buys |
|---|---|---|
| Chalkos Scrap | Desert | Andesite Alloy, Copper, basic building materials |
| Chrys Scrap | Jungle | Zinc, Gold|
| Nether Scrap | Plains | Iron, Redstone, Diamonds (rare/expensive) |

### Ingot Upgrades (8x Purchasing Power)

Scraps can be refined into ingots for dramatically higher purchasing power. Each upgrade requires a *different* scrap economy's material — you cannot upgrade using your own resources.

- **4 Chalkos Scrap + 4 Zinc Ingots → Chalkos Ingot** (8× Chalkos purchasing power)
- **4 Chrys Scrap + 4 Copper Ingots → Chrys Ingot** (8× Chrys purchasing power)
- **4 Nether Scrap + 4 Gold Ingots → Nether Ingot** (8× Nether purchasing power)

This forces economic interdependence — teams must trade, fight, or raid to access upgrade materials from other biomes.

### Market Stability

- Prices increase slightly as demand rises (+5% per step), preventing runaway inflation
- No resource depletion — availability stays stable across the season
- Diamonds are available via Nether Scrap but are intentionally expensive and low-quantity

---

## 3. Ore Generation

- All ores generate at approximately **25–40% of vanilla rates**
- Mining supports early-game startup, but large-scale industry depends on the scrap economy
- Key Create bottleneck materials (Andesite, Zinc, Copper) are more limited and biome-dependent

Mining is not the path to dominance — it is the path to getting started.

---

## 4. Extraction

### Base Rate
- Each extractor produces **1 scrap per hour** by default
- Requires manual mechanical input (Create-style cranking) to operate at base level

### Upgrades

Extractors can be upgraded two ways, with a **combined maximum of 8× base output**.

**Mechanical Upgrades (Create Power):**
- Increasing RPM and torque improves output
- Capped at **4× base speed** via mechanical systems alone

**Netherite Upgrades:**
- Each Netherite ingot inserted adds **+10% speed**, up to 10 ingots total (+100%)
- Combined multiplier from Netherite: **2×**
- Netherite upgrades stack with mechanical upgrades

**Maximum output per extractor: 8 scrap/hour** (4× mechanical × 2× Netherite)

### Carry Limit

Players can only carry **1 scrap at a time**. This is intentional — it forces teams to build transport infrastructure: trains, convoys, and automated logistics using Create.

### Yield Decay

To prevent hoarding, scrap output decreases by **5% for every additional scrap processed in a given cycle**. The 10th scrap processed yields less material than the 1st. Upgrading furnaces and maintaining throughput offsets this.

---

## 5. Processing (The Factory)

- Scrap is processed **only at the team's home Factory Zone**
- Base processing rate: **1 scrap every 2 hours**
- Processing is fully AFK once loaded

### Automation Rules
- Auto-loaders can be constructed, but **only 1 scrap can be loaded at a time**
- This enforces factory scaling through engineering, not bulk input

### Factory Upgrades
- Processing speed can be upgraded using Create mechanical power and Netherite ingots
- Scaling works the same as extractor upgrades
- **There is no cap on factory upgrade scaling** — high-end factories become major industrial centers

---

## 6. War Schedule

### Peace Time (All Other Hours)
- No extractor capturing
- No factory or furnace destruction
- Building, logistics, scouting, and transport are allowed

### War Start Deployment
At the beginning of each war window (Extraction War on Friday 6 PM, and each Total War window), **all online players receive a deployment screen** before the war begins. Players have **60 seconds** to select a spawn-in location from the following options:

- Their **team's Factory**
- Any **extractor currently owned by their team** (home extractors always available; neutral/enemy extractors not eligible)

Players who do not select within 60 seconds are automatically deployed to their team's Factory. Players who log in after the war has started spawn at their last known location as normal.

This system is enforced by the server — players are frozen and cannot move or take damage during the deployment window.

### Extraction War — Friday 6 PM to Sunday 10 PM
- All 15 neutral extractors are free to contest and capture
- Light combat and skirmishing are allowed
- Ownership finalizes at **Sunday 10 PM**

### Total War Windows (Factory Destruction Allowed)
Full offensive warfare — bombing factories, destroying furnaces, and major coordinated raids — is only permitted during:

- **Friday: 7:00 PM – 10:00 PM**
- **Saturday: 5:00 PM – 10:00 PM**
- **Sunday: 8:00 PM – 10:00 PM**

Outside these windows, factories and furnaces cannot be destroyed.

---

## 7. Extractor Capture

### How to Capture
1. Reach the extractor core (the heart of the rig)
2. Change the flag to your team's color
3. Hold the rig for **5 uninterrupted minutes** to lock ownership
4. Server announces: *"Extractor #X has been captured — Blue to Red"*

If an enemy enters the area during the hold, progress resets.

All combat — artillery, aircraft, and infantry — remains active during capture attempts.

### Capture Only Happens During War Time
There is no weekday capture window. Extractors can only change hands **Friday 6 PM through Sunday 10 PM**. Ownership finalizes at Sunday 10 PM.

---

## 8. Extractor Ownership Rules

- Once captured, an extractor is **locked for one week** before it can be contested again
- This lock applies only to a team's **first 5 captured extractors**
- Any extractors beyond 5 are always vulnerable during Extraction War hours
- Each team also starts with **2 permanent home extractors** that cannot be captured (but can be destroyed during Total War)

---

## 9. The 15 Neutral Extractors

Fifteen extraction points are distributed across the map by biome:

- **Desert (5):** Chalkos Scrap nodes
- **Jungle (5):** Chrys Scrap nodes
- **Plains (5):** Nether Scrap nodes

These are always known locations — all teams can see where they are. Conflict over them is expected and intentional.

---

## 10. Factory Destruction and Respawn

If a furnace is destroyed during a Total War window:

- It **respawns the following Friday at 6 PM** at its original factory location
- All **Netherite upgrades are preserved** on respawn (encouraging long-term investment)

### Loot Rewards Based on Destruction Method

**Hand Raid (player breaks it manually):**
- Attacker receives **100%** of the defending team's production from the previous week
- Defender receives **0%** that week

**Bombing or Artillery:**
- Attacker receives **50%** of the defending team's previous week's production
- Defender receives production at **50% output** for the following week

Using the previous week's output (not the current week) prevents sandbagging — teams cannot stop production to reduce the enemy's reward.

---

## 11. Thermal Cooling and Ventilation (Anti-Turtle)

### Ventilation Requirement
The furnace requires a **5×5 column of open sky** directly above it.

If this area is enclosed:
- Server alert fires: *"ALERT: [Team]'s furnace does not have proper ventilation. Cooldown in 5 minutes."*
- If not cleared within 5 minutes, furnace efficiency drops to **40% for 5 real days**

### Depth and Armor Rule
Up to **20 blocks of solid material** above the 5×5 furnace column are permitted (for bunker roofing).

- Beyond 20 blocks: **5% efficiency penalty per additional block**
- Any change to depth or armor triggers a **5-day normalization period** before the new efficiency level takes effect

---

## 12. Surrender System

A team may surrender **before** their factory is destroyed.

**Effects for the following 2 weeks:**
- Winning team receives: **+60% of the surrendering team's previous week output**
- Surrendering team operates at: **40% efficiency for 3 days**, then returns to normal

**Anti-Sandbagging Rule:**
All surrender calculations use the **previous week's output** — not the current week — to prevent teams from throttling production before surrendering.

**Post-Surrender Restrictions:**
Surrendered teams for the remainder of that war period cannot:
- Leave their home territory
- Use aircraft, cannons, or vehicles
- Attack other teams

They can still log on, build, and prepare for the next season.

---

## 13. Balance Systems

### Diminishing Returns on Multiple Extractors
The more extractors a team controls, the less efficient each one becomes:

- 1 extractor: 100% output
- 2 extractors: 90% each
- 3 extractors: 75% each
- 4+ extractors: 60% each

This prevents one team from achieving runaway economic dominance through pure territorial control.

### Logistics Bottleneck
Even a team that captures everything still needs:
- Create power (RPM and stress capacity) to run machines
- Processing infrastructure to convert scrap
- Supply lines to transport materials

Territory alone does not equal power. Engineering does.

### Rebuild Time
Destroyed rigs and factories take time to rebuild. Recapture is not instant — this prevents flip-farming and keeps front lines meaningful.

### Early Game Starter Resources
Small, one-time loot caches exist at the start of the map. These ensure all teams can gear up enough to begin building factories and engaging in early conflict, regardless of starting position.

---

## 14. Design Philosophy

This server is not a PvP server, a faction server, or a conquest game.

It is a **living industrial war simulation** where:

- Territory provides raw resources
- Create factories process and scale them
- Logistics and supply lines determine military reach
- Engineering skill matters as much as combat skill
- Wars are won over time, not in a single raid

The goal is long, back-and-forth warfare where no team dominates permanently, every player has a role, and strategy beats brute force.
