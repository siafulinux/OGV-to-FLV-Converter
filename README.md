---
## What this is — for hiring managers

Bash / ffmpeg video converter for Linux, originally a Nautilus script to convert recordMyDesktop .ogv files to web-ready video. Written in 2008 and featured by FOSSWire — an early open-source contribution showing long-running Linux scripting and community work.

**Skills shown:** Bash, ffmpeg, Linux automation.

---

# OGV to FLV Converter - Nautilus Bash Script

**Bash automation for video transcoding using ffmpeg.**

Originally authored in 2008 and featured in FOSSWire. This was a Nautilus extension to convert recordMyDesktop `.ogv` files to web-ready formats. Preserved here as an early open-source contribution demonstrating 18+ years of Linux scripting and community contribution.

**Original feature:** https://fosswire.com/post/2008/10/quickly-convert-ogg-theora-to-flash-video/  
**Author page:** https://wiki.ubuntu.com/JeanClaude

### What it did
- Frontend for ffmpeg to convert `.ogv`, `.ogg`, `.asf`, `.mp4`, `.flv` 
- Integrated with Nautilus file manager (`~/.gnome2/nautilus-scripts`)
- Custom resolution and bitrate options (320x240 up to 1080p)
- Built for gtk-recordMyDesktop workflow

### License
GPL v2 or later — 2008 Jean-Claude McGeer

### Historical Changelog
v1.4 (10/19/2010): Switched from mencoder to ffmpeg, added HD720/1080 options, default res 800x600
v1.0 (10/07/2008): Added installer, error handling, first stable release
v0.1 (2008): Initial release for recordMyDesktop .ogv conversion

### Why it's preserved
This project shows the start of my work in Linux automation — writing practical Bash tools for real user problems and sharing them with the FOSS community long before GitHub was mainstream. The underlying transcoding logic is still relevant to my current ffmpeg automation workflows.

### Tech
Bash, ffmpeg, Nautilus Scripts, GTK

### Installation (historical - for reference)
The script was installed to `~/.gnome2/nautilus-scripts` and made executable:
```bash
chmod +x "Ogv to Flv Converter"


