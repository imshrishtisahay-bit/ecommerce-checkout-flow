---
title: "Design System"
description: "A sample design system reference for the portfolio site."
---

# Design System

Everything related to your reusable UI components and the design tokens behind them.

<p class="ds-note">Tokens below are taken from the week 4 <code>tokens.json</code> and the week 7 payment-method final screen — colors, type, spacing, and radius all match the checkout flow.</p>

## Design Tokens

### Colors

{{< swatchgrid >}}
{{< swatch name="Surface / Primary" value="#091E48" class="bg-primary" >}}
{{< swatch name="Surface / Secondary" value="#185277" class="bg-secondary" >}}
{{< swatch name="Surface / Tertiary" value="#56C8C8" class="bg-accent" >}}
{{< swatch name="Surface / Quaternary" value="#FFFAFA" class="bg-surface" >}}
{{< swatch name="Text / Tertiary" value="#091E48" class="bg-text" >}}
{{< swatch name="Success" value="#2F855A" class="bg-success" >}}
{{< swatch name="Warning" value="#D97706" class="bg-warning" >}}
{{< swatch name="Error" value="#FF3333" class="bg-error" >}}
{{< swatch name="Background" value="#ffffff" class="bg-soft" >}}
{{< /swatchgrid >}}

### Typography

Type pairing: **Roboto** (headings & display) + **Inter** (body, UI, labels).

<div class="ds-type">
  <div class="ds-type-row">
    <span class="ds-type-meta">Display · Roboto 900 · 40px</span>
    <span class="ds-type-sample h-display">Checkout</span>
  </div>
  <div class="ds-type-row">
    <span class="ds-type-meta">Heading · Roboto 700 · 26px</span>
    <span class="ds-type-sample h-heading">Payment method</span>
  </div>
  <div class="ds-type-row">
    <span class="ds-type-meta">Subheading · Roboto 700 · 18px</span>
    <span class="ds-type-sample h-subheading">Choose how you'd like to pay</span>
  </div>
  <div class="ds-type-row">
    <span class="ds-type-meta">Body · Inter 400 · 16px</span>
    <span class="ds-type-sample h-body">This is an example of body text used for explanatory content and supporting details.</span>
  </div>
  <div class="ds-type-row">
    <span class="ds-type-meta">Button · Inter 600 · 15px</span>
    <span class="ds-type-sample h-button">PAY NOW</span>
  </div>
  <div class="ds-type-row">
    <span class="ds-type-meta">Label · Inter 600 · 13px · uppercase</span>
    <span class="ds-type-sample h-label">Card number</span>
  </div>
  <div class="ds-type-row">
    <span class="ds-type-meta">Caption · Inter 400 · 13px</span>
    <span class="ds-type-sample h-caption">We encrypt your payment details end-to-end.</span>
  </div>
</div>

### Spacing

Spacing scale from <code>tokens.json</code> — 4px base unit.

<div class="ds-spacing">
  <div class="ds-space-row"><span class="name">xs</span><span class="ds-space-bar" style="width:4px"></span><span class="token">4px</span></div>
  <div class="ds-space-row"><span class="name">sm</span><span class="ds-space-bar" style="width:8px"></span><span class="token">8px</span></div>
  <div class="ds-space-row"><span class="name">md</span><span class="ds-space-bar" style="width:12px"></span><span class="token">12px</span></div>
  <div class="ds-space-row"><span class="name">lg</span><span class="ds-space-bar" style="width:16px"></span><span class="token">16px</span></div>
  <div class="ds-space-row"><span class="name">xl</span><span class="ds-space-bar" style="width:24px"></span><span class="token">24px</span></div>
</div>

### Radius

<div class="ds-radius">
  <div class="ds-radius-card">
    <div class="ds-radius-box r-sm"></div>
    <div class="name">Small</div><div class="token">4px</div>
  </div>
  <div class="ds-radius-card">
    <div class="ds-radius-box r-lg"></div>
    <div class="name">Large</div><div class="token">8px</div>
  </div>
  <div class="ds-radius-card">
    <div class="ds-radius-box r-pill"></div>
    <div class="name">Pill</div><div class="token">999px</div>
  </div>
</div>

### Shadow / Elevation

<div class="ds-shadow">
  <div class="ds-shadow-card low"><div class="name">Low</div><div style="color:#6b7280;font-size:.8rem">resting surfaces</div></div>
  <div class="ds-shadow-card med"><div class="name">Medium</div><div style="color:#6b7280;font-size:.8rem">cards, popovers</div></div>
  <div class="ds-shadow-card high"><div class="name">High</div><div style="color:#6b7280;font-size:.8rem">dialogs, sheets</div></div>
</div>

### Opacity

<div class="ds-opacity">
  <div class="ds-opacity-card"><div class="ds-opacity-box o-80"></div><div class="name">0.8</div></div>
  <div class="ds-opacity-card"><div class="ds-opacity-box o-60"></div><div class="name">0.6</div></div>
  <div class="ds-opacity-card"><div class="ds-opacity-box o-40"></div><div class="name">0.4</div></div>
</div>

## Color Palette

The checkout flow is anchored on a deep-navy primary with a teal tertiary accent for interactive highlights.

- **Primary** `#091E48` — brand navy, primary buttons, headers
- **Secondary** `#185277` — supporting navy, secondary buttons, links
- **Tertiary** `#56C8C8` — teal accent, focus rings, highlights
- **Quaternary** `#FFFAFA` — off-white text on dark surfaces
- **Error** `#FF3333` — validation errors, destructive actions
- **Success** `#2F855A` · **Warning** `#D97706` — feedback states
- **Background** `#ffffff` — app canvas

## Typography in Context

{{< designcard >}}
# Display heading

## Section heading

### Subheading

This is an example of body text used for explanatory content and supporting details.

Muted text helps separate secondary information without reducing readability.
{{< /designcard >}}

## Grid

12-column fluid grid with a 960px max container; collapses to 6 columns on mobile.

<div class="ds-grid-demo">
  <span>1</span><span>2</span><span>3</span><span>4</span><span>5</span><span>6</span>
  <span>7</span><span>8</span><span>9</span><span>10</span><span>11</span><span>12</span>
</div>
<p class="ds-grid-note">Spacing units 4 / 8 / 16 / 24px govern gutters and section rhythm.</p>

## Components

### Buttons

{{< designcard >}}
<button class="button">Primary action</button>
<a class="link-pill" href="#">Secondary link</a>
{{< /designcard >}}

### Text Fields

<div class="ds-field">
  <label for="ds-card">Card number</label>
  <input id="ds-card" type="text" placeholder="1234 5678 9012 3456">
  <span class="helper">Helper text — enter the 16 digits on your card.</span>
</div>
<div class="ds-field error">
  <label for="ds-card-err">Expiry date</label>
  <input id="ds-card-err" type="text" placeholder="MM/YY" value="13/26">
  <span class="error-text">Please enter a valid expiry date.</span>
</div>

### Cards

<div class="ds-cards">
  <div class="ds-card">
    <div class="title">Informational card</div>
    <p style="margin:.25rem 0 0;font-size:.9rem;color:#374151">Neutral container for grouped content.</p>
  </div>
  <div class="ds-card feature">
    <div class="title">Feature card</div>
    <p style="margin:.25rem 0 0;font-size:.9rem;opacity:.9">Dark surface to draw attention.</p>
  </div>
  <div class="ds-card">
    <div class="title">Summary card</div>
    <p style="margin:.25rem 0 0;font-size:.9rem;color:#374151">Compact recap of order details.</p>
  </div>
</div>

### Navigation

<div class="ds-nav">
  <span class="brand-mini">Shrishti</span>
  <span class="links">
    <a href="#">Home</a>
    <a href="#">Guidelines</a>
    <a href="#">Design System</a>
  </span>
</div>

### Badges

<div class="ds-badges">
  <span class="badge new">New</span>
  <span class="badge featured">Featured</span>
  <span class="badge updated">Updated</span>
  <span class="badge error">Error</span>
</div>

### Icons

- Consistent 2px stroke style on a 24px grid
- Clear visual meaning — no decorative-only icons in flows
- Inherit current color for flexible theming

### Dialogs

<div class="ds-overlay">
  <div class="ds-dialog">
    <strong>Cancel order?</strong>
    <p style="margin:.5rem 0 0;color:#374151;font-size:.9rem">This will clear your cart and you'll need to start over.</p>
    <div class="actions">
      <a class="button secondary" href="#" style="margin-top:0">Keep order</a>
      <a class="button" href="#" style="margin-top:0">Cancel</a>
    </div>
  </div>
  <div class="ds-sheet">
    <strong>Action sheet</strong>
    <p style="margin:.5rem 0 0;color:#374151;font-size:.9rem">Mobile-friendly panel sliding up from the bottom edge.</p>
  </div>
</div>

### Bottom Sheet

The bottom sheet is a mobile-first panel anchored to the bottom of the viewport (rounded top corners, high elevation) used for filters, payment-method pickers, and quick actions.

### Snackbars

<div class="ds-snacks">
  <div class="snack success">✓ Payment successful</div>
  <div class="snack error">✕ Payment failed — please retry</div>
  <div class="snack info">ℹ Coupon applied</div>
</div>

## States

<div class="ds-states">
  <div class="ds-state"><div class="name">Hover</div><span class="demo-btn hover">Pay now</span></div>
  <div class="ds-state"><div class="name">Focus</div><span class="demo-btn focus">Pay now</span></div>
  <div class="ds-state"><div class="name">Pressed</div><span class="demo-btn pressed">Pay now</span></div>
  <div class="ds-state"><div class="name">Disabled</div><span class="demo-btn disabled">Pay now</span></div>
  <div class="ds-state"><div class="name">Loading</div><span class="demo-btn loading">Pay now</span></div>
</div>

- **Hover** — secondary navy fill signals interactivity
- **Focus** — 2px teal outline ring for keyboard users (WCAG 2.4.7)
- **Pressed** — darker navy confirms the press
- **Disabled** — greyed fill, `not-allowed` cursor
- **Loading** — spinner inline, input blocked
- **Error / Success** — field border + text color per the color palette
