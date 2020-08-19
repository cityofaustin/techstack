---
name: Dev handoff checklist
about: What to consider when writing acceptance criteria for new content types and
  larger feature sets
title: ''
labels: ''
assignees: ''

---

Visual design
- [ ] Mocks for all breakpoints
  - [ ] [Desktop](paste URL here)
  - [ ] [Tablet](paste URL here)
  - [ ] [Mobile](paste URL here)
- [ ] All interactive states: includes all applicable interactive states (hover, down, focus, keyboard focus, disabled)
- [ ] Defined behaviors: includes guidelines for layout (wrapping, truncation, overflow), animation, interactions, etc.
- [ ] Usage guidelines: includes a list of dos and don'ts that highlight best practices and common mistakes
- [ ] Accessible contrast: follows WCAG 2.0 standards for contrast. Minimum is AA, but we should strive for AAA where possible.
- [ ] Keyboard interactions: follows WCAG 2.0 standards for keyboard accessibility guidelines and includes a description of keyboard interactions.
- [ ] Spec is merged into Master XD file
- [ ] Design tokens: all design attributes (color, typography, layout, animation) are included. We're not using tokens yet, but ensuring that the values are consistent before going to dev is a must.
- [ ] Translations: is there anything hardcoded in Janis that needs to be translated to Spanish? What else do we need to consider?
- [ ] Previews: Will this content type or feature set require previews in Janis? 
- [ ] Unit tests: Will we need to write any unit tests for this content type or feature set?
