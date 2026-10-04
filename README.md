<div align="center">

<img src="assets/acouforge-logo.png" width="180" alt="AcouForge">

# AcouForge

### Precision Audio Processing for Windows

A real-time audio processing suite for equalization, dynamics, spatial audio, calibration, and more.

<br>

<a href="https://github.com/Hajime-GG/AcouForge/releases/latest">
&#x20; <strong>Download AcouForge</strong>
</a>
&nbsp;&nbsp;•&nbsp;&nbsp;
<a href="[https://github.com/Hajime-GG/AcouForge/releases](https://github.com/Hajime-GG/AcouForge/releases)">
&#x20; View Releases
</a>

<br><br>

</div>

---

## What is AcouForge?

**AcouForge** is a Windows audio processing application designed to give you precise control over your listening experience.

It provides a complete real-time processing chain between your applications and your physical audio device, bringing equalization, dynamics processing, spatial processing, calibration, and other audio tools together in a single application.

AcouForge is built for people who want more control over how their audio sounds without having to rely on a collection of separate applications.

---

## Features

<table>
<tr>
<td width="50%">

### 🎚️ Equalizer

Shape your sound with precise real-time equalization and detailed control over your audio response.

</td>
<td width="50%">

### 📈 Dynamics

Control the dynamics of your audio with real-time processing designed for flexible playback control.

</td>
</tr>

<tr>
<td>

### 🌌 Spatial Audio

Explore spatial processing designed to provide greater control over the presentation and character of your audio.

</td>
<td>

### 🎧 Calibration

Calibrate your listening setup and work with measurement data to create a more accurate processing profile.

</td>
</tr>

<tr>
<td>

### 🔊 Virtual Audio

Route Windows playback through AcouForge using AcouForge Virtual Audio.

</td>
<td>

### 🛠️ Audio Tools

A collection of additional tools for configuring, measuring, and working with your audio system.

</td>
</tr>
</table>

---

## How It Works

AcouForge sits between your Windows audio applications and your physical listening device.

```text
┌───────────────────────┐
│  Windows Applications │
└──────────┬────────────┘
           │
           ▼
┌──────────────────────┐
│ AcouForge Virtual    │
│ Audio                │
└──────────┬───────────┘
           │
           ▼
┌────────────────────────┐
│      AcouForge         │
│                        │
│  EQ • Dynamics         │
│  Spatial • Calibration │
│  Audio Tools           │
└──────────┬─────────────┘
           │
           ▼
┌───────────────────────┐
│ Physical Audio Device │
│ Headphones / Speakers │
│ / DAC                 │
└───────────────────────┘
```

This allows supported Windows playback to pass through AcouForge before reaching your listening device.

---

## Getting Started

1. Download the latest AcouForge installer.
2. Install AcouForge.
3. Launch **AcouForge Virtual Audio** when prompted.
4. Set **AcouForge Virtual Audio** as your Windows default playback device.
5. In AcouForge, select your physical headphones, speakers, or DAC as the output device.
6. Start processing your audio.

> **Note**
>
> Some applications use their own audio-output setting instead of the Windows default device. If an application does not appear to be passing through AcouForge, select **AcouForge Virtual Audio** as that application's output device in the Windows Volume Mixer.

---

## Screenshots

Screenshots and detailed documentation are coming soon.

---

## Download

The latest version of AcouForge is distributed through **GitHub Releases**.

### Latest Release

**[Download AcouForge](https://github.com/Hajime-GG/AcouForge/releases/latest)**

For previous versions and release notes, see the [Releases](https://github.com/Hajime-GG/AcouForge/releases) page.

---

## System Requirements

AcouForge is designed for modern 64-bit Windows systems.

Detailed system requirements will be listed with each release.

---

## Documentation

- [Getting Started](docs/getting-started.md)
- [Installation](docs/installation.md)
- [AcouForge Virtual Audio](docs/virtual-audio.md)
- [Troubleshooting](docs/troubleshooting.md)

---

## Licensing

AcouForge is proprietary software.

The AcouForge source code is not distributed as open source, and use of the software is subject to the AcouForge End User License Agreement.

Third-party components and their applicable licenses are listed in the [`licenses`](licenses/) directory.

---

## Privacy

AcouForge is designed to perform audio processing locally on your Windows system.

See [PRIVACY.md](PRIVACY.md) for information about data handling.

---

<div align="center">

### AcouForge

**Precision audio processing for Windows.**

</div>
