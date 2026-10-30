---
name: art-deco-luxe-poster-skill
description: Generate a Simplified-Chinese 9:16 poster in the 「装饰艺术」(art-deco-luxe) style by 一张有戏. Use when the user wants a 装饰艺术 / art deco luxe poster.
---

# 装饰艺术 · art-deco-luxe poster skill

一张有戏「装饰艺术」风格海报技能。输出一张 9:16 竖版、简体中文的独立海报。

## 用法
1. 确定一个主标题（2–4 字）和一句短句。
2. 画面只出现三段文字：主标题、短句、页脚「一张有戏 · 视觉习作」。
3. 版式可选：centered-hero, frame-within-frame。
4. 参照下方完整提示词模板，替换 Headline / Supporting phrase / 场景描述。

## 示例主题
- 夜曲：让夜晚沿着旋律展开（frame-within-frame）— Elegant saxophone silhouette centered in stepped emerald and champagne-gold fan geometry, formal typographic lockup.
- 银幕之夜：把光影收进一道金线（centered-hero）— Minimal vintage cinema projector silhouette with one geometric beam, black/ivory and precise gold foil linework.
- 金色回廊：沿着秩序走进光里（frame-within-frame）— Symmetrical stepped Art Deco architectural corridor in deep navy, gold hairline arches, disciplined elegant Chinese title.
- 花间夜色：让盛放也有克制的节奏（centered-hero）— One stylized camellia bloom built from geometric fan petals, burgundy/ivory/champagne gold, central symmetry.
- 星光剧场：把开场前的安静留下来（frame-within-frame）— Art Deco curtain and stepped proscenium, navy/black with spare gold spotlights, no star sparkles.
- 海上假日：让远行拥有优雅的轮廓（centered-hero）— A luxury steamship-like generic geometric silhouette, deep teal/ivory horizontal sea bands and gold stepped frame, no company logos.
- 舞步之间：让一个转身成为节奏（frame-within-frame）— Two small abstract non-identifiable dance silhouettes as one central motif within burgundy/gold fan frame, not human portrait.
- 都市晚宴：让相聚拥有一点仪式感（centered-hero）— One elegant stemmed glass silhouette and geometric table-light motif, emerald/black/gold architecture, refined symmetrical type.

## 完整提示词模板（第 1 张原文）
```
Use case: ads-marketing. Create exactly ONE polished professional 9:16 portrait poster, static flat artwork, Chinese-mainland cultural/creative studio portfolio concept.
Language: Simplified Chinese. Headline: 夜曲. Supporting phrase: 让夜晚沿着旋律展开. Tiny plain footer: 一张有戏 · 视觉习作. Exact visible text ONLY these three phrases, every character correctly formed. No English, random numbers, fake events, dates, addresses, awards, offers, prices, affiliations, calls to action or status labels. All content is fictional/conceptual creative brief, no real client claim.

SOURCE UNIVERSAL RULES:


These rules apply to every poster. Do not repeat them in layout or style notes.

- Build around one dominant message, one clear focal point, and one communication goal.
- Establish a simple reading order: headline -> focal image -> supporting copy -> supplied details.
- Preserve required copy exactly unless the user explicitly asks for rewriting.
- Keep important text readable, high-contrast, and inside safe margins.
- Use confident spacing and avoid overstuffed layouts.
- Avoid fake extra text, random logos, QR codes, decorative clutter, malformed typography, and generic AI-poster noise.
- Treat the poster canvas as static print/editorial artwork rather than a clickable interface. If the source explicitly requests a product UI, browser window, dashboard, or device mockup, preserve that depicted content inside the poster.
- CTA copy is extractive-only: include it only when the source explicitly supplies the wording. When output language differs, verify the translated CTA against a recorded exact source quote. Never invent action or status labels.
- If no CTA is sourced, leave the action area empty. If one is sourced, render it as ordinary poster typography in a footer or text lockup. Do not place poster-level action copy inside a button, rounded rectangle, pill, chip, capsule, tab, input field, or any other clickable-looking UI container; do not decorate it with a shadow, arrow, chevron, or cursor icon.



SELECTED STYLE — STRICTLY THIS VISUAL SYSTEM, DO NOT MIX OTHER STYLES:
# Art Deco Luxe

## Intent

Create a glamorous, geometric poster with Art Deco symmetry, metallic accents, elegant ornament, and premium nightlife/event polish.

## Typography

- Use elegant geometric display type inspired by Art Deco proportions.
- Pair title with refined small caps or clean sans-serif metadata.
- Keep lettering sharp and symmetrical.

## Palette

Black, deep navy, emerald, ivory, champagne gold, bronze, pearl, burgundy.

## Imagery

Geometric frames, fan motifs, stepped forms, spotlight, champagne, stage, architectural ornament, luxury product silhouette.

## Texture / Material

Foil shimmer, lacquer, velvet, marble, subtle metallic linework, dark matte paper.

## Composition Rules

- Favor symmetry, vertical central axis, and ornamental framing.
- Use gold/metal accents sparingly and precisely.
- Keep poster elegant, not overloaded.
- Details should sit in a formal lockup.

## Avoid

Cheap gold gradients, excessive ornament, casino clichés, illegible ornate fonts, and noisy backgrounds.


INTERNAL COMPOSITION:
# Frame Within Frame

## Composition Structure

- Create an inner frame, border, card, photo mat, or window inside the poster.
- Place the main subject inside or breaking through the frame.
- Use outer margins for breathing room and metadata.
- Make the frame a compositional device, not a generic border.

## Hierarchy Rules

1. Inner frame focuses attention.
2. Headline relates to frame edge or subject.
3. Details sit in outer margin, footer, or corner.

## Text Placement

- Align headline to frame edges or outer grid.
- Use small details sparingly in margins.
- Keep high contrast between frame, content, and background.

## Image Treatment

Use refined photography, object close-up, artwork detail, or minimal illustration within the frame.

## Spacing Rules

Outer margins should feel intentional and premium. Inner padding must be consistent.

## Aspect-Ratio Behavior

Excellent for `2:3`, `3:4`, `4:5`, and `1:1`. In `16:9`, use a wide cinematic frame.

## Avoid

Plain border-only layouts, cramped frames, decorative frames that overpower the subject, and unaligned typography.


SPECIFIC SUBJECT AND ART DIRECTION:
Elegant saxophone silhouette centered in stepped emerald and champagne-gold fan geometry, formal typographic lockup.

Quality: exquisite thoughtful art direction, one immediate focal point, sophisticated typographic spacing and clear reading order, original expressive composition with wide enough safe margins. Headline large and readable at phone thumbnail; secondary text restrained, not generic template. Typography adapted sensitively to real Chinese glyphs, with the visual weight demanded by style. Material/light/print treatment consistent with selected style. If any person appears, fictional mainland Chinese adult, natural anatomy and authentic face; otherwise no people. All props physically coherent unless the SPECIFIC surreal idea deliberately changes physics. No trademarks or label text on products, no fake logos/watermarks/QR. No poster mockup, wall frame, multiple-poster collage, UI buttons or decorative website components. The creative theme must determine composition; vary crop, hierarchy and negative space across the series. Output one finished poster only.
```

全部 8 条提示词见 `PROMPTS.json`，来源见 `SOURCES.md`。
