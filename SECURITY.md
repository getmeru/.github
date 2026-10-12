# Security Policy

> **En español:** si encontraste una vulnerabilidad en un producto de Meru o en este código, escríbenos a **security@getmeru.com**. No abras un issue ni un pull request con el hallazgo. Respondemos en 2 días hábiles. El resto de este documento está en inglés porque la mayoría de los reportes externos llegan en ese idioma.

Meru takes the security of its platform and of the people who use it seriously. This policy applies to every repository in the `getmeru` organization and to Meru's production products.

## How to report

Email **security@getmeru.com** with:

- the product or repository affected and, when it applies, the URL or endpoint;
- steps to reproduce, with the minimum proof needed to show the issue;
- the impact you believe it has;
- any logs, screenshots or request samples that help us confirm it.

Please do **not**:

- open a public or internal issue describing the vulnerability;
- open a pull request that fixes it before we have triaged it (a pull request describes the hole before it is closed);
- share the finding on Slack channels, social media or with third parties until it is resolved.

You will get a reply from a person, not an auto-responder.

## What we ask from you

- Test only what is needed to demonstrate the issue. Stop as soon as you have proof.
- Do not access, modify or exfiltrate data that is not yours. If you reach someone else's data by accident, stop and tell us what you saw.
- No denial of service, no spam, no social engineering of Meru staff or customers, no physical attacks.
- Do not use automated scanners against production without talking to us first.
- Keep the finding confidential until we tell you it is fixed, or 90 days have passed, whichever comes first.

## What you can expect from us

| Step | Commitment |
|---|---|
| Acknowledgement | within 2 business days |
| Triage and severity | within 5 business days |
| Fix for a critical issue | within 7 days |
| Fix for a high-severity issue | within 30 days |
| Fix for a medium-severity issue | within 90 days |
| Closing notice | when the fix is in production |

We assign severity using CVSS as a guide and the real impact on customers' funds and data as the deciding factor.

## Scope

In scope:

- Meru's production applications and APIs under `getmeru.com` and its subdomains;
- the mobile applications published by Meru;
- every repository in the `getmeru` GitHub organization.

Out of scope:

- sandbox or test environments of third-party providers;
- reports that only cite a dependency version without a working exploit against Meru;
- unvalidated output from automated tools;
- issues in services we do not operate (report those to their owners).

## Rewards

Meru does not run a bug bounty program at this time. We do credit reporters who want to be credited, once the issue is fixed.

## Safe harbor

If you follow this policy in good faith, Meru will not pursue legal action against you for your research, will work with you to understand and resolve the issue, and will not share your identity without your consent.

## For the Meru team

A security finding discovered internally, including results from penetration tests and high-severity Dependabot alerts, follows the same channel: email security@getmeru.com and track it in a private ticket. Never discuss an open vulnerability in an open Slack channel or in a public issue.

_Maintained by Jesús. Last reviewed: 12 October 2026._
