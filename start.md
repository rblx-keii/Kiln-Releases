---
title: Get started
permalink: /start.html
---

# Get started

Kiln runs on Windows 10 and 11 and works with Affinity 3.3. You'll also need Roblox Studio.

## Install

1. **Download** the latest `Kiln-<version>.zip` from [Releases](https://github.com/rblx-keii/Kiln-Releases/releases/latest).
2. **Unzip** the whole Kiln folder somewhere you can write to, for example `Documents\Kiln`. Don't run it from
   inside the zip, and don't put it in Program Files or in `Desktop\Kiln` (that folder is for your exports).
3. **Run Kiln.exe.** Windows may show "Windows protected your PC" because this first version isn't code-signed
   yet. Click **More info**, then **Run anyway**. You only need to do this once per version.

## Setup

Kiln opens a Setup window that ticks each step off as it happens:

1. **Affinity MCP.** In Affinity, turn on Settings > Model Context Protocol > Enable MCP server.
2. **Bridge.** Kiln links to Affinity by itself once the MCP server is on.
3. **Kiln plugin.** Get the [Kiln plugin](https://create.roblox.com/store/asset/111742931087316) from the
   Creator Store. It's a cloud plugin, so Studio keeps it up to date for you.
4. **Studio connected.** Open the Kiln plugin in Studio and it connects to Kiln.
5. **First export.** Export a screen from Kiln. The plugin builds it in Studio straight away.

## Upload images

Images have to be on Roblox before your UI can show them in a game. On the Pipeline page, click
**Sign in with Roblox** and approve Kiln in your browser. Kiln then uploads your exported images to your account
when you publish, and uses their ids in the build.

## Updates

Kiln checks this site for a new version and asks before updating. Your settings and exports are kept.

## Where Kiln keeps things

| What | Where |
|---|---|
| Program | the folder you unzipped |
| Settings, cache, logs | `%APPDATA%\Kiln` |
| Exports, backups | `Desktop\Kiln` |
| Roblox sign-in or API key | Windows Credential Manager (entry "Kiln") |

## Uninstall

1. Delete the Kiln folder.
2. Delete `%APPDATA%\Kiln`.
3. Optional: delete `Desktop\Kiln` (your exports and backups).
4. Optional: remove the "Kiln" entry from Windows Credential Manager.
5. Optional: in Studio, uninstall the Kiln plugin (Plugins > Manage Plugins).

## Help

Found a bug? In Kiln, choose **Help > Copy Diagnostics** and paste it into an email to
[official.keii@outlook.com](mailto:official.keii@outlook.com).
