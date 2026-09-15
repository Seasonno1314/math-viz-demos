<div align="center">

# Big Math · AI Visualization Demos

**Turning abstract math into pictures you can see — and models you can play with.** One repository, two sites.

[![简体中文](https://img.shields.io/badge/简体中文-README-2EA44F)](README.md)
[![English](https://img.shields.io/badge/English-Current-E8B964)](README.en.md)

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-2EA44F)
![Manim](https://img.shields.io/badge/Rendered%20with-Manim%20CE-6B7A99)
![License](https://img.shields.io/badge/License-MIT-E8B964)
![Static](https://img.shields.io/badge/Build-Zero%20dependency-0B1120)

## Two Sites

| Site | What's inside | Live URL | Source |
|---|---|---|---|
| 🎬 **Primary School · Number–Shape**<br>Animation Library | 18 Manim animations covering core primary-school topics | https://Seasonno1314.github.io/math-viz-demos/ | `index.html` (repo root) |
| 🧩 **K-12 · Interactive**<br>Visualization Library | 32 hands-on interactive cases<br>Primary 6 · Middle 8 · High 9 · Undergrad 9 | https://Seasonno1314.github.io/math-viz-demos/k12/ | `k12/index.html` |

The two sites link to each other: "Interactive Library →" in the primary site's nav, "← Primary School" in the K-12 site's nav.

</div>

---

## Site 1 · Primary School "Number–Shape" Library (repo root)

### 👉 [**Open the video library**](https://Seasonno1314.github.io/math-viz-demos/)

18 animated demonstrations of primary-school math principles. Core idea: **number–shape unity** — draw abstract quantitative relationships as pictures you can actually see, so the principle becomes tangible.

- Cards are full-length, looping **animated WebP previews** (autoplay, no click needed)
- Click a preview to play the **1080p full video**, or download the mp4 directly
- No install, no sign-in — just open it in a browser

### Board features

| Feature | Description |
|---|---|
| 🎬 Flagship carousel | Four flagship cases in the hero area (Gauss Summation · Area of a Circle · Probability Spinner · Fraction Multiplication), auto-rotating with progress bar and keyboard control |
| 🏷 Filters | Operations / Fractions / Motion problems / Geometry / Statistics & probability / Extension, each with a count badge |
| 🃏 3D tilt cards | Hover parallax + preview zoom + gold border growth + play halo |
| ▶ Modal player | Click a preview to play 1080p; press `Esc` to close |
| ⬇ One-click download | Direct 1080p mp4 link for every case |
| 🌙 Graceful degradation | Tilt disabled on touch, global downgrade on `prefers-reduced-motion`, offline font fallback |

### Flagship previews

| Gauss Summation | Area of a Circle | Probability Spinner | Fraction Multiplication |
|---|---|---|---|
| ![Gauss](webp/46-高斯求和.webp) | ![Circle](webp/35-圆的面积.webp) | ![Spinner](webp/44-可能性转盘.webp) | ![Fraction](webp/16-分数乘法.webp) |

### Full list (18 animations)

| No. | Topic | Category | Download |
|---|---|---|---|
| 12 | Distributive Law | Operations | [mp4](mp4/12-乘法分配律.mp4) |
| 13 | Commutative & Associative Laws | Operations | [mp4](mp4/13-乘法交换结合律.mp4) |
| 16 | Fraction Multiplication | Fractions | [mp4](mp4/16-分数乘法.mp4) |
| 17 | Fraction Division | Fractions | [mp4](mp4/17-分数除法.mp4) |
| 22 | Meeting Problem | Motion | [mp4](mp4/22-相遇问题.mp4) |
| 23 | Catch-up Problem | Motion | [mp4](mp4/23-追及问题.mp4) |
| 28 | Train Crossing a Bridge | Motion | [mp4](mp4/28-火车过桥.mp4) |
| 29 | Perimeter | Geometry | [mp4](mp4/29-周长概念.mp4) |
| 31 | Area of a Parallelogram | Geometry | [mp4](mp4/31-平行四边形面积.mp4) |
| 32 | Area of a Triangle | Geometry | [mp4](mp4/32-三角形面积.mp4) |
| 33 | Area of a Trapezoid | Geometry | [mp4](mp4/33-梯形面积.mp4) |
| 34 | Circumference of a Circle | Geometry | [mp4](mp4/34-圆的周长.mp4) |
| 35 | Area of a Circle | Geometry | [mp4](mp4/35-圆的面积.mp4) |
| 37 | Volume of a Cylinder | Geometry | [mp4](mp4/37-圆柱体积.mp4) |
| 39 | Axial Symmetry | Geometry | [mp4](mp4/39-轴对称图形.mp4) |
| 44 | Probability Spinner | Statistics | [mp4](mp4/44-可能性转盘.mp4) |
| 46 | Gauss Summation | Extension | [mp4](mp4/46-高斯求和.mp4) |
| 48 | One-stroke Drawing | Extension | [mp4](mp4/48-一笔画.mp4) |

---

## Site 2 · K-12 Interactive Visualization Library (`k12/`)

### 👉 [**Open the interactive library**](https://Seasonno1314.github.io/math-viz-demos/k12/)

32 **drag-and-click** interactive cases spanning primary school through undergraduate math. Each case ships with:

- 🖱 **An interactive HTML** file (single file, zero dependency — drag sliders and points to see things move)
- 🎥 A **1080p MP4** explanatory video
- 🌀 An **animated WebP** preview plus a cover image

| Level | Count | Sample cases |
|---|---|---|
| Primary | 6 | Ratio & Proportion · Recipe Scaling ／ Mean: Leveling Up ／ Translation & Rotation |
| Middle | 8 | Pythagorean Theorem by Area ／ Linear Function: Three Representations ／ Quadratic Parabola |
| High | 9 | Derivative: Secant → Tangent ／ Sine Curve from the Unit Circle ／ ε-δ Limits |
| Undergrad | 9 | Riemann Sums → Definite Integral ／ Taylor Expansion ／ Fourier Series |

The complete list of all 32 cases is in **[k12/README.md](k12/README.md)**.

---

## Repository layout

```
math-viz-demos/
├── index.html            # Site 1: primary-school library (repo root)
├── webp/                 #   18 animated previews
├── mp4/                  #   18 1080p videos
├── images/               #   Author QR codes, brand logo
├── k12/                  # Site 2: K-12 interactive library
│   ├── index.html        #   Library home
│   ├── cases.js          #   Index data for the 32 cases
│   ├── cases.json        #   Same, as JSON source
│   └── math-cases/       #   32 cases: interactive HTML + MP4 + WebP + covers
├── README.md             # 简体中文
├── README.en.md          # This file
└── LICENSE               # MIT License
```

> Note: to keep the repository lean, only the assets the pages actually load are committed (interactive HTML, 1080p MP4, animated WebP, cover JPG). Intermediate artifacts such as GIF previews and keyframe PNGs are excluded.

## Run locally

Pure static site — no build step, no dependencies:

```bash
# Option 1: just open the file
index.html          # primary site
k12/index.html      # K-12 site

# Option 2: serve locally (recommended — matches production path behavior)
python -m http.server 8000
#   http://localhost:8000/       → primary site
#   http://localhost:8000/k12/   → K-12 site
```

## Tech

- Animation: **[Manim CE](https://www.manim.community/)**, 1920×1080 / 30fps
- Previews: **animated WebP** (640px / 12fps / full loop) — roughly 1/3 the size of an equivalent GIF
- Site: single-file HTML + vanilla JS + CSS. **Zero build, zero dependency, works offline.**
- Design system (shared by both sites — deep-space lab, restrained black & gold):

```css
--bg-0: #0B1120;   --bg-1: #101A31;        /* deep space */
--gold: #E8B964;                           /* the single accent color */
--txt: #EAEDF4; --txt-2: #9CA8C0; --txt-3: #5D6A85;
--line: rgba(255,255,255,.09);             /* hairline */
font: Space Grotesk + PingFang SC / Microsoft YaHei + JetBrains Mono
```

---

## License & Credits

<img src="images/logo-yizhiweilai.png" width="72" alt="Yizhi Weilai" align="left" style="margin-right:14px">

This project is created and shared by **Yizhi Weilai (一知未来)** under the **MIT License**.

You are free to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of this project,
**provided that the copyright notice and this permission notice are included in all copies**.

Full text: **[LICENSE](LICENSE)**.

`Copyright (c) 2026 小何传家 heshenxian1（一知未来 / Yizhi Weilai）`

Both sites carry the same license notice in their page footer.

---

## About the author

**小何传家 heshenxian1** — AI content creator, runs the WeChat public account 「一知未来」 (Yizhi Weilai).

<img src="images/关于作者-小何传家heshenxian1.png" width="220" alt="Author QR code">

| Platform | Account |
|---|---|
| WeChat public account | 一知未来 (Yizhi Weilai) |
| WeChat | 小何传家 heshenxian1 (scan the QR code above) |

WeChat public account QR code:

<img src="images/微信公众号「一知未来」二维码.png" width="320" alt="WeChat public account QR code">

> If this project helps you, follow 「一知未来」 — let's keep turning abstract numbers into pictures you can see.
