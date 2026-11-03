# Garries Anti DDC Scammer 3.4.5

Public edition for Horizon Roleplay funders. Installing the mod does not grant funder status; access is managed by the crew.

[Download the public ZIP](https://github.com/Garries420/Garries-Anti-DDC-Scammer/releases/download/v3.4.5/Anti-DDC-Scammer-public-v3.4.5.zip) · [Release notes](https://github.com/Garries420/Garries-Anti-DDC-Scammer/releases/tag/v3.4.5)

## Installation

1. Close GTA San Andreas.
2. Open your GTA folder containing gta_sa.exe.
3. Extract the release ZIP there, merging moonloader and replacing the mod files.
4. Keep your existing configuration and start SA-MP.

Existing full-release installations update automatically when the mod next starts. The signed update reloads only Anti DDC Scammer and preserves configuration. Use the complete ZIP for a new installation. Older local test builds have automatic updates disabled.

## Requirements

GTA San Andreas with SA-MP; an ASI loader, CLEO 4, MoonLoader 0.26+, compatible SAMPFUNCS, the Microsoft DirectX 9 end-user runtime, and the MoonLoader libraries mimgui, SAMP.Lua, effil and dkjson.

## Commands

Command names can be changed under Shortcuts. These are the defaults:

| Command | Purpose |
| --- | --- |
| /ddcreload | Reload only Anti DDC Scammer. |
| /ddc [playerid/partofname] [amount] | Nearby hand-cash payment. |
| /wddc [playerid/partofname] [amount] | Bank wire payment. |
| /ddcedit | Settings, commands and access check. |
| /pddc | Toggle cooldown checks. |
| /ddclogs | Personal local payment console, recipient-name search and period filters. |
| /ddcsetpay [amount] | Set the Aim and pay amount; no amount shows usage and current value. |

Payments accept $5,000-$30,000, including shortcuts such as 5k, 10k and 30k. Cooldown warnings identify the previous funder and amount before offering a 30-second repeat confirmation. Aim and pay is disabled with no assigned button by default; enable and bind it in Shortcuts. Local logs start fresh on this installation; Clear all affects only your PC.

Overview has separate saved Mute mine and Mute others controls for crew radio. Mute mine stops automatic announcements; Mute others hides only other senders' matching DDC announcements locally. Your own messages and ordinary crew chat remain visible. Payment syncing and Discord logging continue. The payment console supports full/partial recipient names, case-insensitive matching and spaces/underscores. Access/update errors automatically produce a diagnostic report with Windows version, request timing and proxy flags, without credentials or payment history.

The ZIP's README.txt contains installation instructions and requirements.
