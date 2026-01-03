# 👋 Hey, I’m Donnie (DonnieTD)

I build **systems**, not demos — and I care a lot about what’s left behind _after_ code runs.

This repo (and my profile) is a collection of projects where execution is **explicit**, state is **inspectable**, and nothing important is hidden behind “magic”.

Think less _framework glue_, more _clear machinery_.

---

## 🧠 What I Care About

- 🧩 **Structure before optimization**
- 📜 **Artifacts over logs**
- 🔁 **Replayable execution**
- 🕰 **History you can inspect**
- 🔒 **Invariants that don’t lie**

If a system can’t explain itself after the fact, I don’t trust it yet.

---

## 🚀 Projects Worth Looking At

### 🌌 **Liminal**

A structural execution engine for C.

- AST → World → Step timeline
- Execution modeled as data
- Clear separation between parsing, execution, and analysis
- Built for reasoning, auditing, and correctness

This is about making _program execution observable_.

---

### 🤖 **HML (Hierarchical Machine Learning)**

Machine learning without the black box.

- Neural networks built from monoids and folds
- Training runs produce **versioned artifacts**
- Inputs and weights evolve together
- Append-only metadata with strong invariants
- Hashes for reproducibility and trust

Key invariant:

- inputs-meta.json and weights-meta.json are append-only
- index `i` in both files represents the same run
- a run is complete iff both entries exist at index `i`
- mismatches are detectable, not silent

This started as a learning experiment and turned into something… spicy.

---

### 🧵 **NAH**

A language + compiler built from scratch.

- Recursive descent
- No dependencies doing the hard parts for me
- Full control over parsing and semantics

This is where I sharpen fundamentals.

---

### 💾 **giga-arena**

A fast, explicit arena allocator.

- Deterministic lifetimes
- Minimal overhead
- Built for systems that actually care about memory

---

### 📦 **giga-hash-map**

A performance-first hashmap.

- Cache-aware
- Allocation-conscious
- Designed intentionally, not inherited

---

### 🔐 **GoCrypt**

Applied cryptography in Go.

- Practical primitives
- Protocol-focused thinking
- Less ceremony, more understanding

---

## 📐 How I Think About Systems

- Execution is a **phase**, not a side effect
- State should be **versioned**, not overwritten
- Failure should be **detectable**, not surprising
- History is a feature
- Simpler models scale better than clever ones

---

## 🔭 What I’m Exploring Right Now

- Artifact-based execution models
- ML systems you can replay and audit
- Compiler pipelines with explicit semantics
- Low-level systems with high-level guarantees

---

## 🧑‍💻 Final Thoughts

Nothing here is meant to be flashy.
It’s meant to **hold up over time**.

If you like:

- compilers 🧵
- execution models ⏱
- machine learning without mysticism 🧠
- systems that don’t hide their mistakes 🔍

…you’ll probably enjoy poking around.

⭐ Star what you like  
🔁 Fork what inspires you  
🧠 Read the invariants

Thanks for stopping by.
