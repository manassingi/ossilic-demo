# Ossilic demo: a robot team's repository

This is what a team using [Ossilic](https://github.com/manassingi/ossilic) looks like. It holds one robot (`robots/rover`), its test suite (`robots/rover/suites/navigate.json`: 200 paired worlds, success as the primary metric, a 10-point margin) and its accepted baseline (`robots/rover/evidence/navigate.json`).

Every pull request runs the [Ossilic Release Check](.github/workflows/ossilic.yml) and gets a comment with the decision.

The two open pull requests show both outcomes:
- **A slower brain** reaches the goal less often, so it is **blocked**.
- **A brain tuned by Ossilic Adapt** succeeds in 199 of 200 worlds, so it is **safe to ship**.

Both are demonstrations and are never merged.
