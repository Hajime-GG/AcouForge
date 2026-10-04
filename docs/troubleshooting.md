# Troubleshooting

## No Audio

If you are not hearing audio through AcouForge, check the following:

1. AcouForge Virtual Audio is installed.
2. AcouForge Virtual Audio is running.
3. Windows playback is routed to AcouForge Virtual Audio.
4. AcouForge's input is set to AcouForge Virtual Audio.
5. AcouForge's output is set to your physical listening device.
6. Your headphones, speakers, or DAC are connected and functioning.

The expected signal path is:

```text
Windows Applications
        ↓
AcouForge Virtual Audio
        ↓
     AcouForge
        ↓
Physical Audio Device
```

## AcouForge Virtual Audio Is Missing

If AcouForge Virtual Audio does not appear as an available audio device:

1. Make sure AcouForge Virtual Audio is installed.
2. Start the AcouForge Virtual Audio application.
3. Wait for Windows to initialize the device.
4. Refresh the available audio devices in AcouForge.

## An Application Bypasses AcouForge

Some applications use their own audio-output configuration instead of following the Windows default playback device.

Open the Windows Volume Mixer and assign the application to:

**AcouForge Virtual Audio**

## No Audio After Changing Devices

If you connect or disconnect headphones, speakers, a DAC, or another audio device while AcouForge is running:

1. Refresh the available audio devices.
2. Verify the AcouForge input.
3. Verify the AcouForge output.
4. Make sure the physical output device is still available.

## Audio Sounds Incorrect

If audio is playing but does not sound as expected:

1. Temporarily disable processing modules.
2. Verify the selected input and output devices.
3. Check the equalizer configuration.
4. Check dynamics processing.
5. Check spatial processing.
6. Check calibration settings.

This can help identify which processing stage is affecting the signal.

## Settings Do Not Persist

AcouForge stores application settings and profiles locally under:

```text
%LOCALAPPDATA%\AcouForge
```

Close AcouForge before manually modifying or removing configuration files.

## Virtual Audio Stops Working

If AcouForge Virtual Audio stops providing the expected endpoint:

1. Exit the Virtual Audio application.
2. Start it again.
3. Wait for the endpoint to become available.
4. Refresh the audio devices in AcouForge.
5. Verify the Windows playback device.

## Still Having Problems?

If the problem persists, collect:

- AcouForge version
- Windows version
- Input device
- Output device
- Whether AcouForge Virtual Audio is running
- A description of the expected and actual behavior

Then open an issue in the AcouForge GitHub repository with the relevant information.
