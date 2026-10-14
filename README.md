# Kim Asplund

Founder and technologist in Vaasa, Finland. What I publish here falls into three groups: tooling for AI coding agents, Linux and hardware utilities, and libraries that talk to devices directly instead of through a vendor SDK.

[asplund.kim](https://asplund.kim)

## AI agent tooling

- **[thinkbetter-skills](https://github.com/kimasplund/thinkbetter-skills)**: reasoning skills for coding agents. A scored router picks the method, nine pattern skills do the reasoning, and a blind A/B harness checks that a revised skill is actually better before it ships.
- **[LLM-Context-Trace-Library](https://github.com/kimasplund/LLM-Context-Trace-Library)**: time-travel debugging for multi-agent LLM workflows. Replay a run to any point, compare runs, find where they diverged.
- **[mcp-pypi](https://github.com/kimasplund/mcp-pypi)**: MCP server that lets AI assistants search PyPI and check packages and whole projects for known vulnerabilities. Available on [PyPI](https://pypi.org/project/mcp-pypi/).

## Linux and hardware

- **[gnome-oled-shield](https://github.com/kimasplund/gnome-oled-shield)**: GNOME extension that protects OLED screens from burn-in with pixel shift, pixel refresh and dimming of static elements.
- **[Linux-Samsung-Nvme-Firmware-Iso-Extractor](https://github.com/kimasplund/Linux-Samsung-Nvme-Firmware-Iso-Extractor)**: update Samsung NVMe SSD firmware from Linux without making a bootable USB stick.
- **[Ubuntu_Intel_RST_Install](https://github.com/kimasplund/Ubuntu_Intel_RST_Install)**: install Ubuntu onto an Intel RST RAID array next to Windows, which the stock installer won't do.
- **[esp32_universal_extractor](https://github.com/kimasplund/esp32_universal_extractor)**: pull firmware off an ESP32 or a dump, split out the partitions and build ELF files for analysis.
- **[rust-p2p-usb](https://github.com/kimasplund/rust-p2p-usb)**: use a USB device plugged into another machine anywhere on the internet, peer to peer over Iroh. Alpha.

## Libraries

- **[kimsfinance](https://github.com/kimasplund/kimsfinance)**: high-performance financial charting for Python, with optional GPU acceleration.
- **[nokka](https://github.com/kimasplund/nokka)**: Datamax label printing for Python over USB, network or serial. Speaks DPL directly.
- **[kyyhky](https://github.com/kimasplund/kyyhky)**: address, barcode and QR labels for Brother QL printers over plain TCP.

Mostly Python and Rust, with some TypeScript and shell.
