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

Downloading Misha doesn't give you access. Ask for an invite on [dumdummisha.ai](https://dumdummisha.ai). Misha checks the key on your Mac, with no network call, and checks it again each time it starts. Until a key is verified, nothing of Misha runs, and you see one of these:

- "Enter your invite key to use Misha." in the window, before you've pasted a key.
- "This invite key isn't valid. Paste the key from your invitation, or ask the person who invited you for a new one." in the window, for a key that doesn't verify.
- "Misha needs an invite. Open Misha and paste your invite key." in a Claude Code or OpenCode session that calls Misha's tools.

## Install

1. Open the ZIP, and move `Misha.app` to your Applications folder before you open it. Misha writes the app's location into Claude Code and OpenCode, so put it where it will stay.
2. Open Misha. The first time, macOS says that "Misha" is an app downloaded from the Internet and asks whether you're sure you want to open it. Click **Open**. Misha is signed with an Apple Developer ID and notarized by Apple, so after this it opens normally.
3. On **Get started**, paste your key into **Paste your invite key** and click **Activate**.
4. Follow [Get started](https://docs.dumdummisha.ai/start/get-started) to your clone's first answer.

## Updates

Misha updates itself from this repository's releases. It checks for a newer release when it starts and each time the Mac wakes, and downloads it in the background. When it's ready, the menu bar's Misha menu shows **Restart to update Misha**. Click it to restart once on the new version, or carry on: **Quit Misha** quits without reopening, and the update is installed the next time you open Misha.

After an update, a Claude Code or OpenCode session that was already open says "Misha was updated. Restart this Claude Code or OpenCode session." Restart it. Each update replaces the whole app, and there is no rollback: an older Misha refuses data a newer one has saved, with "Your Misha data was saved by a newer Misha. Install the latest Misha, then open it again." [Updates](https://docs.dumdummisha.ai/operate/manage#updates) has the details.

## Remove

Choose **Uninstall Misha…** in the menu bar's Misha menu. [Remove Misha](https://docs.dumdummisha.ai/operate/manage#remove) says what it removes and what it lists for you.

## Privacy and support

[Privacy and security](https://docs.dumdummisha.ai/privacy) says what data goes where. [Troubleshooting](https://docs.dumdummisha.ai/operate/troubleshooting) covers what to do when something goes wrong.
