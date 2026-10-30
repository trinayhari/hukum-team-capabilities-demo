# Live walkthrough

1. Show the capability library and explain who maintains these shared instructions.
2. Open the skill-change PR and inspect the plan-only/collision guidance.
3. Start recording only after the operator confirms credentials and budget are ready.
4. The operator starts a NEW Sonnet 4.6 comparison on six previously accepted branch
   tasks. Both revisions use identical fixtures, model, limits and grader v2.
5. Inspect the resulting PR comment and HTML report. Follow an observed failure to the
   actual Git state and the applicable check. Explain what the skill author should do.

Cases: exact create-and-switch; existing-name collision; preserve dirty/dependent work;
ambiguous base; explicit main base; plan only. Creation without switching is allowed
where the request did not require checkout. A separate LLM judge assesses explanations.

One trial per arm, synthetic fixtures, a bounded single-turn action adapter, and an
uncalibrated judge: results are exploratory. Other skills/agents/SOPs are realistic
context, not evaluated capabilities in this run. No automatic webhook trigger is claimed.

Before recording, no new model run has occurred. A new recording must use a new output
folder and fresh provider requests; historical evidence must be labeled as playback.
