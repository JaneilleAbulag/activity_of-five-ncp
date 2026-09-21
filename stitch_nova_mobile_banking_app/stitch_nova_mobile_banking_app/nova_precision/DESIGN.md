---
name: Nova Precision
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#44474d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#75777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#4d5f7d'
  primary: '#000615'
  on-primary: '#ffffff'
  primary-container: '#0b1f3a'
  on-primary-container: '#7587a7'
  inverse-primary: '#b5c7ea'
  secondary: '#006b5f'
  on-secondary: '#ffffff'
  secondary-container: '#6df5e1'
  on-secondary-container: '#006f64'
  tertiary: '#000710'
  on-tertiary: '#ffffff'
  tertiary-container: '#002136'
  on-tertiary-container: '#1f8dd1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b5c7ea'
  on-primary-fixed: '#071c36'
  on-primary-fixed-variant: '#364764'
  secondary-fixed: '#71f8e4'
  secondary-fixed-dim: '#4fdbc8'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005048'
  tertiary-fixed: '#cce5ff'
  tertiary-fixed-dim: '#93ccff'
  on-tertiary-fixed: '#001d31'
  on-tertiary-fixed-variant: '#004b73'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Inter
    fontSize: 34px
    fontWeight: '700'
    lineHeight: 41px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 17px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  label-lg:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.02em
  numeric-hero:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.03em
  numeric-balance:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system establishes an architectural, high-trust digital banking experience. It pairs institutional solidity with modern technical agility. The aesthetic is strictly minimalist and structural, drawing heavily from contemporary iOS Human Interface Guidelines while elevating tactile clarity through soft, high-fidelity surfaces.

The visual tone eliminates ornamental distractions in favor of extreme clarity, deliberate whitespace, and crisp visual hierarchy. The emotional target is calm confidence, security, and effortless precision—ensuring users immediately perceive their financial data as organized, safe, and actionable.

## Colors

The palette is engineered for financial clarity and strict accessibility compliance (WCAG 2.1 AA+).

- **Primary (`#0B1F3A`)**: Deep Navy Blue serves as the institutional foundation. It anchors headers, high-emphasis text, primary action buttons, and dominant brand surfaces.
- **Secondary (`#14B8A6`)**: Bright Teal provides deliberate, high-energy accents. It is reserved for key interactions, success states, positive financial trends, and active indicators.
- **Tertiary (`#0284C7`)**: Precision Slate Blue handles secondary utility, links, and informational callouts without competing with the primary teal accent.
- **Neutral (`#64748B`)**: Cool Slate provides balanced low-contrast supporting text, borders, and inactive UI states.

### Surface System
- **Canvas / Background**: `#F7F9FC` (Soft Off-White).
- **Surface Level 1 (Cards, Sheets)**: `#FFFFFF` (Pure White).
- **Surface Level 2 (Dividers, Inactive Inputs)**: `#E2E8F0`.
- **Surface Subtle (Pressed, Tonal Fills)**: `#F1F5F9`.

Ensure active tap states preserve minimum 4.5:1 contrast ratios against card and canvas surfaces. Use `#14B8A6` selectively against `#0B1F3A` or white surfaces to retain maximum legibility.

## Typography

Typography relies entirely on **Inter** to ensure maximum legibility at variable sizes, precise tabular rendering, and systematic weight distribution.

- **Tabular Figures**: Enable font-variant numeric tabular figures (`tnum`) across all monetary tables, balance indicators, transaction rows, and timestamps to preserve columnar alignment.
- **Hierarchy Rules**: Primary headers and currency sums use tight negative tracking (`-0.01em` to `-0.03em`) to anchor the eye. Metadata and labels under 13px utilize slight positive tracking (`+0.01em` to `+0.02em`) for optical readability.
- **Dynamic Type**: Text sizes conform to iOS Dynamic Type defaults. Ensure text containers allow up to 200% scaling without truncating critical currency balances or action controls.

## Layout & Spacing

The layout system is mobile-first, operating on an explicit 4px baseline and 8px component pacing structure.

- **Mobile Canvas**: Uses a fluid single-column layout constrained by a `1rem` (16px) outer margin and safe-area insets.
- **Section Stack**: Content cards and vertical sections space out with `1rem` (16px) or `1.5rem` (24px) vertical rhythms to preserve air and scanning efficiency.
- **Touch Target Integrity**: All tap targets enforce a strict minimum physical size of 44×44pt, regardless of visual asset boundaries.
- **Adaptive Breakpoints**:
  - `Mobile (320px - 599px)`: 4 columns, 16px margins, fluid horizontal cards.
  - `Tablet (600px - 1023px)`: 8 columns, 24px margins, structured dual-card grids for accounts and recent transactions.
  - `Desktop (1024px+)`: 12 columns, maximum container width of 1120px centered, split view with navigation/summary pinned on the left.

## Elevation & Depth

Depth is established through subtle ambient occlusion combined with micro-borders, avoiding harsh drop shadows or skeuomorphic bevels.

- **Flat Canvas**: `#F7F9FC` serves as the ground plane.
- **Level 1 (Cards, List Groups, Sheets)**:
  - Background: `#FFFFFF`.
  - Border: 1px solid `rgba(11, 31, 58, 0.06)`.
  - Ambient Shadow: `0px 2px 8px rgba(11, 31, 58, 0.04), 0px 1px 2px rgba(11, 31, 58, 0.02)`.
- **Level 2 (Popovers, Active Dropdowns, Floating Action Bars)**:
  - Background: `#FFFFFF`.
  - Border: 1px solid `rgba(11, 31, 58, 0.08)`.
  - Ambient Shadow: `0px 8px 24px rgba(11, 31, 58, 0.08), 0px 2px 6px rgba(11, 31, 58, 0.04)`.
- **Level 3 (Modals, Alerts)**:
  - Background: `#FFFFFF`.
  - Scrim: `rgba(11, 31, 58, 0.40)` backdrop blur `8px`.
  - Ambient Shadow: `0px 16px 36px rgba(11, 31, 58, 0.16)`.

## Shapes

The geometric architecture relies on consistent 16px (`1rem`) rounding for primary containers, balanced by proportional nested curves.

- **Primary Cards & Modals**: `1rem` (16px) corner radius (`rounded-lg`).
- **Inner Embedded Containers**: `0.5rem` (8px) corner radius to ensure uniform nested concentricity.
- **Interactive Controls (Inputs, Primary Buttons)**: `0.75rem` (12px) to `1rem` (16px) depending on height hierarchy.
- **Small Chips & Badges**: Fully pill-shaped (`9999px`) for functional visual separation from structural cards.

## Components

### Buttons
- **Primary Button**: Background `#0B1F3A`, foreground `#FFFFFF`, minimum height 48px, border-radius 12px. Pressed state: `#152E52`. Focused: 2px ring `#14B8A6`.
- **Accent Button**: Background `#14B8A6`, foreground `#FFFFFF`, minimum height 48px, border-radius 12px. Used exclusively for positive primary flows (e.g., "Send Money", "Deposit").
- **Secondary / Tertiary Button**: Background `#FFFFFF`, 1px border `rgba(11, 31, 58, 0.12)`, text `#0B1F3A`. Minimum height 48px.

### Cards
- **Account Summary Card**: Pure white fill, 16px border-radius, 16px inner padding. Displays account classification, masking number in secondary slate, current balance in `numeric-balance`, and available balance below.
- **Transaction Card**: Grouped in an inset grouped list container with white fill, 16px radius, and single-pixel dividers (`rgba(11, 31, 58, 0.06)`) that inset to align with the text edge.

### Input Fields
- Minimum height 52px, surface fill `#FFFFFF`, 1px border `rgba(11, 31, 58, 0.15)`, radius 12px, padding 12px 16px.
- Floating or fixed micro-label in `label-sm` (`#64748B`). Active focus transitions border to 1.5px `#0B1F3A` with a subtle 3px outer glow `rgba(20, 184, 166, 0.2)`.

### Chips & Badges
- Height 28px–32px, pill-shaped radius. Active chips use `#0B1F3A` with `#FFFFFF` text. Filter/inactive chips use `#F1F5F9` with `#64748B` text. Status badges for transactions: Green `#E6F8F5` with `#0F766E` text for deposits; Neutral `#F1F5F9` with `#475569` text for charges.

### Selection Controls
- **Checkboxes & Radios**: 20×20px box with a 44×44px hit-box envelope. Inactive: 1.5px border `#94A3B8`. Active: `#0B1F3A` fill with white check/dot.
- **Switches**: iOS standard 51×31px footprint. Inactive track `#CBD5E1`, active track `#14B8A6`, thumb `#FFFFFF` with standard iOS drop shadow.

### Financial Data Displays
- **Currency Stat Blocks**: Pair currency symbols in small weights with large tabular numerals (`tnum`). Include a directional trend tag (`+2.4%`) encased in a soft pill container directly adjacent to historical metrics.