# Private workspace

This directory is a standalone private Git repository. It is deliberately
ignored by the parent `SecondFaith` repository rather than registered as a Git
submodule, so publishing the parent does not reveal this repository's URL or
commit history.

Expected local folders:

```text
audio/         Downloaded audio tracks (local cache; ignored here too)
transcripts/   Raw transcripts
drafts/        Extraction drafts and the topic-proposal report
notes/         Private research notes
```

Generated text and private research data are versioned here. Credentials,
browser cookies, downloaded audio, partial downloads, and machine-local files
are excluded by this repository's `.gitignore`.

To restore the workspace beside a fresh checkout of the public project:

```powershell
git clone https://github.com/osafafi/hntbm-raw-data.git workspace
```

Keep the `workspace/` rule in the parent repository's `.gitignore` when the
main repository becomes public. Anything promoted to the public knowledge base
still belongs under `data/kb/`; see `docs/knowledge-base.md`.

Agent sessions started in this repository must follow `AGENTS.md` (Codex) or
`CLAUDE.md` (Claude). Both route back to the public project's authoritative
rules and require a validated commit after each completed step that produced
repository edits.
