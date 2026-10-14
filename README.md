# ✦ Qianwen AI Studio Replica & Short-Drama Workflow (`@MorpheusJoe`)

> **UI Architecture**: 1:1 `create.qianwen.com` Minimalist Home + **Krea AI** Floating Pill Dock Workbenches (`AI 生图` / `AI 视频`) + **FLORA** Pure Visual Infinite Canvas (`画布 · 工作流` replicating RunningHub Camp `#2108417413198807041`) + **Linear / Raycast** `1px` Specular Frosted Glass & `⌘K` Command Palette.

## 📦 Repository Structure

```text
.
├── index.html                                      # 主应用入口（支持 GitHub Pages 直开）
├── qianwen_ai_studio_pc_replica.html               # 完整单文件版 AI 创作工作台
├── skills/
│   └── short-drama-script-to-prompt/
│       └── SKILL.md                                # AI 短剧核心技能（#2 剧本直出4-View与8段式生图词 + #3 文武双模分镜润色）
├── docs/
│   └── qianwen_ai_studio_pc_ui_spec.md             # 1:1 UI 视觉与结构复刻规范文档
└── push_to_github.sh                               # 本地一键推送至 github.com/MorpheusJoe 脚本
```

## 🚀 Quick Start

1. **直接运行**：双击打开 `index.html` 或 `qianwen_ai_studio_pc_replica.html` 即可在浏览器体验完整功能。
2. **连接真实推理引擎**：点击左下角或右上角「登录」，填入本地 `ComfyUI (http://127.0.0.1:8188)`、`Ollama / vLLM`、`DashScope / OpenAI` 或 `RunningHub OpenAPI Key` 即可切换为真机生成。
3. **安装 Claude Code / Codex / OpenClaw 短剧技能**：
   ```bash
   mkdir -p ~/.claude/skills/short-drama-script-to-prompt
   cp skills/short-drama-script-to-prompt/SKILL.md ~/.claude/skills/short-drama-script-to-prompt/
   ```
