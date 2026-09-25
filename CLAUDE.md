# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Push workflow

When asked to push changes to this repository, follow this process instead of pushing directly to `master`:

1. Create a new branch for the change and push commits to it.
2. Open a PR/review for the branch.
3. **Each commit must have its own review** — do not bundle multiple unrelated commits into a single review; split them into separate reviews/PRs if needed, or ensure each commit is independently reviewed before merging.
4. Wait for CI to pass on the branch before proceeding.
5. Once the review is approved and CI is green, squash the branch into `master` (squash merge, not a regular merge).

Never push directly to `master`, and never skip the review or CI wait step even for small changes.
