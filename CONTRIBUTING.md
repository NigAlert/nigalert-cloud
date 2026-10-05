# Contributing to NigAlert

## Branches
- `main` is always demo-ready.
- `develop` is the integration branch and default.
- Branch from `develop` using `feature/...`, `fix/...`, `docs/...`, or `infra/...`.
- Every change requires a pull request with at least one review.

## Owner Safeguards
- Repositories are archived, never deleted.
- Repository deletion, member removal, visibility changes, or org setting edits require written agreement from at least one other owner before it is done.
- Owners do not push directly to `main` or `develop`.

## Secrets
- Never commit `.env` files, keys, tokens, or Terraform state.
- Use `.env.example` with dummy values only.
- All demo data must be synthetic.
