<img src="https://docs.dumdummisha.ai/app-icon-512.png" alt="The Misha app icon" width="96" height="96">

# desktop-downloads

**Misha desktop builds and updates.**

Misha is a personal AI agent that runs on your Mac. The [documentation](https://docs.dumdummisha.ai) says what it does and how to set it up.

## Download

Download `Misha-<version>-darwin-arm64.zip` from [the latest release](https://github.com/dumdummisha/desktop-downloads/releases/latest). Each release lists the ZIP's SHA-256. To check your download, run this in Terminal and compare the result with the release:

```sh
shasum -a 256 Misha-<version>-darwin-arm64.zip
```

## Requirements

- A Mac with Apple silicon and macOS 13 or later.
- Chrome or Brave, version 140 or later, with Slack signed in.
- git.
- Claude Code or OpenCode, signed in. Misha runs on whichever one you have.
- An invite key.

## Access is invite-only

Downloading Misha doesn't give you access. Ask for an invite on [dumdummisha.ai](https://dumdummisha.ai). Misha checks the key on your Mac, with no network call, and nothing of Misha runs until a key is verified. [Activate your invite](https://docs.dumdummisha.ai/start/get-started#invite) covers a key that doesn't verify.

## Install

1. Open the ZIP, and move `Misha.app` to your Applications folder before you open it. Misha writes the app's location into Claude Code and OpenCode, so put it where it will stay.
2. Open Misha. The first time, macOS says that "Misha" is an app downloaded from the Internet and asks whether you're sure you want to open it. Click **Open**. Misha is signed with an Apple Developer ID and notarized by Apple, so after this it opens normally.
3. On **Get started**, paste your key into **Paste your invite key** and click **Activate**.
4. Follow [Get started](https://docs.dumdummisha.ai/start/get-started) to your clone's first answer.

## Updates

Misha updates itself from this repository's releases. It checks for a newer release when it starts and each time the Mac wakes, and downloads it in the background. When it's ready, the menu bar's Misha menu shows **Restart to update Misha**. Click it to restart once on the new version, or carry on: **Quit Misha** quits without reopening, and the update is installed the next time you open Misha.

After an update, restart any Claude Code or OpenCode session that was already open. Each update replaces the whole app, and there is no rollback. [Updates](https://docs.dumdummisha.ai/operate/manage#updates) has the details.

## Remove

Choose **Uninstall Misha…** in the menu bar's Misha menu. [Remove Misha](https://docs.dumdummisha.ai/operate/manage#remove) says what it removes and what it lists for you.

## Privacy and support

[Privacy and security](https://docs.dumdummisha.ai/privacy) says what data goes where, and the [terms of use](https://docs.dumdummisha.ai/terms) govern using Misha. [Troubleshooting](https://docs.dumdummisha.ai/operate/troubleshooting) covers what to do when something goes wrong.
