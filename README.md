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
    - [📝 Note Taking](#-note-taking)
    - [🖊️ Text Editors](#️-text-editors)
    - [⌨️ Code Editors](#️-code-editors)
    - [🚀 Terminals](#-terminals)
    - [📁 FTP Clients](#-ftp-clients)
    - [⏬ Torrent Clients](#-torrent-clients)
    - [🎧 Media Utilities](#-media-utilities)
    - [🎬 Media Players](#-media-players)
    - [🎵 Music & Sound](#-music--sound)
    - [🖼️ Photo Viewers](#️-photo-viewers)
    - [📖 PDF Readers](#-pdf-readers)
    - [🔐 Password Managers](#-password-managers)
    - [🎮 Game Launchers](#-game-launchers)
    - [💬 Discord](#-discord)
    - [⚡ Windows Enhancements](#-windows-enhancements)
    - [🗄️ File Explorer Utilities](#️-file-explorer-utilities)
    - [🏔️ Desktop](#️-desktop)
    - [📶 Remote Control](#-remote-control)

</br>

## ⚙️ Applications

- In the **Price** table column, if you see a `²` it means the application is also *open source*.
- If themes or plugins/extensions are available, click on the ✔️ to browse them.
- If you see a 🟡, hover over it to read more information.
- I recommend using [Revo Uninstaller](https://www.revouninstaller.com/revo-uninstaller-free-download/) to uninstall programs, instead of the default Windows method, this is because Revo also cleans any leftover files and registry entries.
- I also recommend changing **Options -> Uninstaller** in Revo to have `Check mark all leftovers by default` and `Forcibly stop running executable files during their uninstall` checked, while the rest of the options unchecked.

</br>

### 🌍 Browsers

|                            Application                            | Price |                                Themes                                 |                                    Plugins                                     | MS Store |                  Winget                  |                                                                              Mobile                                                                              |
|:-----------------------------------------------------------------:|:-----:|:---------------------------------------------------------------------:|:------------------------------------------------------------------------------:|:--------:|:----------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|        **[Google Chrome](https://www.google.com/chrome/)**        |  🆓   |        [✔️](https://chrome.google.com/webstore/category/themes)        |          [✔️](https://chrome.google.com/webstore/category/extensions)           |    ❌     |  `winget install -e --id Google.Chrome`  |           [🤖](https://play.google.com/store/apps/details?id=com.🤖.chrome&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/google-chrome/id535886823)            |
|    **[Microsoft Edge](https://www.microsoft.com/en-us/edge)**     |  🆓   | [✔️](https://microsoftedge.microsoft.com/addons/microsoft-edge-themes) | [✔️](https://microsoftedge.microsoft.com/addons/Microsoft-Edge-Extensions-Home) |    ❌     | `winget install -e --id Microsoft.Edge`  |                 [🤖](https://play.google.com/store/apps/details?id=com.microsoft.emmx&hl=en&gl=US) [🍎](https://apps.apple.com/app/id1288723196)                 |
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

|                        Application                        | Price |                        Themes                        |                      Plugins                      |                          MS Store                           | Winget |                                                                        Mobile                                                                        |
|:---------------------------------------------------------:|:-----:|:----------------------------------------------------:|:-------------------------------------------------:|:-----------------------------------------------------------:|:------:|:----------------------------------------------------------------------------------------------------------------------------------------------------:|
| **[Microsoft To Do](https://to-do.microsoft.com/tasks/)** |  🆓   | [🟡](#-to-do-lists "Light/Dark mode, Fluent design") |                         ❌                         | [✔️](https://www.microsoft.com/store/productId/9NBLGGH5R558) |   ❌    | [🤖](https://play.google.com/store/apps/details?id=com.microsoft.todos&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/microsoft-to-do/id1212616790) |
|           **[Trello](https://trello.com/home)**           |  🆓   |      [🟡](#-to-do-lists "Customizable themes")       | [🟡](#-to-do-lists "Many 3rd party integrations") | [✔️](https://www.microsoft.com/store/productId/9NBLGGH4XXVW) |   ❌    | [🤖](https://play.google.com/store/apps/details?id=com.trello&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/trello-organize-anything/id461504587)  |

</br>

### 📝 Note Taking

|                Application                | Price |                     Themes                     |                      Plugins                      |                          MS Store                           |                     Winget                     |                                                                                Mobile                                                                                |
|:-----------------------------------------:|:-----:|:----------------------------------------------:|:-------------------------------------------------:|:-----------------------------------------------------------:|:----------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|   **[Joplin](https://joplinapp.org/)**    |  🆓²  | [🟡](#-note-taking "Selectable themes in app") | [✔️](https://discourse.joplinapp.org/c/plugins/18) |                              ❌                              |     `winget install -e --id Joplin.Joplin`     |               [🤖](https://play.google.com/store/apps/details?id=net.cozic.joplin&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/joplin/id1315599797)               |
|   **[Obsidian](https://obsidian.md/)**    |  🆓   | [🟡](#-note-taking "Selectable themes in app") |         [✔️](https://obsidian.md/plugins)          |                              ❌                              |   `winget install -e --id Obsidian.Obsidian`   |        [🤖](https://play.google.com/store/apps/details?id=md.obsidian&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/obsidian-connected-notes/id1557175442)         |
| **[Simplenote](https://simplenote.com/)** |  🆓   |     [🟡](#-note-taking "Light/Dark mode")      |                         ❌                         | [✔️](https://www.microsoft.com/store/productId/9NXQQ40LDW3X) | `winget install -e --id Automattic.Simplenote` | [🤖](https://play.google.com/store/apps/details?id=com.automattic.simplenote&hl=en&gl=US) [🍎](https://apps.apple.com/it/app/simplenote-notes-and-todos/id289429962) |

</br>

### 🖊️ Text Editors

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
| **[Visual Studio Code](https://code.visualstudio.com/)** |               🆓²               | [✔️](https://vscodethemes.com/)  | [✔️](https://marketplace.visualstudio.com/VSCode) |    ❌     | `winget install -e --id Microsoft.VisualStudioCode` |   ❌    |

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

### 🎧 Media Utilities

|                          Application                          | Price |                  Themes                   |                       Plugins                        |                          MS Store                           |                       Winget                        | Mobile |
|:-------------------------------------------------------------:|:-----:|:-----------------------------------------:|:----------------------------------------------------:|:-----------------------------------------------------------:|:---------------------------------------------------:|:------:|
|         **[Audacity](https://www.audacityteam.org/)**         |  🆓²  | [🟡](#-media-utilities "Light/Dark mode") | [✔️](https://www.audacityteam.org/download/plug-ins/) |                              ❌                              |     `winget install -e --id Audacity.Audacity`      |   ❌    |
|             **[Fre:ac](https://www.freac.org/)**              |  🆓²  |                     ❌                     |                          ❌                           | [✔️](https://www.microsoft.com/store/productId/9P1XD8ZQJ7JD) |                          ❌                          |   ❌    |
|            **[Handbrake](https://handbrake.fr/)**             |  🆓²  | [🟡](#-media-utilities "Light/Dark mode") |                          ❌                           |                              ❌                              | `winget install -e --id thehandbraketeam.handbrake` |   ❌    |
|            **[Mp3Tag](https://www.mp3tag.de/en/)**            |  🆓   |                     ❌                     |                          ❌                           | [✔️](https://www.microsoft.com/store/productId/9NN77TCQ1NC8) |       `winget install -e --id Mp3tag.Mp3tag`        |   ❌    |
|       **[VB-AudioCable](https://vb-audio.com/Cable/)**        |  🆓   |                     ❌                     |                          ❌                           |                              ❌                              |                          ❌                          |   ❌    |
| **[Voicemeeter](https://vb-audio.com/Voicemeeter/index.htm)** |  🆓   |                     ❌                     |                          ❌                           |                              ❌                              | `winget install -e --id VB-Audio.VoiceMeeterPotato` |   ❌    |

</br>

### 🎬 Media Players

|                   Application                    | Price |                     Themes                     |                           Plugins                           |                                              MS Store                                              |                 Winget                  |                                                                     Mobile                                                                      |
|:------------------------------------------------:|:-----:|:----------------------------------------------:|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------------------------:|:---------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------:|
| **[Mpv.net](https://github.com/stax76/mpv.net)** |  🆓²  |  [🟡](#-media-players "Customizable themes")   |                              ❌                              |                                                 ❌                                                  | `winget install -e --id stax76.mpv.net` |                                         [🤖](https://play.google.com/store/apps/details?id=is.xyz.mpv)                                          |
|   **[PotPlayer](https://potplayer.daum.net/)**   |  🆓   | [✔️](https://daumpotplayer.com/category/skins/) |                              ❌                              |                                                 ❌                                                  | `winget install -e --id Daum.Potplayer` |                                                                        ❌                                                                        |
|     **[VLC](https://www.videolan.org/vlc/)**     |  🆓²  |  [✔️](https://www.videolan.org/vlc/skins.html)  | [✔️](https://addons.videolan.org/browse/cat/323/ord/latest/) | [🟡](https://www.microsoft.com/store/productId/9NBLGGH4VVNH "Different from the original version") |  `winget install -e --id VideoLAN.VLC`  | [🤖](https://play.google.com/store/apps/details?id=org.videolan.vlc&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/vlc-for-mobile/id650377962) |

</br>

### 🎵 Music & Sound

|                    Application                    |              Price              |                            Themes                             |                            Plugins                             | MS Store | Winget |                                                                Mobile                                                                |
|:-------------------------------------------------:|:-------------------------------:|:-------------------------------------------------------------:|:--------------------------------------------------------------:|:--------:|:------:|:------------------------------------------------------------------------------------------------------------------------------------:|
| **[SoundPad](https://leppsoft.com/soundpad/en/)** |           **€ 4.99**            |        [🟡](#-music--sound "Selectable themes in app")        |                               ❌                                |    ❌     |   ❌    |                                                                  ❌                                                                   |
| **[Touch Portal](https://www.touch-portal.com/)** | [🟡](#-music--sound "Freemium") | [✔️](https://www.touch-portal.com/assetsdb/show-all.php?cat=i) | [✔️](https://www.touch-portal.com/assetsdb/show-all.php?cat=pl) |    ❌     |   ❌    | [🤖](https://play.google.com/store/apps/details?id=rils.apps.touchportal) [🍎](https://apps.apple.com/app/touch-portal/id1410172542) |

</br>

### 🖼️ Photo Viewers

|                                  Application                                   | Price |                         Themes                         |                      Plugins                      |                          MS Store                           |                     Winget                      | Mobile |
|:------------------------------------------------------------------------------:|:-----:|:------------------------------------------------------:|:-------------------------------------------------:|:-----------------------------------------------------------:|:-----------------------------------------------:|:------:|
|                  **[IrfanView](https://www.irfanview.com/)**                   |  🆓   |        [✔️](https://www.irfanview.com/skins.htm)        |    [✔️](https://www.irfanview.com/plugins.htm)     | [✔️](https://www.microsoft.com/store/productId/9PJZ3BTL5PV6) | `winget install -e --id IrfanSkiljan.IrfanView` |   ❌    |
| **[Microsoft Photos](https://www.microsoft.com/store/productId/9WZDNCRFJBH4)** |  🆓   | [🟡](#-photo-viewers "Light/Dark mode, Fluent design") |                         ❌                         | [✔️](https://www.microsoft.com/store/productId/9WZDNCRFJBH4) |                        ❌                        |   ❌    |
|              **[XnViewMP](https://www.xnview.com/en/xnviewmp/)**               |  🆓   |      [🟡](#-photo-viewers "Customizable themes")       | [🟡](#-photo-viewers "Selectable plugins in app") |                              ❌                              |    `winget install -e --id XnSoft.XnViewMP`     |   ❌    |

</br>

### 📖 PDF Readers

|                        Application                        |             Price              |                Themes                 | Plugins |                          MS Store                           |                       Winget                        |                                                                              Mobile                                                                              |
|:---------------------------------------------------------:|:------------------------------:|:-------------------------------------:|:-------:|:-----------------------------------------------------------:|:---------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| **[Adobe Acrobat Reader](https://get.adobe.com/reader/)** | [🟡](#-pdf-readers "Freemium") | [🟡](#-pdf-readers "Light/Dark mode") |    ❌    |                              ❌                              | `winget install -e --id Adobe.AdobeAcrobatReaderDC` | [🤖](https://play.google.com/store/apps/details?id=com.adobe.reader&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/adobe-acrobat-reader-pdf-maker/id469337564)  |
|           **[Okular](https://okular.kde.org/)**           |              🆓²               |                   ❌                   |    ❌    | [✔️](https://www.microsoft.com/store/productId/9N41MSQ1WNM8) |                          ❌                          |                                                                                ❌                                                                                 |
|             **[Xodo](https://www.xodo.com/)**             | [🟡](#-pdf-readers "Freemium") | [🟡](#-pdf-readers "Light/Dark mode") |    ❌    | [✔️](https://www.microsoft.com/store/productId/9WZDNCRDJXP4) |                          ❌                          | [🤖](https://play.google.com/store/apps/details?id=com.xodo.pdf.reader&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/pdf-reader-annotator-by-xodo/id805075929) |

</br>

### 🔐 Password Managers

|               Application               | Price |                        Themes                        |                Plugins                 |                          MS Store                           |                     Winget                     |                                                                                        Mobile                                                                                         |
|:---------------------------------------:|:-----:|:----------------------------------------------------:|:--------------------------------------:|:-----------------------------------------------------------:|:----------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| **[Bitwarden](https://bitwarden.com/)** |  🆓²  | [🟡](#-password-managers "Selectable themes in app") |                   ❌                    | [✔️](https://www.microsoft.com/store/productId/9PJSDV0VPK04) |  `winget install -e --id Bitwarden.Bitwarden`  | [🤖](https://play.google.com/store/apps/details?id=com.x8bit.bitwarden&hl=en&utm_source=downloadatoz.com) [🍎](https://apps.apple.com/us/app/bitwarden-password-manager/id1137397744) |
|  **[KeePass](https://keepass.info/)**   |  🆓²  |     [🟡](#-password-managers "Light/Dark mode")      | [✔️](https://keepass.info/plugins.html) |                              ❌                              | `winget install -e --id DominikReichl.KeePass` |                                                   [🤖](https://keepass.info/download.html) [🍎](https://keepass.info/download.html)                                                   |

</br>

### 🎮 Game Launchers

|                      Application                      | Price |                     Themes                      |                    Plugins                    | MS Store |                   Winget                   |                           Mobile                           |
|:-----------------------------------------------------:|:-----:|:-----------------------------------------------:|:---------------------------------------------:|:--------:|:------------------------------------------:|:----------------------------------------------------------:|
|     **[Pegasus](https://pegasus-frontend.org/)**      |  🆓²  | [✔️](https://pegasus-frontend.org/tools/themes/) |                       ❌                       |    ❌     |                     ❌                      | [🤖](https://github.com/mmatyas/pegasus-frontend/releases) |
| **[Playnite](https://github.com/microsoft/terminal)** |  🆓²  |  [✔️](https://playnite.link/forum/forum-8.html)  | [✔️](https://playnite.link/forum/forum-6.html) |    ❌     | `winget install -e --id Playnite.Playnite` |                             ❌                              |

</br>

### 💬 Discord

|             Application             | Price |              Themes               | Plugins | MS Store |                  Winget                  |                                                                        Mobile                                                                         |
|:-----------------------------------:|:-----:|:---------------------------------:|:-------:|:--------:|:----------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------:|
| **[Discord](https://discord.com/)** |  🆓   | [🟡](#-discord "Light/Dark mode") |    ❌    |    ❌     | `winget install -e --id Discord.Discord` | [🤖](https://play.google.com/store/apps/details?id=com.discord&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/discord-talk-chat-hangout/id985746746) |
|  **[PreMid](https://premid.app/)**  |  🆓²  |                 ❌                 |    ❌    |    ❌     |                    ❌                     |                                                                           ❌                                                                           |

</br>

### ⚡ Windows Enhancements

|                           Application                           | Price |                            Themes                             | Plugins |                          MS Store                           |                          Winget                          |                                                Mobile                                                 |
|:---------------------------------------------------------------:|:-----:|:-------------------------------------------------------------:|:-------:|:-----------------------------------------------------------:|:--------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------:|
|            **[EarTrumpet](https://eartrumpet.app/)**            |  🆓²  | [🟡](#-windows-enhancements "Light/Dark mode, Fluent design") |    ❌    | [✔️](https://www.microsoft.com/store/productId/9NBLGGH516XP) |   `winget install -e --id File-New-Project.EarTrumpet`   |                                                   ❌                                                   |
|          **[Everything](https://www.voidtools.com/)**           |  🆓   |                               ❌                               |    ❌    |                              ❌                              |      `winget install -e --id voidtools.Everything`       |                                                   ❌                                                   |
| **[ModernFlyouts](https://modernflyouts-community.github.io/)** |  🆓²  | [🟡](#-windows-enhancements "Light/Dark mode, Fluent design") |    ❌    | [✔️](https://www.microsoft.com/store/productId/9MT60QV066RP) |   `winget install -e --id ModernFlyouts.ModernFlyouts`   |                                                   ❌                                                   |
|     **[PowerToys](https://github.com/microsoft/PowerToys)**     |  🆓²  | [🟡](#-windows-enhancements "Light/Dark mode, Fluent design") |    ❌    |                              ❌                              |       `winget install -e --id Microsoft.PowerToys`       |                                                   ❌                                                   |
|    **[Revo Uninstaller](https://www.revouninstaller.com/)**     |  🆓   |                               ❌                               |    ❌    |                              ❌                              | `winget install -e --id RevoUninstaller.RevoUninstaller` | [🤖](https://play.google.com/store/apps/details?id=com.vsrevogroup.revouninstallermobile&hl=en&gl=US) |
|  **[RightKeyboard](https://github.com/mnivet/RightKeyboard)**   |  🆓²  |                               ❌                               |    ❌    |                              ❌                              |                            ❌                             |                                                   ❌                                                   |
|              **[ShareX](https://getsharex.com/)**               |  🆓²  |    [🟡](#-windows-enhancements "Selectable themes in app")    |    ❌    | [✔️](https://www.microsoft.com/store/productId/9NBLGGH4Z1SP) |          `winget install -e --id ShareX.ShareX`          |                                                   ❌                                                   |

</br>

### 🗄️ File Explorer Utilities

|                           Application                            | Price |                                  Themes                                  |                          Plugins                           |                                 MS Store                                  |                        Winget                        | Mobile |
|:----------------------------------------------------------------:|:-----:|:------------------------------------------------------------------------:|:----------------------------------------------------------:|:-------------------------------------------------------------------------:|:----------------------------------------------------:|:------:|
|               **[7-Zip](https://www.7-zip.org/)**                |  🆓²  | [🟡](https://github.com/huanrenfeng/7zipDarkmode "Unofficial dark mode") |                             ❌                              | [🟡](https://www.microsoft.com/store/productId/9MZ81RMK8JFD "Unofficial") |          `winget install -e --id 7zip.7zip`          |   ❌    |
| **[File Converter](https://file-converter.org/?from=readme.md)** |  🆓²  |                                    ❌                                     |                             ❌                              |                                     ❌                                     | `winget install -e --id FileConverter.FileConverter` |   ❌    |
|         **[Files](https://files-community.github.io/)**          |  🆓²  |     [🟡](#️-file-explorer-utilities "Light/Dark mode, Fluent design")     |                             ❌                              |        [✔️](https://www.microsoft.com/store/productId/9NGHP3DX8HDX)        |    `winget install -e --id Files-Community.Files`    |   ❌    |
|           **[QTTabBar](http://qttabbar.wikidot.com/)**           |  🆓   |                                    ❌                                     | [✔️](#️-file-explorer-utilities "Selectable plugins in app") |                                     ❌                                     |                          ❌                           |   ❌    |

</br>

### 🏔️ Desktop

|                           Application                           | Price |                                Themes                                |                               Plugins                                |                          MS Store                           | Winget |            Mobile             |
|:---------------------------------------------------------------:|:-----:|:--------------------------------------------------------------------:|:--------------------------------------------------------------------:|:-----------------------------------------------------------:|:------:|:-----------------------------:|
| **[Lively Wallpaper](https://rocksdanister.github.io/lively/)** |  🆓²  |           [🟡](#-desktop "Light/Dark mode, Fluent design")           |                                  ❌                                   | [✔️](https://www.microsoft.com/store/productId/9NTM2QC6QWS7) |   ❌    |               ❌               |
|           **[Rainmeter](https://www.rainmeter.net/)**           |  🆓²  | [🟡](https://visualskins.com/ "Many more skins across the internet") | [🟡](https://visualskins.com/ "Many more skins across the internet") |                              ❌                              |   ❌    |               ❌               |
|           **[Wallpaper Engine](https://premid.app/)**           |  🆓   |              [🟡](#-desktop "Selectable themes in app")              |                                  ❌                                   |                              ❌                              |   ❌    | [🤖](#-desktop "Coming Soon") |

</br>

### 📶 Remote Control

|                   Application                    | Price | Themes | Plugins | MS Store |                        Winget                        |                                                                               Mobile                                                                               |
|:------------------------------------------------:|:-----:|:------:|:-------:|:--------:|:----------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|      **[AnyDesk](https://anydesk.com/en)**       |  🆓   |   ❌    |    ❌    |    ❌     | `winget install -e --id AnyDeskSoftwareGmbH.AnyDesk` |        [🤖](https://play.google.com/store/apps/details?id=com.anydesk.anydeskandroid&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/anydesk/id1176131273)         |
| **[TeamViewer](https://www.teamviewer.com/it/)** |  🆓   |   ❌    |    ❌    |    ❌     |    `winget install -e --id TeamViewer.TeamViewer`    | [🤖](https://play.google.com/store/apps/details?id=com.teamviewer.teamviewer.market.mobile&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/teamviewer/id692035811) |
