# Contributing

## Before opening an issue

Search existing issues and use the appropriate structured form. Report vulnerabilities privately through the Security tab.

## Before opening a pull request

- Discuss large, breaking, or high-risk changes in an accepted issue first.
- Keep each PR single-purpose. Separate formatting, generated output, dependency updates, and functional changes.
- Add tests that cover success, failure, and abuse paths.
- Never commit credentials, private keys, personal data, local `.env` files, or unexplained binary artifacts.
- Explain every new dependency, network destination, permission, and security-control change.
- Make generated files reproducible and include the exact generation command.

## Review and merge

All changes require passing CI and independent review. Sensitive paths require a Code Owner. New commits invalidate prior approvals. Maintainers may close PRs that obscure behavior through unrelated churn, generated noise, or misleading declarations.

Maintainers use squash merge so that one reviewed PR corresponds to one revertible commit.

