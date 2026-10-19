# Best System Design Resources

> A curated list of the best system design resources for learning how large systems work and for passing the system design interview: courses, books, free guides, papers, videos, engineering blogs, and practice problems, sorted by level and goal.

[![GitHub stars](https://img.shields.io/github/stars/design-gurus/best-system-design-resources?style=social)](https://github.com/design-gurus/best-system-design-resources/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/design-gurus/best-system-design-resources)](https://github.com/design-gurus/best-system-design-resources/commits/main)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)

There are thousands of system design links online, and most lists give you all of them with no order. This list is shorter on purpose. Every entry says who it is for, and the first table tells you where to begin. Free resources are marked **Free**.

## Contents

- [Where to start](#where-to-start)
- [Courses](#courses)
- [Books](#books)
- [Free guides and GitHub repositories](#free-guides-and-github-repositories)
- [Core concepts, one link each](#core-concepts-one-link-each)
- [Interview framework and cheat sheets](#interview-framework-and-cheat-sheets)
- [Practice problems by difficulty](#practice-problems-by-difficulty)
- [Company-specific interview guides](#company-specific-interview-guides)
- [Papers every engineer should read](#papers-every-engineer-should-read)
- [Real-world case studies](#real-world-case-studies)
- [Engineering blogs](#engineering-blogs)
- [Newsletters](#newsletters)
- [YouTube channels and talks](#youtube-channels-and-talks)
- [AI and machine learning system design](#ai-and-machine-learning-system-design)
- [Mock interviews and practice platforms](#mock-interviews-and-practice-platforms)
- [Diagramming tools](#diagramming-tools)
- [Frequently asked questions](#frequently-asked-questions)
- [Contributing](#contributing)

## Where to start

Pick the row that matches your situation. Do the first column, then the second.

| Your situation | Start with | Then |
|----------------|------------|------|
| New to system design | [Grokking System Design Fundamentals](https://www.designgurus.io/course/grokking-system-design-fundamentals?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=where-to-start) or the free [System Design Primer](https://github.com/donnemartin/system-design-primer) | [Grokking the System Design Interview](https://www.designgurus.io/course/grokking-the-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=where-to-start) |
| Interview in two to four weeks | [Grokking the System Design Interview](https://www.designgurus.io/course/grokking-the-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=where-to-start) with the free [2-week plan](https://github.com/design-gurus/grokking-system-design/blob/main/roadmaps/2-week-plan.md) | A [mock interview](https://www.designgurus.io/mock-interviews?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=where-to-start) in the final week |
| Interview in a few days | [System Design Interview Crash Course](https://www.designgurus.io/course/system-design-interview-crash-course?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=where-to-start) and the free [1-week plan](https://github.com/design-gurus/grokking-system-design/blob/main/roadmaps/1-week-plan.md) | [System design in one page](https://github.com/design-gurus/grokking-system-design/blob/main/cheat-sheets/system-design-in-one-page.md) the night before |
| Senior or staff loop | [Advanced System Design Interview, Volume II](https://www.designgurus.io/course/grokking-system-design-interview-ii?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=where-to-start) | *Designing Data-Intensive Applications* and the [papers](#papers-every-engineer-should-read) below |
| AI or ML system design round | [Grokking the AI System Design Interview](https://www.designgurus.io/course/grokking-the-ai-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=where-to-start) and its free [companion repo](https://github.com/design-gurus/grokking-ai-system-design) | Chip Huyen's *AI Engineering* |
| You want to understand real systems, not pass an interview | *Designing Data-Intensive Applications* | The [papers](#papers-every-engineer-should-read) and [case studies](#real-world-case-studies) below |

## Courses

### Interview preparation courses

| Course | Provider | Best for |
|--------|----------|----------|
| [Grokking the System Design Interview](https://www.designgurus.io/course/grokking-the-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=courses) | Design Gurus | The original pattern-based interview course, by Arslan Ahmad. The default choice for most candidates. |
| [Advanced System Design Interview, Volume II](https://www.designgurus.io/course/grokking-system-design-interview-ii?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=courses) | Design Gurus | Senior and staff candidates who need harder problems and deeper trade-offs. |
| [System Design Interview Crash Course](https://www.designgurus.io/course/system-design-interview-crash-course?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=courses) | Design Gurus | Candidates with only a few days. A short, focused path. |
| [Grokking Scalable Systems for Interviews](https://www.designgurus.io/course/grokking-scalable-systems-for-interviews?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=courses) | Design Gurus | Learning how systems grow from one server to many, one stage at a time. |
| [ByteByteGo](https://bytebytego.com/) | Alex Xu | Visual learners. The online version of the *System Design Interview* books. |
| [Hello Interview](https://www.hellointerview.com/learn/system-design/in-a-hurry/introduction) | Hello Interview | Written problem breakdowns, with many free guides. |
| [Aced (formerly Exponent)](https://www.aced.io/courses/system-design-interviews) | Aced | Video lessons combined with peer mock interviews. |
| [InterviewReady](https://interviewready.io/) | Gaurav Sen | Video-first learners who already follow Gaurav Sen on YouTube. |
| [AlgoMaster](https://algomaster.io/learn/system-design/course-introduction) | Ashish Pratap Singh | A written course that pairs concepts with interview problems. |
| [Codemia](https://codemia.io/) | Codemia | Practicing problems and getting feedback on your written answers. |
| [System Design School](https://systemdesignschool.io/) | System Design School | A structured course with practice problems and hands-on labs. |

### Foundations and topic courses

| Course | Provider | Best for |
|--------|----------|----------|
| [Grokking System Design Fundamentals](https://www.designgurus.io/course/grokking-system-design-fundamentals?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=courses) | Design Gurus | Beginners. The building blocks, before any interview problem. |
| [System Design Patterns: From Fundamentals to Real Systems](https://www.designgurus.io/course/system-design-patterns?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=courses) | Design Gurus | Learning the recurring patterns and seeing them in production systems. |
| [Grokking Database Fundamentals for Tech Interviews](https://www.designgurus.io/course/grokking-database-fundamentals-for-tech-interviews?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=courses) | Design Gurus | Storage, indexing, transactions, and replication, which every design depends on. |
| [Relational Database Design and Modeling for Software Engineers](https://www.designgurus.io/course/grokking-relational-database-design-and-modeling-for-software-engineers?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=courses) | Design Gurus | Schema design and data modeling. |
| [Grokking Microservices for System Design Interviews](https://www.designgurus.io/course/grokking-microservices-for-system-design-interviews?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=courses) | Design Gurus | Interviews that focus on service boundaries and communication. |
| [Grokking Microservices Design Patterns](https://www.designgurus.io/course/grokking-microservices-design-patterns?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=courses) | Design Gurus | Sagas, CQRS, circuit breakers, and the other microservice patterns. |
| [Grokking Modern API Design Interview](https://www.designgurus.io/course/grokking-modern-api-design-interview?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=courses) | Design Gurus | API design rounds and the API layer of any design. |
| [Grokking Modern Mobile System Design Interview](https://www.designgurus.io/course/grokking-modern-mobile-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=courses) | Design Gurus | Mobile engineers. Offline sync, battery, and network constraints. |
| [Grokking the Object Oriented Design Interview](https://www.designgurus.io/course/grokking-the-object-oriented-design-interview?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=courses) | Design Gurus | Low-level design rounds, which many loops include alongside system design. |
| [Software Architecture & Design of Modern Large Scale Systems](https://www.udemy.com/course/software-architecture-design-of-modern-large-scale-systems/) | Michael Pogrebinsky, Udemy | An architecture-first video course. |
| [Master the Coding Interview: System Design + Architecture](https://zerotomastery.io/ai/courses/system-design/) | Zero To Mastery | A short introduction for developers early in their careers. |
| [Software Architecture](https://www.coursera.org/learn/software-architecture) | University of Alberta, Coursera | Architecture styles and documentation, in a university format. |
| [Cloud Computing Specialization](https://www.coursera.org/specializations/cloud-computing) | University of Illinois, Coursera | The distributed systems theory behind cloud services. |

### Free university courses

- [MIT 6.5840: Distributed Systems](https://pdos.csail.mit.edu/6.824/) **Free**: the best-known distributed systems course. The labs build Raft and a sharded key-value store. Lectures are on [YouTube](https://www.youtube.com/@6.824).
- [Cambridge: Concurrent and Distributed Systems](https://www.cl.cam.ac.uk/teaching/2122/ConcDisSys/materials.html) **Free**: Martin Kleppmann's lecture notes and videos. A short and clear treatment of clocks, replication, and consensus.
- [CMU 15-445: Database Systems](https://15445.courses.cs.cmu.edu/) **Free**: Andy Pavlo's course on how databases work inside. Lectures are on the [CMU Database Group channel](https://www.youtube.com/@CMUDatabaseGroup).
- [CMU 15-440: Distributed Systems](https://www.andrew.cmu.edu/course/15-440/) **Free**: a second university course, with a different set of readings from MIT's.
- [Stanford CS 329S: Machine Learning Systems Design](https://stanford-cs329s.github.io/) **Free**: Chip Huyen's course notes on building ML systems.

## Books

### For the interview

- [System Design Interview: An Insider's Guide](https://www.amazon.com/dp/B08CMF2CQF) by Alex Xu: the most widely read interview book. Each chapter works through one classic problem.
- [System Design Interview: An Insider's Guide, Volume 2](https://www.amazon.com/dp/1736049119) by Alex Xu and Sahn Lam: harder problems such as proximity services, payment systems, and a stock exchange.
- [Acing the System Design Interview](https://www.manning.com/books/acing-the-system-design-interview) by Zhiyong Tan: strong on non-functional requirements and how to discuss them.
- [Machine Learning System Design Interview](https://www.amazon.com/dp/1736049127) by Ali Aminian and Alex Xu: the ML round, from problem framing to serving.
- [Generative AI System Design Interview](https://www.amazon.com/dp/1736049143) by Ali Aminian and Hao Sheng: LLM and generative AI design problems.

### For depth

- [Designing Data-Intensive Applications](https://dataintensive.net/) by Martin Kleppmann: the single most recommended system design book. Read it once for understanding, not for the interview.
- [Understanding Distributed Systems](https://www.amazon.com/dp/1838430202) by Roberto Vitillo: a shorter and more practical companion to DDIA.
- [Database Internals](https://www.amazon.com/dp/1492040347) by Alex Petrov: storage engines, B-trees, LSM trees, and distributed consensus.
- [Site Reliability Engineering](https://sre.google/sre-book/table-of-contents/) **Free**: how Google runs production systems. The companion [Site Reliability Workbook](https://sre.google/workbook/table-of-contents/) is also free.
- [Fundamentals of Software Architecture](https://www.amazon.com/dp/1492043451) by Mark Richards and Neal Ford: architecture styles and the trade-offs between them.
- [Software Architecture: The Hard Parts](https://www.amazon.com/dp/1492086894) by Neal Ford, Mark Richards, Pramod Sadalage, and Zhamak Dehghani: decomposition and distributed data decisions.
- [Building Microservices](https://www.amazon.com/dp/1492034029) by Sam Newman: the standard book on microservice design.
- [Designing Distributed Systems](https://www.amazon.com/dp/1098156358) by Brendan Burns: reusable patterns for container-based systems.
- [Web Scalability for Startup Engineers](https://www.amazon.com/dp/0071843655) by Artur Ejsmont: a practical, beginner-friendly book on scaling a web application.
- [Release It!](https://www.amazon.com/dp/1680502395) by Michael Nygard: stability patterns such as timeouts, bulkheads, and circuit breakers.
- [Designing Machine Learning Systems](https://www.amazon.com/dp/1098107969) and [AI Engineering](https://www.amazon.com/dp/1098166302) by Chip Huyen: the two best books on production ML and LLM systems.

Not sure which book to buy? Read the [System Design Interview book review](https://www.designgurus.io/blog/system-design-interview-book?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=books) first.

## Free guides and GitHub repositories

### From Design Gurus

- [Grokking System Design](https://github.com/design-gurus/grokking-system-design) **Free**: the open companion to the Grokking course. Patterns, worked questions, company guides, paper deep dives, cheat sheets, and study plans.
- [Grokking the AI System Design Interview](https://github.com/design-gurus/grokking-ai-system-design) **Free**: building blocks, design questions, and reference sheets for ML, LLM, and agent rounds.
- [System Design Interview Guide](https://www.designgurus.io/blog/complete-guide-sys-design?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=free-guides-and-github-repositories) **Free**: the framework, the common questions, and how to prepare.
- [System Design Fundamentals: 25 Core Concepts](https://www.designgurus.io/blog/system-design-interview-fundamentals?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=free-guides-and-github-repositories) **Free**: every core concept in one article, written for beginners.
- [System Design Patterns: The Complete Guide](https://www.designgurus.io/blog/system-design-patterns-complete-guide?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=free-guides-and-github-repositories) **Free**: more than sixty patterns, each explained in plain language.
- [System Design Building Blocks](https://www.designgurus.io/blog/system-design-building-blocks?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=free-guides-and-github-repositories) **Free**: the components that appear in almost every design.
- [System Design Interview Library](https://www.designgurus.io/blog/system-design-interview-library?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=free-guides-and-github-repositories) **Free**: an index of more than 185 guides on questions and case studies.
- [System Design for Beginners: Where to Start](https://www.designgurus.io/blog/system-design-for-beginners?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=free-guides-and-github-repositories) **Free**: a roadmap for engineers with no distributed systems background.

### Community repositories

- [System Design Primer](https://github.com/donnemartin/system-design-primer) **Free**: the most-starred system design repository. A broad overview with Anki flashcards.
- [System Design 101](https://github.com/ByteByteGoHq/system-design-101) **Free**: ByteByteGo's diagrams, each explaining one concept visually.
- [karanpratapsingh/system-design](https://github.com/karanpratapsingh/system-design) **Free**: a book-length guide that reads well from start to finish.
- [Awesome System Design Resources](https://github.com/ashishps1/awesome-system-design-resources) **Free**: concept articles and interview problems, maintained by AlgoMaster.
- [Awesome System Design](https://github.com/madd86/awesome-system-design) **Free**: a broad list of articles, talks, and tools.
- [Awesome Scalability](https://github.com/binhnguyennus/awesome-scalability) **Free**: real engineering blog posts grouped by topic. Good for case studies.
- [Awesome Distributed Systems](https://github.com/theanalyst/awesome-distributed-systems) **Free**: papers, books, and courses on distributed systems theory.
- [InterviewReady System Design Resources](https://github.com/InterviewReady/system-design-resources) **Free**: Gaurav Sen's reading list of engineering articles.

### Free guides from other sites

- [Hello Interview: System Design in a Hurry](https://www.hellointerview.com/learn/system-design/in-a-hurry/introduction) **Free**: a compact written guide to the interview, with a [delivery framework](https://www.hellointerview.com/learn/system-design/in-a-hurry/delivery).
- [interviewing.io system design guide](https://interviewing.io/guides/system-design-interview) **Free**: a long guide written from the interviewer's side of the table.
- [Patterns of Distributed Systems](https://martinfowler.com/articles/patterns-of-distributed-systems/) **Free**: Unmesh Joshi's catalog on Martin Fowler's site. Write-ahead log, leader and followers, quorum, and more.
- [microservices.io](https://microservices.io/patterns/) **Free**: Chris Richardson's catalog of microservice patterns.
- [The Amazon Builders' Library](https://builder.aws.com/learn/topics/builders-library) **Free**: how Amazon builds and operates services, written by its senior engineers.
- [Azure cloud design patterns](https://learn.microsoft.com/en-us/azure/architecture/patterns/) **Free**: a well-organized pattern catalog with clear diagrams.
- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/) **Free**: the review questions AWS uses for reliability, cost, and performance.
- [Google Cloud Architecture Center](https://docs.cloud.google.com/architecture) **Free**: reference architectures for common workloads.

## Core concepts, one link each

Learn these before you attempt interview problems. Each row gives one clear article to read first and one source that goes deeper.

| Concept | Read first | Go deeper |
|---------|------------|-----------|
| Scalability | [Scalability in system design](https://www.designgurus.io/blog/grokking-system-design-scalability?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Scaling 101](https://www.designgurus.io/blog/scaling-101-comprehensive-learning-for-large-system-designs?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) |
| Availability | [High availability: 15 strategies](https://www.designgurus.io/blog/high-availability-system-design-basics?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Active-active vs active-passive](https://www.designgurus.io/blog/active-active-vs-active-passive-architecture?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) |
| Load balancing | [Complete load balancer guide](https://www.designgurus.io/blog/complete-load-balancing-guide?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Load balancing algorithms](https://www.designgurus.io/blog/load-balancing-algorithms-guide?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) |
| Proxies and gateways | [Load balancer vs reverse proxy vs API gateway](https://www.designgurus.io/blog/load-balancer-reverse-proxy-api-gateway?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [L4 vs L7 load balancing](https://github.com/design-gurus/grokking-system-design/blob/main/cheat-sheets/l4-vs-l7-load-balancing.md) |
| Caching | [Caching in system design interviews](https://www.designgurus.io/blog/caching-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Caching challenges and strategies (Amazon)](https://builder.aws.com/content/3K9TeXp6strMiJ4vhakpRD7BQWO/caching-challenges-and-strategies) |
| Cache eviction and invalidation | [Cache eviction strategies](https://www.designgurus.io/blog/cache-eviction-strategies?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Cache invalidation strategies](https://www.designgurus.io/blog/cache-invalidation-strategies?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) |
| CDN | [CDN architecture](https://www.designgurus.io/blog/content-delivery-network-cdn-system-design-basics?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [CDN pattern](https://github.com/design-gurus/grokking-system-design/blob/main/patterns/cdn.md) |
| SQL vs NoSQL | [SQL vs NoSQL: key differences](https://www.designgurus.io/blog/sql-vs-nosql-key-differences?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [PostgreSQL vs MongoDB vs DynamoDB](https://www.designgurus.io/blog/postgresql-vs-mongodb-vs-dynamodb?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) |
| Database indexing | [Database indexing explained](https://www.designgurus.io/blog/database-indexing?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [LSM trees vs B-trees](https://www.designgurus.io/blog/lsm-trees-vs-b-trees?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) |
| Replication | [Data replication strategies](https://www.designgurus.io/blog/data-replication-strategies-system-design?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Replication pattern](https://github.com/design-gurus/grokking-system-design/blob/main/patterns/replication.md) |
| Sharding | [Database sharding guide](https://www.designgurus.io/blog/database-sharding-guide-2026?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Sharding strategies cheat sheet](https://github.com/design-gurus/grokking-system-design/blob/main/cheat-sheets/sharding-strategies.md) |
| Consistent hashing | [Consistent hashing vs traditional hashing](https://www.designgurus.io/blog/consistent-hashing-vs-traditional-hashing?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Consistent hashing pattern](https://github.com/design-gurus/grokking-system-design/blob/main/patterns/consistent-hashing.md) |
| CAP and PACELC | [CAP theorem vs PACELC](https://www.designgurus.io/blog/system-design-interview-basics-cap-vs-pacelc?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Brewer's conjecture, the CAP proof](https://users.ece.cmu.edu/~adrian/731-sp04/readings/GL-cap.pdf) |
| Consistency models | [Consistency patterns](https://www.designgurus.io/blog/consistency-patterns-distributed-systems?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Eventual vs strong consistency](https://www.designgurus.io/blog/eventual-vs-strong-consistency?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) |
| Transactions | [ACID and database transactions](https://www.designgurus.io/blog/acid-database-transaction?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Distributed transactions pattern](https://github.com/design-gurus/grokking-system-design/blob/main/patterns/distributed-transactions.md) |
| Message queues | [Messaging patterns: queues, pub/sub, streams](https://www.designgurus.io/blog/message-patterns?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [RabbitMQ vs Kafka vs ActiveMQ](https://www.designgurus.io/blog/rabbitmq-kafka-activemq-system-design?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) |
| Exactly-once delivery | [Exactly-once delivery](https://www.designgurus.io/blog/exactly-once-delivery?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Avoiding insurmountable queue backlogs (Amazon)](https://builder.aws.com/content/3EuRcgkTP1MI0c7zM8W6HL3WIqA/avoiding-insurmountable-queue-backlogs) |
| Sync vs async communication | [Synchronous vs asynchronous communication](https://www.designgurus.io/blog/sync-vs-async?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [WebSockets vs SSE vs long polling](https://github.com/design-gurus/grokking-system-design/blob/main/cheat-sheets/websockets-vs-sse-vs-long-polling.md) |
| API design | [REST vs GraphQL vs gRPC](https://www.designgurus.io/blog/rest-graphql-grpc-system-design?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [API design checklist](https://www.designgurus.io/blog/api-design-checklist?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) |
| Rate limiting | [How to design a rate limiter](https://www.designgurus.io/blog/grokking-rate-limiters?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Rate limiting algorithms cheat sheet](https://github.com/design-gurus/grokking-system-design/blob/main/cheat-sheets/rate-limiting-algorithms.md) |
| Idempotency | [Idempotency in system design](https://www.designgurus.io/blog/grokking-idempotency?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Making retries safe with idempotent APIs (Amazon)](https://aws.amazon.com/builders-library/making-retries-safe-with-idempotent-APIs/) |
| Retries and timeouts | [System design failure modes](https://www.designgurus.io/blog/system-design-failure-modes?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Timeouts, retries, and backoff with jitter (Amazon)](https://builder.aws.com/content/3EumjoZascWd1oZiEgL8ORlv3qE/timeouts-retries-and-backoff-with-jitter) |
| Circuit breakers | [Circuit breaker pattern](https://www.designgurus.io/blog/circuit-breaker-pattern-in-distributed-systems?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Release It!](https://www.amazon.com/dp/1680502395), chapter on stability patterns |
| Microservices | [Monolith vs microservices vs SOA](https://www.designgurus.io/blog/monolithic-service-oriented-microservice-architecture?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [19 microservices design patterns](https://www.designgurus.io/blog/19-essential-microservices-patterns-for-system-design-interviews?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) |
| Service discovery | [Service discovery patterns](https://www.designgurus.io/blog/service-discovery-patterns-dns-consul-kubernetes?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Kubernetes guide for system design](https://www.designgurus.io/blog/kubernetes-ultimate-guide?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) |
| Leader election and consensus | [Leader election algorithms](https://www.designgurus.io/blog/5-best-leader-election-algorithms?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Raft consensus deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/raft-consensus.md) |
| Clocks and ordering | [Vector clocks explained](https://www.designgurus.io/blog/vector-clocks-explained?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Time, Clocks, and the Ordering of Events](https://lamport.azurewebsites.net/pubs/time-clocks.pdf) |
| Conflict resolution | [CRDTs explained](https://www.designgurus.io/blog/crdts-for-eventual-consistency?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Logical clocks pattern](https://github.com/design-gurus/grokking-system-design/blob/main/patterns/logical-clocks.md) |
| Unique IDs | [From UUID to Snowflake](https://www.designgurus.io/blog/database-fragmentation?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Unique ID generator walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-unique-id-generator.md) |
| Event sourcing and CQRS | [Event sourcing and CQRS pattern](https://github.com/design-gurus/grokking-system-design/blob/main/patterns/event-sourcing-cqrs.md) | [Outbox pattern](https://github.com/design-gurus/grokking-system-design/blob/main/patterns/outbox-pattern.md) |
| Probabilistic data structures | [Bloom filters pattern](https://github.com/design-gurus/grokking-system-design/blob/main/patterns/bloom-filters.md) | [12 system design algorithms](https://www.designgurus.io/blog/system-design-algorithms?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) |
| Stream processing | [Kafka Streams vs Flink vs Storm](https://www.designgurus.io/blog/kafka-streams-apache-flink-apache-storm?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) | [Designing an event pipeline with Kafka, Flink, and Elasticsearch](https://www.designgurus.io/blog/designing-event-pipeline-with-kafka-flink-elasticsearch?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=core-concepts-one-link-each) |

## Interview framework and cheat sheets

### How to run the interview

- [How to Design Any System: The 45-Minute Blueprint](https://www.designgurus.io/blog/how-to-design-any-system?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=interview-framework-and-cheat-sheets) **Free**: what to do in each part of the hour.
- [The 7-step method, on video](https://www.youtube.com/watch?v=N3r-Z6_IGTM) **Free**: the Grokking framework explained in five minutes.
- [Interview framework](https://github.com/design-gurus/grokking-system-design/blob/main/cheat-sheets/interview-framework.md) **Free**: the seven steps, with time budgets.
- [How to gather requirements](https://www.designgurus.io/blog/how-to-gather-requirements-in-system-design-interviews?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=interview-framework-and-cheat-sheets) **Free**: the questions to ask in the first five minutes.
- [Back-of-the-envelope estimation](https://www.designgurus.io/blog/back-of-the-envelope-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=interview-framework-and-cheat-sheets) **Free**: how to size storage, bandwidth, and servers quickly.
- [System design trade-offs](https://www.designgurus.io/blog/complex-system-design-tradeoffs?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=interview-framework-and-cheat-sheets) **Free**: how to discuss trade-offs the way senior engineers do.
- [The system design decision tree](https://www.designgurus.io/blog/system-design-decision-tree?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=interview-framework-and-cheat-sheets) **Free**: classify any question in the first few minutes.
- [10 system design interview mistakes](https://www.designgurus.io/blog/system-design-interview-mistakes?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=interview-framework-and-cheat-sheets) **Free**: the mistakes that cost candidates the offer.
- [Annotated mock interview](https://github.com/design-gurus/grokking-system-design/blob/main/cheat-sheets/mock-interview-walkthrough.md) **Free**: a full interview, with notes on what each answer signals.
- [Senior vs staff expectations](https://github.com/design-gurus/grokking-system-design/blob/main/cheat-sheets/senior-vs-staff-expectations.md) **Free**: how the bar changes by level.
- [Hello Interview delivery framework](https://www.hellointerview.com/learn/system-design/in-a-hurry/delivery) **Free**: a second framework, for comparison.

### Cheat sheets

- [System Design Cheat Sheet](https://www.designgurus.io/blog/system-design-cheat-sheet?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=interview-framework-and-cheat-sheets) **Free**: all the key concepts on one page.
- [System Design Cheat Sheet for Senior Engineers](https://www.designgurus.io/blog/system-design-cheat-sheet-for-senior-engineer?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=interview-framework-and-cheat-sheets) **Free**: the deeper topics that senior loops expect.
- [System design in one page](https://github.com/design-gurus/grokking-system-design/blob/main/cheat-sheets/system-design-in-one-page.md) **Free**: a final review before the interview.
- [Latency numbers every engineer should know](https://github.com/design-gurus/grokking-system-design/blob/main/cheat-sheets/latency-numbers.md) **Free**: the numbers you need for estimation. The original list is [Jeff Dean's, kept as a gist](https://gist.github.com/jboner/2841832).
- [Flashcards](https://github.com/design-gurus/grokking-system-design/blob/main/cheat-sheets/flashcards.md) **Free**: more than one hundred question and answer cards for spaced review.
- Comparison sheets **Free**: [Redis vs Memcached](https://github.com/design-gurus/grokking-system-design/blob/main/cheat-sheets/redis-vs-memcached.md), [Kafka vs RabbitMQ vs SQS](https://github.com/design-gurus/grokking-system-design/blob/main/cheat-sheets/kafka-vs-rabbitmq-vs-sqs.md), [Postgres vs DynamoDB vs Cassandra](https://github.com/design-gurus/grokking-system-design/blob/main/cheat-sheets/postgres-vs-dynamodb-vs-cassandra.md), [REST vs gRPC vs GraphQL](https://github.com/design-gurus/grokking-system-design/blob/main/cheat-sheets/rest-vs-grpc-vs-graphql.md), and [push vs pull feeds](https://github.com/design-gurus/grokking-system-design/blob/main/cheat-sheets/push-vs-pull-feeds.md).

## Practice problems by difficulty

Work through the easy problems first. Each one teaches a pattern that the harder problems reuse. Every link below is a free walkthrough.

### Easy

| Problem | Walkthrough | Main pattern |
|---------|-------------|--------------|
| URL shortener (TinyURL) | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-tinyurl.md), [blog version](https://www.designgurus.io/blog/url-shortening?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=practice-problems-by-difficulty), [video](https://www.youtube.com/watch?v=_TsJizByBvE) | Hashing and ID generation |
| Unique ID generator | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-unique-id-generator.md) | Snowflake-style IDs |
| Rate limiter | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-rate-limiter.md), [blog version](https://www.designgurus.io/blog/grokking-rate-limiters?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=practice-problems-by-difficulty) | Token bucket and sliding window |
| Typeahead autocomplete | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-typeahead-autocomplete.md) | Tries and precomputed results |
| Notification system | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-notification-system.md) | Queues and fan-out |
| Web crawler | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-web-crawler.md), [blog version](https://www.designgurus.io/blog/design-web-crawler?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=practice-problems-by-difficulty) | URL frontier and politeness |

More warm-up problems: [10 beginner system design questions](https://www.designgurus.io/blog/10-beginner-system-design-interview-questions-to-master-first?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=practice-problems-by-difficulty) and [10 easy problems for junior engineers](https://www.designgurus.io/blog/easy-system-design-interview-questions?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=practice-problems-by-difficulty).

### Medium

| Problem | Walkthrough | Main pattern |
|---------|-------------|--------------|
| Twitter | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-twitter.md) | Feed fan-out |
| Instagram | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-instagram.md), [blog version](https://www.designgurus.io/blog/how-to-design-instagram-in-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=practice-problems-by-difficulty) | Media storage and feeds |
| News feed | [Blog walkthrough](https://www.designgurus.io/blog/design-social-media-news-feed?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=practice-problems-by-difficulty) | Push vs pull |
| WhatsApp | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-whatsapp.md), [blog version](https://www.designgurus.io/blog/design-chat-application?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=practice-problems-by-difficulty), [video](https://www.youtube.com/watch?v=Va6EgMV9-7k) | Persistent connections |
| YouTube | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-youtube.md), [blog version](https://www.designgurus.io/blog/design-video-streaming-platform?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=practice-problems-by-difficulty) | Transcoding and CDN |
| Dropbox | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-dropbox.md), [blog version](https://www.designgurus.io/blog/design-cloud-storage-service?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=practice-problems-by-difficulty) | Chunking and sync |
| Uber | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-uber.md), [blog version](https://www.designgurus.io/blog/ride-sharing-service?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=practice-problems-by-difficulty) | Geospatial indexing |
| Proximity service (Yelp) | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-proximity-service.md) | Geohash and quadtrees |
| Ticketmaster | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-ticketmaster.md), [blog version](https://www.designgurus.io/blog/design-ticketing-system?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=practice-problems-by-difficulty) | Seat reservation and locking |
| Hotel reservation | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-hotel-reservation.md) | Inventory and double booking |
| Distributed cache | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-distributed-cache.md) | Consistent hashing |
| Distributed message queue | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-distributed-message-queue.md) | Partitioned logs |
| Distributed job scheduler | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-distributed-job-scheduler.md) | Leases and retries |
| Ad click aggregator | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-ad-click-aggregator.md) | Stream aggregation |
| Gaming leaderboard | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-gaming-leaderboard.md) | Sorted sets |

### Hard

| Problem | Walkthrough | Main pattern |
|---------|-------------|--------------|
| Google Docs | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-google-docs.md), [blog version](https://www.designgurus.io/blog/design-real-time-editor?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=practice-problems-by-difficulty) | Operational transforms and CRDTs |
| Google Maps | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-google-maps.md) | Graph partitioning and routing |
| Google Search | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-google-search.md) | Inverted indexes |
| Payment system | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-payment-system.md) | Idempotency and ledgers |
| Stock exchange | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-stock-exchange.md) | Matching engines and low latency |
| Flash sale | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-flash-sale-system.md) | Contention and queueing |
| Metrics and monitoring | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-metrics-monitoring.md) | Time-series storage |
| Zoom | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-zoom.md), [blog version](https://www.designgurus.io/blog/design-video-conferencing-system?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=practice-problems-by-difficulty) | Media servers |
| Amazon S3 | [Repo walkthrough](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-amazon-s3.md) | Erasure coding and metadata |
| Distributed key-value store | [Dynamo deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/dynamo-key-value-store.md) | Quorums and hinted handoff |

### Larger question banks

- [Top 25 system design interview questions with walkthroughs](https://www.designgurus.io/blog/system-design-interview-questions-to-crack-your-next-faang-interview?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=practice-problems-by-difficulty) **Free**
- [50 advanced system design interview questions](https://www.designgurus.io/blog/50-advanced-system-design-interview-questions?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=practice-problems-by-difficulty) **Free**
- [Question catalog and practice bank](https://github.com/design-gurus/grokking-system-design/blob/main/questions/practice-bank.md) **Free**: more than fifty questions grouped by pattern.
- [Hello Interview problem breakdowns](https://www.hellointerview.com/learn/system-design/in-a-hurry/problem-breakdowns) **Free**: written answers to common questions.

## Company-specific interview guides

Each company weights the round differently. Read the guide for your target company once you know the fundamentals.

- [Google system design interview questions](https://www.designgurus.io/blog/google-system-design-interview-questions-ultimate-guide?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=company-specific-interview-guides)
- [Amazon system design interview](https://www.designgurus.io/blog/system-design-interview-amazon?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=company-specific-interview-guides)
- [Meta system design interview questions](https://www.designgurus.io/blog/meta-system-design-interview-questions?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=company-specific-interview-guides)
- [Microsoft system design interview questions](https://www.designgurus.io/blog/microsoft-system-design-interview-questions?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=company-specific-interview-guides)
- [Netflix system design interview questions](https://www.designgurus.io/blog/netflix-system-design-interview-questions-guide?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=company-specific-interview-guides)
- [OpenAI system design interview questions](https://www.designgurus.io/blog/openai-system-design-interview-questions?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=company-specific-interview-guides)
- [Google, Amazon, and Meta compared](https://www.designgurus.io/blog/system-design-interviews-at-google-meta-amazon?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=company-specific-interview-guides)
- [Staff-level (L6) expectations](https://www.designgurus.io/blog/system-design-interview-l6-engineers?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=company-specific-interview-guides)
- [Company guides for more than 120 companies](https://github.com/design-gurus/grokking-system-design/blob/main/companies/README.md) **Free**

## Papers every engineer should read

Most interview designs reuse ideas from a small number of papers. Read the summary first, then the paper.

| Paper | Why read it | Summary |
|-------|-------------|---------|
| [Dynamo](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf) (Amazon) | Consistent hashing, quorums, and vector clocks in one system | [Deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/dynamo-key-value-store.md) |
| [The Google File System](https://research.google/pubs/the-google-file-system/) | A single master and chunk servers for large files | [Deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/gfs-distributed-file-system.md) |
| [Bigtable](https://research.google/pubs/bigtable-a-distributed-storage-system-for-structured-data/) (Google) | The wide-column model and LSM-based storage | [Deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/bigtable-wide-column-store.md) |
| [MapReduce](https://research.google/pubs/mapreduce-simplified-data-processing-on-large-clusters/) (Google) | The model behind batch processing at scale | [Deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/mapreduce-batch-processing.md) |
| [Spanner](https://research.google/pubs/spanner-googles-globally-distributed-database-2/) (Google) | Global transactions using synchronized clocks | [Deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/spanner-global-sql.md) |
| [Chubby](https://research.google/pubs/the-chubby-lock-service-for-loosely-coupled-distributed-systems/) (Google) | A lock service for coordination | [Deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/chubby-distributed-locking.md) |
| [ZooKeeper](https://www.usenix.org/legacy/event/atc10/tech/full_papers/Hunt.pdf) | Coordination primitives used by many systems | [Deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/zookeeper-coordination.md) |
| [Kafka](https://notes.stephenholiday.com/Kafka.pdf) (LinkedIn) | The partitioned log as a messaging system | [Deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/kafka-distributed-messaging.md) |
| [Cassandra](https://www.cs.cornell.edu/projects/ladis2009/papers/lakshman-ladis2009.pdf) (Facebook) | Dynamo's distribution with Bigtable's data model | [Deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/cassandra-wide-column-db.md) |
| [Raft](https://raft.github.io/raft.pdf) | Consensus designed to be understandable | [Deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/raft-consensus.md) |
| [Paxos Made Simple](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf) | The original consensus algorithm, in short form | Read after Raft |
| [Time, Clocks, and the Ordering of Events](https://lamport.azurewebsites.net/pubs/time-clocks.pdf) | Logical clocks and happens-before | [Logical clocks pattern](https://github.com/design-gurus/grokking-system-design/blob/main/patterns/logical-clocks.md) |
| [Scaling Memcache at Facebook](https://www.usenix.org/system/files/conference/nsdi13/nsdi13-final170_update.pdf) | Caching at very large scale, including leases | [Deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/memcached-at-facebook.md) |
| [TAO](https://www.usenix.org/system/files/conference/atc13/atc13-bronson.pdf) (Facebook) | A graph store built on sharded MySQL and caches | Read after Memcache |
| [Amazon Aurora](https://www.amazon.science/publications/amazon-aurora-design-considerations-for-high-throughput-cloud-native-relational-databases) | Separating storage from compute in a relational database | [Deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/aurora-cloud-native-database.md) |
| [Amazon DynamoDB](https://www.usenix.org/system/files/atc22-elhemali.pdf) | How a managed NoSQL service stays predictable | [Deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/dynamodb-managed-nosql.md) |
| [Borg](https://research.google/pubs/large-scale-cluster-management-at-google-with-borg/) (Google) | Cluster management, the ancestor of Kubernetes | [Deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/borg-kubernetes.md) |
| [Dremel](https://research.google/pubs/dremel-interactive-analysis-of-web-scale-datasets-2/) (Google) | Columnar storage for interactive analytics | Read after Bigtable |
| [HNSW](https://arxiv.org/abs/1603.09320) | The graph index behind most vector databases | [Deep dive](https://github.com/design-gurus/grokking-system-design/blob/main/deep-dives/hnsw-vector-search.md) |

For a longer list, see [10 must-read system design papers](https://www.designgurus.io/blog/sys-design-papers?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=papers-every-engineer-should-read) and [40 white papers for system design and architecture](https://www.designgurus.io/blog/system-design-white-papers?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=papers-every-engineer-should-read).

## Real-world case studies

Engineering posts that explain a real design decision, with the numbers behind it.

- [How Discord stores trillions of messages](https://discord.com/blog/how-discord-stores-trillions-of-messages): a migration from Cassandra to ScyllaDB, with request coalescing.
- [How Figma's databases team lived to tell the scale](https://www.figma.com/blog/how-figmas-databases-team-lived-to-tell-the-scale/): horizontal sharding of Postgres.
- [Herding elephants: sharding Postgres at Notion](https://www.notion.com/blog/sharding-postgres-at-notion): when and how to shard a growing database.
- [Partitioning GitHub's relational databases](https://github.blog/engineering/infrastructure/partitioning-githubs-relational-databases-scale/): splitting one MySQL cluster by domain.
- [Online migrations at scale](https://stripe.com/blog/online-migrations) (Stripe): the four-step pattern for changing data models with no downtime.
- [Real-time messaging at Slack](https://slack.engineering/real-time-messaging/): how messages reach every connected client.
- [Inside the Magic Pocket](https://dropbox.tech/infrastructure/inside-the-magic-pocket) (Dropbox): moving exabytes of storage off a public cloud.
- [Scaling Pinterest](https://highscalability.com/scaling-pinterest-from-0-to-10s-of-billions-of-page-views-a/) (High Scalability): how Pinterest sharded MySQL and kept the design simple during rapid growth.
- [Schemaless at Uber](https://www.uber.com/blog/schemaless-part-one-mysql-datastore/): a datastore built on top of MySQL.
- [How Cloudflare built Pingora](https://blog.cloudflare.com/how-we-built-pingora-the-proxy-that-connects-cloudflare-to-the-internet/): replacing NGINX with a proxy written in Rust.
- [TAO: the power of the graph](https://engineering.fb.com/2013/06/25/core-infra/tao-the-power-of-the-graph/) (Meta): the social graph store, in a short blog version.
- [Timelines at scale](https://www.infoq.com/presentations/Twitter-Timeline-Scalability/) (Twitter): the talk that explains fan-out on write.

## Engineering blogs

Follow a few of these to see how real systems change over time.

- [Netflix Tech Blog](https://netflixtechblog.com/)
- [Uber Engineering](https://www.uber.com/blog/engineering/)
- [Engineering at Meta](https://engineering.fb.com/)
- [Airbnb Engineering](https://medium.com/airbnb-engineering)
- [Discord Engineering](https://discord.com/category/engineering)
- [Stripe Engineering](https://stripe.dev/blog/topic/engineering)
- [Pinterest Engineering](https://medium.com/pinterest-engineering)
- [Figma Engineering](https://www.figma.com/blog/engineering/)
- [Cloudflare Blog](https://blog.cloudflare.com/)
- [Slack Engineering](https://slack.engineering/)
- [Dropbox Tech](https://dropbox.tech/)
- [LinkedIn Engineering](https://www.linkedin.com/blog/engineering)
- [Shopify Engineering](https://shopify.engineering/)
- [GitHub Engineering](https://github.blog/engineering/)
- [Spotify Engineering](https://engineering.atspotify.com/)
- [DoorDash Engineering](https://careersatdoordash.com/engineering-blog/)
- [Lyft Engineering](https://eng.lyft.com/)
- [Grab Tech](https://engineering.grab.com/)
- [Canva Engineering](https://www.canva.dev/blog/engineering/)
- [AWS Architecture Blog](https://aws.amazon.com/blogs/architecture/)
- [All Things Distributed](https://www.allthingsdistributed.com/), by Werner Vogels
- [High Scalability](https://highscalability.com/): architecture write-ups of many well-known sites.

## Newsletters

- [Design Gurus newsletter](https://designgurus.substack.com/) **Free**: system design and interview preparation, by Arslan Ahmad.
- [ByteByteGo newsletter](https://blog.bytebytego.com/): weekly visual explanations, by Alex Xu.
- [The System Design Newsletter](https://newsletter.systemdesign.one/): case studies of real systems, by Neo Kim.
- [The Pragmatic Engineer](https://newsletter.pragmaticengineer.com/): how large engineering organizations build software, by Gergely Orosz.
- [The Developing Dev](https://www.developing.dev/): career growth for engineers at large companies, by Ryan Peterman.
- [AlgoMaster newsletter](https://blog.algomaster.io/): concept explainers and interview problems.
- [Quastor](https://www.quastor.org/): summaries of engineering blog posts.
- [Architecture Notes](https://architecturenotes.co/): long illustrated articles on infrastructure.

## YouTube channels and talks

### Channels

- [Design Gurus](https://www.youtube.com/@designgurus1173) **Free**: system design lessons and interview walkthroughs.
- [ByteByteGo](https://www.youtube.com/@ByteByteGo) **Free**: short animated explanations of one concept each.
- [Gaurav Sen](https://www.youtube.com/@gkcs) **Free**: interview-focused explanations of classic problems.
- [Hussein Nasser](https://www.youtube.com/@hnasr) **Free**: backend and database engineering in depth.
- [Jordan Has No Life](https://www.youtube.com/@jordanhasnolife5163) **Free**: dense, detailed interview walkthroughs.
- [Hello Interview](https://www.youtube.com/@hello_interview) **Free**: mock interviews and problem breakdowns.
- [Aced (formerly Exponent)](https://www.youtube.com/@tryexponent) **Free**: recorded mock interviews.
- [Arpit Bhayani](https://www.youtube.com/@AsliEngineering) **Free**: paper and engineering blog breakdowns.
- [CMU Database Group](https://www.youtube.com/@CMUDatabaseGroup) **Free**: university database lectures and talks.
- [MIT 6.824](https://www.youtube.com/@6.824) **Free**: the distributed systems lectures.

### Videos from Design Gurus

Full interview walkthroughs:

- [URL Shortener and Pastebin System Design](https://www.youtube.com/watch?v=_TsJizByBvE) (1 h 39 min) **Free**: a complete walkthrough of the first problem in Grokking the System Design Interview.
- [Designing Messenger](https://www.youtube.com/watch?v=Va6EgMV9-7k) (1 h 43 min) **Free**: a chat system from requirements to storage and delivery.
- [Grokking the System Design Interview: The 7-Step Method](https://www.youtube.com/watch?v=N3r-Z6_IGTM) (5 min) **Free**: the framework the course uses for every problem.

Short explainers, most under five minutes:

- Data: [How database sharding works](https://www.youtube.com/watch?v=5OvOpa57G6w), [7 database indexes](https://www.youtube.com/watch?v=zfmcL1gbgYk), [how SQL queries execute](https://www.youtube.com/watch?v=UnP5Vrdihgg), and [PostgreSQL vs MySQL](https://www.youtube.com/watch?v=XJhH1de4_oM).
- Caching and messaging: [8 Redis patterns for system design interviews](https://www.youtube.com/watch?v=d1eBQyRXlr4), [6 distributed caching pitfalls](https://www.youtube.com/watch?v=W33QbFF2oPs), [Apache Kafka explained](https://www.youtube.com/watch?v=d2C2G3YWP8U), and [event-driven architecture patterns](https://www.youtube.com/watch?v=p7tgsc4ym08).
- APIs and networking: [REST vs gRPC vs GraphQL](https://www.youtube.com/watch?v=y_ur1tUxlfQ), [RPC vs gRPC](https://www.youtube.com/watch?v=AsRWFvrbLJQ), [API architecture patterns](https://www.youtube.com/watch?v=nc7aTjT4LTE), [forward vs reverse proxy](https://www.youtube.com/watch?v=3A34I1fG4BM), [HTTP/1.1 vs HTTP/2 vs HTTP/3](https://www.youtube.com/watch?v=ef-jru5ofuA), and [how HTTPS works](https://www.youtube.com/watch?v=Y192TRjqaLU).
- Security: [JWT vs OAuth 2.0](https://www.youtube.com/watch?v=zHAjzuhK3_0) and [how OAuth 2.0 works](https://www.youtube.com/watch?v=z7gQETX50ik).
- Reliability and scale: [10 system design failure modes](https://www.youtube.com/watch?v=XzNe5QPDMUk) and [why a vibe-coded app crashes at 10,000 users](https://www.youtube.com/watch?v=JKaaIMHFOP0).

### Talks and long videos

- [System Design for Beginners Course](https://www.youtube.com/watch?v=m8Icp_Cid5o) (freeCodeCamp) **Free**: a full introductory course in one video.
- [20 System Design Concepts Explained in 10 Minutes](https://www.youtube.com/watch?v=i53Gi_K3o7I) (NeetCode) **Free**: a fast overview of the vocabulary.
- [Scaling Instagram Infrastructure](https://www.youtube.com/watch?v=hnpzNAPiC0E) (InfoQ) **Free**: how Instagram scaled across data centers.
- [Building Software Systems at Google and Lessons Learned](https://www.youtube.com/watch?v=modXC5IWTJI) (Jeff Dean, Stanford) **Free**: design lessons from Google's early systems.

## AI and machine learning system design

AI questions now appear in ordinary system design loops, not only in ML roles.

- [Grokking the AI System Design Interview](https://www.designgurus.io/course/grokking-the-ai-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=ai-and-machine-learning-system-design): the course for LLM, RAG, and agent design rounds.
- [Grokking Modern AI Fundamentals](https://www.designgurus.io/course/grokking-modern-ai-fundamentals?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=ai-and-machine-learning-system-design): the AI concepts to learn before the design round.
- [Grokking the AI System Design Interview repo](https://github.com/design-gurus/grokking-ai-system-design) **Free**: building blocks and worked questions.
- [AI System Design Interview: The Complete Guide](https://www.designgurus.io/blog/ai-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=ai-and-machine-learning-system-design) **Free**
- [How to prepare for an AI/ML system design interview](https://www.designgurus.io/blog/prepare-for-ai-ml-system-design-interview-2026?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=ai-and-machine-learning-system-design) **Free**: a study roadmap.
- [System design for RAG](https://www.designgurus.io/blog/system-design-for-rag?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=ai-and-machine-learning-system-design) **Free**: vector databases, chunking, and re-ranking.
- [Designing LLM inference systems](https://www.designgurus.io/blog/design-llm-inference-systems?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=ai-and-machine-learning-system-design) **Free**: batching, memory, and GPUs.
- [Vector database system design](https://www.designgurus.io/blog/vector-database-hnsw-ivf?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=ai-and-machine-learning-system-design) **Free**: HNSW, IVF, and product quantization.
- [Design an AI agent](https://www.designgurus.io/blog/design-an-ai-agent?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=ai-and-machine-learning-system-design) **Free**: a seven-layer blueprint.
- [AI cost estimation](https://www.designgurus.io/blog/mastering-ai-cost-estimation?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=ai-and-machine-learning-system-design) **Free**: why designs that ignore cost fail.
- Repo walkthroughs **Free**: [ChatGPT](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-chatgpt.md), [RAG pipeline](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-rag-pipeline.md), [LLM gateway](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-llm-gateway.md), [LLM inference platform](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-llm-inference-platform.md), [semantic search](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-semantic-search.md), and [recommendation system](https://github.com/design-gurus/grokking-system-design/blob/main/questions/design-recommendation-system.md).
- [Hello Interview: ML System Design in a Hurry](https://www.hellointerview.com/learn/ml-system-design/in-a-hurry/introduction) **Free**: a written guide to the ML round.
- [Building effective agents](https://www.anthropic.com/engineering/building-effective-agents) (Anthropic) **Free**: when to use workflows and when to use agents.
- [Patterns for building LLM-based systems](https://eugeneyan.com/writing/llm-patterns/) (Eugene Yan) **Free**: evals, retrieval, caching, and guardrails.
- [Chip Huyen's blog](https://huyenchip.com/blog/) **Free**: long essays on ML and LLM systems in production.

## Mock interviews and practice platforms

A mock interview shows you gaps that reading does not. Do at least one before the real interview.

- [Design Gurus mock interviews](https://www.designgurus.io/mock-interviews?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=mock-interviews-and-practice-platforms): 60-minute system design mocks with engineers from FAANG companies, followed by detailed feedback on your design and trade-offs.
- [interviewing.io](https://interviewing.io/mocks): anonymous mock interviews with engineers from large tech companies.
- [Aced (formerly Exponent)](https://www.aced.io/practice): peer mock interviews.
- [Codemia](https://codemia.io/): practice problems with AI evaluation, plus peer mock interviews.
- [System Design School](https://systemdesignschool.io/): practice problems with feedback on each attempt.
- [The 14-day system design interview plan](https://www.designgurus.io/blog/two-week-system-design-interview-plan?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=mock-interviews-and-practice-platforms) **Free**: what to practice each day.

## Diagramming tools

- [Excalidraw](https://excalidraw.com/) **Free**: a hand-drawn style whiteboard, used in many remote interviews.
- [draw.io](https://www.drawio.com/) **Free**: detailed architecture diagrams.
- [Top 7 tools for system design diagrams](https://www.designgurus.io/blog/top-7-tools-for-creating-system-design-diagrams?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=diagramming-tools) **Free**: a comparison.
- [The diagram everyone must make in a system design interview](https://www.designgurus.io/blog/diagram-to-make-in-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=diagramming-tools) **Free**

## Frequently asked questions

### What is the best resource to learn system design?

For most engineers, the best path is one structured course plus one deep book. [Grokking the System Design Interview](https://www.designgurus.io/course/grokking-the-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=frequently-asked-questions) teaches the patterns that interview problems reuse. *Designing Data-Intensive Applications* explains why those patterns work. If you are new to the subject, start with [Grokking System Design Fundamentals](https://www.designgurus.io/course/grokking-system-design-fundamentals?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=frequently-asked-questions) first.

### What are the best free system design resources?

The [System Design Primer](https://github.com/donnemartin/system-design-primer), the free [Grokking System Design repo](https://github.com/design-gurus/grokking-system-design), MIT's [6.5840 lectures](https://pdos.csail.mit.edu/6.824/), and the [Amazon Builders' Library](https://builder.aws.com/learn/topics/builders-library) together cover most of what an interview needs. See also [10 free resources to learn system design](https://www.designgurus.io/blog/free-system-design-resources?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=frequently-asked-questions) and [the best system design GitHub repos](https://www.designgurus.io/blog/best-system-design-github-resources?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=frequently-asked-questions).

### What is the best system design book?

For understanding, *Designing Data-Intensive Applications* by Martin Kleppmann. For the interview, Alex Xu's *System Design Interview* volumes. Read DDIA for depth and use an interview book or course for practice.

### How long does it take to prepare for a system design interview?

Most engineers need four to eight weeks of steady study. Engineers with production distributed systems experience often need less. See [how long it takes to prepare](https://www.designgurus.io/blog/how-long-to-prepare-for-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=frequently-asked-questions) for a breakdown by experience level.

### Which resources are best for senior and staff engineers?

[Advanced System Design Interview, Volume II](https://www.designgurus.io/course/grokking-system-design-interview-ii?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=frequently-asked-questions), the [papers](#papers-every-engineer-should-read) above, and the [senior and staff refresher](https://github.com/design-gurus/grokking-system-design/blob/main/roadmaps/senior-staff-refresher.md). Senior loops reward trade-off reasoning more than component lists, so practice explaining why you chose each part of a design.

### Which system design course should I buy?

It depends on your level and how you learn. The [comparison of system design interview courses](https://www.designgurus.io/blog/best-system-design-interview-courses-2026?utm_source=github&utm_medium=repo&utm_campaign=best-system-design-resources&utm_content=frequently-asked-questions) compares the main options side by side.

## Contributing

Suggestions are welcome. Open an issue or a pull request with the resource, the section it belongs in, and one sentence on who it helps. A resource should be accurate, maintained, and useful on its own. Affiliate and referral links are not accepted.

## License

This list is licensed under [CC BY 4.0](LICENSE). Each linked resource belongs to its author.
