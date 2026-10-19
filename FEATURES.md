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
