<img width="999" height="990" alt="OALSVRC" src="https://github.com/user-attachments/assets/7464083f-3834-4138-9849-f1a357505e10" />

currently in development.
---
# OALSVRC: Outside AudioLink System for VRChat

OALSVRC is a standalone audio analysis system that captures system audio, breaks it down into bass, mids, highs, amplitude, and waveform, and sends real-time data to VRChat avatars via OSC. It allows avatars to react to any music playing on your device — Spotify, YouTube, games, anything — without needing in-world audio or mic routing.

# Features
- System audio capture via WASAPI Loopback (no mic required)
- Real-time FFT analysis (bass, mids, highs)
- Waveform and amplitude detection
- OSC transmission to VRChat avatars
- Customizable parameter mapping and reaction styles
- GUI for live control, presets, and OSC routing
- In-VR feedback messages for connection status

# Primary Focus
OALSVRC is built primarily for VRChat avatars, giving users full control over how their avatars react to system audio. It enhances AudioLink by making it truly external, customizable, and universal.

## Beyond VRChat
While designed for avatars, OALSVRC can be used with:
- VRChat worlds (via OSC listeners)
- OSC-enabled games (e.g., ChilloutVR, NeosVR)
- Interactive installations
- Live performance setups
- Custom Unity projects

Its flexible OSC architecture makes it compatible with any system that can receive OSC data—opening up possibilities far beyond its original intent.

# License
- Creative Commons - Attribution-NonCommercial-NoDerivatives 4.0 International

## You are free to:
- Share — copy and redistribute the material in any medium or format 

## NonCommercial:
- You may not use the material for commercial purposes 

## NoDerivatives:
- If you remix, transform, or build upon the material, you may not distribute the modified material.
 
## Attribution:
- You must give appropriate credit.
