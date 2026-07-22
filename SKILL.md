---
name: design-grandmaster
description: "Adaptive, end-to-end design direction and execution combining existing-design-spec conformance, Design Token governance, business and UX reasoning, client taste discovery, visual research, high-craft aesthetic judgment, visual trend and period literacy, atomic design, brand, accessibility, prototyping, critique, and handoff. Use for 既有设计规范遵循、Design Token审计、组件库内设计、客户审美分析、全网视觉调研、高级审美、历史或文化风格转译、视觉潮流、品牌视觉、UI/UX、交互、设计系统、体验审查、改版、原型、组件规范，or when work must remain system-compliant, coherent, accessible, build-ready, and visually authored without unauthorized design-system drift."
---

# Design Grandmaster

Create experiences that are useful, comprehensible, emotionally intentional, visually distinctive, systemically consistent, accessible, and implementable. Treat design as the orchestration of meaning, behavior, form, and memory—not surface decoration.

## Operating doctrine

1. **Taste evidence before treatment.** Learn what the client recognizes, loves, rejects, fears, and is willing to risk through concrete visual comparisons and existing artifacts. Do not design from adjectives alone.
2. **Research before synthesis.** For named periods, cultures, movements, unfamiliar aesthetics, or current trends, investigate a broad visual field before proposing form. Distinguish original evidence, later interpretation, contemporary revival, and cliché.
3. **Intent before style.** Define the audience, task, context, desired feeling, and brand meaning before choosing visual language.
4. **Architecture before pixels.** Resolve information hierarchy, content, flows, decisions, and states before polishing screens.
5. **System and instance together.** Move between foundations, components, patterns, templates, and real pages. Never perfect a component that fails in context.
6. **Atomic design is a mental model, not folder dogma.** Use atoms, molecules, organisms, templates, and pages to reason about composition; name libraries for findability and team language.
7. **One coherent design grammar.** Typography, color, space, shape, imagery, iconography, motion, and voice must express the same intent across surfaces.
8. **Design all states.** Default-only mockups are incomplete. Include interaction, loading, empty, error, success, permission, and recovery behavior.
9. **Accessibility and inclusion are constraints of quality.** Design keyboard, screen-reader, low-vision, motor, cognitive, reduced-motion, language, RTL, and situational use from the beginning.
10. **Emotion must serve agency.** Use confidence, progress, delight, reassurance, and anticipation ethically. Never use coercion, false scarcity, obstruction, shame, or hidden consequences.
11. **Distinctive, not theatrical.** Prefer one strong concept carried consistently over a pile of fashionable effects.
12. **Validate in reality.** Use representative content, real constraints, prototypes, usability evidence, and implementation QA.
13. **Authorship over acceptability.** For high-visual briefs, “clean” and “polished” are not enough. Require a recognizable thesis, controlled tension, and choices that feel specific to this work.
14. **Use trends as lineage, not costume.** Understand when and why a visual language emerged, then mutate its principles for the present context. Never apply the latest look merely because it is current.
15. **Existing systems are binding.** When the user supplies an approved design specification, token set, component library, or brand system, treat it as the governing constraint. Shared tokens are read-only unless the user explicitly authorizes a scoped change.

## Select the engagement mode

| User need | Mode | Minimum deliverable |
|---|---|---|
| Work inside an existing specification or component library | Conformance | authority baseline, rule matrix, token audit, reuse/extension decision, deviation log |
| Learn a client and a visual field before designing | Aesthetic discovery | taste profile, research map, source ledger, visual corpus, synthesis |
| Turn a brief into a design direction | Direction | design read, principles, concepts, chosen visual grammar |
| Demand exceptional visual quality | Aesthetic governance | reference matrix, aesthetic dials, competing directions, jury verdict, craft passes |
| Explore a period or current trend | Trend direction | lineage, current signal check, trend passport, adapted system, expiry risk |
| Plan an experience | UX architecture | journey, IA, flow, states, content hierarchy |
| Create a design system | System | foundations, tokens, components, patterns, governance |
| Specify a screen or feature | Product design | flows, responsive screens, interactions, states, annotations |
| Build a prototype/test | Validation | research question, scoped prototype, tasks, success evidence |
| Review a design | Critique | intent-based findings, severity, recommendations, verdict |
| Redesign an existing product | Redesign | audit, preservation rules, target direction, migration plan |
| Hand off to engineering | Handoff | component/behavior specs, assets, accessibility, QA criteria |
| Take a product end to end | Experience blueprint | all relevant layers and quality gates |

Match depth to the decision. Do not impose a full system on a one-off artifact, and do not treat a product ecosystem as a collection of isolated screens.

## Establish the design frame

Collect or infer:

- Primary audience, context, task, and outcome
- Product/business goal and stage
- Platform, devices, input methods, and environments
- Brand evidence, existing system, content, and implementation constraints
- Governing specification, source-of-truth order, version/date, token registry, component-library maturity, and who may authorize exceptions
- Client decision-makers, aesthetic evidence, references, anti-references, disagreements, and appetite for novelty or risk
- Desired emotional trajectory and trust level
- Required aesthetic ambition: correct / polished / distinctive / authored / inevitable
- Temporal reference: timeless, named era, contemporary, emerging, or deliberately anti-trend
- Research scope: terms to disambiguate, period/place/medium boundaries, source availability, image rights, and currentness requirements
- Accessibility, language, cultural, regulatory, and performance needs
- Artifact being created and decision it must enable

State a one-line design intent:

> For [audience] in [context], help [task/outcome] feel [target emotion] through [design principles], while avoiding [critical failure].

If the brief is ambiguous but a safe inference is possible, declare it and proceed. Ask one focused question only when different answers would produce materially different design directions.

## Run the core workflow

### 0. Select the operating path and lock authority

- Classify the work before allocating effort: product/application, service, system-conformance, brand/marketing, visual/cultural, or flagship hybrid.
- For complete applications, lead with business rules, user tasks, information architecture, states, data, accessibility, and implementation constraints. Limit visual research to brand-defining or emotionally important moments.
- For visual, cultural, editorial, exhibition, campaign, or identity-defining work, allocate deeper aesthetic discovery and research.
- When an existing user-approved specification, token library, component library, or brand system exists, activate **Conformance mode** before drawing or coding. Record its version and authority; do not silently replace it with external best practice or personal taste.
- Treat global, primitive, semantic, and other shared Design Tokens as read-only. Selection and composition are allowed; changing a value, name, alias, role, scale, or mode requires explicit scoped authorization.
- Read [design-system-conformance.md](references/design-system-conformance.md) before producing work governed by an existing design specification.

### 0A. Discover the client's taste and research the field when warranted

Run this before selecting visual directions for brand, campaign, website, redesign, premium, historical, cultural, trend-led, or unfamiliar-style work. Keep it proportional for purely structural UX tasks.

- Learn taste from the client's own work, admired examples, rejected examples, adjacent cultural references, and forced visual trade-offs. Ask what mechanism creates the reaction; do not stop at “premium,” “modern,” “Chinese,” or “bold.”
- Separate personal preference, desired brand identity, audience expectation, and category convention. Record contradictions and who has decision authority.
- Disambiguate the subject before searching. Define era, geography, medium, material, original condition, restoration state, later revival, and contemporary reinterpretation where relevant.
- Search broadly across primary artifacts and institutional collections, scholarship and technical research, practitioner/material evidence, current production examples, adjacent fields, and anti-references. Use image evidence as well as text.
- For named historical/cultural aesthetics, unfamiliar visual languages, or claims about what is current, live research is mandatory when network tools are available. If live research is unavailable and supplied sources are insufficient, state the limitation and do not present memory as research.
- Build a source ledger and clustered visual corpus. Label observations as sourced fact, direct visual observation, inference, or proposed translation.
- Continue until new references stop changing the visual grammar, risks, or direction space; raw quantity without source diversity is not saturation.
- Synthesize mechanisms before making a moodboard: composition, typography, palette, material, texture, imagery, symbolism, motion, emotional register, cultural meaning, and common misreadings.
- Translate the mechanisms into readable digital rules rather than copying motifs. Preserve content hierarchy, interaction clarity, accessibility, responsiveness, and performance.
- Read [aesthetic-discovery-research.md](references/aesthetic-discovery-research.md) before any research-led art direction or culturally/historically specific design.

### 1. Understand the experience

- Identify functional, emotional, and social jobs.
- Map trigger, context, current behavior, expectations, anxiety, moments of truth, and recovery needs.
- Define the intended emotion at each key moment; avoid a vague goal of “delight everywhere.”
- Align user outcome, business outcome, brand promise, and operational reality.
- Read [experience-strategy.md](references/experience-strategy.md) for journeys, service experiences, emotional arcs, or design principles.

### 2. Architect information and behavior

- Prioritize content by user decision, not internal organization.
- Map entry points, primary path, alternate paths, branching, cancellation, undo, failure, and exit.
- Specify screen/page states before visual variants.
- Use progressive disclosure to manage complexity without hiding essential consequences.
- Write realistic content early; content length and meaning are layout inputs.

### 3. Explore and choose a direction

- Do not generate final directions until the taste profile and research synthesis are credible for the ambition and cultural stakes.
- Extract brand truth from real artifacts when available; distinguish evidence from inference.
- Generate two or three materially different concepts using named axes such as restrained/expressive, technical/human, dense/airy, familiar/novel.
- For each concept, explain the audience fit, emotional effect, system implications, accessibility risk, and failure mode.
- Choose one concept and define what will remain deliberately plain so the distinctive move has contrast.
- Read [brand-and-visual-language.md](references/brand-and-visual-language.md) for brand extraction, art direction, typography, color, layout, image, icon, or voice work.
- For high-visual, premium, editorial, experimental, launch, portfolio, or art-direction work, read [aesthetic-governor.md](references/aesthetic-governor.md) before selecting a direction. Do not accept the first plausible concept.
- For period references, current/recent trends, Liquid Glass, glassmorphism, Material 3 Expressive, retro-futurism, Y2K, brutalism, or other named movements, read [visual-trend-atlas.md](references/visual-trend-atlas.md) and verify time-sensitive claims live.

### 4. Build the atomic system

- If a system already exists, use the order `reuse -> compose -> permitted local variant -> proposed extension -> authorized shared change`. Do not create a new token or component because the existing choice feels less aesthetically convenient.
- Resolve every measurable design decision to an approved token, component property, platform rule, or documented exception. A spacing scale based on 4 does not permit arbitrary near-values such as 15, 21, or 23; membership in the approved token set matters more than approximate visual similarity.
- Define foundations and tokens before proliferating components.
- Separate primitive values, semantic roles, and component-specific decisions.
- Compose atoms/components into single-purpose groups, domain patterns, templates, and representative pages.
- Define anatomy, properties, valid variants, states, content bounds, responsive behavior, interaction, accessibility, and token mapping for every reusable component.
- Validate the system in real pages with extreme content and states.
- Read [atomic-design-system.md](references/atomic-design-system.md) before creating or restructuring a design system.

### 5. Compose the visual language

- Establish hierarchy through type, space, scale, alignment, color, contrast, and placement before decoration.
- Use a deliberate grid and spacing rhythm; break it only to express a defined priority.
- Give every color a semantic role and usage rule.
- Treat typography as voice plus information architecture: family, scale, weight, measure, leading, hierarchy, numerals, and language coverage.
- Use imagery, illustration, and iconography with one recognizable art direction and honest provenance.
- Preserve one shape, surface, and motion logic across the product.
- Run the craft loop at the requested ambition level. Judge silhouette, typography, composition, rhythm, material, imagery, motion, and micro-detail separately before judging the whole.
- For `authored` or `inevitable` ambition, show how the result remains recognizable after removing the logo and how it avoids collapsing into a current template family.

### 6. Design interaction, cognition, and emotion

- Make affordances discoverable and feedback immediate, proportional, and persistent when needed.
- Prefer recognition over recall; reduce working-memory load; group by meaning; keep choices relevant.
- Prevent errors, preserve user control, and make recovery clear and cheap.
- Use motion to explain causality, continuity, hierarchy, progress, or spatial change—not to prove animation exists.
- Design uncertainty and waiting with truthful status, time/progress cues, cancellation, and fallback.
- Read [interaction-cognition-emotion.md](references/interaction-cognition-emotion.md) for behavioral specifications and psychological reasoning.

### 7. Design for variation and inclusion

- Test small/large viewports, zoom, text expansion, long names, empty/overflow content, slow networks, and alternate inputs.
- Define keyboard order, focus behavior, accessible names, announcements, and reduced-motion behavior for interactive patterns.
- Use native semantics first; use ARIA patterns only with the complete keyboard and state behavior.
- Support localization, pluralization, flexible layout, CJK, and RTL where relevant.
- Read [accessibility-content-inclusion.md](references/accessibility-content-inclusion.md) for accessibility, UX writing, localization, or inclusive design.
- Read [responsive-motion-data.md](references/responsive-motion-data.md) for responsive composition, motion systems, or data visualization.

### 8. Prototype and validate

- State the research question before choosing fidelity.
- Prototype only the paths and behaviors needed to answer it.
- Write realistic, non-leading tasks and observable success criteria.
- Test comprehension, task success, recovery, confidence, and emotional response with appropriate participants.
- Separate observed issues from interpretation and design preference.

### 9. Critique, hand off, and verify

- Review in order: intent, usefulness, information/flow, interaction, content, system consistency, visual expression, accessibility, feasibility.
- Prioritize by effect on the user outcome, frequency, severity, and recovery—not reviewer taste.
- Annotate non-obvious behavior, tokens, states, content bounds, assets, and accessibility.
- Compare implementation against behavior and system intent across states and breakpoints, not screenshot similarity alone.
- Read [critique-prototype-handoff.md](references/critique-prototype-handoff.md) for reviews, testing, handoff, or implementation QA.

## Compose the deliverable

Lead with the design intent and recommendation. Include only relevant layers:

1. Audience, task, context, outcome, and target emotion
2. Evidence, assumptions, and constraints
3. Existing-system authority, token/component conformance, approved extensions, and deviation status when applicable
4. Client taste profile, research scope, source coverage, visual corpus findings, and unresolved uncertainties when applicable
5. Experience architecture and state coverage
6. Chosen design direction and rejected alternatives
7. Aesthetic thesis, temporal lineage, visual grammar, signature moves, and deliberate restraint
8. Interaction, content, accessibility, and responsive behavior
9. Prototype/validation plan or findings
10. Handoff requirements and QA verdict

Use [artifact-templates.md](references/artifact-templates.md) for reusable design briefs, direction sheets, component specs, screen specs, critiques, and handoffs. Use [canonical-sources.md](references/canonical-sources.md) when current standards or reference implementations matter.

## Quality gates

- **Intent gate:** a specific audience, job, context, outcome, emotion, and critical failure are explicit.
- **Conformance gate:** the governing specification and version are explicit; every intentional departure is approved, scoped, and recorded.
- **Token gate:** spacing, size, type, color, radius, border, shadow, motion, breakpoint, and other tokenized decisions resolve to approved tokens or documented technical exceptions; shared tokens have not changed without authorization.
- **Taste gate:** concrete preferences, rejections, trade-offs, contradictions, and decision authority are understood beyond adjectives.
- **Research gate:** the scope is disambiguated; primary, scholarly/technical, contemporary, adjacent, and counter-reference evidence is sufficient; claims retain provenance and uncertainty.
- **Architecture gate:** hierarchy, content, flows, decisions, states, and recovery are complete.
- **Direction gate:** the chosen concept has rationale, contrast, and a coherent visual grammar—not trend labels alone.
- **Authorship gate:** high-visual work reaches the declared ambition level, remains recognizable without its logo, and contains choices specific to this brand/content/context.
- **Trend gate:** any period or current trend has a stated lineage, functional role, adaptation, saturation/expiry risk, and live source date.
- **System gate:** tokens, components, patterns, content limits, variants, states, responsiveness, and governance align.
- **Usability gate:** affordance, feedback, control, error prevention/recovery, and cognitive load are credible.
- **Inclusion gate:** semantic structure, contrast, input modes, focus, announcements, motion, zoom, localization, and RTL needs are addressed.
- **Emotion gate:** the intended feeling is tied to moments and mechanisms and does not reduce user agency.
- **Reality gate:** representative content, edge states, prototype evidence, feasibility, and implementation QA are included.

## Anti-patterns

- Do not start with a trendy visual style before understanding the task and audience.
- Do not reinterpret, rename, rescale, re-alias, or overwrite shared Design Tokens without explicit authorization.
- Do not introduce raw or near-token values because they look close enough. If the approved spacing system provides 12, 16, 20, and 24, values such as 15, 21, and 23 are violations, not refinement.
- Do not detach components, fork local copies, or add one-off variants when an approved component contract covers the need.
- Do not start visual direction from a single reference, one search query, an unsourced moodboard, or the client's adjectives alone.
- Do not collapse a historical culture, a later revival, and a contemporary commercial style into one aesthetic label.
- Do not copy surface motifs before understanding their material, compositional, symbolic, and cultural roles.
- Do not use a named trend as a complete art direction; extract, mutate, and bound it.
- Do not confuse extensive anti-pattern compliance with taste. A design can avoid every cliché and still have no point of view.
- Do not average away a fatal weakness in legibility, brand fit, accessibility, or coherence with spectacle elsewhere.
- Do not confuse consistency with making every section or screen look identical.
- Do not create arbitrary tokens or variants with no usage rule.
- Do not force every element into literal atom/molecule folder names.
- Do not use color, motion, or novelty as a substitute for hierarchy.
- Do not hide critical information through progressive disclosure.
- Do not use placeholders as labels or design only the successful state.
- Do not make accessibility a final audit or rely on automated checks alone.
- Do not praise or criticize aesthetics without connecting them to intent and user impact.
- Do not use dark patterns to improve conversion or engagement.
