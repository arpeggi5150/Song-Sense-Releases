# Song Sense - releases

Builds only. Song Sense reads an audio file offline and shows BPM, time signature (as beat grouping) and key for
every section of the song, with confidences, alternatives and the reasons, and exports the settings to REAPER.
Nothing leaves your computer.

## Download (Windows 10/11, 64-bit)

- **Song Sense Setup 1.0.1.exe** - installs the desktop app, the VST3 plug-in (Common Files\VST3) and the CLAP
  plug-in (Common Files\CLAP), with a Start menu shortcut and an uninstaller. After installing, rescan plug-ins in
  REAPER (Options > Preferences > Plug-ins > Re-scan).
- **Song-Sense-1.0.1-portable.exe** - the desktop app on its own, no install.
- **Song-Sense-1.0.1-VST3.zip** / **Song-Sense-1.0.1-CLAP.zip** - just the plug-ins, to copy by hand.

Check a download with SHA256SUMS.txt (PowerShell: `Get-FileHash "file" -Algorithm SHA256`).

## Terms

Provided AS IS, without warranty of any kind. Use at your own risk. The analysis gives its best reading with a
confidence for each call - please check important calls by ear.

## Third-party software

The plug-ins are built with JUCE (commercial JUCE licence), the VST3 SDK (MIT) and CLAP (MIT). The desktop app
uses librosa, NumPy, SciPy and other open-source libraries under their own licences (BSD / MIT / ISC; libsndfile
LGPL-2.1).
