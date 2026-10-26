# Video Studio for Mac

Turn a raw talking-head clip into a finished vertical video for Reels, Shorts and TikTok. Video Studio cuts the
pauses and retakes, adds captions, picks one of 16 reel formats and its effects, and exports a ready-to-post MP4.

It is free. It runs on your Mac, and your footage stays on your Mac.

## Download

**[Download Video Studio for Mac (Apple Silicon)](https://github.com/agilekaur/video-studio-app/releases/latest/download/Video-Studio-arm64.dmg)**

About 420 MB. You need:

* A Mac with Apple Silicon (M1 or newer). Intel Macs are not supported yet.
* macOS 13 or newer
* About 3 GB of free disk space, plus 1 to 3 GB for each project
* An internet connection the first time you transcribe a clip or use the speaker cutout, to download those models

Nothing else to install. You don't need Terminal, Homebrew or Claude Code.

## Install

1. Open the downloaded `Video-Studio-arm64.dmg`.
2. Drag **Video Studio** onto the **Applications** folder.
3. Open Video Studio from Applications or Launchpad.

**The first time you open it,** macOS says it can't check the app, because this early version is not yet signed with
an Apple developer certificate. To open it:

1. Click **Done** in that message.
2. Open **System Settings → Privacy & Security** and scroll down to Security.
3. Next to "Video Studio was blocked", click **Open Anyway**, enter your Mac password, then click **Open**.

On macOS 13 or 14 you can instead right-click Video Studio in Applications, choose **Open**, then click **Open**.

You only do this once. The first launch then takes about a minute to set itself up.

## Your first video

1. Click **New** and drop in your clip, or drag the clip onto the Video Studio icon in the Dock.
2. Choose a format from the **Format** menu at the top, or leave it on none for clean captions.
3. Check the transcript, fix any word with a double-click, then click **Render**.

Your projects are saved in `Movies/VideoStudio` in your home folder.

## Updating

Download the latest version from the link above and drag it into Applications again, choosing **Replace**. Your
projects and brand kits are kept.

## Problems

Choose **Help → Backend Log** in the app and send the log with a short note of what happened.

## Licence

Video Studio is free to use. The videos you make with it are yours. The app includes open-source tools under their own
licences, listed in [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).

If your company has more than three people, Remotion (one of the tools inside) needs a paid company licence. See
[remotion.dev/license](https://www.remotion.dev/license).

© 2026 AgileKaur
