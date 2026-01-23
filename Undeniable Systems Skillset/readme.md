# Undeniable Systems Skillset  
## Next-Generation Low-Level Skills for the AI Era

This repository curates **high-signal learning resources** for building
durable, low-level systems skills relevant to modern AI systems,
distributed infrastructure, and security-by-design.

Focus:
- systems behavior
- failure modes
- invariants
- performance
- AI as a system component (not just a model)

---

# PATH A — 6-Month Intensive Knowledge Path

Goal:
Build strong foundational and intermediate skills in systems engineering,
concurrency, distributed systems, AI system behavior, and safety testing.

Constraint:
- At most **2 heavy learning tracks at a time**
- Learning is paired with **building and experimentation**

---

## Month 1–2 — Rust & Systems Foundations

### Rust Systems Programming
Focus:
- ownership & lifetimes
- memory safety
- error handling
- async fundamentals

Resources:
- Rust Full Course (freeCodeCamp)  
  https://www.youtube.com/watch?v=BpPEoZW5IiY
- Rust Ownership & Lifetimes Explained  
  https://www.youtube.com/watch?v=VFIOSWy93H0
- Async Rust Explained (Jon Gjengset)  
  https://www.youtube.com/watch?v=ThjvMReOXYM
- The Rust Programming Language (Book)  
  https://doc.rust-lang.org/book/

---

### Concurrency Fundamentals
Focus:
- threads vs async
- race conditions
- deadlocks
- backpressure

Resources:
- Concurrency is NOT Parallelism — Rob Pike  
  https://www.youtube.com/watch?v=oV9rvDllKEg
- Threads, Locks, and Deadlocks  
  https://www.youtube.com/watch?v=HHoB2bL6jvY
- Rust `std::sync` documentation  
  https://doc.rust-lang.org/std/sync/

---

## Month 3–4 — Performance, Failure & Distributed Reality

### Low-Level Debugging & Performance
Focus:
- CPU vs I/O
- flamegraphs
- memory behavior
- bottleneck analysis

Resources:
- Linux Performance Tools — Brendan Gregg  
  https://www.youtube.com/watch?v=FJW8nGV4jxY
- CPU Flamegraphs Explained  
  https://www.youtube.com/watch?v=K8spO4hHMhg
- Linux Performance Resources  
  https://www.brendangregg.com/linuxperf.html

---

### Distributed Systems Fundamentals
Focus:
- partial failure
- retries vs timeouts
- state & consistency
- graceful degradation

Resources:
- MIT 6.824 — Introduction  
  https://www.youtube.com/watch?v=UEAMfLPZZhE
- Designing Distributed Systems for Failure  
  https://www.youtube.com/watch?v=rypHj3jST5U

---

## Month 5 — Security Thinking & AI Systems

### Threat Modeling & Invariant Thinking
Focus:
- trust boundaries
- misuse and abuse cases
- system invariants

Resources:
- Threat Modeling for Engineers  
  https://www.youtube.com/watch?v=AJUo6Z6vP8c
- OWASP Threat Modeling Overview  
  https://owasp.org/www-community/Threat_Modeling

---

### AI Systems Behavior
Focus:
- instruction hierarchy
- context drift
- role confusion
- tool misuse

Resources:
- LLMs in Production — Andrej Karpathy  
  https://www.youtube.com/watch?v=zjkBMFhNj_g
- LLM Failure Modes (search)  
  https://www.youtube.com/results?search_query=llm+failure+modes+production

---

## Month 6 — Evaluation, Testing & Regression

### Adversarial Testing & Fuzzing
Focus:
- mutation strategies
- scenario testing
- property-based testing

Resources:
- Property-Based Testing Explained  
  https://www.youtube.com/watch?v=zi0rHwfiX1Q
- Hypothesis (Property-Based Testing)  
  https://hypothesis.readthedocs.io/

---

### Safety Regression & Drift Analysis
Focus:
- baseline comparison
- degradation tracking
- multi-step failures

Resources:
- Testing Distributed Systems  
  https://www.youtube.com/watch?v=U6Yzcm7xgHU

---

# PATH B — Refinement, Building & Mastery

Goal:
Convert knowledge into **judgment, clarity, and reliability**.

No new topics are introduced here.

---

## The Build–Break–Refine Loop

Repeat continuously:

1. Build a small system or feature
2. Stress it under failure conditions
3. Observe behavior (logs, metrics, traces)
4. Refine design and invariants
5. Document failure modes and tradeoffs

---

## Mastery Focus Areas

- determinism vs nondeterminism
- reproducibility
- simplicity over cleverness
- failure explanation
- invariant clarity

---

## Optional Validation (Non-Core)

### AWS Solutions Architect — Associate
Purpose: architectural validation and shared vocabulary.

Resources:
- AWS Architecture Talks (re:Invent)  
  https://www.youtube.com/results?search_query=aws+architecture+reinvent

---

## Guiding Principle

> Depth before breadth.  
> Invariants before features.  
> Systems before tools.

---

_End._