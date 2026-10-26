# Instructions for AI agents in this repository

## Project
Mini-PRD for a copy-request app for the medical records unit of Klinik Harapan (fictional).
Before every task, read `docs/interview_notes.md`, `docs/client_message_CR.md`,
`docs/PRD.md` and `docs/data_list.md`.

## The golden rule
Every rule in the PRD must come from the client (`docs/interview_notes.md` or
`docs/client_message_CR.md`). If a rule is not there, do NOT add it. Either write it
as an open question in part 6 of `docs/PRD.md`, or, only if the team asks you to,
add it with the label "(our assumption)".

## Rules
- Use FICTIONAL data only. Never add real names, NIK or medical record numbers.
- Never commit passwords, API keys or tokens.
- Never commit to `main`. Always create a branch named `issue-<number>-<short-name>`.
- One issue = one branch = one pull request. Change only what the issue asks.
- Commit messages start with the issue number and say WHY,
  e.g. `#5 Replace "fast" with the 3-working-day rule (Ibu Ratna, decision 2)`.
- Keep the folder structure. Do not rename, move or merge files or folders.
- Do not use force push. Do not delete branches or files you did not create.
- First show the team your plan and wait for their OK.

## Pull request description must contain
1. What changed and why (link the issue with "Closes #<number>").
2. How to check it.
3. What the AI did, and what it was unsure about.
