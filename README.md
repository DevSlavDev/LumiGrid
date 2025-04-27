# ✨ LumiGrid ✨

---

## 💡 Project Goal

Welcome to LumiGrid! 👋 This project is an exciting ecosystem of interconnected hardware nodes built on the powerful ESP32 and Raspberry Pi platforms. Our mission? To bring flexible and dynamic control to addressable/LED lighting, vibrant digital signage (HUB75 panels), and standard HDMI displays. Think of it as the foundation for creating awesome, responsive smart environments! ✨

Developed with passion by **DevSlavDev** 👨‍💻 in collaboration with **Cube & Reclame Fabriek** 🏢.

---

## 🚀 Core Concepts

LumiGrid is designed around a few key ideas:

* **Nodes:** 🧠 The individual brains of the operation, each performing a specific task (like controlling LEDs or showing content).
* **Control Modes:** 🚦 Each node can operate in different modes:
    * External: 📡 Taking commands from outside (Art-Net, MQTT).
    * Sync: ⏱️ Working together in perfect harmony (Master/Slave) for synchronized playback.
    * Independent: 🚶 Running its own show autonomously.
* **Sequences & Presets:** 🎬 Create captivating timelines of predefined actions and effects for your nodes!
    * Calendar-Based Playback: 🗓️ Schedule your sequences to run automatically at specific times (enabled by onboard RTCs on most nodes!).
    * Trigger-Based Playback: 💥 React to external events, like sensor data!

---

## 🧠 Node Types (So Far!)

Here's a peek at the different types of nodes we're building:

* **LED Controller Node:** ✨🌈
    * Control addressable LEDs (WS2812B, SK6812, etc.) on **2 independent channels**!
    * Drive standard LEDs or spotlights with **5 PWM channels** (R/G/B/W/WW)! 💡
    * Each channel is a separate track in the sequencer for independent control! 💪
    * Also capable of handling basic addressable display functions! 🔢
* **Display Node:** 🖼️📺
    * Power vibrant HUB75 LED matrix panels (up to 3 parallel chains)!
    * Act as a Digital Signage player for HDMI screens (images, videos, apps)! 📊
    * Show dynamic content like Time, Date, Sensor Data, Text, Images, Videos, Crypto/Finance Tickers, Weather, and more! 📰💲☁️
* **Sensor Node:** 📊👂
    * Collect environmental data (temperature, humidity, pressure, gas, light, motion). 🌡️💧 압 🌱
    * Push data to other nodes to trigger actions! ➡️ nodes
    * Initial sensors: BME680, BH1750, Microwave Radar Motion.
    * Can also output data via UART! 🔌
* **AC Relay/Dimmer Node:** 🔌💡
    * Control standard AC devices (on/off and dimming)!
    * Great for integrating traditional lighting or appliances. 🏠
* **Remote Node:** 🎛️👆
    * Control other LumiGrid devices via a touchscreen and rotary encoders!
* **Audio Node:** 🔊🎶
    * Synchronized audio playback or generation!
    * Adds an auditory layer to your light and display shows!
* **Advanced Sensor Node Types:** 🌱🔬
    * Planned nodes for specialized sensing like Air Quality, Sound Level, etc.

---

## 🚧 Work In Progress (WIP)! 🚧

LumiGrid is currently under active development. 🌱 We are building this system step-by-step, focusing initially on getting the Raspberry Pi Display Node and core sync mechanisms solid! 💪

### Development Roadmap:

1.  **Phase 1: Display Node & Raspberry Pi Sync:** Getting our Pi-based display nodes talking and syncing perfectly! ✨
2.  **Phase 2: ESP32 Nodes:** Bringing our ESP32 friends online, starting with the Sensor Node and then the rest! 🤖
3.  **Adding Features:** Integrating advanced functionality like channel grouping, preset linking, and conditional logic! 🔗🧠

We'll be updating the documentation and code as we progress!

---

## 🤝 Contributions

Currently, contributions are not being actively accepted. We are focusing on building the core system structure and getting the main code base stable.

**HOWEVER!** We are building this with future collaboration in mind! 🎉 Once the main code is complete and stable, we plan to open up contributions. Keep an eye on this space for updates! 👀

---

## 🔗 Stay Tuned!

Follow the repository for updates on our progress! We're excited to see what we can build together! 😊

---

Made with ❤️ by DevSlavDev for Cube & Reclame Fabriek
