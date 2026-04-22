# VS Code Setup

This directory contains a shared `settings.json` for VS Code and an `install.sh` script to install the required extensions.

## Files

- `settings.json`: VS Code user settings in JSONC format.
- `install.sh`: Installs the extensions used by the settings file.

## Setup Steps

1. Change into this directory:

```bash
cd path/to/vs-code-settings-json
```

2. Copy the settings file into the macOS VS Code user settings location:

```bash
cp ./settings.json "$HOME/Library/Application Support/Code/User/settings.json"
```

3. Make the installer executable:

```bash
chmod +x ./install.sh
```

4. Install the required extensions:

```bash
./install.sh
```

## Installed Extensions

- `akamud.vscode-theme-onedark`
- `esbenp.prettier-vscode`
- `PKief.material-icon-theme`
- `hashicorp.terraform`
