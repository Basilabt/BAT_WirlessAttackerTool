# BAT 🦇

![License](https://img.shields.io/github/license/yourusername/your-repo.svg)
![Issues](https://img.shields.io/github/issues/yourusername/your-repo.svg)
![Forks](https://img.shields.io/github/forks/yourusername/your-repo.svg)
![Stars](https://img.shields.io/github/stars/yourusername/your-repo.svg)

## Table of Contents

- [Description](#Description)
- [Vulnerability](#Vulnerability)
- [Scenario](#Scenario)
- [Usage](#configuration)
- [License](#license)
- [Contact](#contact)

## Description
BAT is a tool for discovering wireless networks, listening on specific wireless networks and performing deauthentication attacks by exploiting a vulnerability in IEEE 802.11 standard.

## IEEE 802.11 Vulnerability

The vulnerability lies in the fact that the IEEE 802.11 standard does not include robust authentication mechanisms for management frames. As a result, an attacker can easily spoof deauthentication frames and send them to a target device, causing disruption to its connection to the Wi-Fi network.

## Deauthentication attack scenario
The attacker sends forged deauthentication frames to the target device, causing it to disconnect from the Wi-Fi network. These deauthentication frames are part of the IEEE 802.11 standard and are used by legitimate network administrators to disconnect devices from a network. However, in a deauthentication attack, the frames are maliciously crafted and sent by an unauthorized party.


## Installation

Step-by-step instructions on how to get the development environment running.

```bash
# Clone the repository
git clone https://github.com/yourusername/your-repo.git

# Navigate to the project directory
cd your-repo

# Install dependencies
pip install -r requirements.txt
