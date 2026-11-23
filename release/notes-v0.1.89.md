## Exvius Offline v0.1.89 (Beta) — Data r33

### Battles, Challenges & Exploration
- Fixed Challenge of the Brave and all multi-slot battle groups dropping 0 items (per-slot drop binding).
- Fixed Esper finishing blow and Item finishing blow mission tracking (action IDs 3/4 swap).
- Fixed awakened (+1/+2/+3) spells and abilities not counting for "Use" / "No-use" / "Finish-with" objectives (e.g., Fina's Curada+2 on Windy Heights West - Entrance).
- Fixed compound magic/ability mission objectives (`13:1,13:2`, `21:A,21:B`) and specific-unit LB finishes (`code 67`) when using awakened unit rarities.
- Fixed *A Musical Showdown* INT (`9001702`) boss spawn and map collisions, *Into the Abyss* (`9000001`) exploration prompts, battle groups, and harvest points, and converted 10 missing-map exploration stages into wave battles.
- Fixed 43+ unbeatable or broken-HP event/trial bosses, restored missing monster AI & GL bosses (Youkai Lantern, Abraxas), fixed Mermaid IDs, and restored Chamber of Crystals PRO colored magicite/megacite/supercite drops.
- Fixed Season 4 & event raid boss HP/scaling (`9Ahc8Vqn=1`), added Chamber of Supercite challenges & Esper Ore steals, and implemented Global Daily Fragment Challenge (`10440101`) settlement (1–3 fragments per unique deployed NV/NVA unit).
- Fixed Season 2 / `0.1.83` raid clear switches (`"New"` badge and difficulty unlock chains) and story cutscene switch sync (`mRPo5n2j`).

### Summons, Units, Shops & UI
- Overhauled summon banners: fixed step-up `draws` count (`0GgK6ytT`) across all 96+ step-ups, missing lap limits, step fragment/pearl bonuses, wrong preview units/rates, and Exchange Shop shortcut buttons across all archived coin/ticket shops.
- Added 15 new banners (DQXI S Heroes + Step-Up, FMA NV Wave 2, late-S4 JP/holiday NVs, WOFF) with 14 English-translated 640px banners, added 7 promo units to Standard Summon+, activated *The Unsent Fiend* Raid Summon (`71106`), and cleaned up 40 summon-only currencies from Fragment Shops.
- Fixed 19 GL-first trust passives, 15 broken ability awakening recipes (Hawkeye, SINoALICE, DQ Roto), and Trance Terra's *Magical Activation +2* unlocking *Chaos Wave Awakened*.
- Fixed Unit Reserve storage updates (`5ik69cuw`), Item World equipment favorite persistence (`q7NfU6FH`), Home Vision Card crash/echo handling, rank-up orb refresh, and missing FFX medal store schedules (`900218`/`900222`).
- Converted indexed master tables to plaintext for faster startup and cleaner patching; added 7 new permanent supporter companions (25 total).
