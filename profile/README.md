# [ViriyaDB](https://viriyadb.com/)

> Internal engineering organization — members only.
> Please keep repo contents and links confidential.

---

## About

Brief description of what this org is for, what it owns, and who it
serves. One or two sentences.

**Org owner:** [Khulung Bursa](https://github.com/viriyakhulung) · **Admins:** [Muhamad Lutfi Azizan](https://github.com/mlutfiazizan13)

---

## Repositories

| Repo | Description |
|------|-------------|
| `[repo-name]` | What it does |
| `[repo-name]` | What it does |
| `docs` | Internal documentation |

---

## Getting Started

1. Request org + repo access from an admin.
2. Set up your dev environment: [tools / versions].
3. Clone the repo you're working on and follow its own README.
4. Read the docs before your first contribution.

---

## Conventions

### Branching

	Format: `type/short-description` (e.g. `feat/payment-retry`)

| Prefix | Purpose |
|--------|---------|
| `feat/` | New feature branch |
| `fix/` | Bug fix branch |
| `hotfix/` | Urgent production fix |
| `refactor/` | Refactoring without behavior change |
| `docs/` | Documentation changes |
| `test/` | Test additions or fixes |
| `chore/` | Tooling, deps, maintenance |
| `release/` | Release preparation |

**Rules:** branch off `main` · keep branches short-lived · delete after merge · use lowercase with hyphens.

### Commit Format

Format: `type(scope): description` — imperative mood, lowercase, no trailing period.

| Element | Description |
|---------|-------------|
| `type` | One of the commit types below (required) |
| `scope` | Area affected, e.g. `auth`, `api` (optional) |
| `description` | Short summary in imperative mood (required) |
| `body` | What & why, separated by a blank line (optional) |
| `footer` | `Closes #123`, `BREAKING CHANGE:` (optional) |

### Commit Types
| Type | Description |
|------|-------------|
| `feat:` | A new feature |
| `fix:` | A bug fix |
| `docs:` | Documentation only |
| `style:` | Formatting, no code change (whitespace, semicolons) |
| `refactor:` | Code change that isn't a fix or feature |
| `perf:` | Performance improvement |
| `test:` | Adding or fixing tests |
| `build:` | Build system or dependencies |
| `ci:` | CI config |
| `chore:` | Maintenance, tooling |
| `revert:` | Reverts a previous commit |

### Versioning

We follow [Semantic Versioning](https://semver.org): `MAJOR.MINOR.PATCH`

| Segment | When to bump | Triggered by |
|---------|-------------|--------------|
| `MAJOR` | Breaking / incompatible changes | `feat!:` or `BREAKING CHANGE:` |
| `MINOR` | New backward-compatible feature | `feat:` |
| `PATCH` | Backward-compatible bug fix | `fix:`, `perf:` |

**Rules:** tag releases as `vMAJOR.MINOR.PATCH` (e.g. `v1.4.2`) · maintain a `CHANGELOG.md` · pre-release tags use `-alpha.1`, `-beta.1`, `-rc.1`.

### Code Style

Style is enforced automatically — run the formatter/linter before committing.

| Aspect | Standard |
|--------|----------|
| Formatting | Auto-formatter (no manual formatting) |
| Linting | Linter must pass with no errors |
| Naming | Consistent with existing code in the repo |
| Imports | Ordered and grouped; no unused imports |
| Comments | Explain *why*, not *what*; keep them current |
| Pre-commit | Hooks run format + lint before commit |
| CI | Style checks block merge on failure |

**Rules:** match each repo's existing conventions · don't mix formatting-only changes into feature commits (use `style:`) · fix all linter warnings before opening a PR.

---

## Documentation

- Architecture & design
- Runbooks
- Wiki / internal docs

---
