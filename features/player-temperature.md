# Apparent Temperature System

> Now this system is WIP, and it might can not work perfectly!

**Apparent Temperature System** is a mechanic added by the *After the Drizzle* Mod,

which is based on the Environmental System, and influences your survival gameplay.

## What is that

**Player's Apparent Temperature**, or **PAT** in short, 

is divided into 6 levels which is the same as the [Temperature System](humid.md), and is updated per 2.5 seconds.

**Environmental Apparent Temperature**, or **EAT** in short, 

is divided into 6 levels which is the same as the [Temperature System](humid.md), 

and is calculated from the environmental temperature and humid.

![Icons of all levels of PAT](../.gitbook/assets/descriptions/temperature.png)

## Description(For 0.1.20-Beta-1.14.4 version and newer)

> For older versions before 0.1.20-Beta-1.14.4, skip the contents below and go to the end.

- PAT changes：

  If you are in a position where EAT is higher than yout current PAT, your PAT will rise, and vise versa.

- Cold/Heat Resistance

  For 0.1.20-Beta and newer version, Cold/Heat Resistance is added into the game.
  
  equipped with related items, you can survive in tougher environments(biomes).

  Each point of Cold/Heat Resistance gives you the ability to survive in 1 lower/higher temperature level.

- Fluids:

  If you are in some fluid, EAT will be ignored, but use the temperature of the fluid instead.

- Light:

  The *lowest* EAT level of the position you are standing is related to the light level of that position,
  
  as the table below shows:

  | Light Level Range | Lowest EAT |
  |---------------|------------------|
  |         15         |          Hot         |
  |     11 ~ 14    |           Warm        |
  |      8 ~ 10     |           Cool         |

- Underground：

  Only when you are in the Overworld will this feature be enabled.
  
  If you are at a position, where Y coordinate is lower than 45 and you cannot see the sky,
  
  Your EAT will not be lower than Cool. But Thermometers will still show the EAT as if this rule did not exist.

- Daily highest and lowest temperatures

  Daily lowest temperature comes at 3:00(21000 ticks), while the highest temperature comes at 14:00(8000 ticks)

- Daily temperature fluctuation:

  The magnitude of temperature fluctuations in an area is decided by [Humid](humid.md) of that area.
  
  The greater the humidity, the smaller the magnitude is, and vice versa.
  
  If it is rain, daily magnitude of temperature fluctuations will decrease for 50%.

  If you are in the rain, the Humid level will +1 when calculating your EAT.
  
  A dimension where is no daylight cycle, such as the Nether and the End, will not see the temperature fluctuation.

- Too high or too low PAT will bring you debuffs.

  | PAT | Debuff |
  |----------|-----------|
  |    Freezing   | Hunger Ⅱ, Slowness Ⅱ, and get 4-point damaged per 4 second |
  |    Cold   | Hunger Ⅰ, Slowness Ⅰ |
  |    Hot   | Nausea, Slowness Ⅰ |
  |    Heat   | Nausea, Slowness Ⅰ, and get 4-point damaged per 5 second |

  Fire Resistance potion effect can protect you from Hot and Heat debuffs.

  Damage dealt by Freezing and Heat temperature ignores armor.

## Description for older version

> Descriptions below is for 0.1.17c-Alpha-1.14.4 or older versions. If no special instructions to some feature, either the feature is the same as the newer version, or the feature is not added into the game yet.

- Light:

  If your position's Block Light Level is higher than 8, your EAT will not be lower than Warm.

- Underground：

  ~~Only when you are in the Overworld will this feature be enabled.~~ This rule is enabled in any dimension.
  
  If you are at a position, where Y coordinate is lower than 45 and you cannot see the sky,
  
  Your EAT will not be lower than Cool. But Thermometers will still show the EAT as if this rule did not exist.
- Daily highest and lowest temperatures

  Daily lowest temperature comes at 6:00(0 tick), while the highest temperature comes at 14:00(8000 ticks).


- Too high or too low PAT will bring you debuffs.

  | PAT | Debuff |
  |----------|-----------|
  |    Freezing   | Hunger Ⅱ, Slowness Ⅱ, and get cold damage |
  |    Cold   | Hunger Ⅱ, Slowness Ⅱ |
  |    Hot   | Nausea, Slowness Ⅱ |
  |    Heat   | Nausea, Slowness Ⅱ, and get heatstroke damage |

Fire Resistance potion effect can protect you from Hot and Heat debuffs.
