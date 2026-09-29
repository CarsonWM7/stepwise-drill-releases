# Stepwise Drill — downloads

Drill writing software for marching band, drum corps and indoor ensembles.

**[Download the latest version](../../releases/latest)** — under *Assets*, pick the file for your
computer:

| Computer | File |
| --- | --- |
| Windows | `Stepwise-Drill-Setup-x.y.z.exe` (installer, recommended) or `Stepwise-Drill-Portable-x.y.z.exe` (runs without installing) |
| Mac (Apple silicon or Intel) | `Stepwise-Drill-x.y.z-mac-universal.dmg` |
| Linux | `.AppImage` (any distribution) or `.deb` (Ubuntu, Debian) |

## Installing

Stepwise Drill isn't signed with a paid Microsoft or Apple certificate yet, so your computer will
warn you the first time. This is expected.

### Windows

1. Run `Stepwise-Drill-Setup-x.y.z.exe`.
2. If you see **"Windows protected your PC"**, click **More info**, then **Run anyway**.
3. Follow the installer. Stepwise Drill appears in the Start menu.

Some browsers also warn that the file "isn't commonly downloaded". Choose **Keep** (in Edge:
*⋯ → Keep → Show more → Keep anyway*).

### Mac

1. Open the `.dmg` and drag **Stepwise Drill** into **Applications**.
2. The first time, **right-click** (or Control-click) Stepwise Drill in Applications and choose
   **Open**, then **Open** again. After that it opens normally.
3. If macOS says it **"is damaged and can't be opened"** or there's no Open button: open
   **System Settings → Privacy & Security**, scroll down and click **Open Anyway** next to
   Stepwise Drill. If that doesn't appear, open **Terminal** and run
   `xattr -cr "/Applications/Stepwise Drill.app"`, then open it again.

### Linux

- **AppImage:** make it executable (`chmod +x Stepwise-Drill-*.AppImage`, or *Properties →
  Permissions → Allow executing*) and double-click it.
- **.deb:** `sudo apt install ./Stepwise-Drill-*.deb`

## Updating

The app tells you when a new version is out, with a **Download** button that brings you here.
Nothing is installed automatically: download the new version and install it over the old one.
Your shows are separate files and aren't affected.

## Reporting a bug

In the app, click the **bug** button in the toolbar (or **Help → Report a Bug…**), describe what
happened and press **Submit**. It opens a pre-filled report here for you to check and send (you'll
need a free GitHub account). You can also
[open a report directly](../../issues/new?labels=bug).

## Privacy

Stepwise Drill doesn't collect anything about you or your shows. The only thing it does online is
check `latest-version.json` in this repository when it starts, to see if there's a newer version;
that request sends nothing personal. Bug reports are only sent if you choose to submit one, and you
see everything in it first. Your show itself is never included.

---

This repository only holds the downloads; the app's source code is private.
