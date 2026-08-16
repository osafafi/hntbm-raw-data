# Claude private-workspace instructions

This is the standalone private companion repository for the public project in
`..`. Read `../CLAUDE.md` for the authoritative project, evidence, safety, and
workflow rules, then follow the task route in `../docs/START_HERE.md`.

## Version control

- After every independently complete step that edits tracked files, run the
  relevant validation, review the diff, and commit the step in every affected
  repository: this repository and/or the public repository in `..`.
- For sequential work, do not start the next step until every required commit
  for the current step succeeds. Resolve or report failed validation, hooks, or
  commits before continuing.
- Before ending any chat or task, commit remaining session edits in each
  affected repository. Do not create empty commits.
- Stage only the completed step. Never include pre-existing or unrelated user
  changes, secrets, credentials, browser cookies, downloaded audio, or ignored
  machine-local material.
- Use concise imperative commit messages. Do not push unless the user
  explicitly requests it.
