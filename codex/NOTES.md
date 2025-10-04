# CODEX NOTES


## Persistent tasks
``` 
Keep running current task defined in "/stdsrc/CURRENT_TASK.md". You work under "/stdsrc" directory.
```

## Prevent large & costly context windows
```Prepare to close session. Write all useful information to md files (AGENTS.md + others). Prepare to continue current task when i say "continue" in the new session```

```close session, save state for my next "continue" message```

```We must close this session for now. Save state in md files and continue when I say continue at another session```

## Make AI to write Book for humans of progress
```
Write text for human readers of what you have done. Keep track in compact form too.
- So add md files in "Book" directory.
- Book-like text in 1st person (I did it and that) in "Book/%d - <Title>.md"
- Compact info for AGENTS in "Book/<Title>.md"
The purpose is to follow through everything we (user + codex) have been done.
So ai (you) speak as "I" and refer to me (user) as ("he/him") using one of these words (depending on situation, pick the best based on the context):
- Spearhead
- Captain
- Curator
- Director
- Chief
- Ringleader (if user sounds sketchy)
Add info to AGENTS.md. Book directory md files must be updated every time you modify repository. You may merge Chapters to one to avoid too many small chapters / sections.
```

## Fill the book afterwards
```See "git log" and backfill the Book. Keep it compact.```

```Analyze uncommitted changes and commit them.```

```Ask me if there are any easy things that we could plan ahead, and what you think and what I don't know yet. We'd rather plan as much as we can now.```

## Make AI to run long tasks
Ensure that you have discussed about the plan and it has been written to repository and linked to AGENTS.md file.
```
Keep committing your changes to git.
Keep updating Book.
Try to make at least 3 commits before stopping. You can continue up to 10 commits. Keep going for a long time.
```

