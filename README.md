# Database Internals

Standalone learning repo. Work here on its own — no other repos required.

**Phase (for your own roadmap):** Data

## Context

Indexes, WAL, replication, and isolation levels are why databases behave the way they do under load and failure. This is systems thinking for storage engines — independent of any particular product tutorial.

This repository is the single place for everything related to **Database Internals**: notes, exercises, and small projects. Clone it, open it, and treat it as a complete unit of study.

## Scope

- B-trees and LSM trees
- Write-ahead logging (WAL)
- Replication styles and failover intuition
- Sharding and partitioning
- Isolation levels and anomalies
- What \"durable\" and \"consistent\" mean under the hood

## Outcomes

When you are done with this repo, you should be able to:

- Explain how a write becomes durable
- Contrast B-tree vs LSM workloads
- Reason about isolation level choice for a given workload

## How to work in this repo

1. Read / write concept notes under `notes/`.
2. Solve practice problems under `exercises/`.
3. Ship at least one small project under `projects/` that forces the ideas to stick.
4. Tick the checklist below as you go.

You do not need any other curriculum repo open while you work here.

## Layout

```
database-internals/
├── README.md       # Context and checklist (this file)
├── notes/          # Concept write-ups
├── exercises/      # Practice problems and solutions
└── projects/       # Mini builds that apply the topic
```

## Progress

- [ ] Core concepts noted
- [ ] Exercises completed
- [ ] Mini-project shipped
- [ ] Can explain the main ideas without looking anything up

## Resources

Add books, docs, courses, and articles here as you find them. Keep this list local to this topic.

---

_This repo is independent. Progress elsewhere does not block work here._
