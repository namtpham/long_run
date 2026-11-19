<p align="center">
  <img src="icon.png" width="96" alt="">
</p>

<h1 align="center">Long Run Tool<br><sub>for embedded Linux devices</sub></h1>

<p align="center">
  Long-run testing through the serial console: the full log, memory and CPU of every process,<br>
  crashes, memory leaks, live charts and reports. A free app for Windows 10 / 11 and Linux (64-bit).
</p>

<p align="center">
  <a href="https://namtpham.github.io/long_run/"><b>Home page</b></a> ·
  <a href="https://github.com/namtpham/long_run/releases/latest"><b>Download</b></a> ·
  <a href="https://namtpham.github.io/long_run/#how">How to use</a> ·
  <a href="https://namtpham.github.io/long_run/#whats-new">What's new</a> ·
  <a href="https://namtpham.github.io/long_run/#feedback">Feedback</a> ·
  <a href="https://buymeacoffee.com/namtpham">Buy me a coffee</a>
</p>

## What it is

Long Run Tool connects to an embedded Linux device's **serial console**, keeps the complete log of
every session and watches the device while it runs - for hours or days, several devices at once.

- **One tab per device**, and an **All devices** tab to see them all at a glance.
- **Auto login** as root (or another user) with the passwords you saved; the device's **model and IP** are found by themselves.
- **Memory and CPU of every process**, **live charts**, **crashes and other big issues**, **memory leak detection**.
- **Highlights, quick filter, search, blacklist / whitelist** with plain text or patterns - and a **pattern suggested** from a few example lines.
- The log in **any browser** on your network or **over TCP**, with commands typed from there if you allow it.
- **Test cases**, a **report** for every session, **shortcut commands and buttons**, **Change IP**, **pinned lines**.
- Updates itself (Help > Check for updates > Update now); Help > Tutorial (F1) shows every feature.

## Get it

1. Download it from the [latest release](https://github.com/namtpham/long_run/releases/latest):
   the `.zip` for Windows, the `.tar.gz` for Linux.
2. Unpack it anywhere you can write to (not Program Files) and start `Long Run Tool.exe`
   (Linux: `Long Run Tool`; `install.sh` adds it to the applications menu).
3. Click your device's port, then add its root password once (the yellow note above the log shows where).

Windows may say "Windows protected your PC" for a new app: click **More info > Run anyway**.

## Feedback

Questions, ideas and bug reports: use the [form on the home page](https://namtpham.github.io/long_run/#feedback)
(no account needed) or [open an issue](https://github.com/namtpham/long_run/issues/new).

---

This repository holds the app's home page and its releases (the app's source code is not public).
`versions.json` lists the versions for the app's update check; `tutorial.json` and `media/tutorial/`
are the app's Help > Tutorial.

Made by [Pham Thanh Nam](https://namtpham.github.io/). Like it? [Buy me a coffee](https://buymeacoffee.com/namtpham).
