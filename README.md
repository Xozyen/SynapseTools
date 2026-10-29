# SynapseTools — By StillBorn

Windows desktop macro editor for 4Classic. This distribution repository contains compiled downloads and documentation. Application source code is private.

## Installation

1. Download the Windows x64 ZIP from Releases.
2. Extract the entire archive into a writable folder. Do not run from inside the ZIP.
3. Run `SynapseTools.exe` and approve the Windows administrator prompt.
4. Run `VYTVORIT-ZASTUPCE.cmd` to create a desktop shortcut.

Select a class and profile in Launcher, check its bindings against your game, then enable the macro. The macro runs using its configured trigger and mode while the game is focused. F12 stops all macros. Ctrl + Alt + Space shows/hides the application; Ctrl + Alt + Backspace also works.

## Combo editor (1.2.1)

- Spell and movement timeline with preview playback and scrubbing. Preview sends no keyboard input.
- Select consecutive steps with Ctrl/Shift and group them into a named block with 1–20 repetitions.
- Copy and paste selected sections with independent settings.
- Pause and resume movement around a selected spell.
- Libraries for Archer, Warrior, Mage, Priest, Night Walker and Evocator, with available reference descriptions and icons.
- Local client spell names are linked only when their English name matches uniquely. Missing or ambiguous names retain their catalogue identity.
- The floating panel shows the currently executed step.

The timeline represents the first cycle and configured timings, not confirmation that the game accepted a cast. Reference spell timings may need adjustment in-game.

## Settings and updates

Languages: Czech, English and German. The UI and floating panel share the selected accent colour.

Before a manual update, close SynapseTools and back up the complete application directory plus `%LOCALAPPDATA%\SynapseTools-WPF`. Preserve your `Macros` folder and any custom macro directory. New versions should not replace your existing profiles with bundled defaults.

Automatic in-app downloading/installing of updates is not implemented in this version. Accounts, subscriptions, licensing enforcement and trials are not implemented.

## Diagnostics

Advanced settings can inspect local client skills and saved binding tables without modifying the game. The experimental screen preview captures the visible foreground game area; it does not confirm casts or cooldowns. Client injection is not implemented.

## Reports

When reporting a problem, include the app version, Windows version and reproduction steps. Do not attach account credentials, personal settings or unrelated logs.
