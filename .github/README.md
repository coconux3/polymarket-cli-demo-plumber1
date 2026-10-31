# CI workflows

| Workflow | File | What it does |
|----------|------|--------------|
| CI | `workflows/ci.yml` | Format, lint and test on every push to `main` and every pull request |
| Release | `workflows/release.yml` | Builds the binaries and publishes the release |
| Plumber | `workflows/plumber.yml` | Checks the CI/CD security posture of these workflows |
