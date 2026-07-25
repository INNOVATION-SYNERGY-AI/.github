# Contributing

Thanks for your interest in contributing. This is the organization-wide default for INNOVATION SYNERGY AI repositories. A repository that ships its own `CONTRIBUTING.md` overrides this file.

## Before you open a pull request

1. Open an issue first for anything larger than a typo or an obvious bug fix. It saves you from building something we are already changing.
2. Keep pull requests focused. One concern per pull request reviews faster and reverts cleanly.
3. Describe the behavior before and after, and how you verified it. Screenshots or a screen recording help for anything with a UI.

## Apple platform code

- Swift and SwiftUI are the defaults. Reach for UIKit only where it clearly earns its place, and say why in the pull request.
- Match the existing formatting in the file you are editing rather than reformatting surrounding code.
- Target the minimum deployment version already declared in the project. Do not raise it as a side effect of an unrelated change.
- Avoid adding third-party dependencies. If one is unavoidable, explain what it replaces and why the platform SDK is not enough.
- Never commit signing certificates, provisioning profiles, API keys, or `.env` files.

## Commits

- Write commit messages in the imperative mood, for example "Fix quote submission on slow networks".
- Rebase rather than merge when updating a branch, so history stays readable.

## Review

- Every pull request needs a review before merge.
- Expect questions about edge cases, offline behavior, and accessibility. These are not nitpicks; they are what separates a shipped app from a demo.
- Force-pushing after a review dismisses it, so re-request review when you do.

## Security and confidential information

Do not report security vulnerabilities in a public issue. See `SECURITY.md` for how to report them privately. Client names, customer data, and anything covered by an NDA do not belong in public issues, pull requests, or commit messages.
