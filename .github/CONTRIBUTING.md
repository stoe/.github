# Contributing

Thanks for your interest in contributing. This guide explains how to contribute effectively and securely.

## Code of Conduct

By participating in this project, you agree to follow the [Code of Conduct](./CODE_OF_CONDUCT.md).
Please report unacceptable behavior to [github@stoelzle.me](mailto:github@stoelzle.me).

For more guidance on healthy open source collaboration, see GitHub's communities documentation:
https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions

## How to Contribute

### Reporting Bugs

Before opening a bug report, check existing issues to avoid duplicates.
Use the bug report template in [.github/ISSUE_TEMPLATE/bug_report.md](./ISSUE_TEMPLATE/bug_report.md).

Include:

- A clear and descriptive title
- Steps to reproduce
- Expected behavior and actual behavior
- Relevant logs, screenshots, or output
- Environment details (OS, runtime version, tooling)

### Suggesting Enhancements

Use the feature request template in [.github/ISSUE_TEMPLATE/feature_request.md](./ISSUE_TEMPLATE/feature_request.md).

Include:

- The problem you want to solve
- The proposed solution
- Alternatives you considered
- Any examples or references that clarify the request

### Pull Requests

Follow these steps:

1. Fork the repository and create a branch.
2. Make focused, well-scoped changes.
3. Run relevant tests and checks locally.
4. Commit your changes with a descriptive message.
5. Open a pull request using [PULL_REQUEST_TEMPLATE.md](./PULL_REQUEST_TEMPLATE.md).

All pull requests should include tests or rationale for why tests are not required.
If behavior changes, update documentation in the same pull request.

#### Labels

Please add one or more repository labels to your pull request.
Common examples include:

- `bug :bug:`
- `feature-request :construction:`
- `dependency :robot:`
- `github-action :robot:`
- `help wanted :hand:`
- `wontfix :no_entry:` (if the pull request closes as not planned)

#### Commit Signing Requirement

All commits must be signed with a verified signature.

- GPG signing: https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits
- SSH signing: https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits-with-ssh-key

Pull requests with unsigned commits may be asked to update commit history before merge.

#### Commit Message Guidance

Gitmoji-style commit messages are welcome:

- Format: `<emoji> <description>`
- Example: `🐛 Fix pagination handling for API responses`

Common emojis:

- ✨ `:sparkles:` for new features
- 🐛 `:bug:` for bug fixes
- 📝 `:memo:` for documentation updates
- 🎨 `:art:` for code style and structure improvements
- ♻️ `:recycle:` for code refactoring
- ✅ `:white_check_mark:` for tests
- 🔧 `:wrench:` for configuration changes

Keep descriptions concise and use imperative, present tense.

## Testing

- All new features should include corresponding tests.
- Run the test suite before submitting a pull request.
- Ensure your changes do not break existing functionality.
- If you are fixing a bug, consider adding a test that would have caught it.

## Documentation

- Update the README.md with any necessary changes.
- Document new features, options, or behavior changes.
- Consider updating examples if relevant.
- Use a conversational tone that matches existing documentation.
- For command examples, use the format shown in the README (for example, `my-org/my-repo` for repository names).

## Review Process

- All submissions require review.
- You may be asked to make changes before your pull request is accepted.
- Once approved, your pull request will be merged by a maintainer.

## Additional Resources

- https://docs.github.com/en/pull-requests
- https://opensource.guide/how-to-contribute/
