<p align="center">
  <a href="https://jetonecloud.com">
    <img src="https://avatars.githubusercontent.com/u/244311199?s=200&v=4" alt="Jet1" height="64">
  </a>
</p>

<h3 align="center">Accountable infrastructure operations.</h3>

<p align="center">
  Pipelines, AWS, and on-call, run under an SLA by a senior DevOps team,<br>
  in your repos and your cloud accounts.
</p>

<p align="center">
  <a href="https://jetonecloud.com">Website</a> ·
  <a href="https://jetonecloud.com/book">Book a technical review</a>
</p>

---

## What we do

Jet1 is a managed DevOps team. We take SLA-backed ownership of the parts of a platform that usually belong to nobody in particular:

- **Deploys.** CI/CD with canary releases and automatic rollback in under 90 seconds. No maintenance windows, nobody on standby at 2am.
- **AWS.** Everything as code, least-privilege access, and a monthly cost-review pull request you approve line by line.
- **On-call.** A rota, not a single phone number, backed by a runbook for every failure mode.

Everything we build lives in your repositories and your AWS accounts. If you stop working with us, there's nothing to migrate.

## Open source

These tools come out of the work we do for clients. They're Apache-2.0, so read the code before you run it.

| Project | What it does |
| --- | --- |
| [**preflight**](https://github.com/jetonecloud/preflight) | Read-only AWS audit that runs on your own machine. It reports on deploy risk, spend, and how much of your setup depends on one or two people. Your credentials never leave your laptop. |
| [**hardened-al2023**](https://github.com/jetonecloud/hardened-al2023) | CIS Level 1-aligned Amazon Linux 2023 AMI, built with Packer and Ansible and gated by Goss compliance tests and a Trivy scan before anything is published. |
| [**github-runner-ami**](https://github.com/jetonecloud/github-runner-ami) | Ephemeral, hardened AMI for self-hosted GitHub Actions runners on AWS: one job per instance, then wipe and terminate. Builds for x86_64 and Graviton. |

Try Preflight in under a minute, no AWS account needed for the demo:

```sh
curl -fsSL https://jetonecloud.com/preflight | sh
preflight demo
```

## How we build

The same rules apply to our open-source repos and to client work:

- **Least privilege by default.** Read-only where possible, no wildcard IAM.
- **No secrets in code or images.** OIDC instead of static keys, credentials fetched at runtime.
- **Every change is a pull request**, tested and scanned before it ships.
- **Honest docs.** What we implement, what we deliberately skip, and why.

## Contributing and security

Issues and pull requests are welcome on any project; each repo has a `CONTRIBUTING.md`. Please report vulnerabilities privately as described in the repo's `SECURITY.md`, not in a public issue.

## Talk to an engineer

[Book a 20-minute technical review](https://jetonecloud.com/book). We'll look at how you deploy today and name the first three delivery risks we'd address, useful whether or not you work with us.

Or email [contact@jetonecloud.com](mailto:contact@jetonecloud.com).
