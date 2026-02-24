# Test

## Branch Protection Rules

The `main` branch is protected. Only administrators can push or merge to `main`.

### Rules applied to `main`:
- All pull requests require review and approval from a code owner (@29574196) before merging (enforced via [CODEOWNERS](.github/CODEOWNERS)).
- Direct pushes to `main` are restricted to admins only (configured in **Settings → Branches → Branch protection rules**).

> **Setup required:** To restrict direct pushes to `main`, go to **Settings → Branches**, add a branch protection rule for `main`, and enable **"Restrict who can push to matching branches"** with only admin users/teams allowed.