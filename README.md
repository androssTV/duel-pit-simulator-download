# Duel Pit Simulator

Classic UO-style spell dueling in 1v1 and 2v2 arenas. Practice against six distinct
CPU personalities, watch CPU battles, or host a game and invite friends.

## Download Alpha 0.3.1

**[Download Alpha 0.3.1 for Windows](https://github.com/androssTV/duel-pit-simulator-download/releases/download/v0.3.1-alpha/DuelPit-Windows-0.3.1-alpha.zip)**

[Release notes and checksum](https://github.com/androssTV/duel-pit-simulator-download/releases/tag/v0.3.1-alpha)

1. Download and extract the entire ZIP, then run **DuelPit.exe**.
2. Open **Character**, choose your name and outfit, and **Save character**.
3. Check **Hotkeys**, then choose **Practice** or **Online**.

Windows x64 required. Keep the included folders beside the executable. No Godot,
Node.js or developer setup is needed. This is an unsigned alpha testing build.

## Play

**Practice:** choose 1v1 or 2v2, pick CPU styles and ranks,
then press **Start match**. Every fighter uses equal combat stats.

**Spectate:** select a CPU for Player 1 to watch a full CPU match. Enable
**Auto rematch** for repeated rounds. **Stop match** ends the CPU round; **Leave match** returns to the main menu.
Enable **Random CPUs** to shuffle all slots at Grandmaster, including all four in 2v2.

**Online:** join a public lobby, paste a friend's private invite, or select
**Create lobby** to host your own public or private game. Internet discovery is
built in. The host's computer runs the match and must keep its client open.
Use **Your room** to select teams, ready up and start. Everyone needs Alpha 0.3.1;
older clients cannot join its protocol 7 hosts.

## New in Alpha 0.3.1

- Fresh profiles start as **Avatar**, dressed in a blue robe and boots.
- Remappable movement with arrow-key defaults; right-click movement remains available.
- Fixed 2v2 spectator setup, four-slot random matches, and session win/loss records.
- Clearer main-menu navigation, a solid menu background, and a frame that fills the window.
- Stable bottom controls and cleaner spectator descriptions.
- **Start / Stop match** controls. Stopping a human match forfeits your team.
- Improved CPU pressure, recovery, Poison upkeep and support-spell cancellation.

Your existing character settings and hotkeys remain saved. Spell defaults are still F1-F11;
check **Hotkeys** or import a portable backup before playing.

## Six opponents, eight ranks

- **The Duelist:** conventional combos and fair play.
- **The Lich:** reckless large-spell burst.
- **The Wasp:** close pursuit, fists, Poison and Magic Arrow.
- **The Viper:** conserve, find an opening, then commit.
- **The Scholar:** study pressure and reconsider failed plans.
- **The Roach:** survival, mana economy, and punishing exhausted opponents.

Choose **Neophyte, Novice, Apprentice, Journeyman, Expert, Adept, Master, or
Grandmaster**. Ranks change decision-making, reaction time and execution, not
combat skills. Styles have different strengths; the ranks are not human ratings.
These replace the previous CPU lineup, including John.

The public opponents use frozen decision rules and do not train or update during
play. Axiom, neural weights and simulation/training tools are not distributed.

## Feedback

After a human wins a 1v1 against an archetype, an optional prompt offers to send
androssTV the match log for analysis. Nothing uploads unless you choose **Send**.
The log includes your name, settings, both fighters' actions, combat events,
random rolls, and CPU identity/rank/version. Contact information is optional.
Reports go to a private inbox and do not automatically change any CPU.
Losses, team games and CPU-only matches do not show the offer.

For other bugs, open an issue with your version, format, CPU settings and steps
to reproduce. Keep private invites, room passcodes and personal information out
of public reports.

Sudden death defaults to five minutes and disables healing and new Cure casts.
The game remains in alpha: timing edge cases and presentation differences are
still being refined. Online play does not yet include movement prediction or
lag compensation. Extract new versions into separate folders.

## Support

Enjoying the duels? [Buy androssTV a coffee](https://buymeacoffee.com/androsstv).

## About this repository

This repository contains packaged downloads and release notes. Development
source and Git history remain in a separate private repository. GitHub's
automatic "Source code" archives here contain only the public download-page
files; choose **DuelPit-Windows-0.3.1-alpha.zip** to play.

Third-party components and art retain their respective ownership and licenses.
Applicable notices are included with the download.
