# ContextScreen

ContextScreen is a local-first screen timeline for Apple Silicon Macs. It
records what was on screen, what was said, and where the Mac was, and keeps
that archive searchable on the machine unless you turn cloud backup on.

## Install

1. Download the latest `.dmg` from [Releases](https://github.com/bobdethird/contextscreen/releases/latest).
2. Open it and drag **ContextScreen** into Applications.
3. Open ContextScreen from Applications.
4. Grant **Screen & System Audio Recording**, then relaunch when asked.
5. Sign in with Google. That creates your account and turns on hosted speech.
6. Choose whether recordings also upload for backup.

## Requirements

- Apple Silicon Mac
- macOS 15 or later

## What it records

Screen samples, OCR text, app and window titles, system and microphone audio
(transcribed after you sign in), and periodic location fixes. Private and
incognito windows are recorded. Pause with **Option-Command-P** before
anything should stay off the archive.

Hold both Command keys together to open the timeline.

The source repository is private. This repo is the public download.
