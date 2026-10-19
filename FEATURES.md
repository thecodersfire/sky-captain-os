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

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for flight simulation:

1. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)
2. **GNOME Weather** — check local weather conditions (org.gnome.Weather)
3. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
4. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
5. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
6. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
7. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
8. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
9. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
10. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
