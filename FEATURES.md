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

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
2. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
3. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
4. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
5. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
6. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
7. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
8. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
9. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
10. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
11. **QElectroTech** (org.qelectrotech.QElectroTech) — draw electrical schematics and wiring diagrams.
12. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
13. **Disk Usage Analyzer** (org.gnome.baobab) — find large files and manage storage.
14. **OBS Studio** (com.obsproject.Studio) — record or stream sessions.
15. **Flatseal** (com.github.tchx84.Flatseal) — review Flatpak app permissions.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **KStars** (org.kde.kstars) — plan sky observations and explore astronomy simulations.
2. **Marble** (org.kde.marble) — explore maps and a virtual globe for geographic context.
3. **KGeography** (org.kde.kgeography) — practice country, capital, and map recognition.
4. **KGeoTag** (org.kde.kgeotag) — add GPS coordinates to photos from a GPX track or map.
5. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
6. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
7. **KDevelop** (org.kde.kdevelop) — edit, navigate, build, and debug software projects.
8. **Kate** (org.kde.kate) — edit configuration, code, notes, and structured project files.
9. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
10. **Ark** (org.kde.ark) — open and create common project archive files.
11. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
12. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
13. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.
14. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.
15. **Konsole** (org.kde.konsole) — run shell commands and inspect development or system tasks.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.
