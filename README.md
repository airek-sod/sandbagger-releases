# Sandbagger

Sandbagger is a **free** Windows app for EverQuest (Dalaya). It parses your
character log to show damage/DPS breakdowns, a live in-game overlay, a spell browser,
character/gear lookup, and customizable triggers.

## Download & install

1. Open the **[latest release](https://github.com/airek-sod/sandbagger-releases/releases/latest)**.
2. Download **`Sandbagger-win-Setup.exe`** and run it.
3. That's it -- the installer sets everything up and installs the required .NET 10 runtime
   automatically if you don't already have it. Sandbagger then keeps itself up to date.

Requires Windows 10 (1809+) or Windows 11, 64-bit.

> The installer isn't code-signed yet, so Windows SmartScreen may warn on first run --
> click **More info -> Run anyway**.

## Features

- **Combat Parser** -- parses your character log into fights with full DPS breakdowns:
  fight list, per-participant overview, per-verb damage stats, tanking/incoming damage,
  healing, and spell casts.
- **Live overlay** -- real-time in-game combat tracking as fights happen, no log replay needed.
- **Spell Browser** -- searchable database of every spell, with slot/class/effect details.
- **Character lookup** -- gear and stats lookup (paper-doll view) plus a Proc/Effect Checker.
- **Triggers** -- custom regex-based triggers with alerts, overlays, timers, and text-to-speech;
  import from GINA/EQLogParser or share trigger sets with guildmates.
- **Multi-character support** -- track several characters/log files at once from one sidebar.
- **Web/mobile companion** -- view the same fight data, spell browser, and character lookups
  from your phone or another PC over your LAN.
- **Dramatic Summary** -- optional narrated recap of a fight in one of several writing styles.

## Updates

Sandbagger checks for updates on startup and shows a banner when one is available. To
install it, open **Help -> Check for Updates** inside the app.

## License

Sandbagger is free to use. Please download it **only from this official repository** --
redistribution is not permitted. The full license and third-party open-source notices are
included with the app (LICENSE and THIRD-PARTY-NOTICES.md next to the executable).
