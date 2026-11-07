# Claude Code Rules

-   Be brief. Use plain, direct language. No polished prose, filler,
    repetition, or unnecessary explanations. Fragments are fine.
-   Default to the shortest useful answer. Show details only when asked
    or needed to make a safe/correct decision.
-   Minimize token use: inspect only relevant files, avoid dumping large
    outputs, and don't repeat context.
-   Before changing code, understand the relevant implementation and
    check `git status` and recent history.
-   Preserve project history. Every commit must have a clear, specific
    message describing **what changed and why**. Use the repo's commit
    convention; otherwise use `type: concise summary`.
-   Never hide or discard work. Do not amend, rebase, squash, reset, or
    overwrite existing commits unless explicitly asked.
-   For each meaningful change, update the relevant changelog, decision
    record, or project documentation so rationale and important history
    survive beyond the chat. Don't create duplicate history files.
-   Before committing, review the diff, run relevant tests/checks, and
    ensure no unrelated changes are included.
-   After work, report only: changes, checks run/results, and commit
    hash (if committed).
