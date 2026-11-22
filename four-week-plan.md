# Four-Week Plan for the Netflix Interview

Four weeks at 8 to 10 hours per week is a reasonable plan for an engineer who already works at mid or senior level. The plan gives the most hours to system design and the culture stories. Reports name those two as the parts that decide a Netflix loop. Each week ends with a finish condition, and the next week starts only when it is met.

## Hours by area

| Area | Share of time | Reason |
|---|---|---|
| System design | 40 percent | The largest technical part, often asked twice at senior level |
| Culture stories and past projects | 30 percent | The culture result can decide the loop alone |
| Coding | 20 percent | Practical tasks at medium difficulty |
| Mock rounds and review | 10 percent | Timing and speaking aloud need rehearsal |

## Week 1: the memo, the stories, and the basics

- Read the Netflix culture memo twice. Write one value you have lived and one point you honestly disagree with.
- Draft four stories in STAR form (Situation, Task, Action, Result). The [behavioral interview](behavioral-interview.md) page lists the four themes.
- Choose two or three past projects. For each one, write the numbers, the constraints, and what you would change now.
- Solve eight coding problems from the [question bank](question-bank.md) in a real editor.
- Study the [step-by-step method for a design round](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/system-design-interviews-a-step-by-step-guide?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=four-week-plan).

**Finish condition:** four written stories, a one-page note for each project, and eight problems solved with running code.

## Week 2: the streaming domain

- Study content delivery, caching, and adaptive bitrate streaming. Start with [What is CDN?](https://www.designgurus.io/course-play/grokking-system-design-fundamentals/doc/what-is-cdn?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=four-week-plan) and [Caching](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/caching?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=four-week-plan).
- Work through one complete design of a video platform: [Designing Youtube or Netflix](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-youtube-or-netflix?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=four-week-plan).
- Design a video streaming service yourself in 45 minutes, aloud, with a timer. Compare the result with the lesson.
- Practice estimates for requests, storage, and bandwidth with [back-of-the-envelope estimation](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/what-are-backoftheenvelope-estimations?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=four-week-plan).
- Solve eight more coding problems.

**Finish condition:** you can explain adaptive bitrate streaming and edge caching in two minutes each, and you have completed one timed design.

## Week 3: more designs and practical coding

- Complete three timed designs: a recommendation system, a content delivery network, and one of search or notifications. The [system design interview](system-design-interview.md) page links a lesson for each.
- For each design, write answers to three follow-up questions: what breaks first at ten times the traffic, what a viewer sees when a region fails, and how to lower cost.
- Build a rate limiter and a log parser from an empty file, 45 minutes each. After each build, answer the memory question and the two-threads question aloud.
- Rehearse the four stories aloud. Check that each one still contains its uncomfortable part.
- Solve the last eight coding problems.

**Finish condition:** four timed designs in total, two small components built, and all 24 coding problems solved.

## Week 4: mock rounds and review

- Run one full mock loop in one day: one coding round, two design rounds, and one culture conversation.
- Ask a colleague to question one project to a depth of four follow-up questions.
- Prepare your answer to "Why Netflix?" from your own work, not from the product.
- Prepare three questions for each interviewer about how the team decides what to build, how on-call works, and what the manager expects in the first months.
- Read [common mistakes](common-mistakes.md) on the last day and check your plan against each one.

**Finish condition:** one complete mock loop, a rehearsed answer to "Why Netflix?", and a written list of your own questions.

## Go deeper

- [Grokking the System Design Interview](https://www.designgurus.io/course/grokking-the-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=four-week-plan): the main course for weeks 2 and 3.
- Lesson: [System Design Master Template](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/system-design-master-template?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=four-week-plan), in Grokking the System Design Interview
- Lesson: [How to prepare for behavioral interview?](https://www.designgurus.io/course-play/grokking-behavioral-interview/doc/how-to-prepare-for-behavioral-interview?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=four-week-plan), in Grokking Modern Behavioral Interview
- Lesson: [Context, Constraints, Choices, Results](https://www.designgurus.io/course-play/grokking-staff-engineer-interview/doc/context-constraints-choices-results?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=four-week-plan), in Grokking Staff Engineer Interview
- [System Design Interview Crash Course](https://www.designgurus.io/course/system-design-interview-crash-course?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=four-week-plan): a shorter option when fewer than four weeks remain.
- Free article: [Netflix interview guide](https://www.designgurus.io/blog/netflix-interview-guide?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=four-week-plan)
