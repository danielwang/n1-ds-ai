---
version: 0.2.0-draft
name: N1 design system
description: Standalone, framework-neutral design specification. Observed N1 palette values inform a proposed light-theme
  baseline; semantic mappings, completed scales and behavior are adaptable defaults requiring design review.
colors:
  palette:
    white: '#ffffff'
    neutral-50: '#f9fafb'
    neutral-100: '#ecf0f3'
    neutral-200: '#dfe2e8'
    neutral-300: '#c4cdd5'
    neutral-400: '#919eab'
    neutral-600: '#637381'
    neutral-700: '#454f5b'
    neutral-800: '#212b36'
    neutral-900: '#161c24'
    blue-600: '#096adc'
    blue-700: '#1b76ac'
    cyan-500: '#44adda'
    purple-500: '#6b52a2'
    green-50: '#ecf8ef'
    green-700: '#07683b'
    green-900: '#024533'
    amber-50: '#fff5e8'
    amber-500: '#e88310'
    amber-800: '#a74d08'
    red-50: '#fdeef0'
    red-500: '#d82934'
    red-800: '#9b1435'
    blue-50: '#edf6fc'
    pink-600: '#d45087'
    overlay-50: '#161c2480'
    shadow-12: '#161c241f'
    shadow-20: '#161c2433'
    transparent: '#ffffff00'
  canvas: '{colors.palette.neutral-50}'
  surface: '{colors.palette.white}'
  surface-muted: '{colors.palette.neutral-100}'
  surface-sunken: '{colors.palette.neutral-200}'
  surface-inverse: '{colors.palette.neutral-900}'
  text: '{colors.palette.neutral-900}'
  text-secondary: '{colors.palette.neutral-700}'
  text-muted: '{colors.palette.neutral-600}'
  text-inverse: '{colors.palette.white}'
  text-disabled: '{colors.palette.neutral-600}'
  border: '{colors.palette.neutral-600}'
  border-hover: '{colors.palette.neutral-800}'
  border-subtle: '{colors.palette.neutral-300}'
  primary: '{colors.palette.neutral-600}'
  primary-hover: '{colors.palette.neutral-700}'
  primary-active: '{colors.palette.neutral-800}'
  on-primary: '{colors.palette.white}'
  secondary: '{colors.palette.cyan-500}'
  on-secondary: '{colors.palette.neutral-900}'
  hover: '{colors.palette.neutral-100}'
  selected: '{colors.palette.neutral-200}'
  disabled: '{colors.palette.neutral-100}'
  focus: '{colors.palette.blue-600}'
  focus-inverse: '{colors.palette.white}'
  focus-gap: '{colors.palette.white}'
  link: '{colors.palette.blue-700}'
  link-hover: '{colors.palette.blue-600}'
  link-visited: '{colors.palette.purple-500}'
  success: '{colors.palette.green-700}'
  success-surface: '{colors.palette.green-50}'
  success-text: '{colors.palette.green-900}'
  warning: '{colors.palette.amber-800}'
  warning-surface: '{colors.palette.amber-50}'
  warning-text: '{colors.palette.amber-800}'
  danger: '{colors.palette.red-500}'
  danger-hover: '{colors.palette.red-800}'
  danger-surface: '{colors.palette.red-50}'
  danger-text: '{colors.palette.red-800}'
  info: '{colors.palette.blue-700}'
  info-surface: '{colors.palette.blue-50}'
  info-text: '{colors.palette.blue-700}'
  overlay: '{colors.palette.overlay-50}'
  data-1: '{colors.palette.blue-600}'
  data-2: '{colors.palette.purple-500}'
  data-3: '{colors.palette.amber-800}'
  data-4: '{colors.palette.green-700}'
  data-5: '{colors.palette.pink-600}'
typography:
  primitives:
    sans:
    - Segoe UI
    - Helvetica Neue
    - Arial
    - sans-serif
    mono:
    - Consolas
    - Liberation Mono
    - monospace
    size:
      '12': 12px
      '14': 14px
      '15': 15px
      '16': 16px
      '18': 18px
      '20': 20px
      '24': 24px
      '32': 32px
      '40': 40px
    weight:
      regular: 400
      semibold: 600
      bold: 700
    line:
      '18': 18px
      '20': 20px
      '22': 22px
      '24': 24px
      '26': 26px
      '28': 28px
      '32': 32px
      '40': 40px
      '48': 48px
    tracking:
      normal: 0px
      tight: -0.4px
      small: 0.35px
  display:
    family: '{typography.primitives.sans}'
    size: '{typography.primitives.size.40}'
    weight: '{typography.primitives.weight.bold}'
    line-height: '{typography.primitives.line.48}'
    letter-spacing: '{typography.primitives.tracking.tight}'
  heading-1:
    family: '{typography.primitives.sans}'
    size: '{typography.primitives.size.32}'
    weight: '{typography.primitives.weight.bold}'
    line-height: '{typography.primitives.line.40}'
    letter-spacing: '{typography.primitives.tracking.normal}'
  heading-2:
    family: '{typography.primitives.sans}'
    size: '{typography.primitives.size.24}'
    weight: '{typography.primitives.weight.semibold}'
    line-height: '{typography.primitives.line.32}'
    letter-spacing: '{typography.primitives.tracking.normal}'
  heading-3:
    family: '{typography.primitives.sans}'
    size: '{typography.primitives.size.20}'
    weight: '{typography.primitives.weight.semibold}'
    line-height: '{typography.primitives.line.28}'
    letter-spacing: '{typography.primitives.tracking.normal}'
  heading-4:
    family: '{typography.primitives.sans}'
    size: '{typography.primitives.size.18}'
    weight: '{typography.primitives.weight.semibold}'
    line-height: '{typography.primitives.line.26}'
    letter-spacing: '{typography.primitives.tracking.normal}'
  body:
    family: '{typography.primitives.sans}'
    size: '{typography.primitives.size.16}'
    weight: '{typography.primitives.weight.regular}'
    line-height: '{typography.primitives.line.24}'
    letter-spacing: '{typography.primitives.tracking.normal}'
  body-small:
    family: '{typography.primitives.sans}'
    size: '{typography.primitives.size.14}'
    weight: '{typography.primitives.weight.regular}'
    line-height: '{typography.primitives.line.22}'
    letter-spacing: '{typography.primitives.tracking.normal}'
  label:
    family: '{typography.primitives.sans}'
    size: '{typography.primitives.size.14}'
    weight: '{typography.primitives.weight.semibold}'
    line-height: '{typography.primitives.line.20}'
    letter-spacing: '{typography.primitives.tracking.normal}'
  caption:
    family: '{typography.primitives.sans}'
    size: '{typography.primitives.size.12}'
    weight: '{typography.primitives.weight.regular}'
    line-height: '{typography.primitives.line.18}'
    letter-spacing: '{typography.primitives.tracking.normal}'
  control:
    family: '{typography.primitives.sans}'
    size: '{typography.primitives.size.14}'
    weight: '{typography.primitives.weight.semibold}'
    line-height: '{typography.primitives.line.20}'
    letter-spacing: '{typography.primitives.tracking.normal}'
  control-large:
    family: '{typography.primitives.sans}'
    size: '{typography.primitives.size.15}'
    weight: '{typography.primitives.weight.bold}'
    line-height: '{typography.primitives.line.26}'
    letter-spacing: '{typography.primitives.tracking.normal}'
spacing:
  '0': 0px
  '1': 1px
  '2': 2px
  '4': 4px
  '6': 6px
  '8': 8px
  '12': 12px
  '16': 16px
  '20': 20px
  '24': 24px
  '32': 32px
  '40': 40px
  '48': 48px
  '64': 64px
  '80': 80px
  '96': 96px
  inline-gap: '{spacing.8}'
  field-gap: '{spacing.8}'
  group-gap: '{spacing.24}'
  section-gap: '{spacing.40}'
  page-mobile: '{spacing.16}'
  page-tablet: '{spacing.24}'
  page-desktop: '{spacing.32}'
rounded:
  '0': 0px
  '4': 4px
  '8': 8px
  '12': 12px
  '16': 16px
  '9999': 9999px
  control: '{rounded.8}'
  surface: '{rounded.12}'
  overlay: '{rounded.16}'
  pill: '{rounded.9999}'
elevation:
  primitives:
    border-thin: 1px
    border-strong: 2px
    focus-width: 3px
    focus-gap: 2px
    layers:
      base: 0
      sticky: 10
      menu: 20
      backdrop: 30
      dialog: 40
      popover: 50
      tooltip: 60
      notification: 70
    shadows:
      flat:
        x: 0px
        y: 0px
        blur: 0px
        spread: 0px
        color: '{colors.palette.transparent}'
      raised:
        x: 0px
        y: 2px
        blur: 8px
        spread: 0px
        color: '{colors.palette.shadow-12}'
      floating:
        x: 0px
        y: 8px
        blur: 24px
        spread: 0px
        color: '{colors.palette.shadow-20}'
  flat: '{elevation.primitives.shadows.flat}'
  raised: '{elevation.primitives.shadows.raised}'
  floating: '{elevation.primitives.shadows.floating}'
  border-width: '{elevation.primitives.border-thin}'
  selected-width: '{elevation.primitives.border-strong}'
  focus-width: '{elevation.primitives.focus-width}'
  focus-gap: '{elevation.primitives.focus-gap}'
motion:
  primitives:
    duration:
      none: 0ms
      feedback: 120ms
      transition: 180ms
      entrance: 240ms
      exit: 160ms
      loading-delay: 200ms
      tooltip-delay: 500ms
      cycle: 1000ms
    easing:
      standard:
      - 0.2
      - 0
      - 0
      - 1
      enter:
      - 0
      - 0
      - 0.2
      - 1
      exit:
      - 0.4
      - 0
      - 1
      - 1
      linear:
      - 0
      - 0
      - 1
      - 1
  feedback: '{motion.primitives.duration.feedback}'
  transition: '{motion.primitives.duration.transition}'
  entrance: '{motion.primitives.duration.entrance}'
  exit: '{motion.primitives.duration.exit}'
  reduced: '{motion.primitives.duration.none}'
  standard: '{motion.primitives.easing.standard}'
  enter: '{motion.primitives.easing.enter}'
  leave: '{motion.primitives.easing.exit}'
breakpoints:
  primitives:
    mobile: 0px
    tablet: 600px
    desktop: 960px
    wide: 1280px
  mobile: '{breakpoints.primitives.mobile}'
  tablet: '{breakpoints.primitives.tablet}'
  desktop: '{breakpoints.primitives.desktop}'
  wide: '{breakpoints.primitives.wide}'
components:
  primitives:
    lengths:
      '1': 1px
      '2': 2px
      '3': 3px
      '4': 4px
      '8': 8px
      '16': 16px
      '20': 20px
      '24': 24px
      '40': 40px
      '44': 44px
      '48': 48px
      '54': 54px
      '56': 56px
      '128': 128px
      '256': 256px
      '280': 280px
      '320': 320px
      '360': 360px
      '400': 400px
      '480': 480px
      '640': 640px
      '880': 880px
      '1280': 1280px
    reading-measure: 68ch
    persistent-timeout: 0ms
    dialog-height-fraction: 0.8
  metrics:
    target: '{components.primitives.lengths.48}'
    compact-target: '{components.primitives.lengths.44}'
    icon-small: '{components.primitives.lengths.16}'
    icon: '{components.primitives.lengths.20}'
    icon-large: '{components.primitives.lengths.24}'
    content-max: '{components.primitives.lengths.1280}'
    reading-max: '{components.primitives.reading-measure}'
    form-max: '{components.primitives.lengths.640}'
    navigation-width: '{components.primitives.lengths.256}'
  button:
    min-height: '{components.primitives.lengths.48}'
    compact-min-height: '{components.primitives.lengths.40}'
    large-min-height: '{components.primitives.lengths.56}'
    padding-inline: '{spacing.16}'
    padding-block: '{spacing.8}'
    gap: '{spacing.8}'
    radius: '{rounded.control}'
    typography: '{typography.control}'
    fill: '{colors.primary}'
    text: '{colors.on-primary}'
  icon-button:
    size: '{components.metrics.target}'
    compact-size: '{components.metrics.compact-target}'
    icon: '{components.metrics.icon}'
    radius: '{rounded.control}'
  field:
    min-height: '{components.primitives.lengths.54}'
    compact-min-height: '{components.primitives.lengths.40}'
    padding-inline: '{spacing.12}'
    padding-block: '{spacing.8}'
    radius: '{rounded.control}'
    typography: '{typography.body}'
    fill: '{colors.surface}'
    text: '{colors.text}'
    border: '{colors.border}'
  textarea:
    min-height: '{components.primitives.lengths.128}'
    padding: '{spacing.12}'
    radius: '{rounded.control}'
    typography: '{typography.body}'
  select:
    min-height: '{components.field.min-height}'
    radius: '{rounded.control}'
    option-min-height: '{components.metrics.target}'
    popup-max-height: '{components.primitives.lengths.320}'
  checkbox:
    visual-size: '{components.primitives.lengths.20}'
    target: '{components.metrics.target}'
    radius: '{rounded.4}'
    mark: '{colors.on-primary}'
    selected: '{colors.primary}'
  radio:
    visual-size: '{components.primitives.lengths.20}'
    dot-size: '{components.primitives.lengths.8}'
    target: '{components.metrics.target}'
    radius: '{rounded.pill}'
    selected: '{colors.primary}'
  switch:
    track-width: '{components.primitives.lengths.40}'
    track-height: '{components.primitives.lengths.24}'
    thumb-size: '{components.primitives.lengths.20}'
    target: '{components.metrics.target}'
    radius: '{rounded.pill}'
    'on': '{colors.primary}'
    'off': '{colors.border}'
  slider:
    track-height: '{components.primitives.lengths.4}'
    thumb-size: '{components.primitives.lengths.24}'
    target: '{components.metrics.target}'
    active: '{colors.primary}'
    inactive: '{colors.surface-sunken}'
    border: '{colors.border}'
  link:
    typography: '{typography.body}'
    text: '{colors.link}'
    underline-width: '{components.primitives.lengths.1}'
    underline-offset: '{components.primitives.lengths.3}'
  tabs:
    min-height: '{components.metrics.target}'
    gap: '{spacing.8}'
    padding-inline: '{spacing.16}'
    indicator-width: '{components.primitives.lengths.2}'
    selected: '{colors.primary}'
  navigation:
    item-min-height: '{components.metrics.target}'
    width: '{components.metrics.navigation-width}'
    padding-inline: '{spacing.16}'
    selected-fill: '{colors.selected}'
    typography: '{typography.label}'
  card:
    padding: '{spacing.24}'
    mobile-padding: '{spacing.16}'
    radius: '{rounded.surface}'
    fill: '{colors.surface}'
    depth: '{elevation.flat}'
  well:
    padding: '{spacing.16}'
    radius: '{rounded.control}'
    fill: '{colors.surface-muted}'
    depth: '{elevation.flat}'
  table:
    row-min-height: '{components.primitives.lengths.56}'
    compact-row-min-height: '{components.primitives.lengths.40}'
    cell-padding-block: '{spacing.16}'
    compact-padding-block: '{spacing.8}'
    cell-padding-inline: '{spacing.16}'
    header-fill: '{colors.surface-muted}'
    divider: '{colors.border-subtle}'
  list:
    item-min-height: '{components.metrics.target}'
    padding-block: '{spacing.12}'
    gap: '{spacing.12}'
    divider: '{colors.border-subtle}'
  badge:
    min-height: '{components.primitives.lengths.24}'
    padding-inline: '{spacing.8}'
    padding-block: '{spacing.2}'
    radius: '{rounded.pill}'
    typography: '{typography.caption}'
    fill: '{colors.surface-muted}'
    text: '{colors.text-secondary}'
  alert:
    padding: '{spacing.16}'
    gap: '{spacing.12}'
    radius: '{rounded.control}'
    icon: '{components.metrics.icon}'
  notification:
    width: '{components.primitives.lengths.360}'
    inset: '{spacing.16}'
    gap: '{spacing.8}'
    depth: '{elevation.raised}'
    timeout: '{components.primitives.persistent-timeout}'
  tooltip:
    max-width: '{components.primitives.lengths.280}'
    padding-block: '{spacing.8}'
    padding-inline: '{spacing.12}'
    gap: '{spacing.8}'
    radius: '{rounded.4}'
    typography: '{typography.body-small}'
    fill: '{colors.surface-inverse}'
    text: '{colors.text-inverse}'
    delay: '{motion.primitives.duration.tooltip-delay}'
  popover:
    width: '{components.primitives.lengths.320}'
    padding: '{spacing.16}'
    gap: '{spacing.8}'
    radius: '{rounded.surface}'
    depth: '{elevation.floating}'
  dialog:
    max-width: '{components.primitives.lengths.640}'
    small-max-width: '{components.primitives.lengths.400}'
    large-max-width: '{components.primitives.lengths.880}'
    max-viewport-height: '{components.primitives.dialog-height-fraction}'
    padding: '{spacing.24}'
    mobile-padding: '{spacing.16}'
    viewport-inset: '{spacing.16}'
    radius: '{rounded.overlay}'
    depth: '{elevation.floating}'
  pagination:
    item-size: '{components.metrics.target}'
    gap: '{spacing.4}'
    radius: '{rounded.control}'
    selected-fill: '{colors.primary}'
    selected-text: '{colors.on-primary}'
  progress:
    track-height: '{components.primitives.lengths.8}'
    radius: '{rounded.pill}'
    fill: '{colors.primary}'
    track: '{colors.surface-sunken}'
    border: '{colors.border}'
  loading:
    indicator-size: '{components.primitives.lengths.24}'
    stroke-width: '{components.primitives.lengths.3}'
    delay: '{motion.primitives.duration.loading-delay}'
    cycle: '{motion.primitives.duration.cycle}'
    color: '{colors.primary}'
  empty:
    max-width: '{components.primitives.lengths.480}'
    padding-block: '{spacing.40}'
    gap: '{spacing.16}'
    heading: '{typography.heading-3}'
    text: '{typography.body}'
  error:
    max-width: '{components.metrics.form-max}'
    gap: '{spacing.12}'
    heading: '{typography.heading-3}'
    text: '{colors.danger-text}'
    fill: '{colors.danger-surface}'
---

# N1 design system

## Overview

N1 provides a shared visual language and interaction baseline for interfaces that need clear hierarchy, predictable controls and accessible task completion. This specification is self-contained and independent of product domain, brand assets, framework and component library. It covers a light theme; it does not define or imply a dark theme.

### Source of truth

**Status and authority.** This is a proposed, complete baseline for the token registry in this file, not a complete export of the existing Figma library. Selected palette values and the use of Segoe UI are informed by retained N1 observations. All new names, semantic aliases, tint colours, dimensional scales, font fallbacks, responsive rules, interaction rules and accessibility requirements are **adaptable defaults requiring design review**, unless independently approved. They are not claims about existing Figma variable aliases, modes or component variants. Exact values make the proposal actionable; they do not establish approval.

Approved Figma variables and visual specifications, verified implemented behavior, and approved human-authored usage guidance retain their respective authority. Record conflicts with this proposed baseline and obtain design review before adopting a deviation. Publishing this file does not promote a proposal to approved policy.

### Design philosophy

The philosophy is to reduce effort and help people complete meaningful work. Apply these guiding principles:

1. Make the next useful action and current status easy to find.
2. Use familiar patterns consistently; change them only to solve a demonstrated problem.
3. Preserve user input, explain consequences and support recovery.
4. Make the same task achievable with keyboard, pointer, touch and assistive technology.
5. Prefer readable content and restrained hierarchy over visual decoration.

The intended character is calm, precise and practical: neutral surfaces, strong text contrast, modest rounding, limited elevation and purposeful colour. Product imagery, logo treatment, terminology and content policy remain product-dependent choices.

**Accessibility target:** WCAG 2.2 Level AA for complete workflows, including responsive, loading, validation and error states. This is the requested target for this specification, not a certification of the existing system. Test actual interfaces with keyboard navigation, assistive technology, zoom, text resizing and touch.

### Design tokens

**Reading the registry.** Primitive values precede semantic mappings within each group. A reference such as {colors.primary} resolves through its aliases to an exact value. Typography and shadows are composite design values. Lengths use reference pixels unless explicitly marked ch; they must scale appropriately with text and user preferences. Easing arrays contain four Bézier control-point coordinates. Component entries describe design measurements and mappings, not implementation interfaces. Do not treat these proposed aliases as original Figma variable names.

Source context: [N1 Figma](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=915-56433), observed 15 October 2026. Palette observations include primary/main #637381, primary/dark #212b36, text/primary #161c24, secondary/main #44adda, error/main #d82934 and success/darker #024533. 

## Colors

### Architecture and primitive palette

Use primitives to define colour values, semantic roles to express intent and component mappings to apply those roles. Consume semantic roles for interface decisions. Reassign a role through review rather than changing isolated instances.

The following primitive values come from retained N1 colour or component observations. Their normalized names are local to this proposal.

| Primitive token | Resolved value | Intended use |
| --- | --- | --- |
| {colors.palette.white} | #ffffff | Light surface and inverse foreground |
| {colors.palette.neutral-50} | #f9fafb | Page canvas |
| {colors.palette.neutral-100} | #ecf0f3 | Muted surface and hover treatment |
| {colors.palette.neutral-200} | #dfe2e8 | Selected or sunken surface |
| {colors.palette.neutral-300} | #c4cdd5 | Decorative separators |
| {colors.palette.neutral-400} | #919eab | Nonessential decoration; insufficient alone for a control boundary on white |
| {colors.palette.neutral-600} | #637381 | Primary action, control boundary and muted text on white |
| {colors.palette.neutral-700} | #454f5b | Secondary text and action hover |
| {colors.palette.neutral-800} | #212b36 | Strong boundary and pressed action |
| {colors.palette.neutral-900} | #161c24 | Main text and inverse surface |
| {colors.palette.blue-600} | #096adc | Focus and first chart series |
| {colors.palette.blue-700} | #1b76ac | Informational foreground and links |
| {colors.palette.cyan-500} | #44adda | Secondary accent with dark text |
| {colors.palette.purple-500} | #6b52a2 | Visited link and chart series |
| {colors.palette.green-700} | #07683b | Success indicator |
| {colors.palette.green-900} | #024533 | Success text |
| {colors.palette.amber-500} | #e88310 | Warning emphasis with dark text |
| {colors.palette.amber-800} | #a74d08 | Warning text and indicator |
| {colors.palette.red-500} | #d82934 | Error indicator and destructive action |
| {colors.palette.red-800} | #9b1435 | Error text and destructive hover |
| {colors.palette.pink-600} | #d45087 | Chart series; not an extra feedback state |

Additional primitives are explicit proposed defaults:

| Primitive token | Resolved value | Intended use |
| --- | --- | --- |
| {colors.palette.green-50} | #ecf8ef | Success surface |
| {colors.palette.amber-50} | #fff5e8 | Warning surface |
| {colors.palette.red-50} | #fdeef0 | Error surface |
| {colors.palette.blue-50} | #edf6fc | Information surface |
| {colors.palette.overlay-50} | #161c2480 | Modal scrim; alpha is exactly 128/255 |
| {colors.palette.shadow-12} | #161c241f | Raised shadow; alpha is exactly 31/255 |
| {colors.palette.shadow-20} | #161c2433 | Floating shadow; alpha is exactly 51/255 |
| {colors.palette.transparent} | #ffffff00 | Transparent shadow and unfilled treatment |

### Semantic mappings

| Token | Resolved value | Intended use |
| --- | --- | --- |
| {colors.canvas} | #f9fafb | Page background |
| {colors.surface} | #ffffff | Controls, cards and overlays |
| {colors.surface-muted} | #ecf0f3 | Wells and table headers |
| {colors.surface-sunken} | #dfe2e8 | Recessed regions |
| {colors.surface-inverse} | #161c24 | Tooltip surface |
| {colors.text} | #161c24 | Primary content |
| {colors.text-secondary} | #454f5b | Supporting content |
| {colors.text-muted} | #637381 | Metadata on white; verify other pairings |
| {colors.text-inverse} | #ffffff | Content on an inverse surface |
| {colors.text-disabled} | #637381 | Inactive content on {colors.disabled} |
| {colors.border} | #637381 | Essential control boundaries |
| {colors.border-hover} | #212b36 | Hovered boundary |
| {colors.border-subtle} | #c4cdd5 | Separators where grouping remains clear without them |
| {colors.primary} | #637381 | Main action fill |
| {colors.primary-hover} | #454f5b | Main action hover |
| {colors.primary-active} | #212b36 | Main action while pressed |
| {colors.on-primary} | #ffffff | Main action label and icon |
| {colors.secondary} | #44adda | Optional accent fill |
| {colors.on-secondary} | #161c24 | Label on accent fill |
| {colors.hover} | #ecf0f3 | Unfilled item hover |
| {colors.selected} | #dfe2e8 | Selected item background with an additional indicator |
| {colors.disabled} | #ecf0f3 | Inactive control background |
| {colors.focus} | #096adc | Focus ring on light surfaces |
| {colors.focus-inverse} | #ffffff | Focus ring on dark surfaces |
| {colors.focus-gap} | #ffffff | Separation between control and outer focus ring |
| {colors.link} | #1b76ac | Underlined navigation text |
| {colors.link-hover} | #096adc | Hovered link |
| {colors.link-visited} | #6b52a2 | Optional visited destination |
| {colors.success} / {colors.success-text} | #07683b / #024533 | Success icon or border / text |
| {colors.success-surface} | #ecf8ef | Success message background |
| {colors.warning} / {colors.warning-text} | #a74d08 / #a74d08 | Warning indicator / text |
| {colors.warning-surface} | #fff5e8 | Warning message background |
| {colors.danger} / {colors.danger-text} | #d82934 / #9b1435 | Error indicator / text |
| {colors.danger-hover} | #9b1435 | Destructive action hover and pressed fill |
| {colors.danger-surface} | #fdeef0 | Error message background |
| {colors.info} / {colors.info-text} | #1b76ac / #1b76ac | Information indicator / text |
| {colors.info-surface} | #edf6fc | Information message background |
| {colors.overlay} | #161c2480 | Background scrim behind a modal dialog |
| {colors.data-1} | #096adc | Categorical series 1 |
| {colors.data-2} | #6b52a2 | Categorical series 2 |
| {colors.data-3} | #a74d08 | Categorical series 3 |
| {colors.data-4} | #07683b | Categorical series 4 |
| {colors.data-5} | #d45087 | Categorical series 5 |

Keep categorical series stable within a view. These colours are not certified as universally distinguishable. Supply direct labels, different marker shapes or line patterns, and a textual or tabular equivalent. Use a contrasting boundary where adjacent marks cannot otherwise be distinguished. Quantitative gradients and additional series require a separate reviewed scale.

### Contrast and non-colour meaning

Normal text requires at least 4.5:1 contrast; large text requires at least 3:1. Large means at least 24px regular or approximately 18.67px bold at reference sizing. Essential control outlines, meaningful graphics and state indicators require at least 3:1 against their relevant adjacent colours; see [non-text contrast](https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html). Placeholder and helper text count as text. Inactive controls have a WCAG contrast exception, but keep them legible. See [WCAG 2.2](https://www.w3.org/TR/WCAG22/) and [contrast guidance](https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html).

White on {colors.primary} passes normal-text contrast; white on {colors.secondary} does not. Use {colors.on-secondary} on that accent. Do not use {colors.border-subtle} as the sole visible boundary of an input. Recheck actual combinations, transparency and every interaction state; token names do not guarantee compliance.

Pair feedback colour with a named status and an icon or explicit message. Pair selection with a check, indicator or weight change. Errors must identify the affected field and explain recovery in text.

## Typography

### Families and styles

The adaptable default is Segoe UI, followed by Helvetica Neue, Arial and the generic sans-serif fallback. Segoe UI occurs in retained N1 component observations; the complete family strategy and scale below are proposed. Do not assume fonts are installed or licensed for embedding. Keep the fallback active until the preferred family is available. Use the monospace stack only for content that needs fixed-width alignment.

| Token | Family | Size | Weight | Line height | Letter spacing | Use |
| --- | --- | --- | --- | --- | --- | --- |
| {typography.display} | Sans stack | 40px | 700 | 48px | -0.4px | Short introductory title |
| {typography.heading-1} | Sans stack | 32px | 700 | 40px | 0px | Page heading |
| {typography.heading-2} | Sans stack | 24px | 600 | 32px | 0px | Main section |
| {typography.heading-3} | Sans stack | 20px | 600 | 28px | 0px | Subsection and dialog heading |
| {typography.heading-4} | Sans stack | 18px | 600 | 26px | 0px | Small group heading |
| {typography.body} | Sans stack | 16px | 400 | 24px | 0px | Main content and field values |
| {typography.body-small} | Sans stack | 14px | 400 | 22px | 0px | Supporting descriptions |
| {typography.label} | Sans stack | 14px | 600 | 20px | 0px | Field, table and navigation labels |
| {typography.caption} | Sans stack | 12px | 400 | 18px | 0px | Secondary metadata and badges |
| {typography.control} | Sans stack | 14px | 600 | 20px | 0px | Standard control labels |
| {typography.control-large} | Sans stack | 15px | 700 | 26px | 0px | Large action labels |

The registry also provides a 0.35px tracking primitive as an optional optical adjustment; none of the default styles uses it. Do not apply it globally.

Use one main page heading and a logical heading hierarchy. Choose heading semantics by document structure, then choose a visual style; do not select heading levels merely to change size. Keep labels in sentence case and avoid long all-capital text. Captions must not carry essential instructions alone.

Limit sustained reading to {components.metrics.reading-max}, resolved as 68ch. Let labels, helper messages and headings wrap. Support 200% text resizing and user text-spacing overrides without clipping, hiding controls or losing content; see [text-spacing requirements](https://www.w3.org/WAI/WCAG22/Understanding/text-spacing.html). At narrow widths, use {typography.heading-1} in place of display text when needed; do not shrink body text to fit. Do not force a fixed-height text container.

## Layout

### Spacing

Use a 4px core rhythm with 1px and 2px structural adjustments and 6px optical gaps. Values are explicit adaptable defaults, not inferred values of similarly named Figma variables.

| Token | Resolved value | Typical use |
| --- | --- | --- |
| {spacing.0} | 0px | No gap |
| {spacing.1} | 1px | Fine structural adjustment |
| {spacing.2} | 2px | Small indicator inset |
| {spacing.4} | 4px | Closely related labels and metadata |
| {spacing.6} | 6px | Small optical gap |
| {spacing.8} | 8px | Icon-label gap; label-field gap |
| {spacing.12} | 12px | Compact padding and list gaps |
| {spacing.16} | 16px | Mobile gutter and standard internal padding |
| {spacing.20} | 20px | Intermediate control spacing |
| {spacing.24} | 24px | Form group gap and card padding |
| {spacing.32} | 32px | Desktop gutter |
| {spacing.40} | 40px | Section separation |
| {spacing.48} | 48px | Large group separation |
| {spacing.64} | 64px | Major section separation |
| {spacing.80} | 80px | Spacious page region |
| {spacing.96} | 96px | Exceptional large separation |

Semantic spacing resolves as follows: {spacing.inline-gap} and {spacing.field-gap} are 8px; {spacing.group-gap} is 24px; {spacing.section-gap} is 40px. Page gutters use {spacing.page-mobile}, {spacing.page-tablet} and {spacing.page-desktop}.

### Responsive design

Breakpoints describe available layout width, not device identity. Ranges use an inclusive lower bound and exclusive upper bound.

| Range | Start token | Columns | Outer gutter | Column gap | Default behavior |
| --- | --- | --- | --- | --- | --- |
| Below 600px | {breakpoints.mobile} = 0px | 4 | 16px | 16px | One primary content column; navigation opens on request |
| 600px to below 960px | {breakpoints.tablet} = 600px | 8 | 24px | 24px | Optional paired fields and two-column cards where content fits |
| 960px to below 1280px | {breakpoints.desktop} = 960px | 12 | 32px | 24px | Optional persistent side navigation and supporting column |
| 1280px and wider | {breakpoints.wide} = 1280px | 12 | 32px | 24px | Centre the container; do not stretch reading text indefinitely |

The outer content container is at most {components.metrics.content-max}, 1280px, including its gutters. A standard form is at most {components.metrics.form-max}, 640px. Optional side navigation is {components.metrics.navigation-width}, 256px; account for its width before deciding whether remaining content supports multiple columns. These are product-dependent adaptable defaults. Collapse earlier if real labels, translation, zoom or content need more room.

Align related labels and controls to a common starting edge. Use one column for sequential form questions; pair only short, closely related fields. Maintain reading and keyboard order when rearranging content. Support right-to-left flow without assuming the starting edge is always left.

At 320px available width, preserve content and actions without page-level horizontal scrolling. Two-dimensional information such as a data table may use a clearly bounded horizontal scroll region; surrounding instructions and controls must still reflow. Follow [reflow requirements](https://www.w3.org/WAI/WCAG22/Understanding/reflow.html).

### Targets and density

Default interactive targets are {components.metrics.target}, 48 × 48px. Compact icon controls may use {components.metrics.compact-target}, 44 × 44px. A smaller visible mark must sit within an unambiguous target; expanded targets must not overlap neighboring controls. WCAG 2.2 AA permits 24 × 24px targets or specified exceptions, but this baseline intentionally uses larger defaults. Inline prose links may follow the inline exception. See [target-size guidance](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html).

Comfortable density is the default. Compact fields and table rows are adaptable defaults for information-dense views, not an automatic mobile treatment. Maintain readable type, target requirements and room for error text. Stack action groups when space is insufficient rather than reducing labels or hiding essential actions.

## Elevation and depth

### Radius and borders

| Token | Resolved value | Use |
| --- | --- | --- |
| {rounded.0} | 0px | Edge-aligned divisions |
| {rounded.4} | 4px | Checkbox and tooltip |
| {rounded.control} | 8px | Controls and wells |
| {rounded.surface} | 12px | Cards and popovers |
| {rounded.overlay} | 16px | Dialog surface |
| {rounded.pill} | 9999px | Badges and round controls; clamp to half the shorter dimension |

Use {elevation.border-width}, 1px, for ordinary solid borders and {elevation.selected-width}, 2px, for an emphasized selection indicator. Keep geometry stable when state changes; draw emphasis within the reserved boundary rather than shifting neighboring content. Essential borders use {colors.border}; decorative separators use {colors.border-subtle}.

Focus-visible treatment is a {elevation.focus-width}, 3px, ring with a {elevation.focus-gap}, 2px, separating gap. Use {colors.focus} around light surfaces and {colors.focus-inverse} around dark surfaces, maintaining visible contrast against adjacent colours. Do not clip the ring. Preserve the platform's high-contrast focus presentation when custom colours are overridden.

### Shadows and layers

| Depth token | Offset x / y | Blur / spread | Colour | Use |
| --- | --- | --- | --- | --- |
| {elevation.flat} | 0px / 0px | 0px / 0px | #ffffff00 | Ordinary cards and page content |
| {elevation.raised} | 0px / 2px | 8px / 0px | #161c241f | Notifications and optional raised surfaces |
| {elevation.floating} | 0px / 8px | 24px / 0px | #161c2433 | Menus, popovers and dialogs |

Use one shadow per surface. A shadow does not replace an essential boundary or an accessible relationship between trigger and overlay.

| Layer token | Resolved level | Use |
| --- | --- | --- |
| {elevation.primitives.layers.base} | 0 | Normal content |
| {elevation.primitives.layers.sticky} | 10 | Sticky page region |
| {elevation.primitives.layers.menu} | 20 | Non-modal menu or select popup |
| {elevation.primitives.layers.backdrop} | 30 | Modal scrim |
| {elevation.primitives.layers.dialog} | 40 | Active modal surface |
| {elevation.primitives.layers.popover} | 50 | Popover belonging to the active surface |
| {elevation.primitives.layers.tooltip} | 60 | Tooltip belonging to the active surface |
| {elevation.primitives.layers.notification} | 70 | Context-appropriate notification |

Levels describe a coordinated stacking order, not a requirement to place every overlay at the page root. Scope menus, tooltips and notifications to their active interaction context. Background overlays must not appear over an unrelated modal. Modal background content is unavailable for interaction. Sticky regions must not obscure focused controls, headings or error messages. Keep essential dialog actions reachable when its content scrolls.

## Motion

| Token | Resolved value | Use |
| --- | --- | --- |
| {motion.feedback} | 120ms | Colour or opacity feedback |
| {motion.transition} | 180ms | Small state transitions |
| {motion.entrance} | 240ms | Overlay entrance |
| {motion.exit} | 160ms | Overlay exit |
| {motion.reduced} | 0ms | Reduced-motion positional transition |
| {motion.primitives.duration.loading-delay} | 200ms | Delay before a decorative loading indicator |
| {motion.primitives.duration.tooltip-delay} | 500ms | Pointer tooltip delay |
| {motion.primitives.duration.cycle} | 1000ms | Indeterminate progress cycle |
| {motion.standard} | 0.2, 0, 0, 1 | General easing |
| {motion.enter} | 0, 0, 0.2, 1 | Entrance easing |
| {motion.leave} | 0.4, 0, 1, 1 | Exit easing |
| {motion.primitives.easing.linear} | 0, 0, 1, 1 | Continuous progress |

These timings are adaptable defaults. Respond to input immediately; animation must not delay activation, focus placement or accessible status updates. Keep feedback changes to colour, border or opacity where practical. Overlay entrance may combine opacity with at most 8px displacement; exit reverses that displacement. Never move surrounding layout to create a pressed-button effect.

When reduced motion is requested, remove positional movement, scale changes, parallax, looping shimmer and rotating indicators. Use an immediate state change and persistent text such as “Loading”; essential progress information must remain available. Completion must not wait for an animation cycle. Avoid flashing, autoplay decoration and animation that competes with reading. Provide pause or stop controls for qualifying moving content that continues beyond five seconds, as required by WCAG.

## Components

### Shared state and accessibility rules

All component specifications below are adaptable defaults. Their names describe control categories, not a claim that an identically named runtime or Figma configuration exists.

| State | Shared treatment |
| --- | --- |
| Default | Apply the component's base semantic mappings |
| Hover | Use {colors.hover} for unfilled items or the specified filled-action hover; do not depend on hover for essential content |
| Focus-visible | Add the 3px ring and 2px gap; preserve any simultaneous selected or invalid indication |
| Active | Show pressed feedback while activation is held; this is distinct from persistent selection |
| Selected | Use {colors.selected} plus a check, underline, marker or explicit selected state |
| Disabled | Use {colors.disabled} and {colors.text-disabled}; prevent activation and explain important prerequisites nearby |
| Loading | Preserve dimensions and label context, prevent duplicate submission and expose status |
| Read-only | Retain readable content and selection/copy access; prevent editing and identify the restriction |
| Invalid | Add {colors.danger} boundary or indicator and an associated error message |
| Error | Explain what failed, preserve user data and provide a practical recovery action |

Apply only meaningful states: a static card has no pressed state; a link has no read-only state; a progress indicator has no hover action. Do not manufacture meaningless variants. Focus-visible must coexist with hover, selected, invalid and read-only when applicable. Disabled controls normally leave the sequential keyboard order; read-only fields remain available for focus and copying.

Give every interactive item a clear accessible name, matching its visible label where present. Expose role, value, selected/expanded state and errors to assistive technology. Support visible keyboard focus, predictable traversal and operation without a pointer. Do not use hover-only content as the sole source of instructions.

### Buttons and icon buttons

- **Purpose:** Trigger actions; use links for navigation to a destination.
- **Base visual specification:** {components.button} uses a 48px minimum height, 16px horizontal padding, 8px vertical padding and icon gap, 8px radius, {typography.control}, {colors.primary} and {colors.on-primary}. Content may increase height.
- **Sizes and styles:** Compact has a 40px minimum height; standard is 48px; large is 56px and uses {typography.control-large}. Compact button hit regions still meet the shared target rules. Primary is filled; secondary uses {colors.surface}, {colors.text} and a 1px {colors.border} outline; quiet is unfilled. Destructive uses {colors.danger} with white text. Icon buttons use {components.icon-button}: 48px square, or 44px compact, with a 20px icon.
- **States:** Filled primary hover/active use {colors.primary-hover}/{colors.primary-active}. Destructive hover/active use {colors.danger-hover}. Secondary and quiet hover use {colors.hover}, active uses {colors.selected}. All actionable variants support focus-visible, disabled and loading. Toggle buttons additionally expose selected state with an indicator. Read-only and invalid are not button states.
- **Token mappings:** {components.button}, {components.icon-button}, {colors.on-primary}, {elevation.border-width} and shared focus tokens.
- **Behavior and usage:** Use one visually dominant action per local decision group. Keep action labels specific. Loading preserves the action's meaning and blocks duplicates; do not replace every action with a spinner. Confirm irreversible high-impact actions when their consequences warrant it.
- **Accessibility:** Buttons activate with Enter and Space. Icon-only buttons need an action name; a tooltip is supplementary. A toggle communicates whether it is pressed. Keep focus stable during loading.

### Text fields and text areas

- **Purpose:** Collect editable text, with single-line fields for short values and text areas for multiple lines.
- **Base visual specification:** {components.field} uses a 54px minimum height, 12px horizontal and 8px vertical padding, {typography.body}, an 8px radius and a 1px {colors.border} boundary on {colors.surface}. Place a persistent label above the field with an 8px gap. {components.textarea} has a 128px minimum height and 12px padding.
- **Sizes and styles:** Compact fields have a 40px minimum height. Text areas span the available form width and allow vertical expansion. Sensitive, search and numeric entry are purpose-dependent adaptations, not separate invented field APIs.
- **States:** Default, hover, focus-visible, disabled, read-only and invalid; use the shared focus ring without removing an error boundary. Loading belongs to validation or submission status and must not erase entered text.
- **Token mappings:** {components.field}, {components.textarea}, {colors.border-hover}, {colors.danger}, {typography.body-small} for help and errors.
- **Behavior and usage:** Label the value and specify required status, units and format before entry. Validate on submission and, where useful, after a field has been left. After an error appears, update it as the user corrects the value. Avoid marking untouched fields invalid. Preserve values on failures.
- **Accessibility:** Associate labels, instructions and errors with each field. Placeholder text never replaces a label. Allow selection, paste and assistive entry. Read-only stays readable and copyable; disabled means unavailable.

### Selects

- **Purpose:** Choose one value from a defined set when displaying every option is impractical.
- **Base visual specification:** Match {components.field}; reserve trailing room for an indicator. {components.select} uses 48px minimum-height options and a 320px maximum popup height before internal scrolling.
- **Sizes and styles:** Standard 54px or compact 40px minimum control height. Searchable or multi-selection versions are product-dependent extensions requiring their own selection and announcement rules.
- **States:** Default, hover, focus-visible, expanded, selected option, disabled and invalid. A loading list shows a status rather than a selectable “Loading” option. Read-only values are shown as labelled text when editing is unavailable.
- **Token mappings:** {components.select}, {colors.hover}, {colors.selected}, {elevation.floating} and the menu layer.
- **Behavior and usage:** Display the current value. Do not commit a new value merely because an option is hovered. Keep the selected option visible when opening and keep the popup within the viewport.
- **Accessibility:** Provide a label and expose expanded/selected state. Keyboard users can open, traverse options, choose and dismiss. Escape closes without an unintended change; restore focus to the trigger. Test the chosen interaction model with assistive technology.

### Checkboxes and radios

- **Purpose:** Checkboxes select independent choices; radios select exactly one choice within a named group.
- **Base visual specification:** {components.checkbox} is a 20px square with 4px radius; {components.radio} is a 20px circle with an 8px selected dot. Both have a 48px target, a 1px {colors.border} boundary and an 8px label gap. Selected controls use {colors.primary}; checkbox marks are white.
- **Sizes and styles:** One default visual size. Checkboxes may show a distinct mixed mark for partial group selection; radio choices have no mixed state.
- **States:** Unselected, selected, hover, focus-visible, disabled and group invalid. Read-only selections are labelled summaries rather than misleading editable controls.
- **Token mappings:** {components.checkbox}, {components.radio}, {colors.primary}, {colors.on-primary}, {colors.danger} and shared focus tokens.
- **Behavior and usage:** Make the label part of the target. Explain a required group rather than marking every option required. A group-level checkbox may select or clear all available child choices; its mixed appearance reflects partial selection.
- **Accessibility:** Name the group and each choice. Space toggles a checkbox; arrow keys move selection within a radio group. Expose selected and mixed states. Keep descriptions and errors associated with the group.

### Switches

- **Purpose:** Turn a setting on or off immediately when the result is safe and understandable.
- **Base visual specification:** {components.switch} has a 40 × 24px pill track, a 20px thumb and a 48px target. On uses {colors.primary}; off uses {colors.border}. Thumb position and a state label distinguish the values.
- **Sizes and styles:** One size; keep the label stable when the state changes.
- **States:** Off, on, hover, focus-visible, disabled and pending update. Use an adjacent error message if a remote update fails.
- **Token mappings:** {components.switch}, {colors.surface}, {motion.feedback} and shared focus tokens.
- **Behavior and usage:** Apply immediately and report failures; restore the prior value when saving fails. For changes submitted later as part of a form, use a checkbox instead. Do not silently discard a failed toggle.
- **Accessibility:** Provide a persistent setting name and expose on/off state. Space changes the value. Announce saving failures without stealing focus.

### Sliders

- **Purpose:** Adjust an approximate value within a meaningful range.
- **Base visual specification:** {components.slider} has a 4px track, 24px thumb and 48px target. Active track uses {colors.primary}; remaining track uses {colors.surface-sunken}. A 1px {colors.border} outline keeps the complete track identifiable. Show the current value and unit.
- **Sizes and styles:** A single-thumb slider is the baseline. Dual-thumb ranges need separately labelled minimum and maximum controls and ordering rules.
- **States:** Default, hover, focus-visible, dragging, disabled and invalid value. Read-only values use a labelled textual presentation.
- **Token mappings:** {components.slider}, {typography.label}, {colors.danger} and shared focus tokens.
- **Behavior and usage:** Bounds, step, unit and default value are product-dependent decisions; define them for every use. Supply direct numeric entry when precision matters. Do not use dragging as the only way to choose a value.
- **Accessibility:** Arrow keys adjust by the defined step; Home and End reach the bounds. Expose a meaningful value description and provide a non-dragging pointer alternative.

### Links

- **Purpose:** Navigate to a destination or a named location.
- **Base visual specification:** {components.link} uses {colors.link}, an always-visible 1px underline, 3px underline offset and surrounding text typography; standalone links use {typography.body}.
- **Sizes and styles:** Inline and standalone. An optional visited state uses {colors.link-visited}; do not rely on it for essential history information.
- **States:** Default, hover, focus-visible, active and optional visited. Hover/active use {colors.link-hover}. If a destination is unavailable, show explanatory text rather than a deceptive disabled link.
- **Token mappings:** {components.link}, {colors.link-hover}, {colors.link-visited} and shared focus tokens.
- **Behavior and usage:** Name the destination or result. Warn before opening an unexpected new browsing context. Use a button for an action that changes data or opens an action dialog.
- **Accessibility:** Enter follows the link. Make its purpose understandable in context. Keep inline links distinguishable without colour and provide a visible focus treatment.

### Tabs and navigation

- **Purpose:** Tabs switch between related panels in one context; navigation changes location.
- **Base visual specification:** {components.tabs} has a 48px minimum height, 16px horizontal padding, 8px gaps and a 2px selected underline. {components.navigation} uses 48px minimum-height items, 16px horizontal padding and {typography.label}. Selected navigation combines {colors.selected} with an indicator and stronger text.
- **Sizes and styles:** Horizontal tabs and optional 256px side navigation. On narrow screens, allow a bounded tab strip to scroll with a visible affordance, or choose a reviewed alternative; do not silently hide tabs. Side navigation becomes an explicitly opened panel.
- **States:** Default, hover, focus-visible, selected/current and disabled where meaningful. Distinguish keyboard focus from the active panel or current page.
- **Token mappings:** {components.tabs}, {components.navigation}, {colors.hover}, {colors.primary}, {colors.selected} and shared focus tokens.
- **Behavior and usage:** Keep tab labels short and stable. Use manual activation by default: arrow keys move tab focus; Enter or Space selects. Preserve relevant panel input when switching. Navigation does not masquerade as tabs.
- **Accessibility:** Name navigation regions, expose the current destination and associate each tab with its panel. Follow the [tab interaction pattern](https://www.w3.org/WAI/ARIA/apg/patterns/tabs/). Home/End move to the first/last tab. Modal navigation panels follow the dialog focus rules; non-modal navigation does not trap focus.

### Cards and wells

- **Purpose:** Cards group a coherent subject; wells distinguish a supporting or recessed region.
- **Base visual specification:** {components.card} uses a white surface, 12px radius, 24px padding and flat depth; mobile padding is 16px. {components.well} uses {colors.surface-muted}, 8px radius and 16px padding. An optional 1px subtle border can reinforce nonessential grouping.
- **Sizes and styles:** Flat is standard; raised cards may use {elevation.raised} when separation is necessary. Card width follows the layout, not a fixed device width.
- **States:** Static surfaces have no interactive states. A selectable card adds explicit selection and focus-visible treatment. A destination card uses a clear link; nested actions retain independent targets.
- **Token mappings:** {components.card}, {components.well}, {colors.text}, {colors.border-subtle} and {elevation.raised}.
- **Behavior and usage:** Keep the title, summary and actions visually related. Do not make an entire complex card a single ambiguous hit area. Avoid shadowing every nested group.
- **Accessibility:** Give meaningful groups headings. Avoid nested or overlapping interactive targets and ensure focus order follows reading order.

### Tables and lists

- **Purpose:** Tables support comparisons across shared attributes; lists present a sequence or collection without a column relationship.
- **Base visual specification:** {components.table} uses a muted header, 16px horizontal cell padding and subtle row dividers. Comfortable rows have a 56px minimum height with 16px block padding; compact rows use 40px minimum height with 8px block padding. Text wrapping can increase row height. {components.list} uses 48px minimum-height items, 12px block padding and 12px content gaps.
- **Sizes and styles:** Comfortable and compact table density; static and actionable list items. Align comparable numbers consistently and keep units explicit.
- **States:** Hover applies to actionable rows/items. Selection has a checkbox or explicit marker as well as background. Sorting, loading, empty and error states are distinct. Cells with invalid edits show associated errors.
- **Token mappings:** {components.table}, {components.list}, {typography.label}, {typography.body}, {colors.hover} and {colors.selected}.
- **Behavior and usage:** Keep headers visible or repeat their context when needed. On narrow screens, use a labelled horizontal scroll region for genuinely tabular data; reformat only when relationships remain clear. Do not truncate the only available value without an accessible way to read it.
- **Accessibility:** Identify headers and their relationships to data. Expose sort direction and selection count. Use ordinary reading/navigation semantics unless the full keyboard behavior of an interactive grid is provided. Row actions need specific names.

### Badges

- **Purpose:** Summarize a short status, category or count.
- **Base visual specification:** {components.badge} has a 24px minimum height, 8px horizontal and 2px vertical padding, pill radius and {typography.caption}. Neutral badges use {colors.surface-muted} with {colors.text-secondary}.
- **Sizes and styles:** Neutral, success, warning, danger and information use the corresponding surface/text role pairs. Counts remain textual; the cap and overflow wording are product-dependent.
- **States:** Static by default. Do not add hover or pressed treatment unless the item is genuinely interactive; interactive filters follow button or checkbox rules and target sizes.
- **Token mappings:** {components.badge} and the semantic feedback surface/text pairs.
- **Behavior and usage:** Keep labels explicit and avoid relying on a coloured dot. Use a separate removal action for removable items.
- **Accessibility:** Include the meaning of a count in its accessible context. Do not force every background count update into an interruptive announcement.

### Alerts and notifications

- **Purpose:** Alerts communicate contextual information; notifications report an event without taking over the task.
- **Base visual specification:** {components.alert} uses 16px padding, 12px gaps, an 8px radius and 20px status icon. Map success, warning, danger and information to their named surface/text pairs. {components.notification} is at most 360px wide, inset 16px and separated by 8px, with raised depth.
- **Sizes and styles:** Inline alerts span their context. Floating notifications shrink to the viewport with 16px side insets. Use neutral messages when no feedback severity is warranted.
- **States:** New, persistent, dismissed and error/retry when relevant. The baseline timeout is 0ms, meaning no automatic dismissal.
- **Token mappings:** {components.alert}, {components.notification}, feedback colours and {elevation.raised}.
- **Behavior and usage:** State what happened and what can be done. Keep errors and actionable messages until resolved or dismissed. Do not stack messages over essential controls or use a temporary notification as the only record of a serious failure.
- **Accessibility:** Announce routine updates politely and reserve interruptions for urgent issues. Do not move focus to routine notifications. A dismissal control needs a name and target; urgent content remains available after the announcement.

### Tooltips and popovers

- **Purpose:** Tooltips provide brief supplementary descriptions; popovers contain contextual interactive or richer content.
- **Base visual specification:** {components.tooltip} uses an inverse surface, white {typography.body-small} text, 4px radius, 8px block and 12px inline padding, an 8px trigger gap and 280px maximum width. {components.popover} is 320px wide by default, with 16px padding, 12px radius and floating depth. Both fit within 16px viewport insets.
- **Sizes and styles:** Text-only tooltip; non-modal contextual popover. Interactive content belongs in the popover, not the tooltip. Tooltip pointer delay is 500ms; keyboard focus reveals its description without that delay.
- **States:** Hidden, opening, visible and closing; interactive popover contents follow their own focus/selected/error rules.
- **Token mappings:** {components.tooltip}, {components.popover}, {motion.entrance}, {motion.exit} and the relevant layers.
- **Behavior and usage:** Keep the content visible while its trigger or content is hovered or focused; allow dismissal with Escape. Reposition rather than clip near an edge. Essential instructions must be visible outside a tooltip.
- **Accessibility:** Associate the tooltip description with its trigger. Keep non-modal popover focus predictable and return it to the trigger on dismissal. Do not trap focus unless the presentation is explicitly modal and follows dialog rules.

### Dialogs

- **Purpose:** Request a bounded decision or focused task that needs attention before returning to the previous context.
- **Base visual specification:** {components.dialog} uses a white surface, 16px radius, floating depth and {colors.overlay} scrim. Default maximum width is 640px, small is 400px and large is 880px. Padding is 24px, reduced to 16px on mobile.
- **Sizes and styles:** Actual width never exceeds available width after two 16px insets. Maximum height is 80% of the available viewport; scroll content internally and keep essential actions reachable. Use a separate reviewed full-screen pattern for tasks that cannot fit this constraint.
- **States:** Opening, open, submitting, validation error and closing. Preserve content and focus when submission fails. Prevent duplicate confirmations during loading.
- **Token mappings:** {components.dialog}, {typography.heading-3}, {colors.overlay}, {motion.entrance} and {motion.exit}.
- **Behavior and usage:** Provide a title, clear action and explicit cancel/close path. Avoid nested dialogs. Escape cancels by default; if unsaved work needs confirmation, explain it rather than silently losing input. Backdrop click does not dismiss by default; changing this is a product-dependent decision.
- **Accessibility:** Move focus to the most useful initial location, contain it within the modal while open, make background interaction unavailable and restore focus to the invoking control or a logical successor. Associate title and concise description. For destructive confirmations, default focus to the least destructive suitable action. Follow the [modal dialog pattern](https://www.w3.org/WAI/ARIA/apg/patterns/dialog-modal/).

### Pagination

- **Purpose:** Move through a bounded collection while showing the current position.
- **Base visual specification:** {components.pagination} uses 48px items, 4px gaps and 8px radius. The current page uses {colors.primary} and {colors.on-primary}, with an additional current-page indication.
- **Sizes and styles:** Numbered pages with previous/next; narrow layouts may show previous, current position and next. Ellipses are noninteractive omission indicators.
- **States:** Default, hover, focus-visible, current, unavailable previous/next and loading.
- **Token mappings:** {components.pagination}, {colors.hover} and shared focus tokens.
- **Behavior and usage:** Page size, total-count availability and position persistence are product-dependent. Preserve filters and sorting. After a user-requested change, announce the updated position and manage focus so the new results can be found; never send it arbitrarily to the page top.
- **Accessibility:** Name the pagination region and each destination. Expose the current page. Use navigation links for destinations and action controls for in-place updates; retain their appropriate keyboard behavior.

### Progress and loading

- **Purpose:** Show that work is underway and, when known, how far it has progressed.
- **Base visual specification:** {components.progress} has an 8px pill track with {colors.primary} fill, {colors.surface-sunken} remainder and a 1px {colors.border} outline. {components.loading} uses a 24px indicator with 3px stroke. Always provide a textual task/status context.
- **Sizes and styles:** Determinate progress includes a meaningful value; indeterminate progress has no invented percentage. A skeleton mirrors the pending region without creating fake interactive content.
- **States:** Idle, loading, paused where supported, complete and failed. Failure switches to a recovery message; it does not spin indefinitely.
- **Token mappings:** {components.progress}, {components.loading}, {motion.primitives.duration.loading-delay}, {motion.primitives.duration.cycle} and {motion.reduced}.
- **Behavior and usage:** Mark the task busy immediately. The decorative indicator may wait 200ms to avoid flicker; completion never waits for this delay. Keep layout stable, preserve prior useful data when safe and expose cancellation for genuinely cancellable long tasks. Exact progress update cadence is product-dependent.
- **Accessibility:** Expose known progress and meaningful status changes without announcing every animation frame. Under reduced motion, use static progress and text. Do not move focus merely because background work completes.

### Empty and error states

- **Purpose:** Explain missing content or failed work and provide an appropriate next step.
- **Base visual specification:** {components.empty} uses at most 480px reading width, 40px block padding and 16px gaps. {components.error} uses at most 640px width and 12px gaps, with {colors.danger-text} on {colors.danger-surface}. Both use {typography.heading-3} and readable body text.
- **Sizes and styles:** Distinguish first-use empty, no search results, no permission, failed request and field validation. Illustrations are optional and never carry the only explanation.
- **States:** Empty, error and recovery in progress. Field errors remain near their fields; form-level summaries link or direct users to affected locations.
- **Token mappings:** {components.empty}, {components.error}, {typography.body}, {colors.text-secondary} and the button/link mappings for recovery.
- **Behavior and usage:** Explain the reason using known facts. Offer creation, filter reset, retry or access guidance only when applicable. Preserve entered data. State uncertainty when the cause is unknown; do not blame users or imply a retry will certainly succeed.
- **Accessibility:** Announce a newly presented failure appropriately. On unsuccessful form submission, focus an error summary or the first invalid field according to the form's agreed pattern. Ensure recovery actions are reachable and repeated failures do not create focus loops.

## Do’s and Don’ts

| Area | Do | Don’t |
| --- | --- | --- |
| Colors | Use semantic roles; test actual foreground/background pairs; add text, icons and non-colour indicators | Treat a palette name as proof of contrast, or use colour alone for errors and charts |
| Typography | Use the defined hierarchy; preserve semantic headings, wrapping, zoom and font fallbacks | Shrink text to avoid reflow, lock text containers to a fixed height or use captions for essential instructions |
| Layout and responsiveness | Fit content to available width; maintain reading order, meaningful gutters and target sizes | Assume device names guarantee space, hide essential actions or force page-level horizontal scrolling |
| Components | Choose the category that matches the task; preserve state distinctions and predictable keyboard behavior | Turn navigation into a button action, make static surfaces look clickable or invent selected/read-only states where they have no meaning |
| Accessibility | Target WCAG 2.2 AA across complete workflows; test keyboard, assistive technology, focus visibility and responsive states | Claim compliance from token values, a screenshot or an automated scan alone |
| Forms and validation | Keep labels visible; explain constraints; preserve input; connect errors to fields and give recovery guidance | Use placeholders as labels, reject untouched fields prematurely, erase values after failure or disable the only explanation of a prerequisite |
| Motion | Use brief purposeful transitions; respect reduced motion; make progress and completion understandable without animation | Add distracting loops, flash content, delay task completion or require movement to understand status |

Product-dependent adaptations must record their scope and retain the accessibility target. Review changes to semantic meaning, colour pairings, density, responsive thresholds, interaction models and motion before treating them as N1 requirements. This standalone registry is the complete definition of this proposed baseline; it does not replace authoritative Figma evidence or approved human guidance without that review.
