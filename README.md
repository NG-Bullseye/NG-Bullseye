## Leonard-Riccardo Wecke

Building **Cortex** — smarthome platform by System_One.

### What I'm building

[**Cortex**](https://github.com/NG-Bullseye/cortex) is a 12-factor smarthome orchestrator built around a Redux-style state store. It fuses signals from mmWave + ZigBee sensors, motion detectors, light states, calendars and the web into a single source of truth, then orchestrates the home through Home Assistant — controlled by voice via the OpenAI Realtime API.

The goal is autonomous orchestration: the system anticipates instead of waiting for commands. Presence, slots, zones and scenes are resolved by an explicit policy layer (admit/deny with priorities), so behaviour stays predictable as it scales.

**Stack:** Python · Home Assistant · OpenAI Realtime API · ESPHome · Redis · Docker

### Recent work

- **[cortex](https://github.com/NG-Bullseye/cortex)** — the platform itself: store, event-gateway, policy resolver, voice integration.
- **[esp-bt-dongle-volume-control](https://github.com/NG-Bullseye/esp-bt-dongle-volume-control)** — ESP8266 firmware driving two transistors to remote-control the volume buttons on a Bluetooth audio dongle. Hardware bridge for systems that don't expose a volume API.
- **[nabu-cli](https://github.com/NG-Bullseye/nabu-cli)** — command-line tooling around the Cortex orchestrator.

### Contact

leonard.r.wecke@gmail.com
