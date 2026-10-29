# tinyshop

A tiny shop library used as the demo repository for [GreenLight](https://github.com/vishesh21105/greenlight).

When the `CI` workflow fails, the `GreenLight` workflow runs: it reproduces the failure in a Docker sandbox,
asks an AI agent to find the cause, verifies the fix with the full test suite, and opens a draft pull request.

To try it: rename `compute_total` to `calc_total` in `tinyshop/pricing.py` and `tests/test_pricing.py`
(but not in `tinyshop/checkout.py`), push to a new branch, and watch the Actions tab.
