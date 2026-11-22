# Netflix System Design Interview

System design is commonly reported as the largest technical part of the Netflix loop, and senior candidates often face it twice. Each round runs about 45 to 60 minutes. The questions come from problems that Netflix engineers solve, such as video streaming and content delivery. The round is reported to be less structured than at other large companies, so the candidate is expected to lead it.

## Format

| Item | Commonly reported |
|---|---|
| Length | 45 to 60 minutes |
| Count | One round, and often two for senior roles |
| Style | An open conversation that the candidate leads |
| Follow-ups | Many, after the first complete answer |
| What is graded | Scale, availability, cost, and the reasons behind each choice |

## Commonly reported questions

| Question | What it tests | Practice lesson |
|---|---|---|
| Design a video streaming service | Encoding, delivery, and adaptive bitrate streaming | [Designing Youtube or Netflix](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-youtube-or-netflix?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=system-design-interview) |
| Design a recommendation system | Data collection, batch computation, and fast serving | [Design a recommendation system for Netflix](https://www.designgurus.io/course-play/grokking-system-design-interview-ii/doc/design-a-recommendation-system-for-netflix?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=system-design-interview) |
| Design a content delivery network | Edge caching, routing, and cache placement | [CDN Architecture](https://www.designgurus.io/course-play/grokking-system-design-fundamentals/doc/cdn-architecture?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=system-design-interview) |
| Design search with autocomplete | Indexing and very fast prefix lookup | [Designing Typeahead Suggestion](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-typeahead-suggestion?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=system-design-interview) |
| Design a notification service | Fan-out, retries, and delivery guarantees | [Designing a notification system](https://www.designgurus.io/course-play/grokking-system-design-interview-ii/doc/designing-a-notification-system?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=system-design-interview) |
| Design a logging and monitoring system | Ingestion, storage, and alerting | [Design a Metrics and Monitoring System](https://www.designgurus.io/course-play/system-design-interview-crash-course/doc/design-a-metrics-monitoring-system-like-datadogprometheus?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=system-design-interview) |

Other reported questions include a real-time analytics system, a user profile service, a metadata store, a global load balancer, and an ad frequency cap. A frequency cap limits how often one viewer sees the same advertisement.

## What the product implies

Netflix streams video to many devices in many regions, and three topics follow from that.

- **Content delivery.** A content delivery network (CDN) is a set of servers placed near users that store copies of content. Netflix runs its own CDN, named Open Connect, with servers inside internet provider networks. Knowing the name is optional, but knowing why edge caching lowers delay is required.
- **Adaptive bitrate streaming.** The video is cut into short chunks at several quality levels. The player requests the level that the current connection can carry, so quality drops before playback stops.
- **Availability over consistency.** Reported guidance is that playback must survive the loss of a server or a whole region. Data such as watch history can be eventually consistent, which means copies may differ for a short time and then agree.

## What a strong answer includes

1. **Scope.** A whole streaming service cannot be designed in 45 minutes. State what you will cover first, what you will leave out, and why.
2. **Numbers.** Estimate requests, storage, and bandwidth aloud, and state the ratio of reads to writes.
3. **Two paths.** Separate the slow path that prepares each video from the fast path that delivers it.
4. **Failure behavior.** Describe what a viewer sees when one region fails, and how traffic moves to another region.
5. **Cost.** Explain how you would lower the cost of titles that are rarely watched.
6. **Trade-offs.** For each major choice, state what you gain and what you give up.

## Follow-up questions to expect

- Why this queue and not another one?
- What breaks first at ten times the traffic?
- What do you give up to get the lower latency? Latency is the delay between a request and its response.
- What happens for a viewer on a slow mobile network?
- How do you roll back a release that fails in one region?

## Go deeper

- [Grokking the System Design Interview](https://www.designgurus.io/course/grokking-the-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=system-design-interview): complete designs with the trade-offs these rounds ask about.
- Lesson: [Design Netflix](https://www.designgurus.io/course-play/system-design-interview-crash-course/doc/design-netflix?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=system-design-interview), in System Design Interview Crash Course
- Lesson: [Importance of Discussing Trade-offs](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/importance-of-discussing-tradeoffs?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=system-design-interview), in Grokking the System Design Interview
- Free article: [Netflix system design interview questions](https://www.designgurus.io/blog/netflix-system-design-interview-questions-guide?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=system-design-interview)
- Free answer: [How to design a video streaming service like Netflix](https://www.designgurus.io/answers/detail/designing-netflixlike-streaming-service?utm_source=github&utm_medium=repo&utm_campaign=netflix-interview-guide&utm_content=system-design-interview)
- Free guide: [Netflix system design interview on GitHub](https://github.com/design-gurus/grokking-system-design/blob/main/companies/netflix.md)
