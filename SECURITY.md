# Security Policy

## Reporting a vulnerability

Please report security issues privately, not in a public issue.

Use the **Report a vulnerability** button on the repository's **Security** tab
(GitHub private vulnerability reporting). If that is unavailable, contact the
organization owner directly through their GitHub profile.

Include:

- The repository and the affected file or workflow.
- What an attacker could do with it.
- Steps to reproduce, if applicable.

Please do not include live credentials in the report. Redact them.

## Scope

These repositories are experiments and are not operated as production
services. There is no uptime guarantee, no support contract, and no bounty.

In scope:

- Committed secrets or credentials.
- GitHub Actions workflows that expose tokens or allow code execution from
  untrusted input.
- Scripts that mishandle data they collect.

Out of scope:

- Vulnerabilities in third-party platforms and services the experiments use.
- Findings that require access we did not grant you.

## Secrets

If you find a credential in this organization, report it immediately. Assume it
is live: the owner will rotate it first and investigate second.

## Supported versions

Only the default branch. There are no maintained release branches.
