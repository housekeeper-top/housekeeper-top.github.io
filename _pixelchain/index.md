---
title: Pixel Chain
author: Jane. R
date: 2026-08-16
category: pixelchain
layout: post
---

**[English](#english)** · **[中文](#中文)**

## English {#english}

**Pixel Chain** is a small-canvas pixel editor where you do not choose colors freely. You choose from what the chain allows.

### How it works

Every pixel you place is appended to a chain. From the second pixel on, a color is legal only when the SHA-256 of every color placed so far, plus that candidate color, ends in a run of zero bits. The number of zero bits is the level you pick when you create the canvas.

Your palette swatches almost never pass that test, so they appear struck through. Underneath each one sits what you can actually place: the legal colors nearest to it, found by sweeping all 16,777,216 colors after every stroke.

### What that feels like

The cursor walks left to right, top to bottom, and you cannot move it by hand — every color depends on the whole chain before it, so the order is fixed. Made a mistake? You can only clear from the end. There is no jumping back to repaint pixel 12.

No two canvases share a palette. The picture you end up with is a negotiation between what you wanted and what the hash allowed.

### Levels

Level 1 leaves 8,192 legal colors in the entire 24-bit space. Level 10 leaves 16. Levels 1 to 4 are free forever; a single purchase — not a subscription — opens levels 5 to 10.

### Export

Fill every cell and export a hand-written 24-bit BMP, scaled with nearest-neighbour so pixels stay razor sharp. Or export a ZIP: many apps quietly re-encode a bare image while sharing it, and the ZIP keeps your bytes exactly as written.

### Everything stays on device

No account, no cloud, no analytics, no ads. Your artworks live in local storage and go nowhere else.

Canvases from 8×8 to 128×128. Ten built-in palettes plus your own. iPhone and iPad.

[Privacy Policy](privacy/en/) · [User Terms](user_terms/en/)

---

## 中文 {#中文}

**Pixel Chain** 是一个小画布像素编辑器。在这里你不能自由挑颜色，只能从链允许的那些里挑。

### 规则

你落下的每一格都会接到一条链上。从第二格起，只有当「已涂颜色串 + 该候选色」的 SHA-256 摘要末尾连续为 0 的位数达到要求时，这个颜色才合法。要求几位，由你新建画布时选的等级决定。

调色板里的原色几乎都过不了这一关，所以显示为被划掉。每个原色下面挂着你真正能落的东西：离它最近的合法色——每落一笔，App 都会把 16,777,216 种颜色重新扫一遍再挑出来。

### 这是什么手感

光标从左上往右下一格一格走，你没法手动挪它——每一格的颜色都依赖它前面的整条链，顺序就不能乱。画错了？只能从尾巴往回清，没有跳回去重涂第 12 格这回事。

没有两张画会共用同一套配色。最后成型的画面，是你想要的和哈希允许的之间谈判出来的产物。

### 等级

1 级在整个 24 位色域里还剩 8,192 个合法色，10 级只剩 16 个。1–4 级永久免费；一次性买断（不是订阅）解锁 5–10 级。

### 导出

填满每一格后，可以导出手写编码的 24 位 BMP，用最近邻放大，像素边缘始终锐利。也可以导出 ZIP：很多 App 在分享图片时会悄悄重新编码，而 ZIP 能让字节和写出时完全一致。

### 一切留在本机

无账号、无云端、无统计、无广告。作品存在本地，哪儿也不去。

画布 8×8 到 128×128。十套内置调色板，也可以自己建。支持 iPhone 与 iPad。

[隐私政策](privacy/zh/) · [用户协议](user_terms/zh/)
