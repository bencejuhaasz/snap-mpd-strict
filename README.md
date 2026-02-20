# snap-mpd-strict

**Music Player Daemon (MPD) packaged as a strictly confined Snap**

`snap-mpd-strict` is a Snap package definition for MPD (Music Player Daemon) built from source with strict confinement.  
It uses PulseAudio for audio output and focuses on a minimal, deterministic runtime environment.

This Snap is designed to be secure and clean — running MPD with **strict confinement** and only the interfaces it needs.

## Usage

Once built and installed as a Snap, MPD can be run via:

```
snap run mpd
```
## WIP
- PipeWire support (might need socket path instead of port?)
