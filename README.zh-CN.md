# Claude-Design

`Claude-Design` 用于设计类 HTML 产出，目标是让 AI 编程工具通过 HTML、CSS、JavaScript 和 React 生成更完整、更有设计感的视觉成品，而不是普通模板化页面。

它适合以下工作：

- 落地页
- HTML 幻灯片
- 交互原型
- UI Mockup
- 视觉方案探索
- 动画演示
- 多版本设计对比

它会引导代理：

- 为任务选择合适的展示形式
- 在信息不足时先补齐设计上下文
- 尽量贴合既有品牌和设计系统
- 在演示稿等场景下使用固定画布
- 生成更完整、更有视觉判断力的 HTML / React 成品
- 避免常见的低质量 AI 设计套路

## 适用场景

当你希望 AI 编程工具直接生成“可看的设计成品”，而不是只给出普通页面骨架时，就适合使用这个 skill。

例如：

- “使用 Claude-Design 做一个高级感更强的 landing page”
- “使用 Claude-Design 把这份内容做成 HTML 演示稿”
- “使用 Claude-Design 为这个后台页面探索 3 套视觉方向”
- “使用 Claude-Design 做一个可点击的高保真原型”

## 安装到常用 AI 编程工具

## Codex

安装：

```text
$skill-installer install https://github.com/Echoxiawan/Claude-Design/tree/main
```

安装后重启 Codex。

使用：

```text
Use the Claude-Design skill to create a high-fidelity landing page in HTML.
```

## Claude Code

安装：

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/Echoxiawan/Claude-Design.git ~/.claude/skills/Claude-Design
```

安装后重启 Claude Code。

使用：

```text
Use Claude-Design to create an interactive onboarding prototype.
```

## Claude 网页版 / 桌面版

安装：

1. 下载 `https://github.com/Echoxiawan/Claude-Design`
2. 将 skill 目录打包为 ZIP
3. 在 Claude 中打开 `Customize > Skills`
4. 选择 `Upload a skill`
5. 上传 ZIP 并启用

使用：

在提示词中直接提到 `Claude-Design`。

## 其他工具

如果某个 AI 编程工具兼容 Agent Skills 或 `SKILL.md` 规范，可以按该工具的“本地技能目录”或“导入 Skill”流程安装本目录。

如果某个工具暂不支持原生 Skill，可以把 `SKILL.md` 的内容作为项目规则、系统提示词或可复用指令集导入。
