# Responsive Composition, Motion, and Data

Use this module for multi-device behavior, motion systems, and information-dense/data experiences.

## Responsive composition

Design by content pressure and task priority, not device labels alone.

For each region specify:

- Minimum/maximum width and content measure
- Grid/stack change points
- Priority and reading order
- Wrap, truncate, scroll, collapse, or relocate behavior
- Input method differences
- Sticky/fixed behavior and viewport safety
- Extreme content and localization

Preserve semantic/DOM order across layouts. Do not visually reorder content into a confusing keyboard or screen-reader sequence.

### Adaptation choices

- **Reflow:** same content, new arrangement
- **Resize:** fluid scale within safe bounds
- **Reprioritize:** move secondary content later
- **Substitute:** use a different control appropriate to context
- **Collapse:** hide detail behind an explicit control
- **Scroll:** appropriate for tables, timelines, galleries when context stays visible
- **Remove:** only when genuinely nonessential

Avoid shrinking desktop composition until it technically fits.

## Responsive typography

- Use semantic roles with fluid bounds where appropriate.
- Validate line length, line count, hierarchy, and control labels at every breakpoint.
- Keep body text comfortably readable without horizontal scrolling.
- Avoid type that becomes decorative and unusable on small screens.
- Test user font scaling and language-specific metrics.

## Motion system

Define tokens by purpose, not arbitrary milliseconds:

- Immediate feedback
- Small state transition
- Container/layout transition
- Enter/exit
- Deliberate storytelling only when the experience supports it

Specify duration, easing, property, trigger, interruption behavior, reduced-motion alternative, and performance budget.

Rules:

- Animate transform and opacity when possible.
- Keep input feedback immediate.
- Preserve continuity between origin and destination.
- Allow interruption and avoid trapping the user in animation.
- Do not animate every element independently.
- Never require motion to understand state.

## Data and dense interfaces

Start with the decision:

- What question should the user answer?
- What comparison, trend, distribution, part-to-whole, relationship, or anomaly matters?
- What precision and uncertainty are required?

Choose representation accordingly. Prefer position/length for precise comparison, then angle/area, and use color carefully. Tables are correct for lookup and exact values; charts are correct for patterns.

### Data visualization contract

- Title states the question or finding
- Units, time window, population, filters, source, and freshness
- Honest baseline and scale
- Uncertainty, missing data, and estimates distinguished
- Color not the only encoding
- Accessible data table or equivalent
- Tooltips supplement rather than contain essential information
- Responsive behavior preserves comparison
- Empty, loading, partial, stale, and error states

Avoid decorative chart variety, dual axes without strong justification, truncated scales that distort, rainbow palettes, and dashboards where every metric has equal emphasis.

## Performance as experience

- Reserve space to avoid layout shift.
- Prioritize meaningful content and interaction readiness.
- Use progressive loading with stable structure.
- Compress and size media for display context.
- Respect battery, bandwidth, and reduced-data constraints when relevant.
- Test slow networks and low-end devices for critical paths.

Perceived performance must remain truthful; never fake completion or hide stalled work.
