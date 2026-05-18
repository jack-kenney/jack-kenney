# Jack Kenney

Hello, and welcome! My name is Jack, and I like building things. Specifically, my projects usually sit at the boundary between software and the physical world: embedded telemetry, MQTT/SCADA integrations, laboratory automation, game/graphics systems, and AI-assisted engineering tools.

I’m especially interested in turning messy real-world processes into reliable, software-defined systems. Lately, that has meant a lot of work around LIMS/lab automation, MCP-style tool interfaces, and engineering tools for regulated environments.

I also maintain a (somewhat) robust homelab built around Proxmox, ZFS, Windows/Linux VMs, home automation, monitoring, and development environments for the platforms I use at work (mainly LIMS and industrial automation tools). I use it to prototype integrations, test infrastructure patterns, and run personal observability and automation projects. You'll find several ESP32/MQTT projects linked below; these drive various apps and integrations used in my home.

I’m currently working on an AI-assisted development workflow for digital lab methods. The goal is to turn requirements into executable LIMS procedures with a tight review-and-iteration loop. Under the hood, it parses requirements, emits a structured method model, creates it in LIMS through custom API wrappers, executes it with a hand-rolled domain-specific language, and reviews the result for further iteration. The project is inspired by Kiro and is under active development.

## Selected Projects

- [Banana Bandits](https://github.com/jack-kenney/Banana-Bandits) — Nintendo 64 homebrew arena brawler in C using libdragon/tiny3d.
- [MQTT Kitchen Scale](https://github.com/jack-kenney/mqtt-kitchen-scale) — ESP32 + HX711 kitchen scale publishing calibrated weight telemetry over MQTT.
- [Home Air Quality Monitor](https://github.com/jack-kenney/home-air-quality) — ESP32-based CO₂, temperature, humidity, and particulate monitoring pipeline using MQTT, Ignition, Prometheus, and Grafana.
- [JKLS Flight Computer](https://github.com/jack-kenney/JKLS-flight-computer) — Arduino-based model rocket flight computer with BMP388 altitude tracking, apogee detection, ejection output, and SD telemetry logging.
- [Twitch RGB Matrix](https://github.com/jack-kenney/twitch-rgb-matrix) — ESP8266 NeoPixel matrix connected to Twitch API events for real-time visual display.
