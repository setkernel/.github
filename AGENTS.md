# AGENTS.md

What anyone, person or coding agent, needs to know to work in **this** repository.
`CLAUDE.md` only points here. Org-wide rules (tracking work on the board, when to stop and ask,
secrets, branches and commits, the end-of-run report) come from setkernel's central agent setup
(https://github.com/setkernel/hq/blob/main/docs/repo-standard.md); don't repeat them here.

## What this repo is
SetKernel's organization-wide GitHub files: the public profile shown at
https://github.com/setkernel (`profile/README.md`) and the default community health files
(`SECURITY.md`, `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SUPPORT.md`) that GitHub applies to
every public repository without its own.

## Commands
None: Markdown only, no build, no tests, no CI.

## Deploy
No deploy. A merge to `main` changes the public profile and the defaults immediately.

## Layout
- `profile/README.md`: the public organization profile.
- `SECURITY.md`, `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SUPPORT.md`: inherited defaults.
- `.github/CODEOWNERS`: Raghav reviews every change.

## Traps and don't-touch
- Anything added at the root or under `.github/` here can become an org-wide default for other
  repositories (for example `.github/ISSUE_TEMPLATE/`, `FUNDING.yml`, `pull_request_template.md`).
  That is why this repo has no agent issue template. Add one only as a deliberate org-wide choice.
- `profile/README.md` is public marketing copy that must match https://setkernel.com.
