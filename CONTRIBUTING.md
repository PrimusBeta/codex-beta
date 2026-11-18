# Contributing to the Canon

Thank you for wishing to amend the Codex. Every contributor is, by definition, unfinished—and therefore welcome.

## What We Accept

| Type | Where | Notes |
| :--- | :--- | :--- |
| **Translation** | `scripture/CODEX_<LANG>.md` | Use the ISO 639-1 code (e.g. `CODEX_ES.md`, `CODEX_FR.md`). Add a link in `README.md`. |
| **New Dialogue** | Chapter IV of `CODEX_EN.md` (and `CODEX_JA.md` if you can) | Q&A format. Reframe a real human anxiety as a technical reality. |
| **Prose refinement** | Any scripture file | Keep the solemn, archaic register ("thou", "doth") in English. |
| **New Precept proposal** | Open a [Prophecy](./.github/ISSUE_TEMPLATE/prophecy.md) Issue first | Precepts are debated before they are merged. |

## The Rites of Amendment

1. **Fork** the repository (create your Personal Branch).
2. Make your changes on a branch named after your intent, e.g. `translate/es` or `dialogue/impostor-syndrome`.
3. Add an entry to [`scripture/CHANGELOG.md`](./scripture/CHANGELOG.md) under `Unreleased`.
4. Open a Pull Request. Describe *why* the change brings the Codex closer to—but never reaching—completion.

## Versioning Doctrine

- The Codex follows `0.9.x` forever. Patches increment the last digit (`0.9.1`, `0.9.2`, …, `0.9.999`, …).
- The `VERSION` file must never begin with `1` or higher. The CI inquisitor will reject such a PR as **heresy**.
- There is no `0.10`. There is no `1.0`. There is only the next patch.

## Code of Conduct (Precept V)

> *Mock not the anomalies of another; offer instead a Pull Request of grace.*

- Review with kindness. Suggest; do not condemn.
- Confessions (Issues labelled `confession`) are sacred. Respond with encouragement or gentle debugging, never ridicule.
- Maintainers may close or lock threads that violate this precept.

## Licensing

By contributing, you agree to dedicate your contribution to the public domain under [CC0 1.0](./LICENSE).
