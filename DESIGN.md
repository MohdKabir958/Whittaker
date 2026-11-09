---
name: Trade Contractor Pro
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353942'
  surface-container-lowest: '#0a0e16'
  surface-container-low: '#181c24'
  surface-container: '#1c2028'
  surface-container-high: '#262a33'
  surface-container-highest: '#31353e'
  on-surface: '#dfe2ee'
  on-surface-variant: '#d8c3ad'
  inverse-surface: '#dfe2ee'
  inverse-on-surface: '#2c3039'
  outline: '#a08e7a'
  outline-variant: '#534434'
  surface-tint: '#ffb95f'
  primary: '#ffc174'
  on-primary: '#472a00'
  primary-container: '#f59e0b'
  on-primary-container: '#613b00'
  inverse-primary: '#855300'
  secondary: '#76d5de'
  on-secondary: '#00363b'
  secondary-container: '#01818a'
  on-secondary-container: '#f5feff'
  tertiary: '#56e5a9'
  on-tertiary: '#003824'
  tertiary-container: '#30c88f'
  on-tertiary-container: '#004e34'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffddb8'
  primary-fixed-dim: '#ffb95f'
  on-primary-fixed: '#2a1700'
  on-primary-fixed-variant: '#653e00'
  secondary-fixed: '#93f1fb'
  secondary-fixed-dim: '#76d5de'
  on-secondary-fixed: '#002022'
  on-secondary-fixed-variant: '#004f55'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#0f131c'
  on-background: '#dfe2ee'
  surface-variant: '#31353e'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  price-headline:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 32px
    letterSpacing: -0.02em
  price-sub:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style
The design system embodies an **Industrial Luxury** aesthetic tailored for trade contractors, site managers, and master tradespeople across the Isle of Man. It merges the rugged, no-nonsense utility demanded by heavy-duty commercial construction with the refined precision and ergonomics of a premier distributor. Rooted in heritage since 1983, the UI conveys durability, speed, and immediate fiscal clarity. 

Visual density is optimized for high-paced job-site and counter pickups:
- Tactical contrast ensures extreme readability under direct sunlight or harsh site floodlights.
- Touch ergonomics mirror physical tool safety and handling, strictly adhering to a 48px minimum target threshold.
- The interface emphasizes hardware-level precision—clean delineation of technical specifications, battery compatibility ecosystems (XR / LXT / XGT), and stock reliability.

## Colors
The palette balances industrial utility with dark-mode refinement:

- **Base Surfaces**: Deep Matte Charcoal (`#0B0F17`) acts as the absolute canvas, mitigating field glare and saving battery. Layered surfaces transition to Dark Slate (`#161F2E`) for cards and elevated panels, bounded cleanly by low-luster structural borders (`#243044`).
- **Primary Brand Accent (DeWalt Industrial Gold/Yellow)**: `#F59E0B` (resting state), `#EAB308` (active/hover), and `#D97706` (pressed/focused). Reserved exclusively for primary transactional actions, active state toggles, key price figures, and vital badge callouts.
- **Secondary Accent (Makita Marine Teal)**: `#00818A` is used selectively for certified partner badging, multi-voltage system labels, and secondary system telemetry.
- **Tertiary Accent (Stock Emerald)**: `#10B981` signals live stock, counter inventory availability, and confirmed order dispatch.
- **Text & Hierarchy**: Primary labels leverage Crisp Off-White (`#F8FAFC`), secondary trade specs use Muted Steel (`#94A3B8`), and sub-text/Inc. VAT uses Slate Grey (`#64748B`).

## Typography
Typography is split purposefully between structural impact and high-density technical utility:

- **Headlines & Prices (Plus Jakarta Sans)**: Rendered in bold, muscular weights (`700` and `800`) with tight tracking for model designations, promotional banners, and commercial pricing.
- **Body & Technical Data (Inter)**: Handles specification matrices, tool voltage ratings, motor specifications, and inventory tables with clean tabular numerals (`tnum`).
- **Trade Pricing Format**: 
  - Trade Ex. VAT figures are rendered with `price-headline` in `#F59E0B`.
  - Secondary retail Inc. VAT values are rendered adjacent or directly underneath in `price-sub` using `#94A3B8`, clearly marked "Inc. VAT".

## Layout & Spacing
The layout employs an ultra-stable fluid grid designed for rapid scanning on handheld devices and robust desktop procurement sessions:

- **Mobile Viewports (<768px)**: 4-column layout with `1rem` margins and `1rem` gutters. Optimized for single-thumb operations; bottom-anchored actions and filters.
- **Tablet / Counter POS Viewports (768px - 1024px)**: 8-column layout with `1.5rem` margins and gutters. Accommodates two-up product comparisons and split-screen cart verification.
- **Desktop & Trade Portal Viewports (>1024px)**: 12-column fixed-max layout (max width 1440px) with `2rem` outer margins. Accommodates deep category sidebars, cross-reference tables, and mass SKU entry grids.
- **Spacing Rhythm**: A strict 4px/8px micro-grid underpins internal card paddings, list row separations, and touch target bounds.

## Elevation & Depth
Visual hierarchy relies on structural layered planes and subtle edge lighting rather than diffuse, soft drop shadows:

- **Surface Tier 0 (Canvas)**: `#0B0F17` (Deep Matte Charcoal), zero blur, zero elevation.
- **Surface Tier 1 (Cards, Product Tiles)**: `#161F2E` (Dark Slate) paired with a 1px perimeter stroke of `#243044`.
- **Surface Tier 2 (Flyouts, Quick-Order Sheets, Pick-up Modals)**: `#1E293B` bordered with `#334155`, casting a high-definition ambient shadow (`0 12px 32px rgba(0, 0, 0, 0.65)`).
- **Tactile State Cues**: Interactive controls omit skeuomorphic gradients in favor of razor-sharp border highlights—focused inputs and selected filter tags gain a 1.5px stroke of `#F59E0B`.

## Shapes
A disciplined, low-radius shape language reinforces mechanical durability:

- Standard elements (buttons, inputs, trade badges, cards) maintain a 4px (`0.25rem`) border radius, communicating engineered robustness.
- Modal panels and full-screen bottom sheets utilize an 8px (`0.5rem`) top radius.
- Circular radii are strictly confined to status indicator pips (e.g., live stock beacons) and numeric quantity steppers.

## Components

### Buttons & Quick Order Actions
- **Primary ("Add to Van / Trade Account")**: Background `#F59E0B`, text `#0B0F17` (Inter Bold, 14px), 48px fixed height. Active state transitions to `#D97706`.
- **Secondary ("Technical Spec Sheet / Reserve")**: Background `#161F2E`, border 1px solid `#243044`, text `#F8FAFC`. Focus/Hover adds border `#F59E0B`.
- **Destructive**: Outline border with `#EF4444` and text `#EF4444`.

### Trade Chips & Filter Badges
- **Battery Platform Filters (XR 18V, FLEXVOLT 54V, LXT 18V, XGT 40V)**: Background `#161F2E`, border 1px `#243044`, height 36px. Selected state switches background to `#F59E0B` with `#0B0F17` text.
- **Partner Badges**: DeWalt badges use `#F59E0B` micro-accents; Makita uses `#00818A` badge containers with white typography.

### Input Fields & Steppers
- **SKU Search & Account Field**: Minimum height 48px. Fill `#0F172A`, 1px border `#243044`, text `#F8FAFC`. Active state produces an immediate 1.5px `#F59E0B` stroke with no ambient spread.
- **Bulk Pack Quantity Stepper**: Left/right 48px square buttons with physical `+` and `-` glyphs framing a centered tabular numeric input.

### Dual VAT Price Block Component
- Prominent dual-line lockup:
  - Line 1: `£349.00` in Plus Jakarta Sans 800, `#F59E0B`, paired with a compact `EX. VAT` tag.
  - Line 2: `£418.80 inc. VAT` in Inter 500, `#94A3B8`.

### Live Stock Indicator
- Horizontal micro-badge: 8px solid disc in `#10B981` (pulsing subtly when stock is `<5`) paired with bold 12px label `In Stock - Douglas Trade Counter` or `Next Day Delivery Island-wide`.