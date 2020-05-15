# Environment System

**Environment System** is a Vanilla-Minecraft-based mechanic, which influences many aspects of your survival gameplay.

![Thermometer, Rain Gauge ,and Hygrometer](../.gitbook/assets/blocks-items/environment.png)

## Temperature

Based on Vanilla Minecraft's biome "temperature" data, *After the Drizzle* Mod devided biomes into 6 temperature levels.

You may refer to Minecraft Wiki to find out the biome temperature data.

| No. | Temperature level | Temperature Range |
|------|------|------|
| 1 | Freezing | (-∞, 0.15F] |
| 2 | Cold | (0.15F, 0.3F] |
| 3 | Cool | (0.3F, 0.5F] |
| 4 | Warm | (0.5F, 0.75F] |
| 5 | Hot | (0.75F, 1.5F] |
| 6 | Heat | (1.5F, +∞) |

Each temperature level has a corresponding scale on the Thermometer.

But the Thermometer will give you the actual temperature, which varies from time to time,

instead of the default biome temperature.

## Rainfall

Based on Vanilla Minecraft's biome data, *After the Drizzle* Mod devided biomes into 5 rainfall levels.

You may refer to Minecraft Wiki to find out the biome data.

| No. | Rainfall Level | 范围 |
|----------|------|------|
| 1 | Rare | (-∞, 0.1F] |
| 2 | Scarce | (0.1F, 0.3F] |
| 3 | Moderate | (0.3F, 0.6F] |
| 4 | Adequate | (0.6F, 0.8F] |
| 5 | Abundant | (0.8F, +∞) |

Rain Gauge can roughly reflect the rainfall level of your position, but not precisely.

## Humid

Based on the temprature and rainfall level systems, *After the Drizzle* Mod devided biomes into 5 humid levels.

| No. | Humid Level |
|------|----------|
| 1 | Arid |
| 2 | Dry |
| 3 | Moderate |
| 4 | Moist |
| 5 | Humid |

**How Humid Levels devided**

For each biome, 

its Humid Level number = rainfall level number - floor(abs(rainfall level number - temperature level number) / 2).

abs() means to take the absolute value, floor() means to round down.

If you dislike calculating, just check the table below.

For "Rainfall and Temperature" column, the 2-digit number means：

The left digit means Rainfall Level number, the other digit means Temperature Level number.

| Humid Level | Rainfall and Temperature |
|------|------|
| Arid | 11，12，13，14，15，16，24，25，26 |
| Dry | 21，22，23，31，35，36 |
| Moderate | 32，33，34，41，42，46，51 |
| Moist | 43，44，45，52，53 |
| Humid | 54，55，56|

Most environmental mechanics is related to the Humid system.

## How to craft related tools

![Glass * 7 + Water Bucket * 1 → Thermometer * 1](../.gitbook/assets/recipes/thermometer_recipe.png)

![Glass * 6 + Water Bucket * 1 → Rain Gauge * 1](../.gitbook/assets/recipes/rain_gauge_recipe.png)

![Thermometer * 1 + Rain Gauge * 1 → Hygrometer * 1](../.gitbook/assets/recipes/hygrometer_recipe.png)
