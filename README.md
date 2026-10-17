<p align="center">
  <a href="README.md"><img src="images/drapeau-en.svg" width="36" alt="English"></a>&nbsp;<a href="README.md"><b>English</b></a>&nbsp;&nbsp;
  <a href="README.fr.md"><img src="images/drapeau-fr.svg" width="36" alt="Français"></a>&nbsp;<a href="README.fr.md">Français</a>&nbsp;&nbsp;
  <a href="README.es.md"><img src="images/drapeau-es.svg" width="36" alt="Español"></a>&nbsp;<a href="README.es.md">Español</a>&nbsp;&nbsp;
</p>

<div align="center">

# 🐠 Aquatech

**A virtual aquarium for the Waveshare ESP32-S3 AMOLED 1.8" screen**

One-click install from your browser, no development tools needed.

[![Install](https://img.shields.io/badge/🐠_Install_on_my_screen-ff7a59?style=for-the-badge)](https://bgotech.github.io/aquarium/?lang=en)

![Platform](https://img.shields.io/badge/ESP32--S3-AMOLED_1.8"-0b4a63?style=flat-square)
![Browsers](https://img.shields.io/badge/Chrome_|_Edge-compatible-4fe0d6?style=flat-square)
![Languages](https://img.shields.io/badge/languages-FR_|_EN_|_ES-ffb347?style=flat-square)

<br>

<img src="images/aquarium.png" alt="The Aquatech aquarium" width="300">

</div>

---

## ✨ Overview

Aquatech turns Waveshare's little AMOLED screen into a living aquarium. Buy fish, feed them, decorate the tank and clean off the algae. The game runs on real time: your fish grow and age even while the screen is asleep.

### Features

- 🐠 **16 species**: 10 fish (Neon, Guppy, Black molly, Clown, Corydoras, Loach, Betta, Blue tang, Oscar and Discus), plus the Pufferfish that inflates when scared, the pulsing Jellyfish, the Seahorse that stays near the decorations, the Crayfish and the Axolotl that walk on the sand, and the Snail that climbs the glass. Each has its own price, behaviour and lifespan.
- 🍤 **Feeding**: tap the top of the screen to drop food. An animal left hungry for too long dies and leaves a skeleton.
- 🧽 **Algae and sponge**: wipe algae off with a finger, or adopt a Black molly, a Blue tang or a Snail to graze on it.
- 💶 **Economy**: start with €10, earn a daily income, buy decorations and sell animals.
- 🪸 **Decorations**: corals, a chest, plants, rocks… placed in the background or the foreground.
- 🌍 **3 languages**: French, English and Spanish. Adjustable sound and brightness, automatic saving.

## 📸 Screenshots

<div align="center">
<table>
  <tr>
    <td align="center"><img src="images/aquarium.png" width="180"><br><sub><b>The aquarium</b></sub></td>
    <td align="center"><img src="images/boutique.png" width="180"><br><sub><b>The shop</b></sub></td>
    <td align="center"><img src="images/fiche-en.png" width="180"><br><sub><b>A fish's card</b></sub></td>
    <td align="center"><img src="images/menu-en.png" width="180"><br><sub><b>The menu</b></sub></td>
  </tr>
</table>
</div>

## 📖 User guide

<table>
  <tr>
    <td align="center"><a href="manuels/Aquatech_user_guide.pdf"><img src="images/drapeau-en.svg" width="60"><br><b>English</b></a></td>
    <td align="center"><a href="manuels/Aquatech_mode_d_emploi.pdf"><img src="images/drapeau-fr.svg" width="60"><br><b>Français</b></a></td>
    <td align="center"><a href="manuels/Aquatech_manual_de_usuario.pdf"><img src="images/drapeau-es.svg" width="60"><br><b>Español</b></a></td>
  </tr>
</table>

## 🔧 Required hardware

Aquatech is designed for the **[Waveshare ESP32-S3-Touch-AMOLED-1.8](https://www.waveshare.com/esp32-s3-touch-amoled-1.8.htm)** board (about $30).

| | |
|---|---|
| **Processor** | ESP32-S3R8, dual-core LX7 240 MHz, Wi-Fi + Bluetooth LE |
| **Memory** | 16 MB flash · 8 MB PSRAM |
| **Display** | 1.8" touch AMOLED, 368 × 448 px, 16.7 M colours |
| **Sensors** | 6-axis IMU, RTC clock |
| **Audio** | Built-in microphone and speaker |
| **Power** | USB-C, optional 3.7 V LiPo battery |

> [!WARNING]
> Waveshare sells several very similar screens (1.43", 1.75", 2.06"… and an **ESP32-C6** version of the 1.8"). **Only the ESP32-S3-Touch-AMOLED-1.8 is compatible.**

You also need:
- a **USB-C cable that carries data** (not a charge-only cable);
- a computer with **Google Chrome** or **Microsoft Edge**.

## 🚀 Installation

1. Connect the screen to your computer with USB-C.
2. Open **[bgotech.github.io/aquarium](https://bgotech.github.io/aquarium/?lang=en)** in Chrome or Edge.
3. Click **“Install on my screen”** and pick the board's port.
4. Wait about a minute: Aquatech starts by itself.

To **update**, just come back to the page and run the installation again.

## 🛟 Troubleshooting

<details>
<summary><b>The board doesn't show up in the list</b></summary>

Try another cable. Otherwise: unplug the board, hold the **BOOT** button, plug it back in, release the button and try again.
</details>

<details>
<summary><b>The install button doesn't appear</b></summary>

Use Chrome, Edge or Opera on a computer. Firefox and Safari don't support browser-based installation (WebSerial).
</details>

<details>
<summary><b>The screen stays black after installation</b></summary>

Unplug and replug the board. If needed, run the installation again and accept the full erase.
</details>

---

<div align="center">
<sub>Installation powered by <a href="https://esphome.github.io/esp-web-tools/">ESP Web Tools</a></sub>
</div>
