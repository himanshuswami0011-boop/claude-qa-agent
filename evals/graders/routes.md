# Routing Evaluation Grader

## Scoring
- One point per case; total: 18 points.
- Pass only when the selected route exactly matches the expected route.
- Overall pass threshold: 18/18. Report the score and every failed case.

## Required checks
1. All English trigger cases continue routing to their existing skills.
2. Devanagari and Roman Hindi trigger cases route to the intended skill.
3. The two unrelated requests do not activate one of the three tested skills solely due to keyword overlap.
4. Evaluate the user's intent, not just a matching word.
5. Record the actual route for each case; do not infer success from the final answer text.

## Limitations
These cases are a manual evaluation specification, not an automated router.
Run them in the target Claude Code/plugin environment to verify real routing.
