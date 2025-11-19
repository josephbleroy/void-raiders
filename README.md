# Void-Raiders Theme

![Void-Raiders](https://img.shields.io/badge/Status-Operational-brightgreen?style=for-the-badge&logo=radar)

> "In the void, only the bold survive."

**Void-Raiders** is a gritty, retro-futuristic Hugo theme for the digital wasteland. Forked from the excellent [Hello Friend NG](https://github.com/rhazdon/hugo-theme-hello-friend-ng), this theme has been heavily modified to embody the aesthetic of *Arc Raiders*—pulsating neon, analog glitches, and the raw survivalist energy of the resistance.

---

## 📡 Transmission Contents

- [Features](#features)
- [Deployment](#deployment)
- [Configuration](#configuration)
- [Components](#components)
  - [Glitch Title](#glitch-title)
  - [Void Background](#void-background)
  - [Holo-Socials](#holo-socials)
  - [Terminal Code](#terminal-code)
- [Social Protocols](#social-protocols)
- [License](#license)

---

## ⚡ Features

- **Atmospheric Visuals**: A subtle, animated rainbow gradient background that breathes with the site.
- **Glitch Typography**: The site title features a custom "bobbing" random animation, simulating signal instability.
- **Tactile Interactions**: Pulsating "Arc Raiders" rainbow hover effects on all interactive elements.
- **Modern Comms**: Integrated support for **Bluesky**, **Mastodon**, **Signal**, and **X** (formerly Twitter).
- **Retro-Tech Styling**: Code blocks and UI elements styled to look like scavenged terminal interfaces.
- **Responsive Design**: Fully operational on all devices, from handheld scanners to mainframe terminals.

## 🚀 Deployment

### Standard Drop
Download the theme and extract it to your `themes/` directory:

```bash
git clone https://github.com/josephbleroy/void-raiders.git themes/void-raiders
```

### Submodule Uplink (Recommended)
For easier updates from the mothership:

```bash
git submodule add https://github.com/josephbleroy/void-raiders.git themes/void-raiders
```

## ⚙️ Configuration

The theme is ready to deploy with minimal configuration. Update your `config.toml` to establish your signal.

```toml
theme = "void-raiders"
baseurl = "https://your-comms-link.com"
title = "Resistance Outpost"

[params]
  # Enable the atmospheric background
  enableVoidBackground = true
  
  # Social sharing on posts
  enableSharingButtons = true
  
  # Date format for logs
  dateform = "Jan 2, 2006"
```

## 🧩 Components

### Glitch Title
The site title isn't just text; it's a living signal. It uses a custom CSS animation to "bob" and float, giving it an ethereal, unstable presence. No configuration needed—it's active by default.

### Void Background
A slow-moving, animated gradient background that shifts colors subtly, mimicking the shifting lights of the Arc. 

### Holo-Socials
Social icons and sharing buttons are equipped with a `rainbow-text` hover effect. When interacted with, they pulse with a spectrum of colors, indicating active transmission.

### Terminal Code
Code blocks are styled with a dark, high-contrast theme suitable for reading schematics in low-light environments.

## 📡 Social Protocols

We've purged the old networks. Void-Raiders supports the following modern communication channels:

- **Bluesky**: The new open sky.
- **Mastodon**: The federated resistance.
- **Signal**: Secure, encrypted comms.
- **X**: The chaotic public square.

Configure them in your `config.toml`:

```toml
[[params.social]]
  name = "bluesky"
  url = "https://bsky.app/profile/your-handle"

[[params.social]]
  name = "mastodon"
  url = "https://mastodon.social/@your-handle"
```

## 📝 License

**Void-Raiders** is open source. 

Copyright © 2025 Joseph B. LeRoy.
Based on Hello Friend NG by Djordje Atlialp.

Released under the MIT License. Use it to build something that survives.
