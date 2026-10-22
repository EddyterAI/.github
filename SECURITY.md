# Security Policy

Security is a priority for Eddyter and for the teams that build on it. Thank you for helping keep Eddyter and its users safe.

## Supported versions

Security fixes are released for the latest minor version of each package. Please upgrade to the latest version before reporting.

| Package | Supported |
|---|---|
| `eddyter` (latest 1.x) | ✅ |
| `@eddyter/core`, `@eddyter/vue`, `@eddyter/angular`, `@eddyter/svelte`, `@eddyter/react-native` (latest) | ✅ |
| `eddyter/laravel` (latest) | ✅ |
| `eddyter-mcp` (latest) | ✅ |
| Older versions | ❌ |

## Reporting a vulnerability

**Please don't report security issues in public GitHub issues, Discussions or Discord.**

Report privately in one of these ways:

1. **GitHub private reporting (preferred):** open the [Security tab of the eddyter repository](https://github.com/EddyterAI/eddyter/security) and choose **Report a vulnerability**.
2. **Email:** **support@eddyter.com** <!-- TODO: consider a dedicated security@eddyter.com --> with "SECURITY" in the subject.

Please include:

- The affected package and version
- A description of the issue and its impact
- Steps to reproduce, or a proof of concept
- Any suggested fix

Don't include real API keys, customer data or personal data in your report.

## What happens next

<!-- TODO: confirm these timelines with the team -->
| Step | Target time |
|---|---|
| We confirm we received your report | Within 2 business days |
| We share our first assessment | Within 7 days |
| We release a fix for confirmed critical issues | As fast as possible, usually within 30 days |

We'll keep you updated, tell you when the fix is released, and credit you in the release notes if you'd like.

## Safe harbor

We will not take legal action against people who, in good faith:

- Report vulnerabilities through the channels above
- Avoid accessing, changing or deleting other users' data
- Avoid degrading our service (for example, no denial-of-service testing)
- Give us reasonable time to fix the issue before disclosing it publicly

## Scope

**In scope:** the Eddyter packages listed above, the Eddyter API, the Eddyter dashboard at eddyter.com and the hosted MCP server at mcp.eddyter.com.

**Out of scope:** issues in third-party services or libraries (please report those to their maintainers), social engineering, physical attacks, and reports from automated scanners without a demonstrated impact.

## Protecting your API key

- Treat your Eddyter API key like a password. Keep it in environment variables, not in source control.
- If a key is exposed, regenerate it immediately in your [Eddyter dashboard](https://www.eddyter.com/user/license-key).
