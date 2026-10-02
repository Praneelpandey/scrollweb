<div align="center">

# ⬛ MIDNIGHT

### AirPods Max 2 × iPhone 17 Pro — The New Black

A cinematic, scroll-driven product experience. Pure black, engineered light, and spring-physics motion in every frame.

<br />

<img src="public/images/duo.png" alt="AirPods Max 2 and iPhone 17 Pro in Space Black" width="880" />

<br />

![React](https://img.shields.io/badge/React-19-111?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-5-111?style=flat-square)
![Tailwind](https://img.shields.io/badge/Tailwind-4-111?style=flat-square)
![Framer%20Motion](https://img.shields.io/badge/Framer_Motion-12-111?style=flat-square)
![Lenis](https://img.shields.io/badge/Lenis-Smooth-111?style=flat-square)

</div>

---

## ✦ Overview

**MIDNIGHT** is an award-grade concept website built as a tribute to Apple's product page craft — a full-bleed scroll film where two devices in Space Black are revealed through staged, sticky-viewport scenes choreographed to the scrollbar.

Every movement is transform-based and spring-smoothed for a true 60fps, butter-smooth feel.

## ✦ Gallery

All photography below was generated exclusively for this experience.

<div align="center">

**The Headliners**

<table>
  <tr>
    <td><img src="public/images/airpods-hero.png" alt="AirPods Max 2 — hero" /></td>
    <td><img src="public/images/iphone-back.png" alt="iPhone 17 Pro — camera plateau" /></td>
  </tr>
</table>

**Obsessive — the detail macros**

<table>
  <tr>
    <td><img src="public/images/airpods-earcup.png" alt="Anodized ear cup macro" /></td>
    <td><img src="public/images/airpods-mesh.png" alt="Knit mesh canopy macro" /></td>
  </tr>
  <tr>
    <td><img src="public/images/airpods-side.png" alt="Side profile silhouette" /></td>
    <td><img src="public/images/iphone-lens.png" alt="Sapphire camera lenses macro" /></td>
  </tr>
</table>

**Forged in black titanium**

<img src="public/images/iphone-front.png" alt="iPhone 17 Pro — front" width="420" />

</div>

## ✦ The Experience

| Act | Scene | Technique |
| --- | --- | --- |
| Prologue | Eased 0→100 preloader with full-screen wipe | `requestAnimationFrame` counter + exit choreography |
| I. Hero | Headphones with gyroscopic mouse tilt; split typography shears apart on scroll | Sticky 240vh stage, mix-blend-difference, 3D perspective |
| Interlude | Word-by-word prose reveal | Per-word blur + opacity scroll mapping |
| II. Spec Theater | Product rotates ±14° across ghost numerals `2×` `40h` `H2` | 460vh sticky, crossfading windows, progress rail |
| III. Craft Gallery | Horizontal-scroll macro photography | 420vh pinning, counter-parallax per panel |
| IV. iPhone Rise | Front rises, then fans out to reveal the triple-lens back | Dual-stage image choreography, swapping headlines |
| V. Bento Lab | A19 Pro, waveform animation, self-drawing battery bars | Staggered viewport reveals |
| VI. The Pair | Products converge from ±115vw — *Better together.* | Symmetric vw travel, blend-difference headline |
| Finale | "The new black." — floating duo, pricing, replay | Gradient typography, idle drift animation |

## ✦ Tech Stack

- **React 19** + **TypeScript**
- **Vite 7**
- **Tailwind CSS v4** — CSS-first `@theme` design tokens
- **Framer Motion** — `useScroll`, `useTransform`, `useSpring`, `AnimatePresence`
- **Lenis** — smooth-scroll engine with expo easing
- **Lucide** — icon system
- All product photography is AI-generated; typography is Inter / Inter Tight

## ✦ Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/midnight.git
cd midnight

# 2. Install dependencies
npm install

# 3. Start the dev server
npm run dev

# 4. Build for production
npm run build

# 5. Preview the production build
npm run preview
```

## ✦ Project Structure

```
├── public/images/          # AI-generated product photography
├── src/
│   ├── lib/scroll.ts       # Lenis singleton + smooth anchor navigation
│   ├── components/
│   │   ├── Preloader.tsx   # Intro counter + exit wipe
│   │   ├── Navbar.tsx      # Frosted-glass navigation
│   │   ├── Hero.tsx        # Act I — sticky hero, mouse gyroscope
│   │   ├── Statement.tsx   # Word-by-word prose reveals
│   │   ├── SoundFrames.tsx # Act II — spec theater
│   │   ├── Marquee.tsx     # Infinite spec ribbon
│   │   ├── Gallery.tsx     # Act III — horizontal craft gallery
│   │   ├── PhoneReveal.tsx # Act IV — iPhone fan-out stage
│   │   ├── Bento.tsx       # Tech-spec bento grid
│   │   ├── Duo.tsx         # Act VI — the convergence
│   │   ├── Finale.tsx      # Pricing + closing shot
│   │   └── Footer.tsx      # MIDNIGHT watermark footer
│   └── App.tsx             # Scroll orchestration + Lenis setup
└── ...
```

## ✦ Performance Notes

- All animation runs on `transform` / `opacity` — zero layout thrash
- Product images use radial feather masks to blend seamlessly into true black
- Film-grain overlay applied via a fixed, GPU-friendly tiling layer
- Lenis locks scroll during preloading for a clean entry

---

<div align="center">

*A fictional concept experience. Not affiliated with Apple Inc.*
*AirPods, iPhone, and all related marks are trademarks of Apple Inc.*

</div>
