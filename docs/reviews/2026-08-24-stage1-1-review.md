<!-- PR TARGET: https://github.com/ericcarmichael-bot/eric-carmichael | Stage 1.1 (2.5 pts) -->
# Stage 1.1 review — engagement brief · **93 / 100** (A) · 2.33 / 2.5 pts

**Brief:** [`docs/briefs/perfect-competition-brief.md`](https://github.com/ericcarmichael-bot/eric-carmichael/blob/main/docs/briefs/perfect-competition-brief.md)

> Re-graded 2026-09-02 against your revision of this morning. Your previous score was 82. You added the section that was missing and you added the sentence I said you already knew but had not written. That is the largest single-pass gain anyone has made on this stage without starting from a floor.

| Criterion | Earned | Notes |
|---|---|---|
| Problem restated in your own voice | 28 / 30 | Up from 25. The five-point deduction last time was for one absent sentence: what happens if this is decided badly. You wrote it, and you wrote it better than I described. "The season is planted a single time. There is no mid-season reallocation if the mix is incorrect. Any error here isn't an inefficiency; it's locked in for the 36-week season." The distinction between an inefficiency and a locked-in commitment is the reason this decision deserves a written brief at all. Two points still off because the middle of the section is the case table transcribed, and transcription is not restatement. |
| Hypothesis names a specific mix | 25 / 25 | Eight tomato, 20 carrot, 30 mesclun, 58 beds, six idle and stated as a consequence. Unchanged and still full marks. |
| Economic mechanism | 22 / 25 | Unchanged. Still crop by crop, still directional, and the substitution argument — mesclun becomes attractive as tomatoes decline — is still the best framing anyone brought to this stage. The three points are the same three: you never put a number to the compounding. "Their margin will decline quickly" is the claim; 1.10 to the eighth is about 2.14, so the eighth tomato bed carries roughly twice the labor hours of the first, and that is the sentence that would close it. |
| Falsifiability and process | 18 / 20 | Up from 10, and this is the whole move. Four conditions, each naming a number the model could return and the claim it would break — more than or fewer than 8 tomato beds, carrots under 20, mesclun under 30, more than 58 beds total. They are yours: I listed three of them out of your own text and you wrote the fourth. Two points off for no tolerance. "Fewer or additional beds of tomatoes" makes 9 beds and 19 beds the same verdict, and they mean different things about how fast you think the penalty bites. |
| **Final** | **93 / 100** | entered |

### What actually moved, so you can repeat it

Two of the four criteria moved and both moved for the same reason: you took a claim you were already making implicitly and wrote it down explicitly.

You always knew the season is planted once. You always knew tomatoes are the crop that stops early. The brief scored 82 because those things were in your head and not on the page, and a brief is only worth what is on the page — in Stage 3 you compare what you committed to against what the model says, and an unwritten belief cannot be compared to anything.

That is the whole discipline, and it is not about writing more. Your revision added about ten lines.

### The one thing to add before you build

Decide your tolerance now, while you cannot see the answer.

You predict 8 tomato beds. If the model returns 9, were you wrong? If it returns 14? Pick the number you would accept as close enough that your mechanism was right and only your crossover estimate was off, and write it into the brief in one sentence. It takes thirty seconds and it is the difference between a Stage 3 reflection that says "I was wrong" and one that says what exactly was wrong.

Do not wait until after the Solver run. A tolerance chosen after you have seen the answer is not a tolerance.

### Looking ahead to Stage 1.2

There is nothing at capabilities/marginal-analysis/spec.md yet beyond a stub, and the stage is due 6 September. The specification is the deliverable that matters most in that stage — it is the document the workbook is built from, and the rule is that when a check fails you fix the specification and regenerate rather than patching the sheet.

Your substitution argument gives you a head start on part of it. The specification has to say how a marginal cost schedule is built, and the reason yours will be right is that you already understand the answer is not a ranking — it is a comparison that moves as the beds fill.

---

### How to work this review

Treat this PR the way an analyst treats feedback from a senior reviewer — a review is a proposal to engage with, not a checklist to rubber-stamp.

1. **Read it yourself first.** Form your own view before you change anything. Disagreeing *with a documented reason* is a legitimate, senior response.
2. **Stress-test it with an LLM.** Paste this review and your brief into your assistant and ask it to (a) explain anything you are unsure of, and (b) argue the *other side* — where might the reviewer be wrong, and what would you give up by making each change.
3. **Then write the changes yourself.** For a brief, this matters more than usual: a hypothesis you did not generate cannot be honestly compared against your model in Stage 3, and that comparison is the entire point of writing the brief first.
4. **Close the loop.** Reply in this thread with what you changed and what you pushed back on, then commit and push.

*One standing rule for this stage: do not revise your hypothesis to match what your model later tells you. If the model contradicts the brief, that is a finding, not an error — Stage 3 asks you to explain the gap, and a brief quietly edited to be right afterwards has nothing left to explain.*

— Adam
