<p align="center">
  <a href="https://www.sprinqua.com/?ref=github-org"><img src="https://www.sprinqua.com/site_img/og-image.png" width="720" alt="Sprinqua — Smart Irrigation Controller for Raspberry Pi. Open source, no cloud, Home Assistant ready. Powered by Orbit OS."></a>
</p>

<h3 align="center">Smart irrigation for Raspberry Pi — an app built for Orbit OS</h3>

<p align="center">
Sprinqua turns a Raspberry Pi and a relay board into a self-hosted irrigation controller.<br>
Schedule your zones, skip watering when it rains, and connect to Home Assistant — all from a web page on your local network.
</p>

<p align="center">
  <a href="https://www.sprinqua.com/?ref=github-org"><img src="https://img.shields.io/badge/Website-sprinqua.com-1565C0?style=for-the-badge" alt="Website"></a>
  <a href="https://www.sprinqua.com/install.html?ref=github-org"><img src="https://img.shields.io/badge/Install-Guide-2ea44f?style=for-the-badge" alt="Install guide"></a>
  <a href="https://www.orbit-os.org/?ref=github-sprinqua"><img src="https://img.shields.io/badge/Built%20for-Orbit%20OS-564fd1?style=for-the-badge" alt="Built for Orbit OS"></a>
  <a href="https://www.youtube.com/watch?v=Phg4g1hm4A0"><img src="https://img.shields.io/badge/Demo-YouTube-ff0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Demo video"></a>
</p>

<p align="center">
  <a href="https://store.orbit-os.org/app/sprinqua?ref=github-sprinqua"><img src="https://www.orbit-os.org/images/badges/get-it-on-orbit-os-store@3x.png" width="200" alt="Get it on Orbit OS Store"></a>
</p>

---

## What Sprinqua does

- **Zone control** — turn zones on and off, run a short pulse, with a safety auto-off per zone
- **Scheduling** — multi-zone watering programs by day of the week, with soak pauses between zones
- **Smart Watering** — skips a run when rain or frost is forecast, and adjusts the duration to the weather (fixed percentage, monthly curve, Zimmerman or FAO-56 reference ETo), using free [Open-Meteo](https://open-meteo.com) data with no API key
- **Home Assistant** — every zone appears automatically as a switch over MQTT; choose Standalone or Home Assistant Managed mode
- **History** — a log of every run (manual, scheduled, MQTT or skipped) with a 24-hour timeline
- **Six languages** — English, Portuguese, Spanish, French, German and Italian
- **No cloud** — no account, no subscription, no data leaving your home

## Built for Orbit OS

Sprinqua is an app for **[Orbit OS](https://www.orbit-os.org/?ref=github-sprinqua)**, the platform for embedded Linux devices. Orbit OS runs on the Raspberry Pi, on top of its Linux, and gives Sprinqua what a product needs beyond the app itself:

- **Installation in one click** from the [Orbit OS Store](https://store.orbit-os.org/app/sprinqua?ref=github-sprinqua), and updates the same way
- **Access to the hardware** — the relay boards, over GPIO and I²C — through the Orbit OS API
- **A place on the device** — Sprinqua opens from the Orbit OS Launcher, behind the device login

That is why there is no Docker image to pull and no service to configure by hand: install Orbit OS on the Pi, then install Sprinqua from the Store.

## Get started

| 1 · Install Orbit OS | 2 · Install Sprinqua | 3 · Run the wizard |
|---|---|---|
| On a Raspberry Pi 3, 4, 5 or Zero 2 W — [guide](https://www.orbit-os.org/getting_started.html?ref=github-sprinqua) | From the [Orbit OS Store](https://store.orbit-os.org/app/sprinqua?ref=github-sprinqua), in one click | Pick your relay board, name the zones, test each relay |

The full walkthrough is in the **[install guide](https://www.sprinqua.com/install.html?ref=github-org)**.

## Supported relay boards

| Board | Model | Channels |
|---|---|---|
| SB Components | 14088 | 2 |
| Waveshare | 11638 | 3 |
| Seengreat | 250509 | 3 |
| Keyestudio | KS0212 | 4 |
| Seengreat | 220741 | 4 |
| BC Robotics | RAS-193 | 4 |
| 52Pi (I²C, stackable) | EP-0099 | 4 / 8 / 12 / 16 |
| Waveshare RPi Zero | 20863 | 6 |
| Waveshare | 15423 | 8 |
| Seengreat | 260115 | 8 |

Don't see your board? [Tell us](https://www.sprinqua.com/?ref=github-org#contact) and we'll look into adding it.

## Watch it

[![Sprinqua — open-source smart irrigation controller for Raspberry Pi on Orbit OS](https://img.youtube.com/vi/Phg4g1hm4A0/hqdefault.jpg)](https://www.youtube.com/watch?v=Phg4g1hm4A0)

## Open source

Sprinqua is free and open source under the **GPL-3.0** license. Fork it, add your board, translate it to a new language.

- **Source code:** [Sprinqua/sprinqua](https://github.com/Sprinqua/sprinqua)
- **Report a problem or ask for a board:** [open an issue](https://github.com/Sprinqua/sprinqua/issues)

## We're looking for developers

Sprinqua is growing and we want more people building it with us. If you'd like to contribute regularly and become part of the team, we'd love to hear from you.

Useful experience: Go, web interfaces (HTML, HTMX), MQTT and Home Assistant, or hands-on work with Raspberry Pi and relay hardware. You don't need all of it; knowing irrigation or gardening well counts too.

**How to reach us:** start a thread in [Discussions](https://github.com/orgs/Sprinqua/discussions) or use the [contact form](https://www.sprinqua.com/?ref=github-org#contact) on the website. Tell us what you'd like to work on.

## Links

[Website](https://www.sprinqua.com/?ref=github-org) · [Install guide](https://www.sprinqua.com/install.html?ref=github-org) · [Orbit OS Store](https://store.orbit-os.org/app/sprinqua?ref=github-sprinqua) · [Orbit OS](https://www.orbit-os.org/?ref=github-sprinqua) · [Demo video](https://www.youtube.com/watch?v=Phg4g1hm4A0)
