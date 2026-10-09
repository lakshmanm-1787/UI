---
name: Kinetic Transit
colors:
  surface: '#f7f9fc'
  surface-dim: '#d8dadd'
  surface-bright: '#f7f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f7'
  surface-container: '#eceef1'
  surface-container-high: '#e6e8eb'
  surface-container-highest: '#e0e3e6'
  on-surface: '#191c1e'
  on-surface-variant: '#5a403f'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f4'
  outline: '#8e706e'
  outline-variant: '#e2bebc'
  surface-tint: '#b6212e'
  primary: '#b31e2c'
  on-primary: '#ffffff'
  primary-container: '#d63941'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb3b0'
  secondary: '#535f75'
  on-secondary: '#ffffff'
  secondary-container: '#d4e0fb'
  on-secondary-container: '#57637a'
  tertiary: '#b10e6b'
  on-tertiary: '#ffffff'
  tertiary-container: '#d23285'
  on-tertiary-container: '#fffcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3b0'
  on-primary-fixed: '#410006'
  on-primary-fixed-variant: '#93001a'
  secondary-fixed: '#d7e3fe'
  secondary-fixed-dim: '#bbc7e1'
  on-secondary-fixed: '#0f1c2f'
  on-secondary-fixed-variant: '#3b475d'
  tertiary-fixed: '#ffd9e4'
  tertiary-fixed-dim: '#ffb0cd'
  on-tertiary-fixed: '#3e0022'
  on-tertiary-fixed-variant: '#8c0053'
  background: '#f7f9fc'
  on-background: '#191c1e'
  surface-variant: '#e0e3e6'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
  display-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 38px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
  mono-seat:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system powers an online travel booking ecosystem designed to eliminate uncertainty from intercity transit. It combines corporate reliability with high-efficiency booking workflows. The aesthetic merges modern utility with functional warmth, leveraging clear typographic hierarchies, instant feedback states, and structured micro-surfaces.

### Core Philosophy
- **Effortless Discovery**: Complex routing, schedules, and pricing matrices are parsed into frictionless visual chunks.
- **High Information Density with Generous Air**: Critical trip details (departure times, boarding points, operator ratings, seat availability) remain scanning-friendly through disciplined spacing and contrast boundaries.
- **Reassurance & Safety First**: Explicit color accents for female-only seating allocations, on-time punctuality rates, and clear cancellation policies foster user trust.

### Design Style
The system employs a refined modern card-based framework with tactile surfaces: crisp 1px perimeter outlines, warm ambient drop-shadows, generous border radii, and elevated interactive states designed specifically for rapid mobile-first conversions.

## Colors

The palette balances urgency, trustworthiness, and functional utility across diverse ambient contexts (from direct sunlight bus stands to dim night journeys).

### Primary & Brand Identity
- **Primary Red (`#D63941`)**: High-visibility booking action points, search submissions, dynamic price highlights, and selected active journey markers. Hover state sits at `#B82830`; pressed state at `#9B1D24`.
- **Navy Secondary (`#172337`)**: Anchors global headers, footer environments, heavy route headers, and bus class indicators (e.g., Sleeper, Multi-Axle, Executive).

### Semantic & Operational
- **Female-Reserved Pink (`#EC4899`)**: Dedicated semantic reservation token for female-only berths, seats, and reassurance messaging. Tints to `#FCE7F3` for seat background badges.
- **Success Emerald (`#10B981`)**: Confirmed reservations, on-time indicators, refundable tags, and live tracking pings.
- **Warning Amber (`#F59E0B`)**: Fast-filling trip alerts ("Only 2 seats left"), boarding time warnings, and delay notices.

### Background & Neutral Surface
- **Surface Canvas (`#F5F7FA`)**: Soft cool base preventing eye strain across dense inventory grids.
- **Surface Raised (`#FFFFFF`)**: Pure card backgrounds, modals, input containers, and seat map overlays.
- **Text Hierarchy**: Slate `#1F2937` (Primary Headings/Prices), Slate `#4B5563` (Body & Durations), Slate `#9CA3AF` (Placeholders & Secondary Metadata).

## Typography

The typography couples geometric vitality with systematic, tabular precision.

- **Plus Jakarta Sans**: Drives structural landmarks, conversion headers, pricing figures, and interaction targets. Its modern terminal curves infuse energy into standard booking interfaces.
- **Inter**: Powers travel itineraries, vehicle amenities, review passages, and legal clauses. Inter’s vertical metrics guarantee exceptional legibility across numeric boarding times and terminal names.
- **Tabular Numerals (`font-variant-numeric: tabular-nums`)**: Enforced globally on currency values, arrival/departure timestamps, duration badges, and seat identifiers to eliminate horizontal jitter during dynamic filtering and sorting.

## Layout & Spacing

The layout is built upon an 8-point base grid, adapting to a 4-point sub-grid for compact density in seat selection matrices and amenity pills.

### Grid Breakpoints & Architecture
- **Desktop (1200px+)**: 12-column layout. Search modification bar pinned at top; split screen during seat selection (40% seat layout deck, 60% passenger & fare summary deck).
- **Tablet (768px - 1199px)**: 8-column layout. Gutter adjusts to 1rem. Collapsible search filters via overlay sheet.
- **Mobile (Below 768px)**: 4-column layout. Edge gutters collapse to 0.75rem (`gutter-mobile`). Search triggers, route timelines, and primary booking buttons dock inside a sticky mobile viewport baseline with safe-area hardware padding.

### Spacing Principles
Component internals apply `space-sm` (8px) and `space-md` (16px) tokens to preserve scanning momentum across dense schedule listings, while major layout card groupings separate via `space-lg` (24px) to avoid visual clustering.

## Elevation & Depth

This system avoids heavy, muddy drop shadows in favor of ambient multi-stop shadow casting combined with soft borders, ensuring elements pop distinctly over the neutral `#F5F7FA` canvas.

### Depth Scales
- **Surface Tier 0 (Base Canvas)**: Flat `#F5F7FA` with no elevation.
- **Surface Tier 1 (Inventory Cards, Filter Modules)**: Background `#FFFFFF`, 1px outline in `#E5E7EB`, layered with ambient shadow: `0 1px 3px 0 rgba(23, 35, 55, 0.04), 0 1px 2px -1px rgba(23, 35, 55, 0.02)`.
- **Surface Tier 2 (Hovered Inventory Card, Dropdowns, Date Pickers)**: Elevated focus with `0 10px 15px -3px rgba(23, 35, 55, 0.08), 0 4px 6px -4px rgba(23, 35, 55, 0.04)`, primary border shifting to `#CBD5E1`.
- **Surface Tier 3 (Seat Selection Drawers, Floating Bottom Bar)**: Raised interaction state with `0 20px 25px -5px rgba(23, 35, 55, 0.1), 0 8px 10px -6px rgba(23, 35, 55, 0.06)`.
- **Surface Tier 4 (Emergency Alerts, Booking Confirm Modals)**: Centered focal projection with `0 25px 50px -12px rgba(23, 35, 55, 0.25)`.

## Shapes

The interface embraces generous, modern curvatures that feel friendly, approachable, and ergonomically tactile on mobile touchscreens.

- **Base Radius (`0.5rem` / 8px)**: Applied to input fields, dropdown trigger targets, seat status indicators, and operational amenity icons.
- **Container Radius (`rounded-lg` / 1rem / 16px)**: Applied to primary travel cards, filter clusters, itinerary timeline markers, and modal sheets.
- **Macro Radius (`rounded-xl` / 1.5rem / 24px)**: Applied to primary search widgets, bottom booking interaction sheets, and highlight hero banners.
- **Pill (`9999px`)**: Reserved exclusively for dynamic status chips (e.g., "Fastest Route", "AC Sleeper 2+1", "Female Only"), pagination steps, and micro amenity tags.

## Components

### Buttons & Interactive Controls
- **Primary CTA**: Background `#D63941`, text `#FFFFFF`, font `label-lg`, height 48px, radius 8px (`rounded-base`). Hover scales to `#B82830`; active state uses a 0.98 scale transition.
- **Secondary Action**: Border 1.5px solid `#172337`, background transparent, text `#172337`. Hover fills with `#172337` and white text.
- **Ghost/Tertiary**: Text `#4B5563`, radius 8px, hover background `#E5E7EB`.

### Travel Inventory & Booking Cards
- **Structure**: Surface `#FFFFFF`, border 1px solid `#E5E7EB`, radius 16px (`rounded-lg`), ambient padding `space-lg`.
- **Timeline Display**: Departure time left-aligned in bold `headline-sm`, vertical journey dashed connector with total duration chip ("6h 30m"), arrival time right-aligned.
- **Seat Availability Indicators**: Highlighting available count with `#10B981` ("14 Seats Left") or urgency highlight `#F59E0B` when below 5 seats.

### Interactive Bus Seat Deck Matrix
- **Available Seat**: White background, 1.5px border `#9CA3AF`, radius 6px, numeric indicator inside.
- **Selected Seat**: Solid `#D63941` background, white text, drop shadow `0 2px 4px rgba(214, 57, 65, 0.3)`.
- **Booked (General)**: Disabled background `#E5E7EB`, border `#D1D5DB`, text `#9CA3AF`, cursor not-allowed.
- **Female-Reserved Seat**: Soft background `#FCE7F3`, border 1.5px solid `#EC4899`, female passenger glyph indicator.

### Badges & Chips
- **Contextual Tags**: Height 24px, pill-shaped (`9999px`), padding `0.25rem 0.75rem`, font `label-sm`.
- **Color Pairings**:
  - Punctuality/Eco: Background `#D1FAE5`, text `#065F46`.
  - Operator Rating: Background `#FEF3C7`, text `#92400E`, with integrated star icon.
  - Female Safety: Background `#FCE7F3`, text `#9D174D`.

### Form & Route Inputs
- **Base Fields**: Height 52px, surface `#FFFFFF`, border 1px solid `#D1D5DB`, radius 8px, text `body-lg`. Focus rings employ a 2px offset glow in `#D63941` at 20% opacity.
- **Swap Destination Action**: 36px floating circular button centered between "From" and "To" input fields with secondary navy icon `#172337`.