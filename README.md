# Netflix Interview Guide

> A free guide to the Netflix software engineer interview from [DesignGurus.io](https://www.designgurus.io/course/grokking-the-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=readme), created by Arslan Ahmad.

[![GitHub stars](https://img.shields.io/github/stars/design-gurus/netflix-interview-guide?style=social)](https://github.com/design-gurus/netflix-interview-guide/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/design-gurus/netflix-interview-guide)](https://github.com/design-gurus/netflix-interview-guide/commits/main)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

The Netflix loop differs from other large technology companies in three ways. Netflix hires mostly senior engineers, so the loop is calibrated to people who work with very little supervision. System design is commonly reported as the largest technical part, and senior candidates often face it twice. The culture round maps directly to a public culture memo, and a weak result there is reported to outweigh strong technical rounds.

This repository is a short, free guide to that loop. It covers every stage, the three interview types, the level ladder, a question bank, and a four-week plan. Each page takes about three minutes to read. The guide is independent. It is not affiliated with, endorsed by, or reviewed by Netflix, and every process detail is a common candidate report, not an official statement.

## The loop at a glance

Teams at Netflix run their own hiring, so the stages below vary by team.

| Stage | Length | What it measures | Guide page |
|---|---|---|---|
| Recruiter screen | About 30 minutes | Background, motivation, and interest in the culture memo | [Interview process](interview-process.md) |
| Hiring manager screen | 30 to 60 minutes | Past work, team fit, and the role | [Interview process](interview-process.md) |
| Technical screen | 45 to 60 minutes | Working code, reasoning, and practical judgment | [Coding interview](coding-interview.md) |
| Onsite coding | 45 to 60 minutes | Clean code that runs, and answers to follow-up questions | [Coding interview](coding-interview.md) |
| Onsite system design | 45 to 60 minutes, often twice for senior roles | Scale, availability, cost, and trade-offs | [System design interview](system-design-interview.md) |
| Culture and values | Several conversations | Judgment, candor, and independence | [Behavioral interview](behavioral-interview.md) |
| Director conversations (some loops) | About 45 minutes each | Judgment and fit beyond one team | [Interview process](interview-process.md) |

## Start here

| Your situation | Read this first |
|---|---|
| A recruiter contacted you and you want the outline | [Interview process](interview-process.md) |
| You have four weeks before the onsite loop | [Four-week plan](four-week-plan.md) |
| You are unsure whether you fit L4 or L5 | [Levels](levels.md) |
| You want practice questions today | [Question bank](question-bank.md) |

## All pages

| Page | What it covers |
|---|---|
| [Interview process](interview-process.md) | Every stage from application to offer, and what each stage decides |
| [Coding interview](coding-interview.md) | The practical format, the three things graded, and the topics to practice |
| [System design interview](system-design-interview.md) | The commonly reported questions and what a strong answer includes |
| [Behavioral interview](behavioral-interview.md) | The culture memo, the keeper test, and the four stories to prepare |
| [Levels](levels.md) | The L3 to L7 ladder and how the interview changes by level |
| [Question bank](question-bank.md) | 54 questions for coding, system design, and behavioral rounds |
| [Four-week plan](four-week-plan.md) | A week-by-week schedule with a finish condition for each week |
| [Common mistakes](common-mistakes.md) | Ten mistakes that are specific to the Netflix loop |

## FAQ

### How many rounds are in a Netflix interview?

Candidates commonly report four main stages: a recruiter call, a hiring manager screen, a technical screen, and a virtual onsite loop. The onsite loop is reported as four to six interviews. Some teams add a take-home project, a second system design interview, or director conversations. See the [interview process](interview-process.md).

### How hard is the Netflix interview?

It is commonly reported as hard, and the reason is the level of the bar more than the difficulty of the questions. The loop is calibrated to senior work. Mid-level candidates are reported to pass every technical round and still receive no offer, because the gap is independence. See [levels](levels.md).

### How long does the Netflix hiring process take?

Most reports give four to eight weeks from the first call to a decision. Some candidates report under three weeks. Scheduling several interviewers is the usual cause of a longer wait. See the [interview process](interview-process.md).

### What coding questions does Netflix ask?

Reports describe medium difficulty questions in a practical setting, such as a rate limiter, a parser, or a small service. A rate limiter is a component that caps how many requests one user can send in a period. Algorithm puzzles are reported less often than at other large companies. See the [coding interview](coding-interview.md).

### Does Netflix ask system design?

Yes. System design is commonly reported as the largest technical part of the loop for senior roles. Reported questions include a video streaming service, a recommendation system, and a content delivery network. See the [system design interview](system-design-interview.md).

### What is the Netflix keeper test?

The keeper test is a question that Netflix managers are reported to ask about their own staff: would I fight to keep this person? Interviewers look for evidence that a candidate would pass it. See the [behavioral interview](behavioral-interview.md).

## Go deeper

This repository gives the outline. The courses and articles below teach each round in full.

- [Grokking the System Design Interview](https://www.designgurus.io/course/grokking-the-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=readme): complete design problems, including a video streaming platform, for the round that carries the most weight.
- Lesson: [Designing Youtube or Netflix](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-youtube-or-netflix?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=readme), in Grokking the System Design Interview
- [Grokking the Coding Interview](https://www.designgurus.io/course/grokking-the-coding-interview?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=readme): the coding patterns that practical tasks assume.
- [Grokking Modern Behavioral Interview](https://www.designgurus.io/course/grokking-behavioral-interview?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=readme): the STAR method and a story bank for the culture round.
- Free article: [Netflix interview guide](https://www.designgurus.io/blog/netflix-interview-guide?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=readme): the process, the questions, and how to prepare.
- Free article: [Netflix engineer levels explained](https://www.designgurus.io/blog/netflix-software-engineer-levels?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=readme): L3 to L7 and what each level expects.

Related free guides: [Netflix levels](https://github.com/design-gurus/software-engineer-levels/blob/main/companies/netflix.md), [Netflix system design interview](https://github.com/design-gurus/grokking-system-design/blob/main/companies/netflix.md), [Grokking the Coding Interview](https://github.com/design-gurus/grokking-coding-interview), and [Staff Engineer Interview](https://github.com/design-gurus/staff-engineer-interview).

For the system design round, see [Grokking System Design](https://github.com/design-gurus/grokking-system-design), the free companion guide with 30 patterns, 59 question walkthroughs, and 35 cheat sheets.

## More free guides

Every guide below is free, follows the same short-page format, and comes from DesignGurus.io.

- **Core guides:** [Grokking System Design](https://github.com/design-gurus/grokking-system-design), [Grokking Coding Interview](https://github.com/design-gurus/grokking-coding-interview), [Grokking AI System Design](https://github.com/design-gurus/grokking-ai-system-design), [Design Patterns](https://github.com/design-gurus/design-patterns), [Best System Design Resources](https://github.com/design-gurus/best-system-design-resources), [Best System Design Courses](https://github.com/design-gurus/best-system-design-courses)
- **By interview round:** [System Design Numbers](https://github.com/design-gurus/system-design-numbers), [API Design Interview](https://github.com/design-gurus/api-design-interview), [Frontend System Design Interview](https://github.com/design-gurus/frontend-system-design-interview), [Mobile System Design Interview](https://github.com/design-gurus/mobile-system-design-interview), [Microservices Interview Questions](https://github.com/design-gurus/microservices-interview-questions), [Concurrency Interview](https://github.com/design-gurus/concurrency-interview)
- **By role:** [DevOps and SRE Interview](https://github.com/design-gurus/devops-sre-interview), [Data Engineering Interview](https://github.com/design-gurus/data-engineering-interview), [Forward Deployed Engineer Interview](https://github.com/design-gurus/forward-deployed-engineer-interview), [Solutions Architect Interview](https://github.com/design-gurus/solutions-architect-interview)
- **Seniority and behavioral:** [Staff Engineer Interview](https://github.com/design-gurus/staff-engineer-interview), [Engineering Manager Interview](https://github.com/design-gurus/engineering-manager-interview), [Amazon Leadership Principles](https://github.com/design-gurus/amazon-leadership-principles), [Software Engineer Levels](https://github.com/design-gurus/software-engineer-levels)
- **By company:** [Google Interview Guide](https://github.com/design-gurus/google-interview-guide), [Meta Interview Guide](https://github.com/design-gurus/meta-interview-guide), [Amazon Interview Guide](https://github.com/design-gurus/amazon-interview-guide), [Microsoft Interview Guide](https://github.com/design-gurus/microsoft-interview-guide), [Apple Interview Guide](https://github.com/design-gurus/apple-interview-guide), [OpenAI Interview Guide](https://github.com/design-gurus/openai-interview-guide), [Anthropic Interview Guide](https://github.com/design-gurus/anthropic-interview-guide)

## Contributing

Corrections, new questions, and reports of how a Netflix loop was run are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## License

The content is licensed under [CC BY 4.0](LICENSE). See [NOTICE.md](NOTICE.md) for what the license covers and how to attribute.
