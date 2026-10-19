# Built-in features for green-thumb-os

Purpose: gardening

1. **prepare field and mapping files** — run green-thumb-os-workspace. It creates ~/Documents/green-thumb-os-workspace/ with Field Notes, Source Data, Map Exports folders.
2. **plan field work** — run green-thumb-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/green-thumb-os-session-plans/.
3. **check data and location readiness** — run green-thumb-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/green-thumb-os-workspace features/green-thumb-os-plan features/green-thumb-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for gardening:

1. **QGIS** — org.qgis.qgis
2. **GNOME Maps** — org.gnome.Maps
3. **Zotero** — org.zotero.Zotero

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for gardening:

1. **GNOME Weather** — check local weather conditions (org.gnome.Weather)
2. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
3. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
4. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
5. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
6. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
7. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
8. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
9. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
10. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
