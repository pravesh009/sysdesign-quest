# SysDesign Quest

Learn system design by playing. An interactive, gamified course that takes you from a single server to a sharded, cached, fault-tolerant distributed system - with hands-on simulators, real-world examples, and interview-focused framing at every step.

It's a **single self-contained HTML file**. No build step, no dependencies, no backend. Open it and it works.

---

## Quick start

Direct GitHub pages: https://pravesh009.github.io/sysdesign-quest/

**Try it locally** - download `index.html` and double-click it. That's the whole setup.

**Host it on GitHub Pages:**
1. Create a public repo and add this file as `index.html`.
2. Go to **Settings → Pages → Build and deployment**, set **Source** to *Deploy from a branch*, pick **main** / **/ (root)**, and Save.
3. Wait 1–3 minutes. Your site is live at `https://<your-username>.github.io/<repo>/`.

Progress is saved in each visitor's browser (localStorage), so redeploying never resets anyone's XP.

---

## What's inside

**8 levels**, gated so each boss quiz unlocks the next:

| # | Level | You'll learn |
|---|-------|--------------|
| 1 | Scaling Basics | Vertical vs horizontal, stateless services, load balancing |
| 2 | Caching | Strategies, invalidation, stampedes, eviction, CDNs |
| 3 | Databases & Sharding | SQL vs NoSQL, indexes, replication, shard keys |
| 4 | Consistency & CAP | CAP, quorums, transactions, sagas, PACELC |
| 5 | APIs & Rate Limiting | REST/GraphQL/gRPC, idempotency, gateways |
| 6 | Queues & Async | Message queues, pub/sub, Kafka, delivery guarantees |
| 7 | Resilience Patterns | Cascading failure, retries, circuit breakers, observability |
| 8 | Design Challenges | The 45-min framework, estimation, a full worked design |

Each of the **32 topics** follows the same arc: *What it is → Why it exists → How it works (with pseudocode) → When to use it → In the wild → In the interview → Key takeaways you can say from memory.*

**7 hands-on simulators** - the concepts you can poke at instead of just read:
- **Load balancer** - switch algorithms, kill servers, watch traffic redistribute
- **LRU cache** - click keys, watch hits, misses, and evictions
- **Consistent hash ring** - add/remove nodes, compare key movement vs plain modulo
- **CAP playground** - cut the network, read stale data under CP vs AP rules
- **Token bucket** - spam requests and watch rate limiting kick in
- **Message queue** - trigger a spike, drain the backlog by adding consumers
- **Circuit breaker** - trip it, watch it fail fast, then recover

**Design challenges** - pick components for a URL shortener, chat app, and news feed, and get graded on what's missing *and* what's overengineered.

---

## Gamification

- **XP and levels** - six ranks from Intern to Principal Architect
- **12 badges** for completing labs and acing quizzes
- **Daily streak** counter
- **Boss quizzes** - pass 2 of 3 to unlock the next level

---

## Tech

Plain HTML, CSS, and vanilla JavaScript in one file. The only external requests are to Google Fonts; if those are blocked, the page falls back to system fonts and still works. Responsive down to phone width. Light and dark themes (follows your system, with a manual toggle).

---

## Credits

Curriculum built from the concepts in [ashishps1/awesome-system-design-resources](https://github.com/ashishps1/awesome-system-design-resources).
