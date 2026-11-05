# 25 Top Tips — Stop Your Agents Burning Tokens

From the SI Agents film *"Your AI Agents Won't Manage Themselves — Manage Them or Pay the Price."*

Ranked by dual impact — how much compute each tip saves, and whether it also makes the agent more capable, reliable or accurate. **Tips 1–5 are the dual winners:** the biggest savers that also make a better agent.

## 1. Give the agent a memory it reads before it works

A memory file the agent reads at the start of every session ends the daily amnesia — who you are, what’s settled, what not to retry.

## 2. Have the agent write back what it learned at the end of every session

At the end of the day the agent writes in the notebook — decisions, dead ends, what failed — so the next session starts working instead of re-deriving it.

## 3. Compact the history into a tight brief at each milestone — don’t re-send the saga

When the history gets long, old turns are compressed into a short brief the agent re-reads instead — not the whole growing stack.

## 4. Fetch just-in-time; never pre-load the whole world

Don’t carry the warehouse. Walk to the filing cabinet, pull exactly the folder the step needs, read it, put it back.

## 5. If it happens twice, have the agent script it

The agent builds the script once and verifies it once — then plain code stamps out the repetitions for fractions of a cent.

## 6. Cache the stable prefix with prompt caching

The parts of the prompt that never change — the rules, the role, the project brief — sit on the cache shelf and are bought back at a steep discount, not full price on every call.

## 7. Send subagents to do messy work in their own context; only conclusions come home

A subagent runs off to do the messy research in its own room and returns carrying only a one-page summary.

## 8. Trim, page, or summarize every tool result — never swallow a phone book

Tool output arrives as a fat scroll; trim it to the lines the next decision actually uses — page it, trim it, summarize it.

## 9. Plan first, in a file that survives the session — and tick steps off as they finish, never re-doing done work

Plan first, write the plan down where it survives the session, and tick steps off once, in order.

## 10. Checkpoint state to disk as you go — a stopped run resumes where it died instead of re-deriving from zero

A run that leaves its state on disk resumes where it stopped instead of paying to start over.

## 11. Define “done” — exit criteria — before the run starts

Draw the finish line under the last box before starting: an agent that can’t tell it’s finished will keep finishing forever.

## 12. Route by difficulty: small, cheap, fast model for mechanical steps — frontier reserved for hard ones

Small errands — sorting, fetching, formatting — route to a small, quick engine; the big engine lights up alone for the one genuinely hard problem.

## 13. Match the reasoning dial to the step: low for errands, high only where it’s earned

The reasoning dial sits low for errands, high only for the hard one — not every step deserves full reasoning.

## 14. Batch independent calls into a single step — every round trip re-buys the context

Calls that don’t depend on each other go into one step — every extra round trip re-buys the whole context.

## 15. Prune stale memory — a bloated notebook costs more than it saves

Keep the notebook curated: a second notebook, overstuffed and out of date, tips the desk over.

## 16. Cap retries, back off on errors, and treat stopping as a result

The retries counter ticks down and the agent stops instead of spinning — after a few honest attempts, stopping is a result too. On a rate limit: back off, don’t spin.

## 17. Keep cached instructions unchanged — every edit empties the cache

Keep the instruction book unchanged: every edit empties the cache shelf and the next call pays full price again.

## 18. Put scheduled jobs on a timer — no agent needs to be awake

Once scripted, the job runs on schedule with no agent present at all — take the agent out of the loop entirely.

## 19. Check the token counter daily — don’t wait for the empty allowance

Most owners never look at the counter until it’s empty — check it daily, not at the autopsy.

## 20. Remember: hidden reasoning is billed too — every thought is a token

The new models think longer, and every thought is a token — thinking you never see is still thinking you pay for.

## 21. Put a hard budget cap on every task

The safeguard against the overnight runaway — an agent left looping until morning. Put numbers on the leash.

## 22. Put a step limit on every run

Paired with the budget cap: when the step count is spent, the run stops — it doesn’t keep finishing forever.

## 23. Limit how deep subagents can spawn

The hiring-spiral safeguard: a subagent that spawns subagents that spawn subagents gets a spawn depth limit.

## 24. Gate irreversible actions behind a human approval

Full autonomy with no approvals is the no-leash landmine — approval gates are the safeguard.

## 25. Test your kill switch before the night you need it

A kill switch only counts if you’ve tested it before the night you need it.

---

*Pair these with **The First Message** — the setup prompt that installs this discipline in a new agent from its first turn.*