# Kim Asplund

AI agent engineer in Vaasa, Finland. I build agents that run real workflows in production, and the tooling that shows whether they behave: evaluations, tracing, and guardrails enforced in code rather than in prompts.

[asplund.kim](https://asplund.kim)

## In production

**Aino** runs the EU B2B sales of a product line end to end: prospecting, outreach and customer correspondence in four languages, the CRM, and orders booked into Odoo through to invoice. It's built on Hermes Agent and Claude. The guardrails live in code: a banned-claims preflight across 18 languages, a tool-call guard, approval gates before a new market goes live, and audit trails for opt-outs and customer promises. The code is private because it runs a live business.

## Evaluation and observability

- **[thinkbetter-skills](https://github.com/kimasplund/thinkbetter-skills)**: 15 reasoning skills for coding agents, shipped with skill-gauntlet, a pre-registered blind A/B harness that decides whether a revised skill is actually better. Every scorecard is published, including the revisions that failed and were reverted.
- **[LLM-Context-Trace-Library](https://github.com/kimasplund/LLM-Context-Trace-Library)**: time-travel debugging for multi-agent workflows. Record a run, replay it to any step, and diff two runs to find where they diverged. Integrations for LangChain, CrewAI, AutoGen, OpenAI Agents, PydanticAI, Semantic Kernel, DSPy and LlamaIndex.

## Tools for agents

- **[mcp-pypi](https://github.com/kimasplund/mcp-pypi)**: MCP server that lets agents search PyPI and check packages and whole dependency trees against the OSV vulnerability database before they suggest anything. Available on [PyPI](https://pypi.org/project/mcp-pypi/).
- **[nokka](https://github.com/kimasplund/nokka)** and **[kyyhky](https://github.com/kimasplund/kyyhky)**: label-printer drivers that speak the printers' own protocols (Datamax DPL, Brother QL raster), each with an agent skill so a coding agent can drive real hardware without wasting labels.

## Systems

- **[kimsfinance](https://github.com/kimasplund/kimsfinance)**: fast financial charting for Python, with optional Rust and GPU acceleration.
- **[rust-p2p-usb](https://github.com/kimasplund/rust-p2p-usb)**: use a USB device plugged into another machine anywhere on the internet, peer to peer over QUIC with Iroh. Alpha.
- **[gnome-oled-shield](https://github.com/kimasplund/gnome-oled-shield)**, **[Linux-Samsung-Nvme-Firmware-Iso-Extractor](https://github.com/kimasplund/Linux-Samsung-Nvme-Firmware-Iso-Extractor)**, **[Ubuntu_Intel_RST_Install](https://github.com/kimasplund/Ubuntu_Intel_RST_Install)**: Linux tools for OLED burn-in, Samsung SSD firmware updates and installs on Intel RST RAID.

## Background

Before moving into AI in 2020, I spent more than 20 years in technical service engineering (medical devices, IT infrastructure) and running my own businesses, plus ten years as a firefighter and ambulance medic. That's why my work centres on systems that must not fail quietly.

Python, Rust, TypeScript. Swedish (native), English, Finnish.
