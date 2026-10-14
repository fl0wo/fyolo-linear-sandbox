# fyolo-linear-sandbox

Throwaway fixtures for fyolo's Linear plugin: pull requests whose titles name
Linear tickets, in every status the plugin colors. Nothing here is real code.

- PRs into `main` need an approving review (branch rule), so they read **In Review**.
- PRs into `release` have no rule, so a green one reads **Ready to Merge**.
- CI fails on branches containing `fail` and stays running on branches containing `slow`.
