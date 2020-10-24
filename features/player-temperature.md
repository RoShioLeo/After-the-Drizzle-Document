# Apparent Temperature System

> This chapter is only valid for version 1.0.7-beta or later.

**Apparent Temperature System** is a mechanic added by the *After the Drizzle* Mod,

which is based on the Environmental System, and influences your survival gameplay.

## What is that

**Player's Apparent Temperature**, or **Player-Temp** in short, 

is divided into 6 levels which is the same as the [Temperature System](humid.md), and is updated per 2.5 seconds normally, or per 7.5 seconds in an extreme environment.

**Environmental Apparent Temperature**, or **Env-Temp** in short, 

is divided into 6 levels which is the same as the [Temperature System](humid.md), 

and is calculated from the environmental temperature and humid.

![Icons of all levels of Player-Temp](../.gitbook/assets/descriptions/temperature.png)

## Description

- **Player-Temp changes**：

  If you are in a position where Env-Temp is higher than yout current Player-Temp, your Player-Temp will rise, and vise versa.

- **Cold/Heat Resistance**:
  
  Equipped with related items, you can survive in tougher environments (biomes).

  Each point of Cold/Heat Resistance gives you the ability to survive in 1 lower/higher temperature level.
  
  a player without armor will gain 1 point of Heat Resistance.

- **Fluid Temperature**:

  If you are in some fluid, Env-Temp will be ignored, but use the temperature of the fluid instead.

- **Light**:

  The **lowest** Env-Temp level of the position you are standing is related to the light level of that position,
  
  as the table below shows:

  | Light Level Range | Lowest Env-Temp |
  |---------------|------------------|
  |         15         |          Hot         |
  |     11 ~ 14    |           Warm        |
  |      8 ~ 10     |           Cool         |
  
  in a hot place, if you move to a shadowed position, your Player-Temp will become lower.

- **Underground Env-Temp**：

  Only when you are in the Overworld will this feature be enabled.
  
  If you are at a position, where Y coordinate is lower than 45 and you cannot see the sky,
  
  Your Env-Temp will not be lower than Cool. But Thermometers will still show the Env-Temp as if this rule did not exist.

- **Daily highest and lowest temperatures**:

  Daily lowest temperature comes at 3:00 (21000 ticks), while the highest temperature comes at 14:00 (8000 ticks)

- **Daily temperature fluctuation**:

  The magnitude of temperature fluctuations in an area is decided by [Humid](humid.md) of the area.
  
  The greater the humidity, the smaller the magnitude is, and vice versa.
  
  If it is rain, daily magnitude of temperature fluctuations will decrease for 50%.

  If you are in the rain, the Humid level will +1 when calculating your Env-Temp.
  
  A dimension where is no daylight cycle, such as the Nether and the End, will not see the temperature fluctuation.

- Too high or too low Player-Temp will bring you debuffs.

  | Player-Temp | Debuff |
  |----------|-----------|
  |    Freezing   | Hunger Ⅱ, Slowness Ⅱ, and get 4-point damaged per 4 second |
  |    Cold   | Hunger Ⅰ, Slowness Ⅰ |
  |    Hot   | Hunger Ⅰ, Slowness Ⅰ |
  |    Heat   | Hunger Ⅱ, Slowness Ⅱ, and get 4-point damaged per 5 second |

  Fire Resistance potion effect can protect you from Hot and Heat debuffs.

  Damage dealt by Freezing and Heat temperature ignores armor.