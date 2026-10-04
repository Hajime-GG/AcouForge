# AcouForge Virtual Audio

AcouForge Virtual Audio provides the Windows audio entry point used by AcouForge.

It allows supported Windows playback to be routed into AcouForge for real-time processing before being sent to the physical listening device.

## Recommended Audio Path

```text
Windows Applications
        ↓
AcouForge Virtual Audio
        ↓
     AcouForge
        ↓
Physical Audio Device
        ↓
Headphones / Speakers / DAC
```

## Windows Default Playback Device

The simplest configuration is to set:

**AcouForge Virtual Audio**

as the Windows default playback device.

Normal Windows playback can then enter AcouForge through the virtual audio endpoint.

## Application-Specific Audio

Some applications use their own output-device selection instead of the Windows default.

If an application bypasses AcouForge:

1. Open the Windows Volume Mixer.
2. Locate the application.
3. Change its output device.
4. Select **AcouForge Virtual Audio**.

## AcouForge Output

AcouForge's output should normally be your actual physical listening device.

Examples include:

- Headphones
- Speakers
- USB DAC
- Other physical audio endpoints

The virtual audio device should normally be the **input** to AcouForge rather than the final physical output.

## Running Virtual Audio

AcouForge Virtual Audio must be running for its virtual audio endpoint to be available.

If the device is missing:

1. Start AcouForge Virtual Audio.
2. Allow Windows a moment to initialize the audio endpoint.
3. Refresh the available audio devices in AcouForge.

## Technical Details

AcouForge Virtual Audio uses a dedicated virtual audio implementation designed for the AcouForge processing pipeline.

Detailed technical information about its audio architecture, including its UAC 2 implementation and supported capabilities, will be documented here as the Virtual Audio component documentation is finalized.
