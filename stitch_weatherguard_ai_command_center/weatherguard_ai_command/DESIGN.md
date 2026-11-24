---
name: WeatherGuard AI Command
colors:
  surface: '#fbf8fc'
  surface-dim: '#dcd9dd'
  surface-bright: '#fbf8fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f2f7'
  surface-container: '#f0edf1'
  surface-container-high: '#eae7eb'
  surface-container-highest: '#e4e1e6'
  on-surface: '#1b1b1e'
  on-surface-variant: '#434655'
  inverse-surface: '#303033'
  inverse-on-surface: '#f3f0f4'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#712ae2'
  on-secondary: '#ffffff'
  secondary-container: '#8a4cfc'
  on-secondary-container: '#fffbff'
  tertiary: '#006242'
  on-tertiary: '#ffffff'
  tertiary-container: '#007d55'
  on-tertiary-container: '#bdffdb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#eaddff'
  secondary-fixed-dim: '#d2bbff'
  on-secondary-fixed: '#25005a'
  on-secondary-fixed-variant: '#5a00c6'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#fbf8fc'
  on-background: '#1b1b1e'
  surface-variant: '#e4e1e6'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.015em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  mono-metric:
    fontFamily: JetBrains Mono
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.03em
  mono-code:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: -0.01em
  mono-telemetry:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-caps:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system is engineered for mission-critical extreme weather intelligence, situational crisis triage, and AI-driven atmospheric prediction. Built for researchers, municipal disaster management authorities, and field operatives, the visual voice projects institutional authority, absolute technical precision, and hyper-focused calm during emergency conditions. 

The aesthetic is anchored in **Editorial Scientific Precision** paired with **High-Density Technical Utility**:
- High-contrast structure without sensory fatigue: Jet-black framing chrome frames crisp, paper-like data surfaces.
- Strictly functional accents: Color functions exclusively as semantic telemetry, atmospheric state indication, or algorithmic lineage.
- Scientific cartographic discipline: Pale Positron-inspired spatial canvases allow multi-layered atmospheric tensor fields, radar contours, and geospatial vector assets to take center stage without visual competition.
- Absolute rejection of consumer tropes: No glossy sky gradients, skeuomorphic cloud icons, or glowing cyberpunk accents. Instead, the UI favors clinical gauges, monospaced coordinate matrices, topological contours, and restrained structural dividers.

## Colors

The color architecture enforces a strict hierarchy where decorative color is prohibited and all hues convey semantic urgency, computational lineage, or interactive affordance.

### Foundation & Surfaces
- **Canvas Base (`#FFFFFF`)**: The core analytical viewport and primary dashboard canvas.
- **Dark Chrome (`#0A0A0A`)**: Frame elements including the top situational masthead, persistent tool docks, operational status bars, and high-impact control triggers.
- **Secondary Surface (`#F4F4F5`)**: Recessed card containers, telemetry groupings, tabular row striping, and inactive tool trays.
- **Structural Border (`#E4E4E7`)**: Hairline boundary lines establishing visual isolation across dense analytical modules.

### Typography & Content
- **Text Primary (`#18181B`)**: Metric values, active labels, body prose, and core table entries.
- **Text Muted (`#71717A`)**: Unit labels, timestamp labels, coordinate descriptors, inactive tabs, and field keys.

### Chromatic Signals & Semantics
- **Primary Interactive (`#2563EB` - Electric Blue)**: Pipeline progression, interactive control active states, selection brackets, and active GIS layer filters.
- **Intelligence & Algorithmic Lineage (`#7C3AED` - Deep Violet)**: Exclusively designated for Graph Neural Networks (GNN), diffusion-model ensemble nodes, physics-loss monitors, and citizen AI explainability models. It never denotes generic application states.
- **Physics Validation & Nominal State (`#10B981` - Emerald Green)**: Hydrodynamic equation convergence, live sensor health checks, nominal sensor stream pings, and validated telemetry.

### Atmospheric Severity Gradient
Severity indicators must adhere to strict deterministic intervals across heatmaps, alert ribbons, and isobar vectors:
- **Advisory / Elevated (`#FACC15`)**: Low-to-moderate atmospheric instability.
- **Warning / Severe (`#F97316`)**: Rapid barometric drops, high-velocity wind shear, flash flood thresholds.
- **Emergency / Extreme (`#DC2626`)**: Critical cyclonic intensity, landfall trajectory, immediate evacuation zones.

## Typography

The type system creates an explicit operational bifurcation between human prose and machine telemetry:

- **Primary Interface (Inter)**: Handles conversational briefings, situational synopses, procedural directives, action triggers, and operational headers. Tracking is slightly tightened across large scale headers to retain high-density authority.
- **Machine Telemetry & Scientific Notation (JetBrains Mono)**: Handles geospatial coordinates (lat/long), micro-barometric readouts, GNN confidence coefficients, ISO-8601 UTC timestamps, and tensor dimensions. It provides fixed tabular figures (`tnum`) to eliminate layout jitter during high-frequency live data streams.
- **Micro Labels (`label-caps`)**: All-caps micro headers applied to metric tiles and inspection panes must be styled with wide tracking (`0.08em`) to guarantee quick recognition under high-stress command environments.

## Layout & Spacing

The layout employs a high-density, multi-pane command architecture structured to present large volumes of spatial and tabular information without vertical scroll thrashing.

### Grid & Composition Strategy
- **Command Shell**: Desktop layouts pin a global high-contrast masthead (`48px` height) across the top, paired with an asymmetrical three-tier layout:
  - **Left Rail (320px - 380px fixed)**: Geospatial layer switches, GNN hyperparameter controls, and temporal step playback.
  - **Central Viewport (Fluid)**: CartoDB Positron style pale basemap canvas hosting vector contours, wind particle trajectories, and sensor pins.
  - **Right Inspector (360px - 440px fixed or collapsible)**: Deep telemetry feed, physics-informed model validation matrices, and citizen-impact risk scores.
- **Vertical Spacing Rhythm**: Dense interfaces demand predictable micro-rhythms. Internal component padding relies on `space-sm` (`8px`) and `space-md` (`16px`). Section breaks within inspection cards strictly utilize `space-lg` (`24px`).

### Breakpoints & Adaptive Reflow
- **Mobile (< 768px)**: Refits the multi-pane grid into an inspection sheet over a dynamic map viewport. Sidebars become bottom sheets with an active drag handle. Margins drop to `space-md` (`1rem`).
- **Tablet (768px - 1199px)**: Left rail collapses into an iconified docking strip (`64px`); right inspector becomes a drawer toggle to maximize geospatial canvas area.
- **Desktop (1200px+)**: Simultaneous 3-column triage operational view with persistent telemetry streams and live sub-second rendering.

## Elevation & Depth

To preserve scientific rigor and cartographic legibility, this design system avoids heavy drop shadows, neon glows, and muddy blurs. Spatial depth is achieved using **hairline boundaries (`#E4E4E7`)**, **stark structural contrast**, and **subtle surface stacking**:

1. **Level 0 (Base Canvas)**: Raw `#FFFFFF` surface or CartoDB Positron pale neutral basemap. Serves as the substrate for spatial vectors.
2. **Level 1 (Card Modules & Panels)**: `#FFFFFF` or `#F4F4F5` container surfaces delineated by a solid `1px` border (`#E4E4E7`). No ambient shadow is applied under nominal states.
3. **Level 2 (Hover & Active Context Panes)**: Contextual tooltips, coordinate pins, and popover inspection menus receive an ultra-fine, highly diffused technical shadow: `0px 4px 12px rgba(10, 10, 10, 0.05)`, encased in a `1px` border (`#E4E4E7`).
4. **Level 3 (Dark Chrome HUD & Operational Chrome)**: `#0A0A0A` elements (top masthead, timeline controller dock, main navigation hubs) sit elevated by absolute tonal contrast against pale canvases. They cast no drop shadows, maintaining an integrated architectural presence.

## Shapes

The design system adopts a unified geometric identity centered on **precise 16px radius cards** framed by hyper-crisp micro-elements:

- **Primary Cards & Containers (`16px / 1rem`)**: All floating telemetry tiles, analytical cards, situational overviews, and map-overlay panels strictly apply `border-radius: 16px`. This softens dense quantitative dashboards into distinct, readable clusters.
- **Inner Interactive Controls (`8px / 0.5rem`)**: Buttons, input bars, filter pills, dropdown triggers, and status chips inside cards employ a reduced `8px` radius to maintain nested geometric proportion.
- **Structural Tags & Badges (`4px / 0.25rem`)**: Geospatial coordinates, coordinate bounding boxes, and mono-telemetry chips feature sharp, nearly squared `4px` corners, signaling mechanical and technical data points.

## Components

### Buttons & Interactive Controls
- **Command Primary**: `#0A0A0A` background, `#FFFFFF` text, `8px` radius, hover: `#18181B`. Used for irrevocable operational actions (e.g., "Deploy Alert", "Export Model").
- **Interactive Blue (`#2563EB`)**: Used exclusively for simulation controls (e.g., "Run GNN Ensemble", "Sync Radar Stream"). Active states employ `2px` inset focus rings.
- **Secondary / Ghost**: `#FFFFFF` background, `1px` border (`#E4E4E7`), `#18181B` text. Hover shifts to `#F4F4F5`.

### Cards & Telemetry Tiles
- Encapsulated within `16px` border radii with `1px` border (`#E4E4E7`).
- Card headers feature an editorial split layout: uppercase label in Inter (`label-caps`, `#71717A`) paired with live status indicators on the right.
- High-priority metrics feature JetBrains Mono (`mono-metric`, `#18181B`) with inline units styled in muted text (`body-sm`, `#71717A`).

### AI & Deep Model Architecture Containers
- Distinctly identified with a top or left boundary accent in `#7C3AED` (Violet).
- Houses model-specific telemetry: loss convergence charts, diffusion denoising steps, citizen validation confidence, and attention weights.
- Explainer chips within these containers use `#7C3AED` tinting (`rgba(124, 58, 237, 0.08)`) with violet text and mono telemetry notation.

### Severity Badges & Alert Ribbons
- **Warning Ribbon**: Full-width or card-anchored notification with a solid left border (`4px`) corresponding directly to severity level:
  - Yellow: `#FACC15` | Orange: `#F97316` | Red: `#DC2626`
- **Telemetry Pills**: Solid `#FFFFFF` fill with a `1px` tinted border and a pulsating `6px` live-status dot representing sensor validity and physics conservation adherence (`#10B981`).

### Form Elements & Parameter Sliders
- Inputs utilize `#FFFFFF` backgrounds with crisp `#E4E4E7` borders, transitioning to `#2563EB` on focus with zero fuzzy glow.
- Parameter adjustment sliders (e.g., simulation time horizon, ensemble size) feature fine `#E4E4E7` track lines, an active `#2563EB` fill, and an `#0A0A0A` circular thumb with a monospaced readout pinned above.

### Map Dock & Playback Timeline
- Positioned as a floating horizontal dock anchored at the bottom-center of the viewport.
- Styled in dark chrome `#0A0A0A` with `16px` corner rounding.
- Houses high-contrast playback controls (Play/Pause, scrub bar, step-frame forwards/backwards), timestamp scrubber formatted in JetBrains Mono (`UTC+05:30`), and instant precipitation/wind layer toggles.