# ModernRelay Shared Workflows

This repository holds public reusable GitHub Actions workflows for
ModernRelay repositories.

Current workflows:

- `.github/workflows/omnigraph-ci.yml`
- `.github/workflows/omnigraph-package.yml`

`ModernRelay/omnigraph` uses these workflows for public CI and packaging.
`ModernRelay/omnigraph-platform` remains private and owns Terraform, deploy
automation, and environment-specific runbooks.
