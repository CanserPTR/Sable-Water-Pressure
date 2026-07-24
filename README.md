Water Pressure
Adds a realistic depth-based water pressure system to survival diving. The deeper you go without proper gear, the more the ocean punishes you — slowness, weakness, and eventually real damage. Create's diving armor isn't just cosmetic anymore: it's the only thing standing between you and the crushing depths.

How it works
Depth is measured from sea level (Y=62) downward, split into pressure zones:

Zone	Depth below sea level	Effect
0	0–15 blocks	Safe
1	15–25 blocks	Slowness + Weakness
2	25–35 blocks	Slowness/Weakness + light damage every 2s
3	35–50 blocks	Stronger effects (amplified) + moderate damage
4	50+ blocks	Severe damage every 2s
Effects and damage refresh periodically while submerged, and reset the moment you surface.

Diving armor matters
Wearing a full matching diving set shifts your effective pressure zone down, letting you dive deeper safely:

Copper diving set (helmet/boots from Create, chest/legs from Create: Ironworks) — shifts pressure by 1 zone
Netherite diving set (Create netherite diving helmet/boots + vanilla netherite chestplate/leggings) — shifts pressure by 2 zones
Partial sets give no protection — it's all four pieces or nothing. Deep pressure also chips away at your armor's durability piece by piece, synced with the damage you take — dive too deep for too long and your gear will eventually give out.

Submarine immunity (Create Deep Seas + Sable)
Building and riding a submarine with Create Deep Seas. Its vessels are physicalized through Sable, and this mod hooks directly into Sable's sub-level API: while you're sealed inside the hull, water pressure doesn't apply at all — no matter how deep the sub goes, but depends of whether the interior has any water in it. Fully automatic, no configuration needed.

Requirements
Create (required — supplies the diving armor items this mod checks for)
Create: Ironworks (required — copper diving chestplate/leggings)
Sable (optional — enables submarine pressure immunity; also what Create Deep Seas itself runs on)
Configuration
All numbers (depth zone boundaries, damage per zone, effect duration/refresh, armor wear rate) are constants in WaterPressureHandler — straightforward to retune for your pack's balance.
