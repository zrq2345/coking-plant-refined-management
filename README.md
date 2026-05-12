# 焦化厂精细化管理 Claude Skill

> 一个专为焦化厂管理人员设计的 Claude Code Skill，帮你诊断管理漏洞、建立标准体系、规划AI赋能路径。

## 这个 Skill 能做什么

- **管理诊断**：判断你的问题是制度缺失、标准不清、执行变形还是考核失效
- **建体系**：交接班规范、设备点检定修、KPI考核体系、安全环保制度
- **两阶段路径**：先稳管理基础，再用AI放大执行力
- **落地具体**：给数字、给模板、给验收标准，不讲空泛管理学

## 适用场景

- 焦化厂管理人员、厂长、副总
- 正在建立或完善管理体系的团队
- 想推进数字化/AI赋能但不知从哪下手的管理者

## 安装方法

**第一步**：在你的电脑找到 Claude Code 的 skills 目录：
```
Windows: C:\Users\你的用户名\.claude\skills\
Mac/Linux: ~/.claude/skills/
```

**第二步**：在 skills 目录下新建文件夹：
```
coking-plant-refined-management/
```

**第三步**：下载 `SKILL.md` 放入该文件夹，重启 Claude Code 即可。

### 或者直接让 Claude 帮你安装

在 Claude Code 中说：
```
add zrq2345/coking-plant-refined-management
```

## 触发词

说以下任何一句，Skill 自动激活：

`精细化管理` `管理体系` `班组管理` `交接班` `点检定修` `管理漏洞` `考核指标` `数字化转型` `AI赋能焦化` `制度落地` `执行力` `我们管理比较乱` `怎么建体系` `交接班乱` `怎么考核班组`

## 使用示例

```
你：我们交接班比较乱，班组长随便签个字就走了，怎么改？
Claude：[先判断层级 → 问诊断问题 → 给出具体9栏交接班模板+验收标准]

你：我们想上AI，但管理基础还很薄弱
Claude：[AI就绪度诊断 → 三步走路径 → 明确第一个切入场景]

你：帮我起草安全生产责任制
Claude：[直接生成对应规模的制度初稿]
```

## 如何反馈和改进

用得多了发现哪里不准、哪里缺内容，欢迎：
- 提 [Issue](../../issues) 描述问题
- 提 [PR](../../pulls) 直接改进 SKILL.md

大家用得越多，这个 Skill 就越准确。

## 适配规模

当前内置参数基于：**焦炉1座 · 112孔 · 年产136万吨 · 员工约800人**

其他规模的焦化厂同样适用，具体工艺参数请结合本厂实际情况调整。

## 配合达尔文 Skill 使用

安装 [darwin-skill](https://github.com/alchaincyf/darwin-skill) 后，可以对本 Skill 进行自动评分和优化：

```
优化 coking-plant-refined-management 这个skill
```

---

> 作者：[zrq2345](https://github.com/zrq2345)
> 欢迎焦化行业从业者共同完善这个 Skill
