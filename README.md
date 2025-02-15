<p align="center">
  <img src="https://user-images.githubusercontent.com/7659/174594540-5e29e523-396a-465b-9a6e-6cab5b15a568.svg#gh-light-mode-only" alt="Dependabot" width="336">
  <img src="https://user-images.githubusercontent.com/7659/174594559-0b3ddaa7-e75b-4f10-9dee-b51431a9fd4c.svg#gh-dark-mode-only" alt="Dependabot" width="336">
</p>

# Updater Action

**Name:** `github/dependabot-action`

Runs Dependabot workloads via GitHub Actions.

## Usage Instructions

This action is used by the Dependabot [version][docs-version-updates] and [security][docs-security-updates] features in GitHub.com. It does not support being used in workflow files directly.

## Manually upgrading `dependabot-action` on GitHub Enterprise Server (GHES)

To manually upgrade `dependabot-action` on your [GitHub Enterprise Server (GHES)](https://github.com/enterprise), follow [these instructions](https://docs.github.com/en/enterprise-server/admin/managing-github-actions-for-your-enterprise/managing-access-to-actions-from-githubcom/manually-syncing-actions-from-githubcom).
**Warning:** The current release of `dependabot-action` only guarantees backwards compatibility with the [currently supported GHES versions](https://docs.github.com/en/enterprise-server/admin/all-releases). Once a GHES version is deprecated, future versions of `dependabot-action` may introduce incompatible changes.

## Issues

If you have any problems with Dependabot, please [open an issue][code-dependabot-core-new-issue] on [dependabot/dependabot-core][code-dependabot-core] or contact GitHub Support.

[code-dependabot-core]: https://github.com/dependabot/dependabot-core/
[code-dependabot-core-new-issue]: https://github.com/dependabot/dependabot-core/issues/new
[docs-version-updates]: https://docs.github.com/en/code-security/supply-chain-security/keeping-your-dependencies-updated-automatically/about-dependabot-version-updates
[docs-security-updates]: https://docs.github.com/en/code-security/supply-chain-security/managing-vulnerabilities-in-your-projects-dependencies/about-dependabot-security-updates
