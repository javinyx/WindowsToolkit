# 🔧 WindowsToolkit

A collection of **Windows 11 apps** to improve user and poweruser experience.

The applications listed here are evaluated by the following criteria:

- *Free to use / Open source*
- *Theme Support / Fluent design / Dark mode*
- *Plugin / Extension Support*
- *Available in [Winget](https://winget.run/) / [Microsoft Store](https://www.microsoft.com/en-us/store/apps/windows)*
- *Mobile version*

Since the release of Windows 11, winget is already installed and can be used from the command line, the official guide can be found [here](https://docs.microsoft.com/en-us/windows/package-manager/winget/#use-winget).

If you would like to provide feedback please do so by using GitHub Issues.

</br>

## 📑 Table of Contents

- [🔧 WindowsToolkit](#-windowstoolkit)
  - [📑 Table of Contents](#-table-of-contents)
  - [⚙️ Applications](#️-applications)
    - [🌍 Browsers](#-browsers)
    - [📬 Email Clients](#-email-clients)
    - [☑️ To do lists](#️-to-do-lists)
    - [📝 Text Editors](#-text-editors)
    - [⌨️ Code Editors](#️-code-editors)
    - [🚀 Terminals](#-terminals)
    - [📁 FTP Clients](#-ftp-clients)
    - [⏬ Torrent Clients](#-torrent-clients)
    - [🎵 Media Players](#-media-players)
    - [🖼️ Photo Viewers](#️-photo-viewers)
    - [PDF Readers](#pdf-readers)
    - [Password Managers](#password-managers)
    - [Game Launchers](#game-launchers)
    - [Finder Utilities](#finder-utilities)
    - [Audio Utilities](#audio-utilities)
    - [Windows Utilities](#windows-utilities)
    - [Discord](#discord)
    - [Aesthetics](#aesthetics)
    - [Others](#others)

</br>

## ⚙️ Applications

- In the **Price** table column, if you see a `²` it means the application is also *open source*.
- If themes or plugins/extensions are available, click on the ✔️ to browse them, or hover them for more information.
- If you see a 🟡, hover over it to read a note.
- I recommend using [Revo Uninstaller](https://www.revouninstaller.com/revo-uninstaller-free-download/) to uninstall programs, instead of the default Windows method, this is because Revo also cleans any leftover files and registry entries.
- I also recommend changing the **Options -> Uninstaller** options to have `Check mark all leftovers by default` and `Forcibly stop running executable files during their uninstall` checked, while the rest of the options unchecked.

</br>

### 🌍 Browsers

|                            Application                            | Price |                                Themes                                 |                                    Plugins                                     | MS Store |                  Winget                  |                                                                              Mobile                                                                              |
|:-----------------------------------------------------------------:|:-----:|:---------------------------------------------------------------------:|:------------------------------------------------------------------------------:|:--------:|:----------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|        **[Google Chrome](https://www.google.com/chrome/)**        |  🆓   |        [✔️](https://chrome.google.com/webstore/category/themes)        |          [✔️](https://chrome.google.com/webstore/category/extensions)           |    ❌     |  `winget install -e --id Google.Chrome`  |         [🤖](https://play.google.com/store/apps/details?id=com.android.chrome&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/google-chrome/id535886823)         |
|    **[Microsoft Edge](https://www.microsoft.com/en-us/edge)**     |  🆓   | [✔️](https://microsoftedge.microsoft.com/addons/microsoft-edge-themes) | [✔️](https://microsoftedge.microsoft.com/addons/Microsoft-Edge-Extensions-Home) |    ✔️     | `winget install -e --id Microsoft.Edge`  |                 [🤖](https://play.google.com/store/apps/details?id=com.microsoft.emmx&hl=en&gl=US) [🍎](https://apps.apple.com/app/id1288723196)                 |
| **[Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/)** |  🆓²  |         [✔️](https://addons.mozilla.org/en-US/firefox/themes/)         |           [✔️](https://addons.mozilla.org/en-US/firefox/extensions/)            |    ❌     | `winget install -e --id Mozilla.Firefox` | [🤖](https://play.google.com/store/apps/details?id=org.mozilla.firefox&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/firefox-private-safe-browser/id989804926) |

</br>

### 📬 Email Clients

|                                   Application                                   | Price |                                Themes                                |                              Plugins                              |                          MS Store                           |                     Winget                     |                                                                             Mobile                                                                             |
|:-------------------------------------------------------------------------------:|:-----:|:--------------------------------------------------------------------:|:-----------------------------------------------------------------:|:-----------------------------------------------------------:|:----------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| **[Mail and Calendar](https://www.microsoft.com/store/productId/9WZDNCRFHVQM)** |  🆓   |        [🟡](#-email-clients "Light/Dark mode, Fluent design")        |                                 ❌                                 | [✔️](https://www.microsoft.com/store/productId/9WZDNCRFHVQM) |                       ❌                        | [🤖](https://play.google.com/store/apps/details?id=com.microsoft.office.outlook&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/microsoft-outlook/id951937596) |
|                  **[MailSpring](https://getmailspring.com/)**                   |  🆓²  |               [🟡](#-email-clients "Light/Dark mode")                |                                 ❌                                 |                              ❌                              | `winget install -e --id Foundry376.Mailspring` |                                                                               ❌                                                                                |
|          **[Mozilla ThunderBird](https://www.thunderbird.net/en-US/)**          |  🆓²  | [✔️](https://addons.thunderbird.net/en-US/thunderbird/static-themes/) | [✔️](https://addons.thunderbird.net/en-US/thunderbird/extensions/) |                              ❌                              |  `winget install -e --id Mozilla.Thunderbird`  |                                                                               ❌                                                                                |

</br>

### ☑️ To do lists

|                        Application                        | Price |                        Themes                        | Plugins |                          MS Store                           | Winget |                                                                        Mobile                                                                        |
|:---------------------------------------------------------:|:-----:|:----------------------------------------------------:|:-------:|:-----------------------------------------------------------:|:------:|:----------------------------------------------------------------------------------------------------------------------------------------------------:|
| **[Microsoft To Do](https://to-do.microsoft.com/tasks/)** |  🆓   | [🟡](#-to-do-lists "Light/Dark mode, Fluent design") |    ❌    | [✔️](https://www.microsoft.com/store/productId/9NBLGGH5R558) |   ❌    | [🤖](https://play.google.com/store/apps/details?id=com.microsoft.todos&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/microsoft-to-do/id1212616790) |

</br>

### 📝 Text Editors

|                   Application                    | Price |                   Themes                   |                                          Plugins                                           |                                 MS Store                                  |                    Winget                    | Mobile |
|:------------------------------------------------:|:-----:|:------------------------------------------:|:------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|:--------------------------------------------:|:------:|
| **[Notepad++](https://notepad-plus-plus.org/)**  |  🆓²  | [🟡](#-text-editors "Customizable themes") | [✔️](https://github.com/notepad-plus-plus/nppPluginList/blob/master/doc/plugin_list_x64.md) | [🟡](https://www.microsoft.com/store/productId/9PHSCTZMKC27 "Unofficial") | `winget install -e --id Notepad++.Notepad++` |   ❌    |
| **[Notepads App](https://www.notepadsapp.com/)** |  🆓²  |    [🟡](#-text-editors "Fluent design")    |                                             ❌                                              |        [✔️](https://www.microsoft.com/store/productId/9NHL4NSC67WM)        |  `winget install -e --id Notepads.Notepads`  |   ❌    |

</br>

### ⌨️ Code Editors

|                       Application                        |              Price              |             Themes              |                     Plugins                      | MS Store |                       Winget                        | Mobile |
|:--------------------------------------------------------:|:-------------------------------:|:-------------------------------:|:------------------------------------------------:|:--------:|:---------------------------------------------------:|:------:|
|               **[Atom](https://atom.io/)**               |               🆓²               |   [✔️](https://atom.io/themes)   |          [✔️](https://atom.io/packages)           |    ❌     |        `winget install -e --id GitHub.Atom`         |   ❌    |
|     **[Sublime Text](https://www.sublimetext.com/)**     | [🟡](#-code-editors "Freemium") | [✔️](https://packagecontrol.io/) |         [✔️](https://packagecontrol.io/)          |    ❌     |   `winget install -e --id SublimeHQ.SublimeText`    |   ❌    |
| **[Visual Studio Code](https://code.visualstudio.com/)** |               🆓²               | [✔️](https://vscodethemes.com/)  | [✔️](https://marketplace.visualstudio.com/VSCode) |    ✔️     | `winget install -e --id Microsoft.VisualStudioCode` |   ❌    |

</br>

### 🚀 Terminals

|                           Application                            | Price |                         Themes                         | Plugins |                          MS Store                           |                       Winget                       | Mobile |
|:----------------------------------------------------------------:|:-----:|:------------------------------------------------------:|:-------:|:-----------------------------------------------------------:|:--------------------------------------------------:|:------:|
| **[Fluent Terminal](https://github.com/felixse/FluentTerminal)** |  🆓²  | [🟡](#-terminals "Fluent design, Customizable themes") |    ❌    | [✔️](https://www.microsoft.com/store/productId/9P2KRLMFXF9T) | `winget install -e --id Microsoft.WindowsTerminal` |   ❌    |
|  **[Windows Terminal](https://github.com/microsoft/terminal)**   |  🆓²  | [🟡](#-terminals "Fluent design, Customizable themes") |    ❌    | [✔️](https://www.microsoft.com/store/productId/9N0DX20HK701) |                         ❌                          |   ❌    |

</br>

### 📁 FTP Clients

|                  Application                   | Price |                Themes                 | Plugins |                              MS Store                               |                 Winget                 | Mobile |
|:----------------------------------------------:|:-----:|:-------------------------------------:|:-------:|:-------------------------------------------------------------------:|:--------------------------------------:|:------:|
| **[WinSCP](https://winscp.net/eng/index.php)** |  🆓   | [🟡](#-ftp-clients "Light/Dark mode") |    ❌    | [🟡](https://www.microsoft.com/store/productId/9P0PQ8B65N8X "Paid") | `winget install -e --id WinSCP.WinSCP` |   ❌    |

</br>

### ⏬ Torrent Clients

|                    Application                    | Price |                    Themes                     |                     Plugins                      | MS Store |                      Winget                      | Mobile |
|:-------------------------------------------------:|:-----:|:---------------------------------------------:|:------------------------------------------------:|:--------:|:------------------------------------------------:|:------:|
|     **[Deluge](https://deluge-torrent.org/)**     |  🆓²  | [🟡](#-torrent-clients "Customizable themes") | [✔️](https://dev.deluge-torrent.org/wiki/Plugins) |    ❌     |    `winget install -e --id DelugeTeam.Deluge`    |   ❌    |
| **[qBitTorrent](https://github.com/ffftp/ffftp)** |  🆓²  | [🟡](#-torrent-clients "Customizable themes") |                        ❌                         |    ❌     | `winget install -e --id qBittorrent.qBittorrent` |   ❌    |

</br>

### 🎵 Media Players

|                   Application                    | Price |                     Themes                     |                           Plugins                           |                                            MS Store                                            |                 Winget                  |                                                                     Mobile                                                                      |
|:------------------------------------------------:|:-----:|:----------------------------------------------:|:-----------------------------------------------------------:|:----------------------------------------------------------------------------------------------:|:---------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------:|
| **[Mpv.net](https://github.com/stax76/mpv.net)** |  🆓²  |  [🟡](#-media-players "Customizable themes")   |                              ❌                              |                                               ❌                                                | `winget install -e --id stax76.mpv.net` |                                         [🤖](https://play.google.com/store/apps/details?id=is.xyz.mpv)                                          |
|   **[PotPlayer](https://potplayer.daum.net/)**   |  🆓   | [✔️](https://daumpotplayer.com/category/skins/) |                              ❌                              |                                               ❌                                                | `winget install -e --id Daum.Potplayer` |                                                                        ❌                                                                        |
|     **[VLC](https://www.videolan.org/vlc/)**     |  🆓²  |  [✔️](https://www.videolan.org/vlc/skins.html)  | [✔️](https://addons.videolan.org/browse/cat/323/ord/latest/) | [🟡](https://www.microsoft.com/store/productId/9NBLGGH4VVNH "Different from original version") |  `winget install -e --id VideoLAN.VLC`  | [🤖](https://play.google.com/store/apps/details?id=org.videolan.vlc&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/vlc-for-mobile/id650377962) |

</br>

### 🖼️ Photo Viewers

|                                  Application                                   | Price |                         Themes                         |                    Plugins                    |                          MS Store                           |                     Winget                      | Mobile |
|:------------------------------------------------------------------------------:|:-----:|:------------------------------------------------------:|:---------------------------------------------:|:-----------------------------------------------------------:|:-----------------------------------------------:|:------:|
|                  **[IrfanView](https://www.irfanview.com/)**                   |  🆓   |        [✔️](https://www.irfanview.com/skins.htm)        |  [✔️](https://www.irfanview.com/plugins.htm)   | [✔️](https://www.microsoft.com/store/productId/9PJZ3BTL5PV6) | `winget install -e --id IrfanSkiljan.IrfanView` |   ❌    |
| **[Microsoft Photos](https://www.microsoft.com/store/productId/9WZDNCRFJBH4)** |  🆓   | [🟡](#-photo-viewers "Light/Dark mode, Fluent design") |                       ❌                       | [✔️](https://www.microsoft.com/store/productId/9WZDNCRFJBH4) |                        ❌                        |   ❌    |
|              **[XnViewMP](https://www.xnview.com/en/xnviewmp/)**               |  🆓   |      [🟡](#-photo-viewers "Customizable themes")       | [🟡](#-photo-viewers "Configured inside app") |                              ❌                              |    `winget install -e --id XnSoft.XnViewMP`     |   ❌    |

</br>

### PDF Readers

| Application                                           | Free                | Themes                    | Plugins | Packages                                                                              | Mobile                                                                                                                                                                                     | Notes                                                                          |
|-------------------------------------------------------|---------------------|---------------------------|---------|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| [Adobe Acrobat Reader](https://get.adobe.com/reader/) | :heavy_check_mark:  | :heavy_check_mark: In app | :x:     | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/adobereader)     | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=com.adobe.reader&hl=en&gl=US), [iOS](https://apps.apple.com/us/app/adobe-acrobat-reader-pdf-maker/id469337564)  | The most popular PDF reader ever, free version is useful for signing           |
| [Xodo](https://www.xodo.com/)                         | :heavy_check_mark:  | :heavy_check_mark: In app | :x:     | :heavy_check_mark: [MS Store](https://www.microsoft.com/store/productId/9WZDNCRDJXP4) | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=com.xodo.pdf.reader&hl=en&gl=US), [iOS](https://apps.apple.com/us/app/pdf-reader-annotator-by-xodo/id805075929) | The most feature packed free PDF viewer, able to edit, export and import pages |
| [Okular](https://okular.kde.org/)                     | :heavy_check_mark:² | :x:                       | :x:     | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/okular)          | :x:                                                                                                                                                                                        | Very simple interface, but A TON of features, plus it's open source            |

### Password Managers

| Application                         | Free                | Themes                    | Plugins                                                        | Packages                                                                                                                                            | Mobile                                                                                                                                                                                                          | Notes                                                                                                         |
|-------------------------------------|---------------------|---------------------------|----------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| [Bitwarden](https://bitwarden.com/) | :heavy_check_mark:² | :heavy_check_mark: In app | :x:                                                            | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/bitwarden), [MS Store](https://www.microsoft.com/store/productId/9PJSDV0VPK04) | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=com.x8bit.bitwarden&hl=en&utm_source=downloadatoz.com), [iOS](https://apps.apple.com/us/app/bitwarden-password-manager/id1137397744) | Integrates everywhere wonderfully, if you want to use it I recommend installing the browser extension as well |
| [KeePass](https://keepass.info/)    | :heavy_check_mark:² | :x:                       | :heavy_check_mark: [Browse](https://keepass.info/plugins.html) | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/keepass)                                                                       | :heavy_check_mark: [Android](https://keepass.info/download.html), [iOS](https://keepass.info/download.html)                                                                                                     | Simple password manager with plugin support                                                                   |

### Game Launchers

| Application                                       | Free                | Themes                                                                | Plugins                                                               | Packages                                                                           | Mobile                                                                                                                                                                                           | Notes                                                                         |
|---------------------------------------------------|---------------------|-----------------------------------------------------------------------|-----------------------------------------------------------------------|------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------|
| [GOG Galaxy](https://www.gog.com/galaxy)          | :heavy_check_mark:  | :x:                                                                   | :heavy_check_mark: In app                                             | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/goggalaxy)    | :x:                                                                                                                                                                                              | A great way to group all your games from different launchers, growing rapidly |
| [Playnite](https://github.com/microsoft/terminal) | :heavy_check_mark:² | :heavy_check_mark: [Browse](https://playnite.link/forum/forum-8.html) | :heavy_check_mark: [Browse](https://playnite.link/forum/forum-6.html) | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/playnite)     | :x:                                                                                                                                                                                              | Amazing, customizable open source game launcher                               |
| [Steam](https://store.steampowered.com/)          | :heavy_check_mark:  | :heavy_check_mark: In app                                             | :x:                                                                   | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/steam-client) | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=com.valvesoftware.android.steam.community&hl=en&gl=US), [iOS](https://apps.apple.com/us/app/steam-mobile/id495369748) | The biggest videogame marketplace and launcher available                      |

### Finder Utilities

| Application                                                  | Free                | Themes                           | Plugins                   | Packages                                                                                                                                                         | Mobile | Notes                                                                              |
|--------------------------------------------------------------|---------------------|----------------------------------|---------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|------------------------------------------------------------------------------------|
| [7-Zip](https://www.7-zip.org/)                              | :heavy_check_mark:² | :x:                              | :x:                       | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/7zip/19.0), [MS Store (Unofficial)](https://www.microsoft.com/store/productId/9MZ81RMK8JFD) | :x:    | The best archive manager, period.                                                  |
| [File Converter](https://file-converter.org/?from=readme.md) | :heavy_check_mark:² | :x:                              | :x:                       | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/file-converter)                                                                             | :x:    | Very cool finder extension to quickly convert photos, audio, videos and documents. |
| [Files](https://files-community.github.io/)                  | :heavy_check_mark:² | :heavy_check_mark: Fluent design | :x:                       | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/files), [MS Store](https://www.microsoft.com/store/productId/9NGHP3DX8HDX)                  | :x:    | Very cool and modern file explorer alternative.                                    |
| [QTTabBar](http://qttabbar.wikidot.com/)                     | :heavy_check_mark:  | :x:                              | :heavy_check_mark: In app | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/QTTabBar)                                                                                   | :x:    | File Explorer extension which lets you have tabs and a few other functionalities.  |

### Audio Utilities

- VB-AudioCable
- VoiceMeeter
- Audacity
- fre:ac
- Mp3Tag

### Windows Utilities

- Revo Uninstaller
- Everything
- PowerToys
- EarTrumpet
- ShareX
- Snip & Sketch

### Discord

- Discord
- PreMid

### Aesthetics

- ModernFlyouts
- Rainmeter
- Wallpaper Engine

### Others

- SoundPad
- Touch Portal
- Spotify
- Local
- JetBrains Toolbox
- AnyDesk
- Simplenote
- RightKeyboard
