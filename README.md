# Windows 2000 Software Compatibility List

This is a list of software compatible with Windows 2000. This has been tested on a mix of a VM and actual hardware running Windows 2000 Service Pack 4, updated via Legacy Update.

Currently a work in progress. Contributions are welcome!

No AI was used in the making of this list.

# Programs

<details>
<summary>Windows 2000 Specific</summary>

| Program                                    | Description                                    | Works on Win2000 SP4 | Last Tested Working Version | Last Officially Supported Version   | Version Stopped Working             | Notes | Free? |                                    Open Source?                                     |
| ------------------------------------------ | ---------------------------------------------- | :------------------: | --------------------------- | ----------------------------------- | ----------------------------------- | ----- | :---: | :---------------------------------------------------------------------------------: |
| [Legacy Update](https://legacyupdate.net/) | Get back online, activate, and install updates |          ✅           | Current Version             | N/A, current version supports Win2K | N/A, current version supports Win2K |       |   ✅   | [✅ - Apache-2.0](https://github.com/LegacyUpdate/LegacyUpdate/blob/main/LICENSE.md) |

</details>

<details>
<summary>Dependencies</summary>

| Program                                                                                                           | Description | Works on Win2000 SP4 | Last Tested Working Version | Last Officially Supported Version | Version Stopped Working | Notes | Free? | Open Source? |
| ----------------------------------------------------------------------------------------------------------------- | ----------- | :------------------: | --------------------------- | --------------------------------- | ----------------------- | ----- | :---: | :----------: |
| [DirectX 9](https://archive.org/details/microsoft-direct-x-9.0c-redistributable-for-windows-95-98-me-2000-and-xp) |             |                      |                             |                                   |                         |       |       |              |
| [Media Encoder 9](https://archive.org/details/WindowsMediaEncoder9Series_2003)                                    |             |                      |                             |                                   |                         |       |       |              |
| [GDI+](https://web.archive.org/web/20170906231543/http://www.microsoft.com/en-us/download/details.aspx?id=18909)  |             |                      |                             |                                   |                         |       |       |              |
| .NET Framework 2.0                                                                                                |             |                      |                             |                                   |                         |       |       |              |

</details>

<details>
<summary>Security</summary>

| Program                                        | Description      | Works on Win2000 SP4 | Last Tested Working Version                                                                                                                                                                                                                           | Last Officially Supported Version                                                                                                                                                                           | Version Stopped Working                                                    | Notes                    | Free? |                      Open Source?                      |
| ---------------------------------------------- | ---------------- | :------------------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | ------------------------ | :---: | :----------------------------------------------------: |
| [KeePass 1.x](https://keepass.info/index.html) | Password Manager |          ✅           | [v1.43 (.zip portable)](https://sourceforge.net/projects/keepass/files/KeePass%201.x/1.43/KeePass-1.43.zip/download)<br/><br/>[v1.38 (.exe setup)](https://sourceforge.net/projects/keepass/files/KeePass%201.x/1.38/KeePass-1.38-Setup.exe/download) | [v1.33](https://sourceforge.net/projects/keepass/files/KeePass%201.x/1.33/KeePass-1.33-Setup.exe/download)<br/><br/>[Source](https://web.archive.org/web/20170907191227/https://keepass.info/download.html) | N/A, current version supports Win2K (portable)<br/><br/>v1.39 (.exe setup) | Needs GDI+               |   ✅   | [✅ - GPLv2](https://keepass.info/help/v1/license.html) |
| [KeePass 2.x](https://keepass.info/index.html) | Password manager |          ✅           | [v2.58 (.zip portable)](https://sourceforge.net/projects/keepass/files/KeePass%202.x/2.58/KeePass-2.58.zip/download)<br/><br/>[v2.46 (.exe setup)](https://sourceforge.net/projects/keepass/files/KeePass%202.x/2.46/KeePass-2.46-Setup.exe/download) | [v2.36](https://sourceforge.net/projects/keepass/files/KeePass%202.x/2.36/KeePass-2.36-Setup.exe/download)<br/><br/>[Source](https://web.archive.org/web/20170907191227/https://keepass.info/download.html) | v2.59 (portable)<br/><br/>v2.47 (.exe setup)                               | Needs .NET Framework 2.0 |   ✅   | [✅ - GPLv2](https://keepass.info/help/v2/license.html) |
|                                                |                  |                      |                                                                                                                                                                                                                                                       |                                                                                                                                                                                                             |                                                                            |                          |       |                                                        |

</details>

<details>
<summary>Web Browsers</summary>

| Program                                                                                 | Description                                                   | Works on Win2000 SP4 | Last Tested Working Version         | Last Officially Supported Version   | Version Stopped Working             | Notes | Free? | Open Source? |
| --------------------------------------------------------------------------------------- | ------------------------------------------------------------- | :------------------: | ----------------------------------- | ----------------------------------- | ----------------------------------- | ----- | :---: | :----------: |
| [Supermium for Windows 2000](https://github.com/Somehowfreename/windows-2000-supermium) | Unofficial build of Supermium designed to run on Windows 2000 |          ✅           | N/A, current version supports Win2K | N/A, current version supports Win2K | N/A, current version supports Win2K |       |       |              |

</details>

<details>
<summary>File Utilities</summary>

| Program                               | Description         | Works on Win2000 SP4 | Last Tested Working Version                                                       | Last Officially Supported Version                                                 | Version Stopped Working             | Notes | Free? |                                 Open Source?                                 |
| ------------------------------------- | ------------------- | :------------------: | --------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ----------------------------------- | ----- | :---: | :--------------------------------------------------------------------------: |
| [WinDirStat](https://windirstat.net/) | Disk usage analyzer |          ✅           | [1.1.2](https://prdownloads.sourceforge.net/windirstat/windirstat1_1_2_setup.exe) | [1.1.2](https://prdownloads.sourceforge.net/windirstat/windirstat1_1_2_setup.exe) | 2.0.1                               |       |   ✅   | [✅ - GPLv3](https://github.com/windirstat/windirstat/blob/master/LICENSE.md) |
| [7-Zip](https://7-zip.org/)           | File archiver       |          ✅           | [26.03](https://github.com/ip7z/7zip/releases/download/26.03/7z2603.exe)          | [26.03](https://github.com/ip7z/7zip/releases/download/26.03/7z2603.exe)          | N/A, current version supports Win2K |       |   ✅   |                  [✅ - LGPL](https://7-zip.org/license.txt)                   |
| MyDefrag                              |                     |                      |                                                                                   |                                                                                   |                                     |       |       |                                                                              |

</details>



<details>
<summary>Documents</summary>


| Program                                                        | Description                  | Works on Win2000 SP4 | Last Tested Working Version                                                                                                                                             | Last Officially Supported Version                                                                                                                                                                                                   | Version Stopped Working | Notes | Free? | Open Source? |
| -------------------------------------------------------------- | ---------------------------- | :------------------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- | ----- | :---: | :----------: |
| [SumatraPDF](https://www.sumatrapdfreader.org/free-pdf-reader) | PDF, eBook, and comic reader |          ✅           | [1.1](https://www.sumatrapdfreader.org/dl/rel/1.1/SumatraPDF-1.1-install.exe) (needs further testing)                                                                   |                                                                                                                                                                                                                                     |                         |       |   ✅   |              |
| Foxit Reader                                                   |                              |                      |                                                                                                                                                                         |                                                                                                                                                                                                                                     |                         |       |   ✅   |              |
| [LibreOffice](https://www.libreoffice.org/)                    | Open source office suite     |          ✅           | [3.6.7.2]([install](https://downloadarchive.documentfoundation.org/libreoffice/old/3.6.7.2/win/x86/LibO_3.6.7.2_Win_x86_install_multi.msi.asc)) (needs further testing) | [3.6.7.2]([install](https://downloadarchive.documentfoundation.org/libreoffice/old/3.6.7.2/win/x86/LibO_3.6.7.2_Win_x86_install_multi.msi.asc))<br/>[Source](https://wiki.documentfoundation.org/Documentation/System_Requirements) |                         |       |   ✅   |      ✅       |
| Notepad++                                                      |                              |          ✅           |                                                                                                                                                                         |                                                                                                                                                                                                                                     |                         |       |   ✅   |      ✅       |
| Microsoft Office 2000                                          |                              |                      |                                                                                                                                                                         |                                                                                                                                                                                                                                     |                         |       |   ❌   |      ❌       |

</br>
</details>


<details>
<summary>Media</summary>

| Program                | Description | Works on Win2000 SP4 | Last Tested Working Version | Last Officially Supported Version | Version Stopped Working | Notes | Free? | Open Source? |
| ---------------------- | ----------- | :------------------: | --------------------------- | --------------------------------- | ----------------------- | ----- | :---: | :----------: |
| VLC Media Player       |             |          ✅           |                             |                                   |                         |       |       |              |
| Winamp                 |             |          ✅           |                             |                                   |                         |       |       |              |
| Windows Media Player 9 |             |          ✅           |                             |                                   |                         |       |       |              |

</br>
</details>

<details>
<summary>Benchmarking</summary>

| Program                                                 | Description                                                                                | Works on Win2000 SP4 | Last Tested Working Version                               | Last Officially Supported Version | Version Stopped Working | Notes                                                                           | Free? | Open Source? |
| ------------------------------------------------------- | ------------------------------------------------------------------------------------------ | :------------------: | --------------------------------------------------------- | --------------------------------- | ----------------------- | ------------------------------------------------------------------------------- | :---: | :----------: |
| CPU-Z                                                   |                                                                                            |                      |                                                           |                                   |                         |                                                                                 |       |              |
| [PCMark04](https://benchmarks.ul.com/legacy-benchmarks) | PC performance benchmarking with system and component level tests for Windows 2000 and XP. |          ✅           | [1.3.0](https://benchmarks.ul.com/downloads/pcmark04.exe) | N/A                               | N/A                     | **Needed for PCMark04:**<br/>Media Encoder 9 <br/>DirectX 9 <br/>Media Player 9 |       |              |

</br>
</details>

<details>
<summary>Games</summary>

| Program                                                           | Description                        | Works on Win2000 SP4 | Last Tested Working Version                                                        | Last Officially Supported Version | Version Stopped Working | Notes | Free? |                                    Open Source?                                    |
| ----------------------------------------------------------------- | ---------------------------------- | :------------------: | ---------------------------------------------------------------------------------- | --------------------------------- | ----------------------- | ----- | :---: | :--------------------------------------------------------------------------------: |
| [Crispy Doom](https://fabiangreffrath.github.io/crispy-homepage/) | Doom source port with enhancements |          ✅           | [3.2](https://github.com/fabiangreffrath/crispy-doom/releases/tag/crispy-doom-3.2) | ?                                 | 3.3                     |       |   ✅   | [✅ - GPLv2](https://github.com/fabiangreffrath/crispy-doom/blob/master/COPYING.md) |
| Quake 3 Demo                                                      |                                    |          ✅           |                                                                                    |                                   |                         |       |   ✅   |                                         ❌                                          |

</br>
</details>



</br>
</br>
</br>

# Additional Resources

<details>
<summary>Similar lists to refer to as well</summary>

https://retrosystemsrevival.blogspot.com/p/latest-versions-of-software-working-on.html

https://activewin.com/win2000/index.shtml

https://archive.org/details/win-2k-apps-ba

https://www.vogons.org/viewtopic.php?t=71920

</details>

<details>
<summary>Linux distros to consider for a Win2K era PC</summary>

If the aim is to use a Windows 2000 era PC in current day, please consider the following Linux distros. They are going to be much better for security and compatibility with modern software.

All of these distros still support 32-bit x86.

**Easier, GUI based:**

[antiX Linux](https://antixlinux.com/)

[Puppy Linux](https://puppylinux-woof-ce.github.io/)

</br>

**Harder, terminal setup:**

[Alpine Linux](https://www.alpinelinux.org/)

[Arch Linux 32](https://archlinux32.org/)

[Void Linux](https://voidlinux.org/download/#i686)

</br>

**Not Linux based, but worth mentioning:**

Haiku OS

FreeDOS

OpenBSD | FreeBSD

</details>
