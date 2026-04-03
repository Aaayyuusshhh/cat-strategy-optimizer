# CAT Attempt Strategy Optimizer

A decision-support prototype that helps CAT aspirants decide which questions to attempt, skip, or prioritize based on their accuracy profile.

🔗 **Live Demo:** https://aaayyuusshhh.github.io/cat-strategy-optimizer/

## Preview
![App Screenshot](preview.png)

---

## Problem

Through user conversations, a clear pattern emerged: most CAT aspirants are aware of their strengths and weaknesses, but struggle to use that knowledge during mocks.

Decisions about whether to attempt or skip a question are often instinct driven, especially under time pressure. This leads to avoidable negative marking and inefficient time allocation.

Current platforms, including Optima, focus on post-test analysis. However, they do not help users make better decisions during the test itself.

---

## Why this matters

CAT performance is not just about solving questions correctly, but about maximizing score through smart decision-making.

Users repeatedly highlighted:

* “I knew this topic was weak but still attempted it”
* “I waste time deciding whether to attempt or skip”
* “I don’t have a clear plan before starting a section”

This reveals a gap between awareness and execution.

---

## Solution

This prototype converts a user’s accuracy profile into a clear, actionable attempt strategy.

Instead of leaving decisions to instinct, it provides:

* A structured attempt plan
* Clear prioritization of question types
* Decision guidance under time pressure

---

## How it works

1. User inputs accuracy percentages for different question types
2. The system calculates expected value based on CAT’s marking scheme
3. Each question type is categorized into:

   * Always attempt
   * Attempt if time permits
   * Skip
4. A prioritized strategy is generated for the user

---

## Key Insight

The core problem is not lack of preparation, but lack of decision structure.

This product focuses on converting existing user awareness into actionable strategy during the test.

---

## Integration with Optima

This can fit directly after mock analysis as a “Build Your Strategy” layer.

After showing performance insights, Optima can:

* Translate accuracy data into decision strategies
* Help users simulate attempt decisions
* Improve real test performance, not just analysis

This shifts the product from insight generation to decision support.

---

## Tech Stack

* Frontend only (React / JavaScript)
* No backend required
* Expected value based logic
* Local storage for state persistence

---

## Note

This is a working prototype built to demonstrate a real user problem and its solution. It is not production-ready, but focuses on delivering clear, actionable value.
