### Greg Block

Systems engineer. Nearly twenty years at Google, the last decade in the plumbing under **Cloud Run, App Engine and Cloud Functions**: running other people's untrusted code safely, quickly, and at a density that makes security people nervous.

**What I spend my time on**

- **Multi-tenant isolation.** I led the move of Google's serverless fleet onto [gVisor](https://gvisor.dev) guest-kernel sandboxes. I've also been on the team that responds when a CPU vulnerability (Spectre, Meltdown, MDS and their descendants) lands on a fleet running strangers' binaries.
- **Control planes.** I drove a multi-year rebuild of the serverless control plane onto Spanner. Those are the boring migrations that make later work possible.
- **Cold starts.** I worked on container image streaming and filesystem work (EROFS) so that a sandbox doesn't cost you latency.
- **Shipping safely.** I built experiment-gated rollouts, where every change ramps behind a flag and is measured before it's trusted.
- **Abuse.** I built telemetry-driven detection that shuts down crypto-mining abuse in minutes, not hours.

I've gone back and forth between managing large engineering groups (including App Engine's language runtimes) and hands-on technical leadership. Before Cloud I worked in ads in London and Mountain View: AdSense, AdWords and the DoubleClick Ad Exchange.

**What I'm building here**

[**Special Circumstances**](https://github.com/ctoforaday/special-circumstances) is an *adversarial* methodology suite for AI coding agents, a set of Claude Code plugins built on the idea that an assistant should argue back when you're wrong.

- `prosthetic-conscience`: always-on discipline rules and guardrails.
- `frank-exchange-of-views`: a research engine where a red team tries to break a blue team's report before a judge accepts it.
- `gray-area`: trajectory tools that answer "what did the agents *actually* do?"

**Opinions, loosely held**

- A good argument is a courtesy, not an attack.
- A check you didn't run isn't a pass.
- When a format changes, migrate the data instead of keeping a compatibility shim.

Go, mostly. Also Java, C++, Rust, Python and SQL when they're the right tool.
