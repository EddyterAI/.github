# Contributing to Eddyter

Thank you for helping make Eddyter better. Every bug report, idea and documentation fix helps developers around the world.

This guide applies to all repositories in the [EddyterAI](https://github.com/EddyterAI) organization unless a repository has its own `CONTRIBUTING.md`.

## How the project is organized

| Repository | What it holds | What you can contribute |
|---|---|---|
| [eddyter](https://github.com/EddyterAI/eddyter) | Issues, discussions and releases for the editor SDK. The SDK itself is distributed on npm. | Bug reports, feature requests, questions, documentation feedback |
| [examples](https://github.com/EddyterAI/examples) | Runnable starter projects | New examples, fixes, framework upgrades |
| [laravel](https://github.com/EddyterAI/laravel) | Laravel Blade and Livewire integration | Code, tests and documentation |
| [eddyter-mcp](https://github.com/EddyterAI/eddyter-mcp) | MCP server for AI coding tools | Code, tests and documentation |

The core editor is proprietary, so its source code isn't in a public repository. You can still shape it through issues and discussions, and the team reads every one.

## Ways to contribute

### Ask a question

Use [GitHub Discussions → Q&A](https://github.com/EddyterAI/eddyter/discussions/categories/q-a), not issues. Answers there help everyone who searches for the same problem later.

### Report a bug

1. Search [existing issues](https://github.com/EddyterAI/eddyter/issues?q=is%3Aissue) to avoid duplicates.
2. Update to the latest version and check whether the bug still happens.
3. Open a [bug report](https://github.com/EddyterAI/eddyter/issues/new/choose) and fill in every field.

The most useful bug reports include a **minimal reproduction**: a small StackBlitz or CodeSandbox project, or a public repository, that shows the problem.

> **Never post your API key** in an issue, discussion or code sample. Replace it with `YOUR_API_KEY`. If you posted one by accident, regenerate it in your [Eddyter dashboard](https://www.eddyter.com/user/license-key).

### Suggest a feature

Open a [feature request](https://github.com/EddyterAI/eddyter/issues/new/choose) or start a thread in [Discussions → Ideas](https://github.com/EddyterAI/eddyter/discussions/categories/ideas). Explain the problem you're trying to solve, not only the solution you have in mind. Add a 👍 reaction to existing requests you'd like too; we use reactions to decide priorities.

### Report a security issue

**Don't open a public issue.** Follow our [security policy](https://github.com/EddyterAI/.github/blob/main/SECURITY.md).

### Improve documentation

Found a typo, an unclear step or an outdated example? Open an issue with the page link and what should change, or send a pull request to a public repository.

### Translate

We want Eddyter to be easy to use in every language. If you'd like to translate a README or a docs page, open a discussion first so we can avoid duplicate work.

### Share what you built

Post it in [Discussions → Show and tell](https://github.com/EddyterAI/eddyter/discussions/categories/show-and-tell). With your permission, we may feature it on our website or README.

## Pull requests (public repositories)

1. For anything bigger than a small fix, open an issue first so we can agree on the approach.
2. Fork the repository and create a branch from `main`, for example `fix/livewire-rerender`.
3. Follow the setup steps in that repository's README.
4. Keep the change focused: one fix or feature per pull request.
5. Add or update tests and documentation where it makes sense.
6. Run the repository's lint and test commands before you push.
7. Open the pull request and fill in the template.

### Commit messages

We use [Conventional Commits](https://www.conventionalcommits.org/):

```
fix(laravel): keep editor content after Livewire re-render
feat(mcp): add get_usage tool
docs: clarify Next.js setup
```

### Licensing of contributions

<!-- TODO: confirm this wording with the team or a lawyer before publishing -->
By submitting a pull request, you confirm that you wrote the contribution, or have the right to submit it, and that you agree to it being released under the license of the repository you are contributing to.

## What to expect from us

<!-- TODO: confirm these response times -->
- We aim to reply to new issues and pull requests within **3 business days**.
- We label every new issue so you can see its status.
- If we can't accept a change, we'll explain why.

## Code of conduct

Everyone taking part in Eddyter spaces must follow our [Code of Conduct](https://github.com/EddyterAI/.github/blob/main/CODE_OF_CONDUCT.md).

Thank you for contributing. 💙
