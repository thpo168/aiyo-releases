# AIYO downloads

Release files for the AIYO command-line tool and VS Code extension. Source is not in this repository.

## Install the CLI

Windows (PowerShell):

    irm https://github.com/thpo168/aiyo-releases/releases/latest/download/install.ps1 | iex

Linux and macOS:

    curl -fsSL https://github.com/thpo168/aiyo-releases/releases/latest/download/install.sh | sh

Then open a new terminal and run `aiyo`. Run the same line again to upgrade.

## By hand

Each release carries `aiyo-<version>-<platform>.tar.gz` (`.zip` on Windows), the VS Code extension
`aiyo-<version>-<platform>.vsix`, and `SHA256SUMS.txt`. Unpack the archive, put the folder on PATH,
run `aiyo`; `README.txt` inside has the steps, `SECURITY.md` says what the CLI sends to the server and
what it never sends.

Platforms: win32-x64, linux-x64, linux-arm64, darwin-x64 (Intel Mac), darwin-arm64 (Apple Silicon).
