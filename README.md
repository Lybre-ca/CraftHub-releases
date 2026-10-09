# Craft Hub

Install, update and remove the [ArtCraft Crafting Apps](https://getartcraft.com/apps) (PhotoCraft,
EffectCraft, FilmCraft, …) on your Mac or Windows PC. In English and French.

This repository only hosts Craft Hub's releases. Craft Hub is an independent app by Lybre, not made by ArtCraft.

## Install on a Mac

1. Download `CraftHub-<version>.dmg` from the latest [release](../../releases/latest) and open it.
2. Drag **Craft Hub** onto the **Applications** folder, then open it from Applications.
3. The first time, macOS blocks it because it isn't notarized by Apple. Open **System Settings ▸
   Privacy & Security**, find the message about Craft Hub, and click **Open Anyway**. You only do this once.

Craft Hub updates itself after that. Requires macOS 15 or later.

## Install on Windows

1. Open the latest [Craft Hub for Windows release](../../releases?q=windows) (tagged `windows-v…`) and
   download the zip for your PC: `CraftHub-<version>-windows-x64.zip` for most PCs, or
   `-windows-arm64.zip` for Windows on Arm (Snapdragon).
2. Unzip it and open `CraftHub.exe` in the `Craft Hub` folder.
3. The first time, Windows SmartScreen warns because Craft Hub isn't code-signed: click **More info**,
   then **Run anyway**.
4. In **Settings**, click **Install Craft Hub**. It moves to your user folder, with a Start menu
   shortcut, and updates itself after that.

Each app can be installed **portable** (just for you, with no administrator permission, updated in the
background) or with **ArtCraft's installer** (.msi, for everyone on the PC; Windows asks for
administrator permission each time). Choose in Settings. Requires Windows 10 or 11.

## What it installs

Only ArtCraft's official builds, straight from ArtCraft's GitHub releases. Before anything is installed,
each download must match the checksum ArtCraft publishes, and the app must carry ArtCraft's signature:
their Apple Developer ID and Apple's notarization on a Mac, their Windows code signature on Windows.

Craft Hub's own updates are verified too: each release's checksums are signed with Lybre's Ed25519 key
(one for the Mac releases, another for the Windows ones), and Craft Hub only installs a release that
carries that signature.
