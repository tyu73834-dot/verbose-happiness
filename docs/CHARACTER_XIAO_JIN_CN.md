# 萧烬：角色设定与 AI 视觉提示词

本文件用于让萧烬在不同镜头中保持统一的脸、服装、武器与气质。生成画面前应先固定一张“角色基准图”，后续画面都基于该图做参考。

## 角色核心

| 维度 | 设定 |
| --- | --- |
| 姓名 | 萧烬（Xiao Jin） |
| 年龄感 | 16--18 岁的少年感，不是儿童 |
| 身份 | 被逐出宗门的杂役弟子，体内封有天煞骨 |
| 性格 | 寡言、忍耐、警觉；逆境中有不服输的锋利感 |
| 标志 | 右手从手背延伸到手腕的暗红火焰骨纹 |
| 武器 | 未觉醒时为旧铁剑；觉醒后使用有裂纹、边缘泛暗红火光的长剑 |
| 色彩 | 主色炭黑、灰蓝；觉醒特效为深红和熔金，避免明亮霓虹色 |

## 外观规范

- 黑色长发，半束发，额前有自然碎发；发尾略凌乱。
- 深褐色眼睛，觉醒时瞳孔边缘呈熔金色。
- 清瘦但不孱弱，东方面孔，肤色自然小麦色。
- 初始服装是磨损的深灰杂役服，内衬灰蓝，腰带简单；没有华丽盔甲。
- 觉醒后保留旧衣，只有手臂骨纹、衣角灰烬和微弱红光变化，表现“力量突然降临”的反差。

## 角色基准图提示词

先生成正面半身或全身的角色基准图；不要直接生成战斗复杂场景。

```text
Character turnaround concept art of Xiao Jin, a 17-year-old East Asian male fantasy protagonist, lean athletic build, natural warm tan skin, sharp determined dark brown eyes, messy long black hair tied half-up with loose bangs, worn charcoal-gray martial sect disciple robe with muted blue-gray inner layers, simple rope belt, an old iron sword at his side, a subtle dark crimson flame-shaped bone mark across the back of his right hand and wrist, restrained expression, ancient eastern fantasy cultivation world, cinematic ink-wash and painterly animation style, full body, neutral misty mountain background, consistent character design, highly detailed fabric, vertical composition
```

## 觉醒镜头提示词

```text
Xiao Jin, the same 17-year-old East Asian male protagonist with messy half-tied black hair and worn charcoal-gray disciple robe, kneeling before a gigantic ancient black dragon skeleton inside a volcanic mountain chasm, blood falling from his hand onto the bone, dark crimson fire veins spreading over his right arm, molten gold light reflected in his eyes, ash swirling in the air, monumental eastern fantasy ruins, dramatic cinematic lighting, painterly animated series style, high contrast, vertical 9:16 composition
```

## 负面提示词

不同工具的写法略有不同，可作为负面提示词或人工检查表使用。

```text
child, western medieval armor, modern clothes, neon cyberpunk, extra fingers, deformed hands, duplicate person, inconsistent face, smiling expression, text, watermark, logo, low resolution, blurry
```

## 一致性检查

生成每个镜头前后，至少检查以下内容：

1. 发型是否仍是半束黑长发，脸部年龄感是否一致。
2. 服装是否仍是灰黑、灰蓝的旧杂役服。
3. 骨纹是否始终在右手与右手腕。
4. 火焰是否为深红和熔金，而非蓝紫色霓虹光。
5. 成片是否为竖屏构图，人物脸部位于适合短视频观看的安全区域。
