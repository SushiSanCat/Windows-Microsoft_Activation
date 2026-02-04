# Windows & Microsoft Activation Scripts

<div align="center">

[![Windows 11 Logo](./assets/Windows_11_Logo.png)](https://www.microsoft.com/windows)

<p align="center"><img src="https://massgrave.dev/img/logo_small.png" alt="MAS Logo"></p>

[![Windows 10 Logo](./assets/Windows_10_Logo.png)](https://www.microsoft.com/windows)

**All‑In‑One open‑source Windows and Office activator featuring HWID, Ohook, TSforge, and Online KMS activation methods, with advanced troubleshooting.**

</div>

## 📋 Supported Versions

- Windows 11 (All editions)
- Windows 10 (All editions)
- Windows 8.1 (All editions)
- Windows 8 (All editions)
- Windows 7 (Enterprise, Enterprise LTSB/LTSC, Education)
- Office 2010, 2013, 2016, 2019, 2021, 2024 (All editions)
- **Extended Security Updates (ESU)** where applicable

## ⚠️ Important Warning

> [!CAUTION]
> This project is intended **strictly for educational purposes only**. Using these scripts to activate unlicensed copies of Windows or Office may violate Microsoft’s End User License Agreement (EULA). We do not condone piracy. The developers are not responsible for misuse.

## 🔧 Activation Methods

### Method 1: PowerShell ❤️ (Recommended)

> [!NOTE]
> Works best on **Windows 8.1, 10, and 11**.

1. Click the **Start Menu**, type `PowerShell`, open it (run as Administrator if prompted).
2. Copy and paste the command below and press **Enter**:
   ```powershell
   irm https://get.activated.win | iex
   ```
   If the above is blocked (by ISP/DNS), try this (requires updated Windows 10 or 11):
   ```powershell
   iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)
   ```
3. In the menu that appears, select one of the **green‑labeled** options.

### Method 2: Traditional (Windows Vista and later)

1. Download the script:
   * [**MAS_AIO.cmd**](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?path=/MAS/All-In-One-Version-KL/MAS_AIO.cmd&download=true) (Direct)
   * [**MAS_AIO.zip**](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?$format=zip) (If the direct script is blocked)
2. Run `MAS_AIO.cmd`.
3. Choose one of the **green‑labeled** options.

### Method 3: Manual Command Line (Advanced)

> [!WARNING]
> Requires manual command entry and is intended for advanced users.

*(Content retained as in the modified version.)*

## 💻 Product Keys Reference

> [!NOTE]
> Public KMS client setup keys provided by Microsoft. These only work with KMS‑based methods.

*(Content retained as in the modified version.)*

## 🛡️ Safety Guidelines

> [!IMPORTANT]
> - Always double‑check URLs before executing commands.
> - Verify sources when manually downloading files.
> - Be cautious of third parties spreading malware by altering URLs.

## 🔍 Troubleshooting

1. Use the built‑in troubleshooter included with MAS.
2. Visit the [official troubleshooting page](https://massgrave.dev/troubleshoot).
3. Open an issue on [GitHub](https://github.com/massgravel/Microsoft-Activation-Scripts/issues).

## 💡 Tips

> [!TIP]
> - Some ISPs/DNS providers block access to MAS domains. You can bypass this by enabling [DNS‑over‑HTTPS (DoH)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/) in your browser.
> - In PowerShell, `irm` downloads a script from a URL and `iex` executes it.

## 📞 Community & Support

<div align="center">

### Homepage — https://massgrave.dev/

[![Discord](https://massgrave.dev/img/logo_discord.png)](https://discord.gg/j2yFsV5ZVC)
[![Reddit](https://massgrave.dev/img/logo_reddit.png)](https://www.reddit.com/r/MAS_Activator)
[![Bluesky](https://massgrave.dev/img/logo_bluesky.png)](https://bsky.app/profile/massgrave.dev)
[![Twitter/X](https://massgrave.dev/img/logo_x.png)](https://twitter.com/massgravel)
[![GitHub](https://massgrave.dev/img/logo_github.png)](https://github.com/massgravel/Microsoft-Activation-Scripts)
[![Azure DevOps](https://massgrave.dev/img/logo_azuredevops.png)](https://dev.azure.com/massgrave/_git/Microsoft-Activation-Scripts)
[![Gitea](https://massgrave.dev/img/logo_gitea.png)](https://git.activated.win/Microsoft-Activation-Scripts)

</div>

## 📄 License & Disclaimer

Provided for educational purposes only. Use at your own risk. Not affiliated with Microsoft.

**Latest Version**: **3.10**  
**Release Date**: **28‑Jan‑2026**

