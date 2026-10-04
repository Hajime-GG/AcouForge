<div align="center">

<img src="assets/acouforge-logo.png" width="180" alt="AcouForge">

# AcouForge

### Precision Audio Processing for Windows

Real-time equalization, dynamics, spatial processing, calibration,
and audio tools — built into one processing environment.

<br>

<a href="https://github.com/Hajime-GG/AcouForge/releases/latest">
  <strong>⬇ Download AcouForge</strong>
</a>

&nbsp;&nbsp;&nbsp;•&nbsp;&nbsp;&nbsp;

<a href="https://github.com/Hajime-GG/AcouForge/releases">
  View Releases
</a>

<br><br>

</div>

---

## The Audio Processing Layer Between Your Apps and Your Ears

**AcouForge** is a real-time Windows audio processing suite designed
to give you precise control over the sound reaching your listening
device.

Instead of relying on multiple independent applications, AcouForge
brings the processing chain together in one environment.

**Equalization. Dynamics. Spatial processing. Calibration. Audio tools.**

All working together in real time.

---

## ✦ What AcouForge Does

<table>
<tr>
<td width="50%" valign="top">

### 🎚 Equalizer

Shape your sound with real-time equalization and detailed control
over your audio response.

</td>
<td width="50%" valign="top">

### 📈 Dynamics

Control the dynamics of your audio with real-time processing
designed for flexible playback control.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### ◉ Spatial Audio

Explore spatial processing designed to provide greater control
over the presentation and character of your audio.

</td>
<td width="50%" valign="top">

### 🎧 Calibration

Work with measurement data and calibration profiles to create
a more accurate processing setup.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🔊 Virtual Audio

Route Windows playback through AcouForge using the
**AcouForge Virtual Audio** device.

</td>
<td width="50%" valign="top">

### 🛠 Audio Tools

Additional tools for configuring, measuring, and working with
your audio system.

</td>
</tr>
</table>

---

## Signal Flow

AcouForge is designed to sit between your Windows applications
and your physical listening device.

```text
┌─────────────────────────┐
│   Windows Applications  │
└────────────┬────────────┘
             │
             ▼
┌─────────────────────────┐
│  AcouForge Virtual      │
│         Audio           │
└────────────┬────────────┘
             │
             ▼
┌─────────────────────────┐
│        AcouForge        │
│                         │
│  EQ • Dynamics          │
│  Spatial • Calibration  │
│  Audio Tools            │
└────────────┬────────────┘
             │
             ▼
┌─────────────────────────┐
│   Physical Audio Device │
│                         │
│ Headphones • Speakers   │
│          • DAC          │
└─────────────────────────┘