# The Smart Home Gazette

**He just wanted to turn on a light.**

A satirical investigative journalism piece about how IKEA bulbs, Tado thermostats, a robot vacuum, Govee lamps, and a single Aqara FP2 presence sensor triggered a chain of events that ended with merged pull requests across three open-source projects in languages the author had never written.

## Read it

- **English:** [florianhorner.github.io/smart-home-gazette](https://florianhorner.github.io/smart-home-gazette/)
- **German:** [florianhorner.github.io/smart-home-gazette/de.html](https://florianhorner.github.io/smart-home-gazette/de.html)

## What this is

This is a real story, told as a newspaper. Every detail actually happened:

- 5+ smart home ecosystems that refused to talk to each other
- An Aqara FP2 sensor that detects presence at 10 cm resolution — reduced to a binary signal by ecosystem walls
- A Home Assistant Green purchased specifically to avoid tinkering (narrator: there was tinkering)
- An apartment move that required starting fresh with 47 Zigbee devices
- A dedicated Zigbee router so ugly it now lives in a golden epoxy resin hand sculpture next to the coffee machine
- A unicode crash fix in Rust, a stalled add-on revived in Bash, and a Lovelace card built in TypeScript — all submitted as open-source contributions using [Claude Code](https://claude.ai/claude-code)

## The open-source contributions referenced

| Project | Language | What | Status |
|---------|----------|------|--------|
| [govee2mqtt](https://github.com/wez/govee2mqtt) | Rust | Unicode crash fix for Chinese preset names | Merged |
| [addon-glances](https://github.com/hassio-addons/addon-glances) | Bash/Docker | Deprecation fixes, 502 bug fix | [PR #603](https://github.com/hassio-addons/addon-glances/pull/603), [PR #604](https://github.com/hassio-addons/addon-glances/pull/604) |
| [addon-glances fork](https://github.com/florianhorner/addon-glances) | Bash/Docker | MQTT export, security hardening, Glances upgrade | Published |
| [Lightener](https://github.com/fredck/lightener) | TypeScript | Visual brightness curve editor card | In progress |

## About

Written by Florian Horner — an AWS account executive, not an engineer. Built with Claude Code as part of the Cross-Ecosystem Claude Sledgehammer Tour: a series documenting what happens when a non-engineer uses AI to contribute to real open-source projects.

## License

Content: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
