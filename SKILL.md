---
name: art-deco-luxe-poster
description: 装饰艺术海报：用对称几何、金属点缀与夜生活式精致感，做一张华丽克制的装饰艺术海报。根据【主标题】【短句】【场景】【版式】【主色强调】【画幅】生成一张简体中文海报。当用户提到「装饰艺术 / Art Deco / 轻奢几何海报」时使用。 Use when the user asks for a Art Deco luxe poster, geometric metallic glamour poster — produces one poster with only three visible Chinese lines: headline, supporting line, and footer「一张有戏 · 视觉习作」.
license: MIT
---

# 装饰艺术 · Art Deco Luxe Poster

用对称几何、金属点缀与夜生活式精致感，做一张华丽克制的装饰艺术海报。
A glamorous geometric poster with Art Deco symmetry, metallic accents, elegant ornament, and premium nightlife polish.

## 输入 · Inputs

```
【主标题】：
【短句】：
【场景】：
【版式】：（centered-hero / frame-within-frame，缺省 frame-within-frame）
【主色强调】：（champagne gold / bronze / pearl / emerald（金属点缀克制））
【画幅】：9:16（默认）
```

**缺失字段不要追问**：只给了主标题（或部分字段）时，由你根据主标题自行补全其余字段，并保证场景、版式、主色强调彼此协调、指向同一概念。画幅缺省为 9:16。
If any field is missing, fill it yourself coherently from the headline — never ask. Default aspect ratio 9:16.

## 使用方法 · How to use
1. 读取输入，补全缺失字段（内部完成，不输出分析）。
2. 按下方核心规则 + [prompt.md](prompt.md) 组合提示词，交给图像生成工具，**只输出一张**海报。
3. 若当前环境不能生图，输出下方「可直接粘贴的最终提示词」，已填好字段，供用户粘贴到 ChatGPT / 其他图像模型。

示例输入见 [examples/themes.md](examples/themes.md)。

## 核心规则 · Core rules

### 目标 · Intent
用对称几何、金属点缀与夜生活式精致感，做一张华丽克制的装饰艺术海报。
Create a glamorous, geometric poster with Art Deco symmetry, metallic accents, elegant ornament, and premium nightlife/event polish.

### 字体 · Typography
- Use elegant geometric display type inspired by Art Deco proportions.
- Pair title with refined small caps or clean sans-serif metadata.
- Keep lettering sharp and symmetrical.

### 配色 · Palette
- Black, deep navy, emerald, ivory, champagne gold, bronze, pearl, burgundy.
- 【主色强调】只取一个精确强调色，不要彩虹堆砌。

### 意象 · Imagery
- Geometric frames, fan motifs, stepped forms, spotlight, champagne, stage, architectural ornament, luxury product silhouette.
- 【场景】描述应支撑字体与版式，不要喧宾夺主（除非风格本身以主体物件为第一阅读）。

### 质感 · Texture / Material
- Foil shimmer, lacquer, velvet, marble, subtle metallic linework, dark matte paper.

### 构图 · Composition
- Favor symmetry, vertical central axis, and ornamental framing.
- Use gold/metal accents sparingly and precisely.
- Keep poster elegant, not overloaded.
- Details should sit in a formal lockup.
- 版式从该风格允许的布局中选择：`centered-hero / frame-within-frame`；缺省 `frame-within-frame`。
- 单一焦点、清晰阅读顺序：主标题 → 焦点画面 → 短句 → 页脚。

### 文字锁定 · Text lock（一张有戏）
- 画面可见文字**只有三行**：【主标题】、【短句】、页脚「一张有戏 · 视觉习作」。
- 简体中文；每个字正确成形；不要英文乱码、假活动、假日期、假地址、假奖项、假价格、假 CTA、假品牌。
- 不要按钮/圆角胶囊/UI 容器；页脚就是普通小字排印。

### 避免 · Avoid
- Cheap gold gradients, excessive ornament, casino clichés, illegible ornate fonts, and noisy backgrounds.
- 额外假字、随机 logo、二维码、装饰堆砌、畸形字体、通用 AI 海报噪声、水印、UI。

### 执行 · Execution
不提问、不展示分析、不出多版本，直接输出一张海报。

## 可直接粘贴的最终提示词 · Ready-to-paste prompt template

```
【主标题】：{{主标题}}
【短句】：{{短句}}
【场景】：{{场景}}
【版式】：{{版式，缺省 frame-within-frame；可选 centered-hero / frame-within-frame}}
【主色强调】：{{主色强调}}
【画幅】：{{画幅，默认 9:16}}

Create exactly ONE polished professional {{画幅，默认 9:16}} portrait poster, static flat artwork, Chinese-mainland cultural/creative studio portfolio concept.
Language: Simplified Chinese. Headline: {{主标题}}. Supporting phrase: {{短句}}. Tiny plain footer: 一张有戏 · 视觉习作. Exact visible text ONLY these three phrases, every character correctly formed. No English clutter, random numbers, fake events, dates, addresses, awards, offers, prices, affiliations, calls to action or status labels. All content is fictional/conceptual creative brief, no real client claim.
If any field above is empty, fill it coherently from 【主标题】 so scene, accent and layout support one clear idea — do not ask questions.

SELECTED STYLE — STRICTLY THIS VISUAL SYSTEM, DO NOT MIX OTHER STYLES:
# Art Deco Luxe
Intent: Create a glamorous, geometric poster with Art Deco symmetry, metallic accents, elegant ornament, and premium nightlife/event polish.
Typography: Use elegant geometric display type inspired by Art Deco proportions. Pair title with refined small caps or clean sans-serif metadata. Keep lettering sharp and symmetrical.
Palette: Black, deep navy, emerald, ivory, champagne gold, bronze, pearl, burgundy. Use exactly one precise accent from 【主色强调】.
Imagery: Geometric frames, fan motifs, stepped forms, spotlight, champagne, stage, architectural ornament, luxury product silhouette. Scene direction: {{场景}}.
Texture / Material: Foil shimmer, lacquer, velvet, marble, subtle metallic linework, dark matte paper.
Composition: Favor symmetry, vertical central axis, and ornamental framing. Use gold/metal accents sparingly and precisely. Keep poster elegant, not overloaded. Details should sit in a formal lockup. Use layout {{版式，缺省 frame-within-frame}} from allowed set (centered-hero / frame-within-frame). One dominant message, one focal point; reading order headline -> focal image -> supporting copy -> footer. Confident spacing; no overstuffed layout; no UI buttons/pills for the footer.

Avoid: Cheap gold gradients, excessive ornament, casino clichés, illegible ornate fonts, and noisy backgrounds. Also avoid fake extra text, logos, QR codes, decorative clutter, malformed typography, generic AI-poster noise, watermarks, UI chrome.

Do not ask questions. Do not show analysis or alternatives. Output the single finished poster only.
```
