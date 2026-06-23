# ChowSan 小红书行业内容诊断

这是一个用于诊断“小红书某个行业应该做什么内容”的 Codex Skill。

它适合本地生活商家、内容顾问、小红书运营、商业陪跑顾问、知识付费老师和服务线下门店的团队使用。

它要解决的问题很具体：

> 给到一个行业，怎么判断这个行业在小红书上应该发什么内容？

这个 Skill 不做泛泛的平台运营建议，不会只告诉你“坚持更新、做好定位、打造人设”。它会把一个行业拆成一套可执行的内容诊断：

- 用户到底会搜什么
- 商家现在不该发什么
- 产品应该怎么翻译成用户场景
- 账号应该怎么定位
- 内容方向怎么设计
- 标题公式怎么套
- 关键词怎么布局
- 7 天内容怎么排
- 小红书内容怎么承接到到店、咨询、私域或复购

## 这个 Skill 能做什么

你给它一个行业，它可以生成一份完整的小红书内容诊断。

输出内容包括：

- 行业诊断
- 用户真实搜索拆解
- 不该发什么内容
- 应该发什么内容方向
- 账号定位建议
- 标题公式
- 关键词布局
- 7 天内容排期
- 到店、咨询、私域、复购承接方式
- 可复用的行业案例文档

## 适合谁使用

这个 Skill 适合：

- 本地生活商家
- 小红书运营
- 内容顾问
- 商业陪跑顾问
- 本地生活服务商
- 小红书代运营团队
- 教商家做小红书的课程老师
- 给线下门店做内容诊断的咨询师

尤其适合这些行业：

- 便利店
- 水果店
- 早餐店
- 茶饮店
- 健身房
- 家政清洁
- 洗车美容
- 搬家服务
- 亲子摄影
- 鲜花店
- 修脚采耳
- 社区零售店
- 其他本地生活商家

## 核心理念

很多本地商家做小红书，不是不会发内容。

真正的问题是：

> 他们一直站在商家视角发内容，而不是站在用户决策视角发内容。

商家喜欢发：

- 今天到货了
- 今天很新鲜
- 我们很专业
- 环境很好
- 价格优惠
- 项目齐全
- 老板很用心

但用户不是这样搜索和行动的。

用户更关心的是：

- 我现在为什么需要你？
- 你能帮我解决什么具体问题？
- 我会不会踩坑？
- 这笔钱花得值不值？
- 你离我近不近？
- 我什么时候该来一次？
- 我怎么判断你靠不靠谱？

所以这个 Skill 的核心，不是帮商家“多发内容”，而是帮商家完成一次转换：

> 从“我卖什么”，转换成“用户在什么场景下会需要我”。

## 诊断结构

这个 Skill 默认按下面的结构生成行业诊断：

1. 一句话判断
2. 行业生态
3. 用户真实搜索
4. 不要发什么
5. 应该发什么
6. 内容方向
7. 账号定位
8. 标题公式
9. 关键词布局
10. 7 天内容排期
11. 承接方式
12. 最重要的一句话

## 安装方式

如果你使用 Codex，可以直接对 Codex 说：

```text
请帮我从这个 GitHub 仓库安装 skill：
https://github.com/CHOW333/chowsan-xhs-industry-content-diagnosis
```

也可以说得更明确一点：

```text
请把 https://github.com/CHOW333/chowsan-xhs-industry-content-diagnosis 里的 chowsan-xhs-industry-content-diagnosis skill 安装到我的 Codex skills 目录。
```

安装后，可以这样调用：

```text
用 $chowsan-xhs-industry-content-diagnosis 诊断一下，小区门口的水果店应该怎么做小红书内容。
```

## 使用示例

你可以这样问：

```text
Use $chowsan-xhs-industry-content-diagnosis to diagnose how a community fruit store should create Xiaohongshu content.
```

也可以这样问：

```text
Use $chowsan-xhs-industry-content-diagnosis to create a Xiaohongshu content plan for a non-chain gym near an office district.
```

中文可以这样问：

```text
用 $chowsan-xhs-industry-content-diagnosis 诊断一下，小区门口的水果店应该怎么做小红书内容。
```

或者：

```text
用 $chowsan-xhs-industry-content-diagnosis 帮我看一下，写字楼附近的非连锁健身房，小红书应该发什么。
```

## 输出示例片段

以“小区门口水果店”为例，这个 Skill 会先给出这样的判断：

> 小区门口的水果店做小红书，核心不是发“今天水果很新鲜”，而是做附近居民的每日水果购买决策。

它不会建议你只发：

- 今天到货了
- 苹果多少钱一斤
- 榴莲开了
- 水果很新鲜
- 老板进货日常

而是会建议你发：

- 今天小区门口买什么水果
- 家里有孩子，水果别只买贵的
- 给爸妈买水果，甜度和软硬比价格更重要
- 买西瓜别只拍一拍，先看这 3 个地方
- 100 元左右水果篮，怎么搭比较体面

因为水果店真正要解决的，不是让用户知道“你有水果”。

而是让附近居民在想买水果的时候，第一反应是：

> 今天不知道买什么，可以先看看这家店怎么推荐。

## Obsidian 支持

这个 Skill 内置了一个通用的 Obsidian 整理方式。

推荐结构是：

```text
Vault/
└─ ProjectName/
   ├─ Home.md
   ├─ Case Index.md
   ├─ Workflow/
   │  ├─ 01_Workflow.md
   │  ├─ 02_Output Template.md
   │  ├─ 03_Rule Library.md
   │  └─ 04_Update Log.md
   └─ Cases/
      └─ YYYY年M月D日_Industry.md
```

这个 Skill 不预设固定的本地路径。

如果你有自己的 Obsidian Vault，可以按自己的路径调整。

## Skill 名称

```text
chowsan-xhs-industry-content-diagnosis
```

## 文件结构

```text
chowsan-xhs-industry-content-diagnosis/
├─ SKILL.md
├─ agents/
│  └─ openai.yaml
└─ references/
   ├─ workflow.md
   ├─ output-template.md
   ├─ obsidian-sync.md
   └─ case-examples.md
```

## 设计原则

好的小红书内容，不是把商家介绍得更完整。

而是帮用户更快做决定。

一篇真正有效的本地商家小红书内容，应该回答这些问题：

- 用户为什么现在需要这个商家？
- 需求在什么生活场景里被触发？
- 用户下单前担心什么？
- 用户真实会搜索什么词？
- 什么内容能降低用户的不确定感？
- 小红书内容如何承接到到店、咨询、私域或复购？

这个 Skill 就是围绕这套诊断逻辑设计的。

## 一句话总结

ChowSan 小红书行业内容诊断，不是教你多发内容。

它是帮你判断：

> 一个行业在小红书里，应该用什么内容让用户更快做出消费决策。
