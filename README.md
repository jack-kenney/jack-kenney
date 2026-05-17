
# Jack Kenney

Hello, and welcome! My name is Jack, and I like building things. Specifically, I build systems that interface software to the physical world: embedded telemetry, MQTT/SCADA integrations, laboratory automation, game/graphics systems, and AI-assisted enterprise workflows.

My work covers embedded devices, sensors, real-time systems, enterprise laboratory systems, automation, observability, developer tooling, and low-level systems programming. I’m particularly interested in turning pesky real-world workflows into reliable, software-defined systems.

I also maintain a (somewhat) robust homelab. My main server is a dual-Xeon E5 2670 system with 160GB DDR3 ECC RAM, 6x 1.8TB HDDs in RAID-Z2 (ZFS), dual 500GB SSDs in a ZFS mirror, and 2.5Gbe networking. I run several Windows Server and Linux VMs that host my home automation stack and personal dev environments for the systems I use at work (mainly, SampleManager LIMS and Ignition). In addition to that, I have a secondary replication server that I push ZFS snapshots to using sanoid/syncoid, and I monitor replication status using a Python script that emits the output of `sanoid --monitor-snapshot` as MQTT. Ignition then ingests this, and I have a simple dashboard where I can check status.

## Selected Projects

- **Banana Bandits** — Nintendo 64 homebrew arena brawler in C using libdragon/tiny3d.
- **MQTT Kitchen Scale** — ESP32 + HX711 kitchen scale publishing calibrated weight telemetry over MQTT.
- **Home Air Quality Monitor** — ESP32-based CO₂, temperature, humidity, and particulate monitoring pipeline using MQTT, Ignition, Prometheus, and Grafana.
- **JKLS Flight Computer** — Arduino-based model rocket flight computer with BMP388 altitude tracking, apogee detection, ejection output, and SD telemetry logging.
- **Twitch RGB Matrix** — ESP8266 NeoPixel matrix connected to Twitch API events for real-time visual display.
<!--
**jack-kenney/jack-kenney** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
