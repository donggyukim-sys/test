# DESIGN.md — Apple

> `getdesign add apple` 로 가져온 디자인 시스템. 이 프로젝트의 UI는 이 스펙을 기준으로 만든다.

## Color Palette

**Neutrals**
- Pure Black: `#000000`
- Near Black (text): `#1d1d1f`
- Light Gray (surfaces): `#f5f5f7`
- White: `#ffffff`

**Interactive**
- Apple Blue (primary accent): `#0071e3`
- Link Blue: `#0066cc`
- Bright Blue (on dark): `#2997ff`

**Text modifiers**
- Black 80%: `rgba(0,0,0,0.8)`
- Black 48%: `rgba(0,0,0,0.48)`

**Component states**
- Button active: `#ededf2`
- Button default (light): `#fafafc`
- Overlay: `rgba(210,210,215,0.64)`

## Typography

- Font: `-apple-system, "SF Pro Display", "SF Pro Text", "Helvetica Neue", Helvetica, Arial, sans-serif` (fallback: Inter)

| Role | Size | Weight | Line height | Letter spacing |
|------|------|--------|-------------|----------------|
| H1 (Display Hero) | 56px | 600 | 1.07 | -0.28px |
| H2 (Section) | 40px | 600 | 1.1 | normal |
| H3 (Tile) | 28px | 400 | 1.14 | 0.196px |
| Body | 17px | 400 | 1.47 | -0.374px |
| Button | 17px | 400 | 1.0 | normal |
| Caption | 14px | 400 | 1.29 | -0.224px |

## Spacing
XS 2px · SM 4px · MD 7px · LG 10px · XL 12px (필요시 배수로 확장)

## Border radius
SM 5px · MD 8px · LG 12px · Pill 980px

## Shadows
- Card: `rgba(0,0,0,0.22) 3px 5px 30px 0px`
- Nav glass: `backdrop-filter: saturate(180%) blur(20px)`

## Buttons
- **Primary CTA**: bg `#0071e3`, white text, padding 8px 15px, radius 8px
- **Secondary pill**: transparent bg, 1px border `#0066cc`, radius 980px, text `#0066cc`
- **Search/filter**: bg `#fafafc`, 3px border `rgba(0,0,0,0.04)`, radius 11px

## Components / Motion
- Cards: `#f5f5f7` bg (light), no borders, radius 8px
- Nav: translucent dark glass, 48px height, white 12px text
- Focus: 2px solid `#0071e3` outline (accessibility)
- Products shown on solid-color fields only
- Sections alternate black / light gray for cinematic rhythm
