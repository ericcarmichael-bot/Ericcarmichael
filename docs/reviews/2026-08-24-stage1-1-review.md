<!-- PR TARGET: https://github.com/ericcarmichael-bot/eric-carmichael | Stage 1.1 (2.5 pts) -->
# Stage 1.1 review — engagement brief · **82 / 100** (B) · 2.05 / 2.5 pts

**Brief:** [`docs/briefs/perfect-competition-brief.md`](https://github.com/ericcarmichael-bot/eric-carmichael/blob/main/docs/briefs/perfect-competition-brief.md)

> Re-graded 2026-08-31 against your revised brief. Your previous score was 80, and that 80 was the floor rather than a total you had earned — your raw was 60. This one is 82 on merit, so the floor is no longer carrying anything. One section is still missing and it is worth eight points on its own.

| Criterion | Earned | Notes |
|---|---|---|
| Problem restated in your own voice | 25 / 30 | Up from 20. The opening is genuinely yours and it is right: the farm is too small to influence price, it is a price taker, the only variable it controls is what goes into the ground, and every additional bed of a crop makes each bed of that crop more expensive because of pest pressure, harvest bottlenecks, and walking time. That last sentence explains why diminishing returns exist rather than just naming them, which is more than most of this cohort managed. The five points off are that the second half of the section is the case data table transcribed, and transcription is not restatement. What is missing is the one sentence the stage actually asks for: what happens if this is decided badly. You know the answer — the season is planted once — but you do not say it. |
| Hypothesis names a specific mix | 25 / 25 | Up from 18. Eight tomato, 20 carrot, 30 mesclun, totaling 58 beds, with the six idle beds stated as a consequence rather than left unexplained. Last time you wrote "roughly 10 beds" and a mesclun figure of 34 that exceeded the 30-bed cap. Both are fixed and the numbers are now inside the constraints. |
| Economic mechanism | 22 / 25 | Up from 12, and this is where the score moved. Last time the reasoning was "it is likely roughly in this ratio due to the revenue and cost scaling relationship," which is a sentence that could precede any three numbers. Now you argue crop by crop and the argument has a direction: tomatoes are attractive first and decline fastest, carrots use resources most efficiently so they run to the cap, and mesclun "would become increasingly attractive as the tomatoes' return declines." |
| Falsifiability and process | 10 / 20 | Unchanged, and it is now the only thing holding this brief down. There is still no section saying what result would show you were wrong. Everything else in this brief has improved; this has not moved at all, and it is worth more than any other single fix available to you. |
| **Final** | **82 / 100** | earned on merit |

### Why the substitution argument is the best thing here

"I expect Mesclun would become increasingly attractive as the tomatoes' return declines" is doing something the rest of the cohort's briefs do not. Everyone else ranks the three crops once and allocates in that order. You are describing a comparison that changes as you go: mesclun does not get better in absolute terms, it gets better relative to the alternative, because the alternative is getting worse.

That is how the actual decision works. At every bed you are not asking "is this crop good" but "is this crop the best remaining use of a bed right now," and the answer moves as the beds fill. Hold onto that framing for Stage 2. It is the reason the optimizer's answer will not be a simple ranking, and it is the thing you will be able to explain in Stage 3 that others will not.

### What I'd fix first, and it is one paragraph

Add a section called "How I would know I was wrong." Three sentences is enough. Each one names an outcome the model could actually produce and says what claim of yours it would break.

Yours are already sitting in your own text, unwritten. You claim tomatoes decline fastest — so if the model plants more than 8 tomato beds, you were wrong about how fast. You claim carrots and mesclun both run to their caps — so if either comes back under its cap, something stopped them before the cap did and you do not know what. You claim six beds are not worth planting — so if all 64 come back planted, that claim is dead.

Write the version with numbers in it. "If the model plants more than 8 tomato beds" is a real test. "If the model shows a different mix" is not — that is true of every hypothesis ever written, and it is the single most common failure in this stage.

Do this before you build, not after. A falsification condition written after you have seen the answer is not a prediction.

---

### How to work this review

Treat this PR the way an analyst treats feedback from a senior reviewer — a review is a proposal to engage with, not a checklist to rubber-stamp.

1. **Read it yourself first.** Form your own view before you change anything. Disagreeing *with a documented reason* is a legitimate, senior response.
2. **Stress-test it with an LLM.** Paste this review and your brief into your assistant and ask it to (a) explain anything you are unsure of, and (b) argue the *other side* — where might the reviewer be wrong, and what would you give up by making each change.
3. **Then write the changes yourself.** For a brief, this matters more than usual: a hypothesis you did not generate cannot be honestly compared against your model in Stage 3, and that comparison is the entire point of writing the brief first.
4. **Close the loop.** Reply in this thread with what you changed and what you pushed back on, then commit and push.

*One standing rule for this stage: do not revise your hypothesis to match what your model later tells you. If the model contradicts the brief, that is a finding, not an error — Stage 3 asks you to explain the gap, and a brief quietly edited to be right afterwards has nothing left to explain.*

— Adam
