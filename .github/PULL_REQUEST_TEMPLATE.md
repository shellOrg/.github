## Purpose

Closes <!-- issue URL or number; large/high-risk changes require an accepted issue -->

<!-- Explain the user-visible or operational outcome. -->

## Scope

<!-- List what changed, and explicitly state what did not change. Keep this PR single-purpose. -->

## Risk declaration

Check every applicable item. The PR Policy check verifies declarations against the diff.

- [ ] `SECURITY_CHANGE`: authentication, authorization, cryptography, signing, keys, secrets, privacy, or trust boundaries
- [ ] `DEPENDENCY_CHANGE`: dependency manifests, lockfiles, vendored code, downloads, or package sources
- [ ] `CI_RELEASE_CHANGE`: GitHub Actions, build, packaging, installation, deployment, or release logic
- [ ] `GENERATED_BINARY_CHANGE`: generated files, minified bundles, archives, executables, or other binary assets
- [ ] `NETWORK_TELEMETRY_CHANGE`: new destinations, RPC/API calls, analytics, telemetry, or data transmission
- [ ] `PERMISSION_DEFAULT_CHANGE`: permissions, security controls, validation, configuration defaults, or failure behavior
- [ ] `TEST_CHANGE`: tests, fixtures, snapshots, coverage configuration, or assertions were removed/weakened
- [ ] `NO_RISK_FLAGS_APPLY`: none of the declarations above apply

## Security reasoning

<!-- For each checked risk, describe the affected trust boundary, abuse case, and mitigation. Write N/A only when NO_RISK_FLAGS_APPLY is checked. -->

## Verification

<!-- Exact commands and results. Include negative/abuse-path tests for sensitive changes. -->

## Rollback

<!-- Explain how to disable or revert safely, including data/schema compatibility. -->

## Author confirmation

- [ ] The diff contains no unrelated formatting, renaming, refactoring, or generated noise.
- [ ] No credentials, private keys, personal data, or unreviewed binary artifacts are included.
- [ ] New dependencies and third-party services are necessary, attributable, and documented.
- [ ] Failure paths remain fail-closed; tests do not merely exercise the happy path.
- [ ] I reviewed the rendered diff after the final push.

