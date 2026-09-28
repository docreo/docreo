# Doc Reo

**Mareo-Ahmir Lawson, M.Ed., M.A.**  
Author · Producer · Educator · Speaker · U.S. Cavalry Veteran · Founder of Signalproof

# SIGNALPROOF · SAGITTARIUS HORIZON

### One human-controlled AI operating interface. Many models. Clear authority.

**Sagittarius Horizon (V1)** is the current generation we're building at **[Signalproof](https://signalproof.com)**. We're developing a coordinated CLI, model-routing and agent-capability ecosystem designed to bring different AI systems together **without giving up human direction, verification, or recovery**.

> **Control first. AI second. Software third.**  
> Build signal. Cut noise. Leave proof.

**[Explore Horizon ↓](#sagittarius-horizon-four-models-today-room-for-more)** · **[Get the free Community CLI](https://github.com/docreo/docreo-Signalproof-Public1/tree/main/community-cli)** · **[Build Your Own AI CLI](https://github.com/docreo/docreo-Signalproof-Public1/tree/main/build-your-own-cli)** · **[Signalproof](https://signalproof.com)**

---

## Sagittarius Horizon: four models today, room for more

Our **full Signalproof CLI** has a **four-model local integration**, bringing the following separately routed model families into a single operator-facing environment:

| Current integrated local routes | What the CLI does |
| :--- | :--- |
| **Granite** | Explicit, governed Granite selection |
| **Qwen** | Explicit, governed Qwen selection |
| **Gemma** | Explicit, governed Gemma selection |
| **Ministral** | Explicit, governed Ministral selection |

**Four models are our current integrated starting point, not the limit.** The architecture separates the CLI from model adapters, provider connections, the route registry and the control plane. Additional local models, hosted providers and bounded AI workers can be integrated through their own qualification, permissions, readiness and acceptance processes—not by hard-coding a permanent four-model ceiling.

```text
                     HUMAN OPERATOR
                           |
                     SIGNALPROOF CLI
                           |
                  GOVERNANCE / APPROVAL
                           |
                   EXACT MODEL ROUTING
                     /   /   \    \
              GRANITE QWEN GEMMA MINISTRAL
                           |
              + MORE QUALIFIED ROUTES
                           |
                  VERIFICATION / PROOF
                           |
                  HUMAN REVIEW / RECOVERY
```

**The model is a worker behind the system—not the system's authority.** The direction for Horizon includes explicit identity, permissions, approvals, budget boundaries, model and agent routing, verification, an evidence trail and recovery.

**Engineering status:** The four-model CLI has been developed and tested on our local engineering line. The Horizon V1 generation candidate has documented isolated Windows staging acceptance; full public release and permanent Horizon promotion are separate gates. Individual route health depends on the actual runtime. **A supported architecture is not a claim that every future model or provider is installed, connected or approved today.** The current technical CLI line is **V2/RD3** and its accepted terminal visual is **V3/RD4**; those are component versions, separate from the **Horizon V1** generation name.

## Free public edition: start here

[![Approved public Signalproof Community CLI terminal preview](https://raw.githubusercontent.com/docreo/docreo-Signalproof-Public1/main/docs/assets/signalproof-cli-preview.svg)](https://github.com/docreo/docreo-Signalproof-Public1/tree/main/community-cli)

*This approved sanitized preview shows the free **Community CLI**, not the larger four-model Horizon engineering build.*

**[Download / inspect the Community CLI →](https://github.com/docreo/docreo-Signalproof-Public1/tree/main/community-cli)**

The separately released, free **Community CLI 0.2.0** currently includes **two** exact, local, advisory-only Ollama routes: `qwen3.6:latest` and `granite4.2:8b`. The larger engineering CLI already incorporates Gemma and Ministral, but those routes **have not yet been published as part of this Community Edition**.

Community CLI principles: exact model selection, no silent fallback, loopback-only transport, explicit approval before optional model downloads, and no inherited access to private Signalproof infrastructure.

```bash
git clone https://github.com/docreo/docreo-Signalproof-Public1.git
cd docreo-Signalproof-Public1/community-cli
python install.py
signalproof-community setup
signalproof-community chat granite
```

Requires Python 3.11+, local Ollama and sufficient resources for your selected model. Model weights are not bundled. See the [Community CLI documentation](https://github.com/docreo/docreo-Signalproof-Public1/blob/main/community-cli/README.md).

## Public tools, education and operating methods

| Public project | Explore |
| :--- | :--- |
| **[Signalproof Community CLI](https://github.com/docreo/docreo-Signalproof-Public1/tree/main/community-cli)** | A working public entry point to explicit, local model routing. |
| **[Build Your Own AI CLI](https://github.com/docreo/docreo-Signalproof-Public1/tree/main/build-your-own-cli)** | A practical guide, starter template and six CLI-builder skills for designing your own extensible, governed CLI. |
| **[SignalFlow Mini](https://github.com/docreo/SignalFlow-Mini)** | A free local Windows push-to-talk transcription tool with guarded text return. |
| **[Signalproof Skills + /dsp](https://github.com/docreo/Signalproof-Skills)** | Reusable public commands, skills and bounded loops for research, build, testing, verification, recovery and handoff. |

Public code is intentionally separate from private engineering systems, tenant data, infrastructure and credentials. Read the [public distribution boundary](https://github.com/docreo/docreo-Signalproof-Public1/blob/main/PUBLIC-BOUNDARY.md). Each project has its own release status, license and applicable third-party notices.

## Why we're building it

**[Signalproof](https://signalproof.com)** is a human operating standard for the age of AI: systems, methods and tools designed to increase machine capability **without silently reducing human authority**. **[AI NO Hype](https://ainohype.com)** connects practical AI education with the judgment people need before automating important work.

I build at the intersection of software, learning design, research, business strategy and media. My background also spans film and television, music, broadcasting, publishing and veteran advocacy. This GitHub profile showcases the work available for public inspection while the larger Horizon platform advances through its own engineering and release gates.

**[Signalproof](https://signalproof.com)** · **[AI NO Hype](https://ainohype.com)** · **[DocReo.com](https://docreo.com)** · **[Email](mailto:docreo@mail.signalproof.com)**

**Human authority with proof.**
