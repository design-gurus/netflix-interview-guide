# Netflix Coding Interview

The Netflix coding interview is commonly reported as a practical task of 45 to 60 minutes in a shared editor, at medium difficulty. Candidates report fewer algorithm puzzles than at other large companies and more work drawn from the team's own domain. The round is rarely the one that decides the result, but weak code can still end a loop.

## Format

| Item | Commonly reported |
|---|---|
| Length | 45 to 60 minutes |
| Tool | A shared editor such as CoderPad or CodeSignal |
| Where it appears | The technical screen, and again in the onsite loop |
| Difficulty | Medium, with a real-world setting |
| Variations | Pair programming in a real editor, or a take-home project on some teams |

## What is graded

Three things are graded, according to candidate reports.

1. The code runs.
2. The code is clean enough for another engineer to change.
3. You explain your choices while you type.

Expect follow-up questions after the first working version. Two reported examples are "What if the input does not fit in memory?" and "What if two threads write at once?" A thread is one sequence of instructions that runs at the same time as others in a program. Answer each follow-up aloud and name the trade-off, which is what you give up to gain something else.

## Kinds of tasks

| Task type | Reported examples |
|---|---|
| A small component | A rate limiter, which caps how many requests one user can send in a period |
| Data processing | Parsing a file or processing a stream of events |
| A small service | A few endpoints with state held in memory |
| Existing code | Debugging or extending code that the interviewer supplies |
| Front-end work | A task in React for teams that build user interfaces |
| Design, then build | Designing part of a system and implementing one piece |

## Topics that still matter

Practical tasks assume the basics. The data structures and algorithms below are commonly reported for Netflix, either as direct questions or inside a larger task.

| Topic | Why it appears | Practice lesson |
|---|---|---|
| Hash maps | Fast lookup and counting inside almost every practical task | [Introduction to Hash Map Pattern](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/introduction-to-hash-map-pattern?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=coding-interview) |
| Arrays and strings | Searching, sorting, and transforming input | [Introduction to Sliding Window Pattern](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/introduction-to-sliding-window-pattern?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=coding-interview) |
| Linked lists | Reversal, cycle detection, and merging | [Reverse a LinkedList](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/reverse-a-linkedlist-easy?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=coding-interview) |
| Trees and graphs | Depth-first and breadth-first traversal | [Binary Tree Level Order Traversal](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/binary-tree-level-order-traversal-easy?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=coding-interview) |
| Dynamic programming | Recursive problems that repeat the same subproblems | [Unique Paths](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/unique-paths-medium?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=coding-interview) |
| Concurrency | The follow-up question about two threads | [Introduction to Multi-threaded Pattern](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/introduction-to-multithreaded-pattern?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=coding-interview) |

Complexity reasoning also appears. Be ready to state how the running time and the memory use grow as the input grows.

## How to practice

- Practice in a real editor and run your code. This matches the format of the screen.
- Finish a simple version first, then improve it. A working simple version scores better than an unfinished complex one.
- Learn patterns instead of counting problems. A pattern is a solution shape that many problems share, so each pattern covers many questions.
- Build two small components from an empty file within 45 minutes each: a rate limiter and a log parser.
- For every practice problem, write two follow-up questions about memory and concurrency, and answer them aloud.
- Use the coding list in the [question bank](question-bank.md) for timed practice.

## Go deeper

- [Grokking the Coding Interview](https://www.designgurus.io/course/grokking-the-coding-interview?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=coding-interview): coding questions grouped into repeatable patterns.
- [Grokking 75: Top Coding Interview Questions](https://www.designgurus.io/course/grokking-75-top-coding-interview-questions?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=coding-interview): a short list for timed practice.
- Lesson: [DSA Patterns Cheat Sheet](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/coding-patterns-a-cheat-sheet?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=coding-interview), in Grokking the Coding Interview
- Lesson: [Designing an API Rate Limiter](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-an-api-rate-limiter?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=coding-interview), in Grokking the System Design Interview
- Free answer: [Does Netflix ask LeetCode questions in interviews?](https://www.designgurus.io/answers/detail/does-netflix-ask-leetcode-questions-in-interviews?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=coding-interview)
- Free guide: [Grokking the Coding Interview on GitHub](https://github.com/design-gurus/grokking-coding-interview)
