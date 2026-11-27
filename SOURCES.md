# 设计参考与许可

核对日期 2026-11-27。链接固定到查阅的 GitHub 提交。千问妙笔 2.0 延续 [V1.3.0 源码](https://github.com/qcdwl/qwen-miaobi/tree/5a63bb6667bc23a2ea51cf4f03525ff0f9f0a6d1)，以下仓库是方法研究对象。规则、测试素材、模板和新增示例由本项目独立撰写。发布包没有上游代码、原文、语料或运行依赖。

| 项目 | 研读范围 | 在千问妙笔里的设计 |
| --- | --- | --- |
| human-writing | [入口](https://github.com/KKKKhazix/human-writing/blob/288297b6c2d9b6df23e0ceb64888443f15cfbcc3/human-writing/SKILL.md) · [参考目录](https://github.com/KKKKhazix/human-writing/tree/288297b6c2d9b6df23e0ceb64888443f15cfbcc3/human-writing/references) | 先确定叙述者靠什么知道，再用读者的问题推进。分开起稿和语感复核，按任务保留汉语节奏。 |
| Humanizer-zh | [模式与审稿](https://github.com/op7418/Humanizer-zh/blob/f4518a8eab97b8bfebc66a89d34320a89bef6930/SKILL.md) · [验收夹具](https://github.com/op7418/Humanizer-zh/tree/f4518a8eab97b8bfebc66a89d34320a89bef6930/tests) | 把模板化表达当成审阅线索，按上下文修整。回对原文的事实、确定程度、来源和编辑范围。 |
| writing-dna-skill | [语料分析](https://github.com/larashero3-dotcom/writing-dna-skill/blob/1335568bfd1141fc8447caaa812e6119e2d2fbbf/SKILL.md) · [流程参考](https://github.com/larashero3-dotcom/writing-dna-skill/tree/1335568bfd1141fc8447caaa812e6119e2d2fbbf/references) · [档案结构](https://github.com/larashero3-dotcom/writing-dna-skill/tree/1335568bfd1141fc8447caaa812e6119e2d2fbbf/templates/author-corpus) | 从授权样文观察表达、结构和取材。用原创的单文件档案记录依据和适用范围，后续更新先确认。 |
| khazix-writer | [入口](https://github.com/KKKKhazix/khazix-skills/blob/76fc0f8e8245b40a809d8eed89b27f04cbcf81bb/khazix-writer/SKILL.md) · [选题、质检与例文](https://github.com/KKKKhazix/khazix-skills/tree/76fc0f8e8245b40a809d8eed89b27f04cbcf81bb/khazix-writer/references) | 用读者问题、素材和时点判断选题。用可信细节推动文章，短稿按实际内容取舍。 |

查到的三份 MIT 授权如下。

- human-writing，MIT，Human Writing Skill contributors。[仓库许可证](https://github.com/KKKKhazix/human-writing/blob/288297b6c2d9b6df23e0ceb64888443f15cfbcc3/LICENSE) · [技能目录许可证](https://github.com/KKKKhazix/human-writing/blob/288297b6c2d9b6df23e0ceb64888443f15cfbcc3/human-writing/LICENSE)
- Humanizer-zh，MIT，歸藏。[许可证](https://github.com/op7418/Humanizer-zh/blob/f4518a8eab97b8bfebc66a89d34320a89bef6930/LICENSE)
- khazix-skills 的 khazix-writer，仓库根目录 MIT，数字生命卡兹克。[许可证](https://github.com/KKKKhazix/khazix-skills/blob/76fc0f8e8245b40a809d8eed89b27f04cbcf81bb/LICENSE)

writing-dna-skill 使用 **PolyForm Noncommercial 1.0.0**，许可覆盖其规定的非商业用途，分发上游代码或其许可下的改作时还须遵循分发与通知条款。当前交付只参考公开的高层做法。[许可证](https://github.com/larashero3-dotcom/writing-dna-skill/blob/1335568bfd1141fc8447caaa812e6119e2d2fbbf/LICENSE) · [NOTICE](https://github.com/larashero3-dotcom/writing-dna-skill/blob/1335568bfd1141fc8447caaa812e6119e2d2fbbf/NOTICE) · [使用边界](https://github.com/larashero3-dotcom/writing-dna-skill/blob/1335568bfd1141fc8447caaa812e6119e2d2fbbf/docs/usage-boundaries.md)

MIT 资源的副本或实质性部分按对应原文保留版权与许可通知。千问妙笔自身的发布许可状态独立说明。 [项目许可状态](LICENSE)

## V2.1.0 写作方法参考

本次研读固定到下列 Git 提交。示例、技能说明、流程及测试为本项目独立撰写，发布包未引入这些项目的代码、段落、模板或运行依赖。

| 项目 | 研读重点 | 许可依据 |
| --- | --- | --- |
| OpenAI Skills 的 Prompting Guide | 从可观察的成稿结果出发，给事实设证据边界，材料够用就停止搜索，让格式服务理解。[指南](https://github.com/openai/skills/blob/49f948faa9258a0c61caceaf225e179651397431/skills/.system/openai-docs/references/prompting-guide.md) | Apache-2.0。[技能目录许可证](https://github.com/openai/skills/blob/49f948faa9258a0c61caceaf225e179651397431/skills/.system/openai-docs/LICENSE.txt) |
| perfectly-replicate-writing-skills | 多维观察和样文交叉验证。千问妙笔将一致性写成有条件的做法，保留反例与证据范围。[入口](https://github.com/zrh091110225/perfectly-replicate-writing-skills/blob/4cb64fd5420255114baa2af223d154461a4098df/SKILL.md) · [分析维度](https://github.com/zrh091110225/perfectly-replicate-writing-skills/blob/4cb64fd5420255114baa2af223d154461a4098df/references/7-dimensions-framework.md) | MIT。[许可证](https://github.com/zrh091110225/perfectly-replicate-writing-skills/blob/4cb64fd5420255114baa2af223d154461a4098df/LICENSE) |
| writing-craft-skill | 把选词、句段节奏、读者需要、事实依据和成稿修改作为正向功课。[入口](https://github.com/vidanov/writing-craft-skill/blob/8ad5eeaca7901f5863055680123c314a1d806c3c/SKILL.md) · [文风校准](https://github.com/vidanov/writing-craft-skill/blob/8ad5eeaca7901f5863055680123c314a1d806c3c/references/voice-calibration-guide.md) | MIT。[许可证](https://github.com/vidanov/writing-craft-skill/blob/8ad5eeaca7901f5863055680123c314a1d806c3c/LICENSE) |
| simonwong/writing-skills | 将通用写法与体裁差异分开，按任务选择适用规则，用改写和作者确认校准。[文章写作](https://github.com/simonwong/writing-skills/blob/f7ce6493acb29363edbf9bcd4e6b05de1d5030ec/skills/write-article/SKILL.md) · [文风学习](https://github.com/simonwong/writing-skills/blob/f7ce6493acb29363edbf9bcd4e6b05de1d5030ec/skills/writing-style-learn/SKILL.md) · [档案研究](https://github.com/simonwong/writing-skills/blob/f7ce6493acb29363edbf9bcd4e6b05de1d5030ec/docs/research/writing-style-extraction.md) | README 与相关技能声明 MIT，所查提交未见单独的根目录许可文件。[README 许可声明](https://github.com/simonwong/writing-skills/blob/f7ce6493acb29363edbf9bcd4e6b05de1d5030ec/README.md) |

参考项目的授权各自适用。千问妙笔自身的许可状态见 [LICENSE](LICENSE)。
