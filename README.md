# Lumen

**A video player for Windows, made for watching films closely.**

Lumen is a free, modern video player designed by a cinema student, for people who don't just watch films but study them: step through a scene frame by frame, loop a shot, write notes at an exact timecode, and see HDR films the way they were meant to look.

### [⬇ Download the latest version](https://github.com/nooelone/lumen-releases/releases/latest)

Windows 10 / 11 (64-bit) · free · installs just for you, no admin needed · updates itself

<!-- Screenshots: drag images into this editor on GitHub and they'll appear here. Suggested: Home, a film playing, the subtitle settings, the shot-notes card. -->

---

## What it does

**🎞 Study a scene**
- Step one frame forward or back, exactly
- **A–B loop**: press `A` where a moment starts and `A` where it ends, and Lumen repeats it
- **Shot notes**: `Shift+N` writes a note at the current frame; export them all with timecodes to a `.txt`
- Full-resolution snapshots, copy the timecode, framing guides (aspect masks, thirds, safe areas)

**🏠 A Home that remembers**
- Opens on the exact frame where you stopped, playing quietly in the background
- Rows for Continue watching, Recently added, Favorites, Short films and Watch again
- Clean titles: `Her.2013.1080p.BluRay.x264.mkv` becomes **Her · 2013**

**🌗 HDR done right**
- HDR10 films are tone-mapped for normal screens, so the picture isn't grey and washed out, even for files that don't say they're HDR

**💬 Subtitles your way**
- Any font on your PC, size, colour, outline, shadow, background box and height, with a live preview

**And also**
- Plays almost every format (it runs on VLC's engine)
- Play YouTube, Vimeo or Twitch links: copy a link, press `Ctrl+V`
- Add a separate audio file to a video, audio waveform on the seek bar, mini player, every shortcut can be changed
- Signed automatic updates: Lumen only installs updates that were signed by its maker

## Installing

1. Download **Lumen-Setup-x.x.x.exe** from the [latest release](https://github.com/nooelone/lumen-releases/releases/latest).
2. Run it. If Windows shows *"Windows protected your PC"*, click **More info**, then **Run anyway**. Lumen isn't signed with a paid certificate, which is normal for independent apps.
3. That's it. Future versions arrive by themselves: Lumen asks before installing anything.

**Check your download (optional):** on the release page, each file shows its `sha256` code. In PowerShell, run `Get-FileHash .\Lumen-Setup-x.x.x.exe` and compare.

## Who made it

Designed by **Rayane Elkhyati** (Ryan Khyati), cinema & audiovisual student at ENSAD Mohammedia, Morocco.

Lumen was built with **Claude** (Anthropic's AI) as the developer: I designed the interface and features, directed the work, and tested every version with feedback from friends.

[Instagram @rhyso_xo](https://www.instagram.com/rhyso_xo/) · [LinkedIn](https://www.linkedin.com/in/rayane-elkhyati-2a2a06320/)

Feedback and bug reports are welcome: open an [issue](https://github.com/nooelone/lumen-releases/issues).

## Credits

Playback is powered by **libVLC** by [VideoLAN](https://www.videolan.org/vlc/libvlc.html), used through [LibVLCSharp](https://github.com/videolan/libvlcsharp). Both are free software under the [GNU LGPL 2.1](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html).
Lumen is not made by, endorsed by or affiliated with VideoLAN. VLC is a trademark of VideoLAN.
