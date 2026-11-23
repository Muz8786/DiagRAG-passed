# What's in this repo

This is the clean copy of my DiagRAG project. Only the experiments that passed
their own gates are in here. The full working repo, with everything including
the failed runs, is at github.com/Muz8786/DiagRAG — nothing there was changed
or deleted, this is just a copy.

Kept:
- every run whose own verdict file says it passed (ADOPTED, S_PASS / V_PASS,
  port passed, framework claim true)
- all the code, notebooks and protocols
- the docs, kept whole
- the v20 attribution study (it has no pass/fail gate, it's an analysis)

Not in here:
- runs that failed their gates: v4 GPU seed 48, v5 CPU seed 49, v8 seed 52,
  the first SciFact port (11/20), the first v15 mutant confirmation
  (INSUFFICIENT, too few harmful mutants), the v14 FiQA guarantee port,
  the first LangChain run (7/15)
- dev runs, trial runs and the voided v15 attempt — those were plumbing,
  not results

Files that are too big for git were never in the original repo either;
where a run has them, its HELD_FILES.md says what is held and its hash.
