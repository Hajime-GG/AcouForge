# Installation

## System Requirements

AcouForge is designed for modern 64-bit Windows systems.

The exact supported Windows version and additional requirements are provided with each production release.

## Installing AcouForge

1. Download the latest AcouForge installer from GitHub Releases.
2. Run the installer.
3. Follow the installation wizard.
4. Launch AcouForge.
5. Make sure AcouForge Virtual Audio is installed and running.

## First-Time Configuration

After installation, configure Windows to use:

**AcouForge Virtual Audio**

as the default playback device.

Then configure AcouForge itself:

```text
Input
    ↓
AcouForge Virtual Audio

Output
    ↓
Physical Headphones / Speakers / DAC
```

This separates the Windows playback input from the physical device receiving the processed audio.

## AcouForge Virtual Audio

AcouForge Virtual Audio is a separate component used to provide the audio entry point into AcouForge.

It must be running for the virtual audio device to be available to Windows and AcouForge.

For technical information about the Virtual Audio implementation, see:

[AcouForge Virtual Audio](virtual-audio.md)

## Updating AcouForge

When a newer version becomes available:

1. Open the GitHub Releases page.
2. Download the latest installer.
3. Run the installer.
4. Follow the installation instructions.

Review the release notes before installing a major version update.

## Uninstallation

AcouForge can be removed using the normal Windows application-uninstallation process.

If application data remains after uninstallation, configuration files can be found under:

```text
%LOCALAPPDATA%\AcouForge
```
