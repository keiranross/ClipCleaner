# ClipCleaner

Scam With Your Friends records your calls (your voice included) to `Documents\Scam With Your Friends\Videos` and never cleans them up. ClipCleaner deletes them automatically by the rule you choose, for privacy, disk space, or both.

**Requires [ScamLoader](https://github.com/keiranross/ScamLoader) 1.0.0 or newer.** ScamLoader is not included.

## Download

**[Download ClipCleaner 1.0.0](https://github.com/keiranross/ClipCleaner/releases/download/v1.0.0/ClipCleaner-1.0.0.zip)**, or see [Releases](https://github.com/keiranross/ClipCleaner/releases).

SHA-256 of `ClipCleaner-1.0.0.zip`: `deea7fbb2fafdd49ef17ed46d358188bf8b9ea81a6f9eb57d5187107cdcae182`

## Rules

- **Off**: nothing is deleted (default)
- **By age**: delete clips older than 1 hour to 1 month
- **Keep newest**: keep only the newest 3 to 50 clips
- **By folder size**: delete the oldest once the folder passes 250 MB to 5 GB
- **When game closes**: delete all clips on quit
- **Delete right after recording (strict privacy)**: each new recording is deleted a few seconds after it finishes, and existing clips go when the game closes or starts

Changing a setting never deletes anything by itself. Clips from your current session are kept until you quit, so the end-of-day boss review still works. Deleted clips go to the Recycle Bin by default; Permanent delete and strict privacy mode ask you to confirm first.

Heads-up: "When game closes" and strict privacy mode empty the main menu replays, the BanditCam gallery and the breakroom TV. Strict mode also breaks the end-of-day boss review.

## Install

1. Install ScamLoader first: if the game's main menu shows a **MODS** button, you have it.
2. Open the game folder (Steam → right-click the game → **Manage** → **Browse local files**), then `ScamLoader\Mods\`.
3. Copy the `ClipCleaner` folder from the zip in there, so you get `ScamLoader\Mods\ClipCleaner\ClipCleaner.dll`.
4. Start the game, click **MODS**, and pick a rule under **CLIPCLEANER**. It starts Off.

## Uninstall

Delete the `ScamLoader\Mods\ClipCleaner\` folder.

## License

Copyright (c) 2026 KeiranR. All rights reserved. Personal use only: **please don't re-upload these files or send them to others** — link to this page instead. See [LICENSE](LICENSE).
