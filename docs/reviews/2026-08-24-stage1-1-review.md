<!-- PR TARGET: https://github.com/ericcarmichael-bot/eric-carmichael | Stage 1.1 (2.5 pts) -->
# Stage 1.1 review — engagement brief · **80 / 100** (B-) · 2.00 / 2.5 pts

**Brief:** [`docs/briefs/perfect-competition-brief.md`](https://github.com/ericcarmichael-bot/eric-carmichael/blob/main/docs/briefs/perfect-competition-brief.md)

| Criterion | Earned | Notes |
|---|---|---|
| Problem restated in your own voice | 20 / 30 | The opening is good and it is clearly yours — the farm is too small to influence prices, the only variable it controls is what goes in the ground, and every extra bed makes each bed more expensive through pest pressure and harvest bottlenecks. That is the case understood. Two things pull it down. One sentence stops mid-thought: "additional labor is at the rate of" and then nothing. And roughly half the file is the case prompt pasted in under a line reading "Ignore everything below this line" — which means a reader has to be told which parts of your brief are yours. |
| Hypothesis names a specific mix | 18 / 25 | "Roughly 10 beds of tomatoes, 20 beds of carrots and 34 beds of mesclun." Specific, which is what the stage asks for — but the mesclun cap is 30, so 34 is not an available choice. It also totals 64, which suggests the numbers were fitted to fill the farm rather than derived from the crop economics. |
| Economic mechanism | 12 / 25 | "It is likely roughly in this ratio due to the revenue and cost scaling relationship" is the whole of the reasoning, and it is too general to be checked. The case hands you the specific scaling relationship — labor hours grow at 10% per tomato bed, 2.5% per carrot bed, 1.25% per mesclun bed — and naming those rates is what turns a ratio into a prediction. The hedge that follows, "although planting fully likely will go beyond the marginal benefit," points at the right idea but pulls back from committing to it. |
| Falsifiability and process | 10 / 20 | No falsification section, and the hedge means the brief can accommodate most outcomes. Brief and spec were committed in the same push on 2026-08-23, so the brief-before-modeling order is not clearly demonstrated by the history — I checked the spec content and there was no real modeling in it, so I am not treating this as a violation. Correct path. |
| **Raw total** | **60 / 100** | — |
| **Floor applied** | **+20** | 80% floor: a committed brief that states the problem and names a specific mix |
| **Final** | **80 / 100** | floored |

### What I'd fix first

- Delete everything below the "Ignore everything below this line" marker. That block is the case prompt, not your work, and leaving it in makes the brief roughly twice as long as it is. A reader — me, or you in Stage 3 — should not have to sort your reasoning from the source material.

- Finish the sentence about temporary labor. It currently ends at "additional labor is at the rate of". The figure is $25,000 per temp worker for 1,440 hours, which works out to $17.36 an hour against the farmer's implied $34.72.

- Bring mesclun down to 30 or below. The cap is 30 beds, so 34 is outside the feasible set. That matters more than a typo would: it means the mix was built to total 64 rather than derived from where each crop stops paying, and fixing the number is a chance to ask what each crop's stopping point actually is.

- Replace "the revenue and cost scaling relationship" with the actual rates. This is the sentence that decides your score on this stage. Tomatoes at 10% a bed compound fast — the 10th bed carries about 2.4 times the labor per bed of the first, the 20th about 6.7 times. Carrots at 2.5% and mesclun at 1.25% barely move by comparison. Say which crop you expect to stop on rising cost and which you expect to run into its cap, and why. You are already halfway there: "planting fully likely will go beyond the marginal benefit" is that idea, just unstated.

- Add a "How I would know I was wrong" section. Three bullets naming results that would count against you.

### A note on the score

Your raw total was 60 and the floor carried it to 80. I want to be clear that this is not a judgment about effort — you turned in the largest Stage 0 improvement in the cohort, and the opening paragraphs of this brief show you understand the case. The gap here is specificity: the brief names a mix but not a mechanism, and this stage grades the mechanism. It is an hour of work and the deadline has not passed.

### Looking ahead to Stage 2

Once you have revised, freeze the brief. Stage 3 compares the prediction against the model, and the comparison only means something if the prediction stopped changing before the model ran.

---

### How to work this review

Treat this PR the way an analyst treats feedback from a senior reviewer — a review is a proposal to engage with, not a checklist to rubber-stamp.

1. **Read it yourself first.** Form your own view before you change anything. Disagreeing *with a documented reason* is a legitimate, senior response.
2. **Stress-test it with an LLM.** Paste this review and your brief into your assistant and ask it to (a) explain anything you are unsure of, and (b) argue the *other side* — where might the reviewer be wrong, and what would you give up by making each change.
3. **Then write the changes yourself.** For a brief, this matters more than usual: a hypothesis you did not generate cannot be honestly compared against your model in Stage 3, and that comparison is the entire point of writing the brief first.
4. **Close the loop.** Reply in this thread with what you changed and what you pushed back on, then commit and push.

*One standing rule for this stage: do not revise your hypothesis to match what your model later tells you. If the model contradicts the brief, that is a finding, not an error — Stage 3 asks you to explain the gap, and a brief quietly edited to be right afterwards has nothing left to explain.*

— Adam
