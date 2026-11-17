### Greg Block

Systems engineer. Nearly twenty years at Google, the last decade in the plumbing under **Cloud Run, App Engine and Cloud Functions**: running other people's untrusted code safely, quickly, and at a density that makes security people nervous.

**What I spend my time on**

- **Sandboxing.** I led the move of serverless isolation onto KVM, across both of Cloud Run's [execution environments](https://cloud.google.com/run/docs/about-execution-environments): [gVisor](https://gvisor.dev) in the first generation and a microVM in the second. Much of the performance, security and migration work on both is mine.
- **Security and abuse.** I'm incident commander for most of our zero-days, including the CPU ones (Spectre, Meltdown, MDS and their descendants) that land on a fleet running strangers' binaries. I handle FedRAMP compliance, built the monitoring and detection that stops abuse such as crypto-mining, and wrote the Cloud Run support for live instance monitoring in [Cloud Run Threat Detection](https://cloud.google.com/security-command-center/docs/cloud-run-threat-detection-overview).
- **Control planes.** I drove a multi-year rebuild of the serverless control plane onto Spanner. Those are the boring migrations that make later work possible.
- **Shipping safely.** I built the experiment system for all of serverless: every change ramps behind a flag and is measured before it's trusted. I added Mantel–Haenszel stratification to it, so that a change's effect is measured within each application instead of being blurred across the whole fleet.

I've gone back and forth between managing large engineering groups (including App Engine's language runtimes) and hands-on technical leadership. Before Cloud I worked in ads in London and Mountain View: AdSense, AdWords and the DoubleClick Ad Exchange.

**What I'm building here**

[**Special Circumstances**](https://github.com/ctoforaday/special-circumstances) is an *adversarial* methodology suite for AI coding agents, a set of Claude Code plugins built on the idea that an assistant should argue back when you're wrong.

- `prosthetic-conscience`: always-on discipline rules and guardrails.
- `frank-exchange-of-views`: a research engine where a red team tries to break a blue team's report before a judge accepts it.
- `gray-area`: trajectory tools that answer "what did the agents *actually* do?"

**Strong opinions, loosely held**

- A good argument is a courtesy, not an attack.
- A check you didn't run isn't a pass.
- When a format changes, migrate the data instead of keeping a compatibility shim.

Go, mostly. Also Java, C++, Rust, Python and SQL when they're the right tool.
