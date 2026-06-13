# Design Reference — Higher Drones

## Design objective

Build a fast, static, GitHub Pages-compatible website that follows the uploaded platform mockup as closely as practical while preserving the Coluve local-service-first strategy.

The website should feel visually polished like Colin's Tradework, but should follow this platform's own mockup for layout, tone, content hierarchy, and brand personality.

## Mockup source

Primary mockup image:

    design/mockups/primary-mockup.png

## Platform-specific visual notes

Contractor and property project showcase with drone compliance kept conservative.

## Design priorities

1. Recreate the mockup's overall visual direction.
2. Preserve the platform's local-service-first offer.
3. Keep the website static, fast, and lightweight.
4. Use semantic HTML and simple CSS.
5. Make the first sellable service clear within 5 seconds.
6. Keep the primary CTA visible.
7. Preserve GitHub Pages compatibility.

## Use Colin's Tradework as a quality reference

Colin's Tradework is the quality/reference site.

Use it only for:

- professional local-service structure,
- spacing and section rhythm,
- trust-building flow,
- CTA clarity,
- polished contractor/service feel.

Do not copy:

- Colin's Tradework text,
- testimonials,
- images,
- project claims,
- service claims,
- customer-specific content.

## Mockup interpretation rules

When recreating the mockup, infer:

- page structure,
- hero composition,
- spacing,
- section order,
- color direction,
- typography feel,
- card style,
- CTA placement,
- visual hierarchy,
- footer structure.

If the mockup conflicts with docs/company-context.md or docs/local-service-offer.md, prioritize the business docs.

If the mockup includes vague platform language, convert it into a clear local service offer.

## Required website sections

The generated site should include:

1. Header
2. Hero section
3. Local service offer section
4. Who this is for
5. What is included
6. How it works
7. Trust/proof section using safe placeholder language only
8. Service area
9. Final CTA
10. Footer

## Safety rules

Do not add:

- payments,
- booking backends,
- forms,
- analytics,
- tracking pixels,
- account systems,
- dashboards,
- API calls,
- new dependencies,
- legal/privacy/terms finalization,
- fake testimonials,
- fake certifications,
- fake guarantees,
- unsupported health, eco, safety, housing, drone, GPS, tokenization, financial, investment, compliance, or AI claims.

## Output requirements for Codex

Codex should update:

- index.html
- style.css
- waypoints/ledger.md
- reports/YYYY-MM-DD-agent-report.md

Codex may update docs if needed.

Open a PR only. Do not merge.

## Current client-facing asset

- `assets/higher-drones-showcase.svg` supports the refined static site with a cinematic project-showcase visual inspired by the mockup's altitude, lens, route, and media-card direction.
- The asset is illustrative only and does not imply guaranteed flight, pilot availability, regulatory clearance, airspace approval, certification, insurance coverage, safety assurance, training, licensing, drone shows, payments, or booking functionality.

## Refinement rationale

The mockup's strongest measurable advantages are immediate visual distinctiveness, a large first-viewport promise, a persistent CTA, and scannable service modules. The refined page keeps those conversion advantages while replacing risky platform mechanics with a manually scoped contractor project showcase offer and explicit boundaries.
