# Craft Hub

Install, update and remove the [ArtCraft Crafting Apps](https://getartcraft.com/apps) (PhotoCraft,
EffectCraft, FilmCraft, …) on your Mac. In English and French.

This repository only hosts Craft Hub's releases. Craft Hub is an independent app by Lybre, not made by ArtCraft.

## Install

1. Download `CraftHub-<version>.zip` from the latest [release](../../releases/latest) and unzip it.
2. Move **Craft Hub** to your Applications folder and open it.
3. The first time, macOS blocks it because it isn't notarized by Apple. Open **System Settings ▸
   Privacy & Security**, find the message about Craft Hub, and click **Open Anyway**. You only do this once.

Craft Hub updates itself after that.

## What it installs

Only ArtCraft's official builds, straight from ArtCraft's GitHub releases. Before anything is installed,
each download must match the checksum ArtCraft publishes, and the app must carry ArtCraft's Apple
Developer ID signature and Apple's notarization.

Craft Hub's own updates are verified too: each release's checksums are signed with Lybre's Ed25519 key,
and Craft Hub only installs a release that carries that signature.

Requires macOS 15 or later.
