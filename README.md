# Testing Github App: dep

See https://probot.github.io/apps/dep/

Given two PRs #1 and #2 while #2 has `Depends on #1.` in its description, PR #2 should be blocked from merging until #1 is merged.
