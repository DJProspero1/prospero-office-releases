# Prospero Office releases

Installers and the auto-update feed for Prospero Office (a fork of T3 Code).

## Install on Windows

Open **PowerShell** (Start menu, type `powershell`) and paste:

```powershell
irm https://github.com/DJProspero1/prospero-office-releases/releases/latest/download/install.ps1 | iex
```

It downloads the latest installer from this page, checks its SHA-512 against `latest.yml`,
installs Prospero Office for your Windows user (no admin rights) and starts it. Run it again any
time to repair or update; an up-to-date install is just started. Installed apps also update
themselves.

**Or download the installer yourself:** `Prospero-Office-<version>-x64.exe` from the
[latest release](https://github.com/DJProspero1/prospero-office-releases/releases/latest). The installer is not code-signed yet,
so Windows shows *"Windows protected your PC"*: click **More info**, then **Run anyway**.

64-bit Intel/AMD (x64) Windows 10 or 11 only. If Smart App Control is on, Windows blocks unsigned
apps however they are downloaded.

Linux servers: `po update` updates an installed Prospero Office server.
