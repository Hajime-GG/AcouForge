# Getting Started

## 1. Install AcouForge

Download the latest installer from the Releases page.

Run the installer and complete the installation.

## 2. Start AcouForge Virtual Audio

AcouForge uses its Virtual Audio device as the playback entry point for processed audio.

Make sure AcouForge Virtual Audio is installed and running.

## 3. Configure Windows

For the recommended configuration, set:

**AcouForge Virtual Audio → Windows default playback device**

This allows normal Windows playback to enter AcouForge.

## 4. Configure AcouForge

Inside AcouForge, use:

- **Input:** AcouForge Virtual Audio
- **Output:** Your physical headphones, speakers, or DAC

The physical output device is where the processed audio will ultimately be played.

## 5. Configure Processing

Once the audio path is working, configure the available AcouForge processing modules.

These include:

- Equalizer
- Dynamics
- Spatial Audio
- Calibration
- Audio Tools

Changes are processed in real time.

## Application-Specific Audio

Most Windows applications follow the Windows default playback device.

Some applications, however, use their own output-device selection.

If an application does not appear to be passing through AcouForge, open the Windows Volume Mixer and assign that application to:

**AcouForge Virtual Audio**

## Recommended Signal Flow

```text
Windows Applications
        ↓
AcouForge Virtual Audio
        ↓
     AcouForge
        ↓
Physical Headphones / Speakers / DAC
```

Once this signal path is established, AcouForge can process the audio before it reaches your physical listening device.
