# Built-in features for sky-captain-os

Purpose: flight simulation

1. **organize project files** — run sky-captain-os-workspace. It creates ~/Documents/sky-captain-os-workspace/ with Inbox, Projects, Archive folders.
2. **draft a session plan** — run sky-captain-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/sky-captain-os-session-plans/.
3. **check task readiness** — run sky-captain-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/sky-captain-os-workspace features/sky-captain-os-plan features/sky-captain-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for flight simulation:

1. **FlightGear** — org.flightgear.FlightGear
2. **Heroic Games Launcher** — com.heroicgameslauncher.hgl
3. **Lutris** — net.lutris.Lutris

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
