# Ambiware Labs

> Building Loqa — the local-first ambient intelligence platform that keeps your data on hardware you control.

Welcome! Ambiware Labs stewards Loqa, an open-core stack for privacy-respecting assistants that run across Macs, Minis, Pis, and anything else on your LAN. This org profile highlights the key repositories, how to try the runtime today, and where to connect with the community.

## Try Loqa in Minutes

```bash
# 1. Start NATS with JetStream enabled (example using Docker)
docker run --rm -p 4222:4222 nats:2.10-alpine -js

# 2. Clone the core runtime
 git clone https://github.com/ambiware-labs/loqa-core.git
 cd loqa-core

# 3. Build sample skills and validate manifests
 make skills

# 4. Launch the runtime with the example configuration
 go run ./cmd/loqad --config ./config/example.yaml
```

Watch the logs for telemetry, bus connections, and skill activity. From here you can publish test events to subjects like `skill.timer.start` or connect additional services. A full getting-started walkthrough (including NATS tips, demo commands, and troubleshooting) is on the way alongside the MVP release. 

## Repository Guide

| Repository | Description |
| --- | --- |
| [`loqa-core`](https://github.com/ambiware-labs/loqa-core) | Runtime, message bus integration, skills host, observability tooling, and sample skills. |
| [`loqa-meta`](https://github.com/ambiware-labs/loqa-meta) | Governance, RFCs, roadmap, and community documentation. |
| [`loqa-site`](https://github.com/ambiware-labs/loqa-site) | Marketing site and launch announcements for ambiware.ai. |
| [`loqa-skills`](https://github.com/ambiware-labs/loqa-skills) | (In progress) Community skills gallery and additional examples. |

## Community & Support

- **GitHub Discussions** – Join the conversation in [Announcements, Ideas, Q&A, Show & Tell, and Polls](https://github.com/ambiware-labs/loqa-core/discussions).
- **Security** – Report vulnerabilities to [security@ambiware.ai](mailto:security@ambiware.ai) and review our [Security Policy](https://github.com/ambiware-labs/loqa-meta/blob/main/SECURITY.md).
- **Launch Announcement** – Read the [Ambiware Labs + Loqa introduction](https://ambiware.ai/blog/2025-09-25-ambiware-labs-loqa.html) for the story behind the project.

## Roadmap & Governance

We maintain the [MVP backlog](https://github.com/ambiware-labs/loqa-meta/blob/main/roadmap/MVP_BACKLOG.md) and RFC process in `loqa-meta`. Contribution guidelines, code of conduct, and governance model live there as well.

## Stay in Touch

- Website: [ambiware.ai](https://ambiware.ai)
- Email: [hello@ambiware.ai](mailto:hello@ambiware.ai)
- GitHub: [@ambiware-labs](https://github.com/ambiware-labs)

Let’s prove ambient intelligence can be fast, thoughtful, and private.
