# zcode-skills

个人 ZCode 技能库。

## 技能列表

| 技能 | 说明 |
|---|---|
| [first-principles-analysis](./first-principles-analysis/) | 第一性原理内容分析器：先筛后拆 → 贴标净化 → 三重验证 → 迁移为行动项。总结/分析视频、文章、访谈时触发，主产品是判断而非复述。 |

## 安装

复制技能目录到用户技能目录（任选其一）：

```bash
git clone https://github.com/XoXoWu/zcode-skills.git

# 跨工具标准位置（推荐）
mkdir -p ~/.agents/skills
cp -r zcode-skills/first-principles-analysis ~/.agents/skills/

# 或 ZCode 用户目录
mkdir -p ~/.zcode/skills
cp -r zcode-skills/first-principles-analysis ~/.zcode/skills/
```

安装后编辑 `SKILL.md` 文末的"用户档案"一节，填入自己的目标与决策域——迁移（Transfer）环节的质量取决于它。

## 使用

直接发内容链接或文本即可，按需指定深度：

- `快筛这篇文章 <链接>` — 30秒判断值不值得消费
- `分析这个视频 <链接>` — 标准深度（还原 + 净化）
- `深拆这篇访谈 <链接>` — 全流程（含验证、迁移、校准）

## 设计原则

- 内容 = 信号 + 修辞 + 噪音 + 意图，分析的原子功能是**先筛 → 提纯 → 验证 → 迁移**。
- 注意力是最稀缺资源："可丢弃"是合法且常见的结论。
- 本技能自身也是一个框架：SKILL.md 文末的"已证伪记录"用于接受现实检验并自我修正。
