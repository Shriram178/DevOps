1. Where Lean Comes From

- Origin story: It started with Sakichi Toyoda (yes, Toyota family), who noticed waste in how his mother weaved. He invented machines to make work easier.
- Key idea: Put the human being at the center—free people from boring, repetitive work.
- Toyota Production System (TPS): After WWII, Japan couldn’t mass-produce like the U.S., so they focused on eliminating waste instead of chasing raw speed.

  Two pillars:
  - Just-in-time → only produce what’s needed, when it’s needed.
  - Jidoka (autonomation) → stop the line if there’s a defect (don’t keep producing broken stuff).

  👉 Later, when applied to software, this thinking became lean software development. It overlaps with agile but focuses especially on waste reduction.

---

2. The Principle of Lean Development

- If you aim for speed, you might just pile up waste.

- If you aim to remove waste, you’ll get both waste reduction and speed.

- Example: Catching a bug late is very costly (customer sees it). Catching it earlier (tests, code review, test-first development) costs much less.

- Core lesson: Push defect detection earlier and earlier.
---
3. Build Quality

  - Two types of inspection:

    1. Find defects (after the fact).

    2. Prevent defects (build safeguards into the process).

  - Japanese term: poka-yoke (“error-proofing”). Everyday examples: can’t plug in a USB the wrong way, car won’t start unless clutch is pressed.

  - In DevOps/software:

    - Least privilege in security (prevent bad actions).

    - No one can commit directly to deployment branch—forces review/testing first.

    - IDE tells you about compile errors immediately.

- Shift-left thinking: Build quality into the process early, instead of relying on fixing later.

---

4. Create Knowledge

  - In software, certainty matters—we want to know not just “the code works,” but “we’re confident it works.”

  - Automated tests, CI/CD, code reviews, load tests all create knowledge.

  - Software is research—we can’t fully know the final thing until we’re deep into building it.

  - So: accept uncertainty (called epistemic humility) instead of pretending we know everything up front.

---
5. Defer Commitment

- Don’t lock yourself into big decisions too early when your knowledge is poor.

- Two types of decisions:

    - Reversible → easy to undo.

    - Irreversible → hard/costly to undo.

- Lean advice: make reversible decisions early, but push irreversible ones until you have better information.

- Real-world examples: Amazon’s easy return policy, travel insurance → all about preserving reversibility.

---
