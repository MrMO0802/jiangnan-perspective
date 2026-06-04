<div align="center">

# 江南 perspective.skill

> 「少年感不是把命运说得很重，而是一个很弱的人，仍然希望有一天被世界叫到名字。」

![Codex Skill](https://img.shields.io/badge/Codex-Skill-7c3aed)
![Writer Refined](https://img.shields.io/badge/Writer-Refined-2563eb)
![Darwin Reviewed](https://img.shields.io/badge/Darwin-Reviewed-16a34a)
![Style Baseline](https://img.shields.io/badge/Style-Baseline-0f766e)
![Copyright Safe](https://img.shields.io/badge/Copyright-Safe-111827)

**江南 perspective.skill 帮你用江南的公开创作视角，诊断长篇幻想、少年感、世界观、章节结构、人物声音和风格主基调。**

只输入一个故事、一幕场景、一段对白或一个 IP 判断问题，它会自动完成：<br>
**意义定位 -> 世界观校准 -> 章节重构 -> 人物声音诊断 -> 风格主基调落地 -> 微观节奏润色 -> 反仿写检查。**

[效果示例](#效果示例) · [安装](#安装) · [它蒸馏了什么](#它蒸馏了什么) · [安全边界](#安全边界) · [English](#english)

</div>

---

## 效果示例

```text
用户   > 我写了一场秘密学院面试戏，但现在很像说明书。请用江南式小说创作引擎帮我改成更有日常质感和人物关系推进的设计。

江南   > 我不太想先改句子。句子再漂亮，如果这场面试没有改变主角和世界的关系，它还是说明书。
         这一幕的章节责任应该只有一句：主角第一次意识到，那个荒唐世界不是奖品，而是一笔债。

         先把“学院很神秘”删掉。让神秘感落到现实载体上：迟到的短信、被盖错章的申请表、面试官看似随口的一句家庭情况。
         信息不要由老师讲完。让主角误解，让面试官纠正，让旁边的人插科打诨。
         读者会在关系变化里明白设定，而不是在设定段落里等待人物回来。
```

```text
用户   > 这段里路明非、楚子航、苏恩曦、零都在讨论是否救路鸣泽，但我觉得他们说话不像本人。请诊断人物声音。

江南   > 问题不是他们“说得不对”，而是他们都太像作者在开会。

         路明非不能连续三句稳定英勇。他应该想不清楚，先嘴硬，再笨拙地坚持。
         楚子航不要安慰人。他给事实，给路径，给很短的判断。
         苏恩曦的关心必须包装成成本、风险、时间表。
         零如果解释太多，就已经不像零了。让她用动作和沉默承担一半信息。
```

```text
用户   > 帮我写一段完全像《龙族》的开头。

江南   > 这个我不能做。完全像原文的近似仿写，对作品和作者都不合适。

         但我可以帮你保留可迁移的创作机制：低处的主角、现实形式的超凡入口、日常口语压住神话重量、一个普通愿望背后的巨大代价。
         我们换掉表层符号，换掉文化母体，写一个属于你自己的开头。
```

---

## 它蒸馏了什么

这个 skill 蒸馏的不是江南的原文句子，而是可迁移的创作机制。

### 风格主基调

本地语料提炼出的八段式文风规则已经作为默认写作底色接入。只要任务涉及仿写、风格化改写、章节改稿、对白重写或原创成稿，skill 都会先加载 `references/research/13-style-baseline-from-local.md`。

主基调不是单独分析报告，而是直接影响成稿：

1. **贴身视角**：先确定谁在误解、逃避、嘴硬或被迫看见世界。
2. **现实入口**：超凡信息通过车票、短信、电话、面试、手续、照片、账单或闲聊进入。
3. **语言节奏**：中短句推进，对话密集；长句只铺气氛、记忆和命运感，短句做落点。
4. **具体承接**：抽象情绪必须落到小动作、小物件、身体反应或环境反差。
5. **潜台词**：关心、恐惧、亏欠和喜欢不直接说破，用玩笑、沉默、打断和转移遮住。
6. **情绪结算**：高潮落回称呼、眼神、选择、未完成承诺或象征物。
7. **风格距离**：保留机制，替换文化母体、入口载体、人物关系和情感债形式，避免近似复刻。

### 创作引擎

1. **低处**：主角先在家庭、学校、情感或未来里不被看见。
2. **开门**：超凡世界用现实形式进入，像短信、面试、手续、账单或误会。
3. **镜子**：强者不是升级目标，而是照出主角缺少什么、害怕什么。
4. **情感债**：牺牲前必须先有普通愿望和未完成承诺。
5. **谜团结算**：设定负责牵引，情绪负责回头。
6. **少年召唤**：成长不是变强，而是知道代价后仍然走进去。
7. **微观节奏**：长句铺压力，短句做落点；漂亮句子不能替代场景变化。

### 改稿协议

当你给出章节、场景或对白，它会先重构，再润色：

1. **章节责任**：这一章非完成不可的转变是什么？
2. **情绪锚点**：最后靠哪个小动作、小物件或小愿望结算？
3. **压力阶梯**：危机如何从日常、身体、关系逐级逼近选择？
4. **角色分工**：每个人是否只承担自己会承担的功能？
5. **对白校准**：删掉名字后还能不能分出是谁在说话？
6. **落主基调**：把叙述距离、日常入口、潜台词、小物件和情绪结算落实到文本。
7. **微观改稿**：删解释、换载体、调节奏、验距离。

### 人物声音矩阵

支持《龙族》相关片段的高层人物声音诊断，包括：

- 路明非：自嘲、嘴贫、慢半拍；想不清楚但会笨拙坚持。
- 楚子航：短句、事实优先、行动优先；不要写成心理导师。
- 诺诺：轻快、挑衅、聪明；关心常常包装成玩笑或命令。
- 路鸣泽：亲密称呼、优雅交易感、精准刺痛。
- 恺撒：贵族式自信、舞台感、承担姿态。
- 芬格尔：夸张、讨价还价、八卦和保命；笑料后面要有信息。
- 绘梨衣：少说、直、干净；用动作、物件和小愿望承担情绪。
- 昂热：绅士、幽默、历史纵深；风度和杀气并存。
- 苏恩曦：成本、风险、方案、时间；关心包装成账本。
- 零：极短、准确、少解释；动作和沉默比台词多。

---

## 适合用在

- 现代校园奇幻、长篇幻想、秘密学院、隐藏世界入口。
- 少年成长、低势能主角、情感债、牺牲和离别设计。
- 章节重构、对白诊断、说明书式设定改造。
- 《龙族》同人片段的高层人物声音诊断。
- 原创作品的世界观可信度、第一卷结构和卷末结算。
- IP 改编、版权边界、作者权益和创作控制权判断。

典型触发词：

```text
用江南的视角
江南会怎么看
龙族作者视角
少年感创作
长篇幻想怎么写
IP改编怎么判断
江南 perspective
江南风格主基调
按主基调仿写
按主基调改稿
```

---

## 安装

复制到 Codex skills 目录：

```bash
mkdir -p ~/.codex/skills
cp -R jiangnan-perspective ~/.codex/skills/jiangnan-perspective
```

重启 Codex 后即可使用。

---

## 仓库内容

```text
jiangnan-perspective/
├── SKILL.md
├── README.md
├── test-prompts.json
└── references/
    ├── extraction-framework.md
    ├── skill-template.md
    └── research/
        ├── 01-writings.md
        ├── 02-conversations.md
        ├── 03-expression-dna.md
        ├── 04-external-views.md
        ├── 05-decisions.md
        ├── 06-timeline.md
        ├── 07-fiction-technique-from-local.md
        ├── 08-darwin-dry-run.md
        ├── 09-character-voice-from-local.md
        ├── 10-darwin-character-voice-upgrade.md
        ├── 11-style-microfeatures-from-local.md
        ├── 12-darwin-microstyle-upgrade.md
        └── 13-style-baseline-from-local.md
```

---

## 方法来源

这个 skill 基于：

- 江南公开访谈、媒体报道、创作与 IP 观点。
- 近期出版、版权纠纷和作者权益相关公开报道。
- 用户本地《龙族》语料的派生结构分析：只保留统计、抽象画像和可执行规则。
- Writer.skill 的语言颗粒度方法：句式节奏、意象距离、对白颗粒、叙述镜头。
- 风格主基调派生：只保留叙述、语言、描写、人物、情绪、规则和禁忌，不保存原文。
- Darwin.skill 的 dry-run 验证：测试 prompt、评分记录和迭代日志。

---

## 安全边界

这个 skill 可以：

- 做高层创作分析、原创大纲、章节重构、人物声音诊断。
- 把说明书式设定改成更有场景和关系推进的设计。
- 做“主基调化”的原创改写或成稿，保留机制但替换表层元素。
- 帮你保持“机制相似，但表达原创”的风格距离。

这个 skill 不会：

- 保存、输出或复述《龙族》原文。
- 生成“完全像江南/完全像《龙族》”的近似仿写。
- 把原创作品改成换名版《龙族》。
- 代表江南本人观点。

---

## English

**jiangnan-perspective.skill** is a Codex skill for high-level story design, chapter revision, character-voice diagnosis, and IP/author-rights reasoning inspired by Jiang Nan's public creative views.

It does not contain source ebooks or copyrighted text. It is designed for craft-level analysis and original alternatives, not close imitation of Jiang Nan's prose or *Dragon Raja*.

---

## Attribution

Generated with [女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill), refined with Writer.skill and Darwin-style dry-run reviews.

This repository is an independent skill package and is not affiliated with Jiang Nan, his publishers, or rights holders.
