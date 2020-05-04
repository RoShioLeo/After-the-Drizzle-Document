# 竹匾（Bamboo Tray）

> 竹匾内各模式配方请使用JEI模组查询！

**竹匾（Bamboo Tray）**
是一个有多种模式用于加工的方块。

![竹匾](../.gitbook/assets/blocks-items/bamboo_tray.png)

## 合成

![竹子 * 4 + 竹板 * 1 → 竹匾 * 1](../.gitbook/assets/recipes/bamboo_tray_recipe.png)

## 交互

竹匾的交互以右键为主，GUI为辅。

手持物品右击时，若该物品在该模式下能够被加工则会被放入竹匾中。

右击时，若竹匾内有物品且已加工完成，则会被取出；若仍在加工则不会。

右键双击，则会强制取出竹匾内的物品。

潜行时，空手右键则会打开GUI，查看详细信息。

## 用途

竹匾总共有五种模式可切换，分别为 **室外模式（Outdoor Mode）**、 **室内模式（Indoor Mode）**、 **烘焙模式（Bake Mode）**、 **加工模式（Process Mode）** 和**淋雨模式（In-rain Mode）**。

### ![](../.gitbook/assets/others/outdoor_mode.png) 室外模式

将竹匾放在阳光可直射到的地方即可切换到室外模式，优先级低于烘焙模式、加工模式和淋雨模式。

干燥时间由该区域的湿度所决定，晚上仍可进行干燥，雨天暂停。

### ![](../.gitbook/assets/others/indoor_mode.png) 室内模式

将竹匾放在可遮住阳光的方块下方即可切换到室内模式，优先级低于烘焙模式、加工模式和淋雨模式。

发酵时间由该区域的湿度所决定。

### ![](../.gitbook/assets/others/bake_mode.png) 烘焙模式

将竹匾放在点燃的炉灶上方即可切换到烘焙模式。

### ![](../.gitbook/assets/others/process_mode.png) 加工模式（暂时无用）

将竹匾放在木架上方即可切换到加工模式。

放入物品后，手持对应的物品进行右键操作即可加工。

### ![](../.gitbook/assets/others/in-rain_mode.png) 淋雨模式

将竹匾放在雨中即可切换到淋雨模式，竹匾内的物品会被打湿。

## 自动化竹匾

将竹匾放置在石制[弹射板](blocks-items/catapult-board.md)上，可装备成自动化竹匾。

在附近有红石信号激活的情况下， 当竹匾内物品完成一次加工时，会将竹匾内的物品朝弹射板方向弹出一格。

可以利用这个特点，在该方向放置漏斗进行收集。