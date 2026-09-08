# uiuX - Adaptive E-Learning Platform


A product case study from my Final Year Design Project (FYDP) at United International University, built by a 3-person team. This repo documents the product thinking behind the platform ( problem framing, research, feature scope, backlog, and design ), rather than the codebase.

## My contribution

I worked across all phases of this project including research, discovery, design, and specification as part of a 3-person team, with primary ownership of framing the "why": articulating the project's motivation, defining the problem statement, and setting the objectives that guided the rest of the team's research, design, and build decisions. The backlog in `/03-backlog` is a reconstruction I did independently afterward, as a personal exercise in product prioritization.

## The problem

Existing e-learning platforms (edX, Coursera, and similar) rely on a one-size-fits-all delivery model: static video lectures with limited interactivity, generic dashboards, and no adaptation to individual performance. They don't adjust to a learner's pace, don't act on quiz or progress data to personalize the path forward, and often bury progress tracking in cluttered navigation. The result is passive content consumption rather than active, motivated learning.

## Motivation & objective

The goal was a platform that moves learners from passive watching to active, measured progress , using embedded quizzes, adaptive leveling, and personalized recommendations to keep engagement high and give learners a clear sense of where they stand.

Core objectives:
1. Replace passive video consumption with in-lecture interactivity (pop-up quizzes, discussion touchpoints).
2. Classify learners into Beginner / Average / Advanced tiers based on quiz and progress data, and personalize the path from there.
3. Give learners a single dashboard view of courses completed, quizzes taken, and progress.
4. Support retention with in-lecture note-taking, downloadable lectures, and transcripts.
5. Make the experience accessible across devices, with accessibility support (screen readers, subtitles).

## Research summary

The team's research (competitive benchmarking against edX, Coursera, and others; a structured literature review of ~50 sources narrowed to 12; and a user survey) identified three consistent gaps in existing platforms: shallow interactivity, weak motivation/retention mechanics, and inconsistent accessibility. See `/01-research` for the benchmark table and findings summary.

## Feature list

1. **Watch lecture video** — adjustable playback, resolution, and speed
2. **Pop-up quiz** — in-lecture comprehension checks with instant feedback
3. **Course progress** — tracks lectures watched, quizzes taken, completion %
4. **Time tracking** — time-on-task insight per lecture/course
5. **Level identification** — classifies learners as Beginner / Average / Advanced from quiz + progress data
6. **Recommendation engine** — suggests content based on level, gaps, and interests
7. **Note-taking** — in-lecture notes tied to the video timeline

## Repo structure

- `/01-research` — competitive benchmark and literature review summary
- `/02-discovery` — problem statement, objectives, survey takeaways
- `/03-backlog` — user stories and prioritization, reconstructed for this case study
- `/04-design` — UI screenshots and UML/flow diagrams
- `/05-roadmap` — build phases and future work

## Future work

Time tracking, the recommendation engine, and level identification were scoped but not fully built out in the original project timeline — see `/05-roadmap` for how I'd sequence them going forward.
