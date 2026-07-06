# 🐵 小悟空配图 Skill（xiaowukong-illustrations）

基于七龙珠幼年孙悟空形象的中文正文配图提示词生成工具。小悟空不是吉祥物，而是正在认真参与系统运转的热血工作者。

## 角色形象

| 特征 | 描述 |
|------|------|
| 发型 | 标志性黑色刺猬头，发丝尖锐向上炸开 |
| 上身 | 白色无袖背心 |
| 下身 | 宽松蓝色灯笼裤，浅蓝色布带系腰 |
| 手腕 | 红色护腕 |
| 脚部 | 深蓝色平底鞋 |
| 道具 | 肩挎如意棒（红色长棍） |
| 头身比 | Q版 3~4 头身 |

## 仓库结构

```
xiaowukong-illustrations/
├── SKILL.md                          # Skill 主文件（触发条件 + 工作流）
├── assets/
│   └── xiaowukong-three-view.png     # 小悟空三视图（形象基准）
├── references/
│   ├── xiaowukong-ip.md              # IP 定义（外形/性格/动作池/禁止项）
│   ├── style-dna.md                  # 风格 DNA（线条/配色/留白规则）
│   ├── composition-patterns.md       # 构图模式与原创隐喻生成法
│   ├── prompt-template.md            # 英文生图提示词模板
│   └── qa-checklist.md              # QA 检查清单
└── examples/
    └── prompts.md                    # 示例 prompt
```

## 动作池

**继承自小黑**（通用操作类）：拉、扛、塞、捞、压、称、缝、剪、拧、守、推、接、拆、标记、回收

**悟空专属**（热血战斗类）：劈、踢、飞、举、修炼、变身、挥棒、冲击

## 致谢

基于 [ian-xiaohei-illustrations](https://github.com/helloianneo/ian-xiaohei-illustrations) 改编，将角色 IP 从小黑替换为七龙珠小悟空。
