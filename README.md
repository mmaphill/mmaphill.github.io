## Professional Self-Assessment
Completing my Computer Science degree at Southern New Hampshire University has changed how I approach software development. I am no longer looking at applications simply as code blocks that work. I see architecture, performance, security, maintainability, and how each decision affects the rest of the system.

My CS 499 capstone, Travlr Getaways, is example of the growth I have experienced. I took an existing full-stack application and improved it across software engineering, algorithms and data structures, and database performance. The result was not just new functionality, but a more maintainable, efficient, and secure application.

## Enhancement Focus

### Software Design and Engineering
I strengthened the Travlr application by introducing a service-layer architecture, improving TypeScript type safety, applying SOLID and DRY principles, and centralizing error handling. These changes have reduced code duplication and created a structure that is easier to maintain and extend in future updates. 

I also learned the importance of approaching development from another developer's perspective. Good software should not only work—it should be understandable, testable, and maintainable.
 
### Algorithms and Data Structures
I applied data structures to solve actual application problems rather than using them simply because they were required. I implemented a Trie for efficient prefix searching, an LRU cache for repeated recommendation requests, and a MinHeap for efficient top-K trip selection.

These enhancements strengthened my ability to evaluate complexity, identify performance bottlenecks, and choose solutions based on the requirements of the application.
 
### Databases
The database enhancement taught me to look beyond whether a query works and determine whether it works efficiently.

I set the application to two indexes backed by actual query patterns, applied .lean() to read-only queries, removed unnecessary document population, and verified database behavior using MongoDB's Explain Plan.

Most importantly, I learned to validate performance improvements with evidence rather than assumptions.

### Security
Security has become part of how I approach development rather than something added at the end of a project. Throughout Travlr, I worked with authentication, authorization, password hashing, session management, JWTs, and protection of personalized user data.

My goal as a developer is to build applications that are secure by design while remaining practical, maintainable, and easy to use.
 
## Professional Goals

The biggest change I see in myself is the ability to look at an existing system, understand how its pieces interact, identify weaknesses, and make improvements without losing sight of the larger application.

I am interested in software engineering, backend development, and secure application development. I enjoy solving problems where the answer requires more than writing code—it requires understanding why the system behaves the way it does and how it can be made better.

My ePortfolio demonstrates that progression through one application and three different engineering perspectives: design, algorithms, and data.

## About This Portfolio

This portfolio includes:
 
- Original project artifacts
- Enhanced implementations
- Code review presentation
- Technical enhancement narratives
- Professional self-assessment
- Source code and documentation

Each enhancement demonstrates not only the technical changes that were made, but also the reasoning behind those decisions and the growth I experienced throughout the Computer Science program.

## CS 499 Capstone Project

### Travlr Getaways Admin Portal
Full-Stack Web Application | Software Engineering & Design Enhancement

A professional full-stack application demonstrating software engineering best practices. This project showcases architectural improvements including design patterns, type safety, centralized error handling, and secure authentication—all guided by code review feedback.

Technologies: Node.js • Angular • MongoDB • TypeScript • Express

[View Project Details](projects/cs499-capstone.html) | [GitHub Repository](https://github.com/mmaphill/cs465-fullstack) | [Live Demo](https://travlr-phill.railway.app/admin)

---

## Key Achievements
Software Design and Engineering
- 40% Code Reduction through service layer pattern
- 100% Type Safety with TypeScript interfaces
- 85% Less Duplication applying DRY principles
- Centralized Error Handling for consistency
- Professional Architecture with SOLID principles

Algorithms and Data Structures
- Custom Trie for O(m) prefix search across trip name, resort, and code
- LRU cache for O(1) cached recommendation lookups
- MinHeap-based top-K selection for O(n log k) trip ranking
- Content-based recommendation engine personalized to user preferences

Databases
- Index footprint reduced from 6 to 2, each backed by a real query pattern
- `.lean()` applied across all read-only queries, eliminating unnecessary document hydration
- Removed an implicit, unconditional populate join firing on every profile query
- Verified index usage empirically via MongoDB Compass Explain Plan

---

## Artifacts & Documentation
- [📄 Artifact Narrative - Software Engineering and Design](https://docs.google.com/viewer?url=https://mmaphill.github.io/artifacts/3-2-Narrative.docx&embedded=true)
- [📄 Artifact Narrative - Algorithms and Datastructure](https://docs.google.com/viewer?url=https://mmaphill.github.io/artifacts/4-2-Narrative.docx&embedded=true)
- [📄 Artifact Narrative - Database](https://docs.google.com/viewer?url=https://mmaphill.github.io/artifacts/5-2-Narrative.docx&embedded=true)
- [🎥 Code Review Video Part 1 (YouTube)](https://youtu.be/g12Vaj7ZMaw)
- [🎥 Code Review Video Part 2 (YouTube)](https://youtu.be/QqyTjVK6HyY)
- [💻 GitHub Repository - Source Code](https://github.com/mmaphill/cs465-fullstack)

---

Thank you for taking the time to review my portfolio. I hope it demonstrates not only the technical skills I have developed but also my approach to problem solving, continuous learning, and building secure, maintainable software.
