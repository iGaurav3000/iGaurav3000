### Backend engineer. Distributed systems, mostly.

Six years on high-throughput Java services — Kafka, Kubernetes, the usual suspects. I spend my days on the parts of a system that only misbehave under load, which turns out to be exactly what senior interviews ask about.

---

### 📘 [Java Backend Interview Handbook](https://github.com/iGaurav3000/java-backend-interview-handbook)

Free, open, and growing weekly.

Most Java interview material stops where real backend work starts. It covers `HashMap` vs `Hashtable` and the SOLID acronym, then hands you a Spring Boot CRUD tutorial — and none of that is what gets asked when you interview for SDE-2 or SSE.

What gets asked is whether you understand the machinery you use every day. What `@Transactional` actually does at the proxy boundary. What a consumer rebalance does to your delivery guarantee. Why your connection pool is sized wrong.

The handbook covers that layer.

**Live now**
- Kafka delivery semantics and idempotency — where the offset commit belongs, and exactly where exactly-once stops

**Coming**
Java internals · Spring internals · low-level design · system design · DSA patterns · behavioral rounds

---

### Who it's for

Engineers with 2–7 years of experience who can already write the code, but keep getting caught by the follow-up: *"okay, but what happens if two instances do that at the same time?"*

If something in it is wrong, open an issue. Corrections get credited.
