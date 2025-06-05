# How to Restart Conversations with Claude

## Session Startup Protocol

### 1. Paste Current Context
Copy and paste these 3 things to start any conversation:

**Current Status** (from CURRENT-STATUS.md):
[Paste current project status]

**Last Decision** (from DECISION-LOG.md):
[Paste most recent decision]

**Next Priority** (from next-actions.md):
[Paste immediate next step]

### 2. State Session Goal
"This session I want to: [specific task]"

### 3. Confirm Understanding
Ask: "Do you understand where we are and what we're working on?"

## Session Ending Protocol

### 1. Update Files
- [ ] Update CURRENT-STATUS.md with progress
- [ ] Add any decisions to DECISION-LOG.md
- [ ] Set next priority in next-actions.md

### 2. Git Commit
```bash
git add .
git commit -m "[session type]: [what was accomplished]"
git push