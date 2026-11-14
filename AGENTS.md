# Agent instructions for this skills library

This repository is the design/frontend skill source of truth for projects maintained by tatarhost.

## Mandatory workflow for website/UI work

1. Read this file and CATALOG.md first.
2. Before writing UI code, read the relevant instructions from the repository. The default foundation is:
   - skills/frontend-design/SKILL.md
   - skills/impeccable/SKILL.md
   - skills/frontend-ui-engineering/SKILL.md
   - skills/design-engineering/SKILL.md
3. Choose the direction with skills/ui-ux-pro-max/SKILL.md and skills/refero-design/SKILL.md; read their referenced data and craft references as needed.
4. If visual research, Figma, native UI, graphics, animation, or a specific framework is relevant, load the matching skill from CATALOG.md.
5. Before the first implementation line, write a project-level DESIGN.md that records: (a) subject/product, (b) target users and constraints, (c) visual direction, (d) one chosen UI style, (e) typography/color/spacing/radius/motion tokens, and (f) source references.
6. Keep implementation aligned to DESIGN.md. Do not invent design tokens when the relevant skill provides a method or values.
7. After the first working build, review where applicable with better-interface, better-ui, break-ui, better-accessibility, and Addy's accessibility. Use web-design-guidelines when its upstream terms permit reading. Fix high-severity issues before visual polish.
8. For animation work, load animate first, then relevant skills such as choreograph, review-animations, improve-animations, animation-performance, and remove-animations.
9. For responsive/mobile work, include mobile-native, better-layout, and better-accessibility as appropriate. Respect reduced-motion, keyboard, focus, contrast, zoom and touch targets.
10. End with a brief report: skills read, files changed, review findings fixed, and any unavailable/upstream-only skills.

## Source and license rules

- Read and preserve each skill's SOURCE.md.
- Keep upstream notices and license texts. Do not strip attribution.
- A skill marked link-only is intentionally not mirrored because the repository did not provide a redistribution license. Read it at its upstream URL when relevant; do not copy its full text into this repository.
- The presence of a skill here does not imply that its CLI, MCP server, Figma connection, font assets, or runtime binary has been installed. State those limitations honestly.
- Prefer complete upstream instructions and their local reference files; never pretend to have read an uninspected file.
