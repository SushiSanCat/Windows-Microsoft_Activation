# Windows & Microsoft Activation Scripts

<div align="center">

[![Windows 11 Logo](./assets/Windows_11_Logo.png)](https://www.microsoft.com/windows)


<p align="center"><img src="https://massgrave.dev/img/logo_small.png" alt="MAS Logo"></p>


[![Windows 10 Logo](./assets/Windows_10_Logo.png)](https://www.microsoft.com/windows)



**All-In-One Open-source Windows and Office activator featuring HWID, Ohook, TSforge, and Online KMS activation methods, along with advanced troubleshooting.**

</div>

## 📋 Supported Versions

- Windows 11 (All editions)
- Windows 10 (All editions)
- Windows 8.1 (All editions)
- Windows 8 (All editions)
- Windows 7 (Enterprise, Enterprise LTSB/LTSC, Education)
- Office 2010, 2013, 2016, 2019, 2021, 2024 (All editions)

## ⚠️ Important Warning

> [!CAUTION]
> This project is intended **strictly for educational purposes only**. Using these scripts to activate unlicensed copies of Windows or Office is illegal and violates Microsoft's End User License Agreement (EULA). We do not condone piracy. The developers of these scripts are not responsible for any misuse.

## 🔧 Activation Methods

### Method 1: PowerShell Script (Recommended)

> [!NOTE]
> This method works best on Windows 8.1, 10, and 11.

1. Click the **Start Menu**, type `PowerShell`, right-click on "Windows PowerShell" and select "Run as administrator"
2. Copy and paste the code below and press **Enter**:
   ```powershell
   irm https://get.activated.win | iex
   ```
   If the above is blocked (by ISP/DNS), try this (requires updated Windows 10 or 11):
   ```powershell
   iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)
   ```
3. In the menu that appears, select one of the **green-labeled** options
4. Follow the on-screen instructions and restart your computer when prompted

### Method 2: Traditional Batch File

1. Download the activation script:
   * [**MAS_AIO.cmd**](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?path=/MAS/All-In-One-Version-KL/MAS_AIO.cmd&download=true) (Direct link)
   * [**MAS_AIO.zip**](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?$format=zip) (Alternative if blocked by browser)
2. Right-click on the downloaded file and select "Run as administrator"
3. Select one of the green-labeled options from the menu
4. Follow the on-screen instructions and restart your computer when prompted

### Method 3: Manual Command Line Activation

> [!WARNING]
> This method requires manual entry of commands and is only recommended for advanced users.

1. Run Command Prompt as Administrator
2. Enter the following commands one by one:

   For Windows 10 Pro:
   ```cmd
   slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
   slmgr /skms kms8.msguides.com
   slmgr /ato
   slmgr /xpr
   ```

   For other versions, use the appropriate product key from the list below.
## 💻 Product Keys Reference

> [!NOTE]
> These keys are publicly available from Microsoft and are used for KMS activation. They only work with KMS activation methods.

### Windows 10/11 Keys
```
Home: TX9XD-98N7V-6WMQ6-BX7FG-H8Q99
Home N: 3KHY7-WNT83-DGQKR-F7HPR-844BM
Home Single Language: 7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH
Home Country Specific: PVMJN-6DFY6-9CCP6-7BKTT-D3WVR
Professional: W269N-WFGWX-YVC9B-4J6C9-T83GX
Professional N: MH37W-N47XK-V7XM9-C7227-GCQG9
Education: NW6C2-QMPVW-D7KKK-3GKT6-VCFB2
Education N: 2WH4N-8QGBV-H22JP-CT43Q-MDWWJ
Enterprise: NPPR9-FWDCX-D2C8J-H872K-2YT43
Enterprise N: DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4
Enterprise 2015 LTSB: WNMTR-4C88C-JK8YV-HQ7T2-76DF9
Enterprise 2015 LTSB N: 2F77B-TNFGY-69QQF-B8YKP-D69TJ
Enterprise 2016 LTSB: DCPHK-NFMTC-H88MJ-PFHPY-QJ4BJ
Enterprise 2016 LTSB N: QFFDN-GRT3P-VKWWX-X7T3R-8B639
```

### Windows 8.1 Keys
```
Core: M9Q9P-WNJJT-6PXPY-DWXTPBDRBPTHC
Core N: 7B9N3D6CM-2DKVF-448X9-7X347-6VRF4
Core Single Language: BB6NG-PQ82V-VRDPW-8XVD2-C8P2T
Core Country Specific: NCTT7-2RGK8-WMHRF-RY7YQ-JTXG3
Professional: GCRJD-8NW9H-F2CDX-CCM8D-9D6T9
Professional N: HMCNV-VVBFX-7HMBH-CTY9B-B4FXY
```


## 🛡️ Safety Guidelines

> [!IMPORTANT]
> - Always disconnect from the Internet during activation to prevent Microsoft from blocking your activation method
> - Disable Windows Defender or add exceptions before running activation scripts
> - Run scripts as Administrator to avoid permission issues
> - If activation fails, run the troubleshooter included in MAS before trying again

## 🔍 Troubleshooting

If you encounter issues:
1. Run the `Troubleshoot.cmd` file included in this repository
2. Visit the [official troubleshooting page](https://massgrave.dev/troubleshoot)
3. Join our [Discord community](https://discord.gg/j2yFsV5ZVC) for support
4. Create an issue on our [GitHub repository](https://github.com/massgravel/Microsoft-Activation-Scripts/issues)

## 💡 Tips

> [!TIP]
> - Some ISPs/DNS providers block access to our domains. You can bypass this by enabling [DNS-over-HTTPS (DoH)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/) in your browser
> - The `irm` command in PowerShell downloads a script from a specified URL, and the `iex` command executes it
> - Always double-check the URL before executing the command and verify the source is trustworthy when manually downloading files
> - Be cautious of third parties spreading malware disguised as MAS by altering the URL in the PowerShell command

## 📞 Community & Support

<div align="center">

### Homepage - [https://massgrave.dev/](https://massgrave.dev/)

[![Discord](https://massgrave.dev/img/logo_discord.png)](https://discord.gg/j2yFsV5ZVC)
[![Reddit](https://massgrave.dev/img/logo_reddit.png)](https://www.reddit.com/r/MAS_Activator)
[![Bluesky](https://massgrave.dev/img/logo_bluesky.png)](https://bsky.app/profile/massgrave.dev)
[![Twitter/X](https://massgrave.dev/img/logo_x.png)](https://twitter.com/massgravel)
[![GitHub](https://massgrave.dev/img/logo_github.png)](https://github.com/massgravel/Microsoft-Activation-Scripts)
[![Azure DevOps](https://massgrave.dev/img/logo_azuredevops.png)](https://dev.azure.com/massgrave/_git/Microsoft-Activation-Scripts)
[![Gitea](https://massgrave.dev/img/logo_gitea.png)](https://git.activated.win/Microsoft-Activation-Scripts)

</div>

## 📄 License & Disclaimer

This project is provided for educational purposes only. The Microsoft Activation Scripts team is not responsible for any consequences resulting from the use of these tools. Use at your own risk.

Microsoft and Windows are registered trademarks of Microsoft Corporation. This project is not affiliated with, sponsored by, or endorsed by Microsoft Corporation.

**Latest Version**: 3.9  
**Release Date**: 19-Nov-2025
