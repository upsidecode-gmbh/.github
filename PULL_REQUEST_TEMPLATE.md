## What

{1–2 sentences. What this PR does in plain language. Not a code-walkthrough — focus on the user-visible or system-visible change.}

## Why

{Why this change is needed. Reference the ticket and pull in the key constraint or context that drove the approach. If a non-obvious decision was made, name it.}

Closes ENG-123

## How to verify

{Step-by-step instructions a reviewer can follow locally. Be specific: env vars to set, routes to hit, fixtures to use, expected output. If there's no manual verification path (pure refactor, infra), say so explicitly and point to the automated tests.}

1. ...
2. ...
3. ...

## Notes for the reviewer

{Optional. Call out anything unusual: a deliberate deviation from a pattern, a follow-up that's deferred, a known limitation. Skip this section if there's nothing to flag.}

---

## Ready to merge

✋ **Go through each point yourself. Do not treat these as formalities.**

**Author**

- Tested the feature end-to-end as a user would, including edge cases and failure states
- Automated tests cover the happy path, edge cases, and failure states where applicable
- Implementation matches the ticket: acceptance criteria, scope, and out of scope
- Regression risk was considered and tested where applicable

**What did you test? List the cases briefly**

1. ...
2. ...
3. ...

**Reviewer**

- Pulled and ran the branch locally for any UI or user-facing changes
- Tested the feature yourself, independently from the author's description
- Verified behavior against the acceptance criteria, not just the code diff
- Regression risk was independently assessed
