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

## Open source (Apache-2.0)

| Project | What it does |
| --- | --- |
| [**preflight**](https://github.com/jetonecloud/preflight) | Read-only AWS audit you run on your own machine. Credentials never leave your laptop. |
| [**crosswind**](https://github.com/jetonecloud/crosswind) | Read-only Terraform drift checker: what changed, who changed it, why it matters. |
| [**bastion-free-ami**](https://github.com/jetonecloud/bastion-free-ami) | Private AWS access with no public bastion, inbound ports, or SSH keys. |
| [**hardened-al2023**](https://github.com/jetonecloud/hardened-al2023) | CIS-aligned Amazon Linux 2023 AMI, tested and scanned on every release. |
| [**github-runner-ami**](https://github.com/jetonecloud/github-runner-ami) | Ephemeral, hardened AMI for self-hosted GitHub Actions runners. |

Try Preflight in under a minute (no AWS account needed for the demo):

```sh
curl -fsSL https://jetonecloud.com/preflight | sh
preflight demo
```

## Talk to an engineer

[Book a 20-minute technical review](https://jetonecloud.com/book) or email [contact@jetonecloud.com](mailto:contact@jetonecloud.com).

Contributions are welcome; report vulnerabilities privately via each repo's `SECURITY.md`.
