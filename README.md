# Jack Kenney

Hello, and welcome! My name is Jack, and I like building things. Specifically, I build systems that interface software to the physical world: embedded telemetry, MQTT/SCADA integrations, laboratory automation, game/graphics systems, and AI-assisted enterprise workflows.

I’m especially interested in turning pesky real-world workflows into reliable, software-defined systems. Lately, that has meant a lot of work around AI-assisted engineering workflows, LIMS/lab automation, MCP-style tool interfaces, and reliable software systems for regulated environments.

I also maintain a somewhat robust homelab built around Proxmox, ZFS, Windows/Linux VMs, home automation, monitoring, and dev environments for the systems I use at work, mainly SampleManager LIMS and Ignition. I use it to prototype integrations, test infrastructure patterns, and run personal observability/automation projects.

I also have a secondary replication server that I push ZFS snapshots to using sanoid/syncoid. I monitor replication status using a Python script that emits the output of `sanoid --monitor-snapshot` as MQTT. Ignition ingests that telemetry, and I have a simple dashboard where I can check status.

## Selected Projects

- [Banana Bandits](https://github.com/jack-kenney/Banana-Bandits) — Nintendo 64 homebrew arena brawler in C using libdragon/tiny3d.
- [MQTT Kitchen Scale](https://github.com/jack-kenney/mqtt-kitchen-scale) — ESP32 + HX711 kitchen scale publishing calibrated weight telemetry over MQTT.
- [Home Air Quality Monitor](https://github.com/jack-kenney/home-air-quality) — ESP32-based CO₂, temperature, humidity, and particulate monitoring pipeline using MQTT, Ignition, Prometheus, and Grafana.
- [JKLS Flight Computer](https://github.com/jack-kenney/JKLS-flight-computer) — Arduino-based model rocket flight computer with BMP388 altitude tracking, apogee detection, ejection output, and SD telemetry logging.
- [Twitch RGB Matrix](https://github.com/jack-kenney/twitch-rgb-matrix) — ESP8266 NeoPixel matrix connected to Twitch API events for real-time visual display.
