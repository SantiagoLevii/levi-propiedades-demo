Top 5 improvements, ranked by impact:

  1. No :active press feedback on any button
  Every clickable element - .submit-btn, .hw-btn, .nav-cta, .om-btn - gives zero tactile
  feedback on press. The interface feels dead. Adding transform: scale(0.97) on :active with
  a 100-160ms ease-out transition is the single change that most immediately elevates how
  premium the whole site feels.

  2. Hero has no typographic anchor
  The hero jumps straight from a 12px eyebrow label into a search widget. There is no
  headline - no emotional moment, no brand confidence. Luxury real estate sites lead with a
  dominant display statement (large, tight letter-spacing, mixed weight) before offering
  utility. The search widget doing all the work makes it feel like a portal, not a boutique
  agency.

  3. Scroll reveal animations are sluggish
  .reveal runs at 0.6s ease with only translateY(20px). At 600ms with the default ease curve
  (which starts slow), sections feel heavy as they enter. Cutting to ~400ms with a strong
  ease-out (cubic-bezier(0.23, 1, 0.32, 1)) and increasing the translate to ~32px would make
  arrivals feel snappy and intentional instead of labored.

  4. Scrolling strips have hard edges
  Both the hero ticker and the amenities strip end abruptly at the viewport edge. Premium
  sites mask these with gradient fade-outs using ::before/::after pseudo-elements
  1. No :active press feedback on any button
  Every clickable element - .submit-btn, .hw-btn, .nav-cta, .om-btn - gives zero tactile
  feedback on press. The interface feels dead. Adding transform: scale(0.97) on :active with
  a 100-160ms ease-out transition is the single change that most immediately elevates how
  premium the whole site feels.

  2. Hero has no typographic anchor
  The hero jumps straight from a 12px eyebrow label into a search widget. There is no
  headline - no emotional moment, no brand confidence. Luxury real estate sites lead with a
  dominant display statement (large, tight letter-spacing, mixed weight) before offering
  utility. The search widget doing all the work makes it feel like a portal, not a boutique
  agency.

  3. Scroll reveal animations are sluggish
  .reveal runs at 0.6s ease with only translateY(20px). At 600ms with the default ease curve
  (which starts slow), sections feel heavy as they enter. Cutting to ~400ms with a strong
  ease-out (cubic-bezier(0.23, 1, 0.32, 1)) and increasing the translate to ~32px would make
  arrivals feel snappy and intentional instead of labored.

  4. Scrolling strips have hard edges
  Both the hero ticker and the amenities strip end abruptly at the viewport edge. Premium
  sites mask these with gradient fade-outs using ::before/::after pseudo-elements
  look unfinished - it is one of those invisible details that users feel without identifying.

  5. All easing curves are generic
  a 100-160ms ease-out transition is the single change that most immediately elevates how
  premium the whole site feels.

  2. Hero has no typographic anchor
  The hero jumps straight from a 12px eyebrow label into a search widget. There is no
  headline - no emotional moment, no brand confidence. Luxury real estate sites lead with a
  dominant display statement (large, tight letter-spacing, mixed weight) before offering
  utility. The search widget doing all the work makes it feel like a portal, not a boutique
  agency.

  3. Scroll reveal animations are sluggish
  .reveal runs at 0.6s ease with only translateY(20px). At 600ms with the default ease curve
  (which starts slow), sections feel heavy as they enter. Cutting to ~400ms with a strong
  ease-out (cubic-bezier(0.23, 1, 0.32, 1)) and increasing the translate to ~32px would make
  arrivals feel snappy and intentional instead of labored.

  4. Scrolling strips have hard edges
  Both the hero ticker and the amenities strip end abruptly at the viewport edge. Premium
  sites mask these with gradient fade-outs using ::before/::after pseudo-elements
  (background: linear-gradient(to right, var(--bg), transparent)). Without these, the strips
  look unfinished - it is one of those invisible details that users feel without identifying.

  5. All easing curves are generic
  Every transition in the file uses bare ease or linear with no custom cubic-bezier. The
  modal, card image zoom, nav link hovers, form focus underlines - motion has no personality.
  Defining --ease-out: cubic-bezier(0.23, 1, 0.32, 1) once and applying it throughout
  creates consistent, punchy motion that reads as intentional craftsmanship rather than
  browser defaults.
