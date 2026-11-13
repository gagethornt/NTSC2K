NTSC2K is a Windows OpenFX video effect that recreates digital video compression, NTSC television signals, VHS tracking, CRT displays, and Windows 95 CD-ROM video. It processes 8-bit or floating-point RGB/RGBA video on the CPU and leaves audio unchanged.

 _The production of this plugin was inspired by [Finn McKenty’s open-source NTSCRT app](https://github.com/finnmckenty/NTSCRT) and its [video distortion demo](https://x.com/thefinnmckenty/status/2119903587409293437). NTSC2K brings a similar range of vintage/modern video looks to VEGAS Pro as an OFX effect. It is a separate project and does not use every part of NTSCRT. Check it out and show support to the creator!_

## Installation

1. Close VEGAS Pro.
2. Extract the folder.
3. Copy extracted folder into your directory (i.e. `C:\Program Files\BorisFX\Vegas Pro 2026\OFX Video Plug-Ins\`). Windows may ask for administrator access.
4. Open VEGAS Pro and add the **NTSC2K** plugin.

## Effects

| Section | What it does |
| --- | --- |
| Downscale | Reduces resolution and adjusts saturation and blending. |
| Digital video | Simulates older cameras and digital compression, including data loss and datamosh. |
| NTSC (TV) | Adds analog signal damage and white signal lines. |
| Glitch | Adds reception errors, tracking problems, search, dropouts, and other tape faults. |
| CRT | Adds scanlines, phosphor mask, and glow. |
| Windows 95 CD-ROM Look | Adds choppy, blocky video with adjustable frame rate, data loss, and bitrate. |

## Notes

The CD-ROM look uses part of the Microsoft Video 1 codec. The analog and datamosh effects approximate the reference NTSCRT app, so results may differ from its screenshots. Datamosh uses earlier frames when the host provides them and otherwise uses a block smear.
