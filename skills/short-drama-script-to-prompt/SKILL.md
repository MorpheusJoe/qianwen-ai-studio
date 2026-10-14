---
name: short-drama-script-to-prompt
description: "AI 短剧与漫剧核心技能（二合一）：(1) 剧本/小说直出角色 4-View 四视图设定板、连续性锁 (LOCK-*) 与 8 段式分镜首尾帧生图提示词；(2) 文戏（FACS 微表情 AU 正反打与权力关系转移）/ 武戏（起势-爆发-落点三段式动作调度与单向运动铁律）双模分镜润色器。"
---

# Short Drama Script to Prompt & Dual-Mode Storyboard Polisher

1. **Asset-First 角色 4-View 设定板与连续性锁 (`LOCK-*`)**：
   - 格式：`[画幅比 16:9/9:16]。[风格锚定]角色四视图设定板（正面全身 + 90度侧面全身 + 背面全身 + 面部骨相特写，4 distinct angles, no duplicate views），纯色干净背景。【面部五官】+【发型头饰】+【服装连续性锁 LOCK-ID】+【随身道具与体态】+【光影与禁令】。`
2. **8 段式分镜首尾帧生图提示词 (`Z/Y/X/F` 相机四维编码)**：
   - 格式：`[画幅与品质锚定] + [Z景别距离 + Y机位高度 + X方位 + F焦段景深] + [场景基底] + [人物 + 原样粘贴 LOCK-* 连续性锁] + [起始/落点姿态与视线契约 gaze_contract] + [环境物理交互] + [三层光影：主光源/光行为/冷暖色调] + [硬性负面禁令：no text, no subtitles, no logo, no watermark, no split grid borders]`
3. **文戏 (FACS 微表情正反打) / 武戏 (起势-爆发-落点三段式) 双模分镜润色**：
   - 文戏：将抽象情绪转化为 `AU1/AU4/AU5/AU14` 生理微表情 + 越肩正反打 (`OTS`) 权力机位递进。
   - 武戏：遵守单镜头单向运动铁律，拆解为 `①起势(0-1.5s 蓄力) → ②爆发(1.5-3.5s 碰撞/Hit-Stop/120fps升格) → ③落点(3.5-5s 支撑姿态 pose_contract)`。
