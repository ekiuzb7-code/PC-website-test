# ULTIMATE MASTER PROMPT --- DREAM PC CINEMATIC LANDING PAGE

## Mission

Create an **award-winning premium landing page** for a futuristic custom
gaming PC brand.

The experience should feel like a blend of:

-   Apple.com
-   ASUS ROG
-   NVIDIA
-   Nothing.tech
-   Linear.app
-   Framer Awards
-   Awwwards

------------------------------------------------------------------------

# Language Rules

-   The entire website UI **MUST** be in **Uzbek**.
-   Only technical names may remain in English:
    -   RTX
    -   DDR5
    -   Intel
    -   AMD
    -   PCIe
    -   NVMe
    -   RGB

No English headings, paragraphs, navigation labels, or buttons.

------------------------------------------------------------------------

# Design Goals

-   Luxury
-   Minimal
-   Cinematic
-   Futuristic
-   Premium
-   Clean
-   Elegant
-   Apple-level spacing
-   Framer-quality polish
-   Awwwards-quality interactions

The visitor should be impressed within **3 seconds**.

------------------------------------------------------------------------

# Hero (Most Important)

The hero section is the entire storytelling experience.

## Structure

-   Hero height: **450vh**
-   Sticky container:
    -   `position: sticky`
    -   `top: 0`
    -   `height: 100vh`
    -   `width: 100%`

Inside the sticky container place **only one HTML Canvas**.

Do **NOT** use an HTML `<video>` element.

Use a **frame-by-frame animation** rendered on Canvas.

Frames already exist:

``` text
/public/frames/
0001.webp
0002.webp
...
0150.webp
```

Preload every frame before interaction.

Render using `requestAnimationFrame`.

## Scroll Behavior

Scrolling down:

-   Frame 1 → Frame 150

Scrolling up:

-   Frame 150 → Frame 1

Requirements:

-   No autoplay
-   No controls
-   No looping
-   Animation follows scroll exactly
-   Hero remains pinned until the last frame
-   Only after the last frame should the next section appear
-   Returning upward reverses the animation naturally

The experience should resemble Apple's scroll-driven product pages.

## Hero Content

Heading:

> O'z orzuingizdagi kompyuterni yarating

Subtitle:

> Har bir detal. Har bir kadr. Mukammal ishlash uchun yaratilgan.

Buttons:

-   Konfiguratsiyani ko'rish
-   Komponentlar

Bottom indicator:

> Pastga aylantiring

As scrolling starts:

-   Fade out heading
-   Fade out subtitle
-   Fade out buttons
-   Fade out indicator

After \~15% progress, only the animation remains.

------------------------------------------------------------------------

# Visual Style

Background: `#050505`

Use:

-   soft radial gradients
-   subtle RGB glow
-   tiny noise texture
-   faint grid
-   premium glassmorphism
-   cinematic lighting

No template look. No cheap gaming aesthetic. No excessive neon.

------------------------------------------------------------------------

# Navigation

Glassmorphism navbar.

Menu:

-   Bosh sahifa
-   Komponentlar
-   Imkoniyatlar
-   Galereya
-   Narxlar
-   Bog'lanish

CTA:

**Boshlash**

------------------------------------------------------------------------

# Sections

## Nima uchun aynan biz?

Three premium glass cards.

## Komponentlar

GPU, CPU, RAM, SSD, Liquid Cooler, Power Supply.

## Haqiqiy quvvat

Animated statistics.

## Galereya

Responsive masonry layout.

## Foydalanuvchilar fikri

Premium review cards.

## Ko'p so'raladigan savollar

Modern accordion.

## CTA

Heading:

> Bugunoq o'z gaming kompyuteringizni yig'ing

Button:

> Boshlash

------------------------------------------------------------------------

# Footer

Minimal dark footer with navigation and contacts.

------------------------------------------------------------------------

# Animations

-   GSAP ScrollTrigger
-   Lenis smooth scrolling
-   Fade
-   Blur
-   Translate Y
-   Scale
-   Stagger
-   Hover glow
-   Glass reflections

------------------------------------------------------------------------

# Glassmorphism

Only for:

-   Navbar
-   Cards
-   Buttons

```{=html}
<!-- -->
```
    background: rgba(255,255,255,.05)
    backdrop-filter: blur(20px)
    border: 1px solid rgba(255,255,255,.08)

------------------------------------------------------------------------

# Tech Stack

-   Next.js
-   React
-   TypeScript
-   Tailwind CSS
-   Canvas
-   GSAP
-   Lenis

Use the existing frame sequence from `/public/frames`.

Optimize for desktop, tablet and mobile.

Every pixel should feel intentional and premium.
