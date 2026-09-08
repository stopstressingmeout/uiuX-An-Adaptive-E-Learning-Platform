# Roadmap

The project followed an **Agile** methodology as its SDLC model, structured into four sprints rather than a single upfront design-then-build cycle. This allowed research findings and interview feedback to feed back into scope before each phase.

## Build phases (as planned)

1. **Sprint 1 — Planning & architecture:** project scope, database schema, and system architecture setup
2. **Sprint 2 — Core features (MVP):** video lecture module, pop-up quiz system, basic progress dashboard
3. **Sprint 3 — Advanced features:** note-taking system, time tracking, exploration of future personalization features
4. **Sprint 4 — Testing & deployment:** unit/integration/system testing, performance optimization, bug fixes, deployment

## What shipped vs. what's scoped

Core features (video playback, pop-up quizzes, progress dashboard, notes) reached a working prototype. Time tracking, the recommendation engine, and adaptive level identification were fully specified (requirements, UI, and data flow defined) but not completed within the original project timeline.

## Future work

- **Time tracking** — surfacing study-time analytics per lecture/course
- **Recommendation engine** — content suggestions driven by level and performance gaps
- **Level identification** — automated Beginner/Average/Advanced classification from quiz results
- **Fairness-aware recommendations** — avoiding bias in what content gets suggested to whom
- **Offline mode expansion** — beyond downloadable video, offline access to quizzes and notes
- **Accessibility hardening** — full WCAG compliance (screen reader support, adjustable text sizing, subtitles across all content)

## My prioritization view

If I were sequencing this backlog today as a PO, I'd move level identification ahead of the recommendation engine as recommendations are only as good as the level data feeding them, so getting the classification logic right first avoids rework later. Time tracking is lower-risk and could run in parallel since it doesn't block other features.
