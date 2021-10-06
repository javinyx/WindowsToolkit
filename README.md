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
    - [📨 Email Clients](#-email-clients)
    - [☑️ To do lists](#️-to-do-lists)
    - [📝 Text Editors](#-text-editors)
    - [⌨️ Code Editors](#️-code-editors)
    - [Terminals](#terminals)
    - [FTP Clients](#ftp-clients)
    - [Torrent Clients](#torrent-clients)
    - [Media Players](#media-players)
    - [Photo Viewers](#photo-viewers)
    - [PDF Readers](#pdf-readers)
    - [Instant Messengers](#instant-messengers)
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
- If themes or plugins/extensions are available, click on the ✔️ to browse them.
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

### 📨 Email Clients

|                                   Application                                   | Price |                                Themes                                |                              Plugins                              |                          MS Store                           |                     Winget                     |                                                                             Mobile                                                                             |
|:-------------------------------------------------------------------------------:|:-----:|:--------------------------------------------------------------------:|:-----------------------------------------------------------------:|:-----------------------------------------------------------:|:----------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| **[Mail and Calendar](https://www.microsoft.com/store/productId/9WZDNCRFHVQM)** |  🆓   |                 [✔️](#-email-clients "Fluent design")                 |                                 ❌                                 | [✔️](https://www.microsoft.com/store/productId/9WZDNCRFHVQM) |                       ❌                        | [🤖](https://play.google.com/store/apps/details?id=com.microsoft.office.outlook&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/microsoft-outlook/id951937596) |
|                  **[MailSpring](https://getmailspring.com/)**                   |  🆓²  |                  [✔️](#-email-clients "Light/Dark")                   |                                 ❌                                 |                              ❌                              | `winget install -e --id Foundry376.Mailspring` |                                                                               ❌                                                                                |
|          **[Mozilla ThunderBird](https://www.thunderbird.net/en-US/)**          |  🆓²  | [✔️](https://addons.thunderbird.net/en-US/thunderbird/static-themes/) | [✔️](https://addons.thunderbird.net/en-US/thunderbird/extensions/) |                              ❌                              |  `winget install -e --id Mozilla.Thunderbird`  |                                                                               ❌                                                                                |

</br>

### ☑️ To do lists

|                        Application                        | Price |           Themes            |             Plugins             |                          MS Store                           | Winget |                                                                        Mobile                                                                        |
|:---------------------------------------------------------:|:-----:|:---------------------------:|:-------------------------------:|:-----------------------------------------------------------:|:------:|:----------------------------------------------------------------------------------------------------------------------------------------------------:|
| **[Microsoft To Do](https://to-do.microsoft.com/tasks/)** |  🆓   | [✔️](#-to-do-lists "Fluent") | [✔️](#-to-do-lists "Light/Dark") | [✔️](https://www.microsoft.com/store/productId/9NBLGGH5R558) |   ❌    | [🤖](https://play.google.com/store/apps/details?id=com.microsoft.todos&hl=en&gl=US) [🍎](https://apps.apple.com/us/app/microsoft-to-do/id1212616790) |

</br>

### 📝 Text Editors

|                   Application                    | Price |               Themes                |                                          Plugins                                           |                                 MS Store                                 |                    Winget                    | Mobile |
|:------------------------------------------------:|:-----:|:-----------------------------------:|:------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------:|:--------------------------------------------:|:------:|
| **[Notepad++](https://notepad-plus-plus.org/)**  |  🆓²  |    [✔️](#-text-editors "In app")     | [✔️](https://github.com/notepad-plus-plus/nppPluginList/blob/master/doc/plugin_list_x64.md) | [✔️](https://www.microsoft.com/store/productId/9PHSCTZMKC27 "Unofficial") | `winget install -e --id Notepad++.Notepad++` |   ❌    |
| **[Notepads App](https://www.notepadsapp.com/)** |  🆓²  | [✔️](#-text-editors "Fluent design") |                                             ❌                                              |       [✔️](https://www.microsoft.com/store/productId/9NHL4NSC67WM)        |  `winget install -e --id Notepads.Notepads`  |   ❌    |

</br>

### ⌨️ Code Editors

|                       Application                        |              Price              |             Themes              |                     Plugins                      | MS Store |                       Winget                        | Mobile |
|:--------------------------------------------------------:|:-------------------------------:|:-------------------------------:|:------------------------------------------------:|:--------:|:---------------------------------------------------:|:------:|
|               **[Atom](https://atom.io/)**               |               🆓²               |   [✔️](https://atom.io/themes)   |          [✔️](https://atom.io/packages)           |    ❌     |        `winget install -e --id GitHub.Atom`         |   ❌    |
|    **[Sublime Text 3](https://www.sublimetext.com/)**    | [🟨](#-code-editors "Freemium") | [✔️](https://packagecontrol.io/) |         [✔️](https://packagecontrol.io/)          |    ❌     |   `winget install -e --id SublimeHQ.SublimeText`    |   ❌    |
| **[Visual Studio Code](https://code.visualstudio.com/)** |               🆓²               | [✔️](https://vscodethemes.com/)  | [✔️](https://marketplace.visualstudio.com/VSCode) |    ✔️     | `winget install -e --id Microsoft.VisualStudioCode` |   ❌    |

</br>

### Terminals

| Application                                                  | Free                | Themes                            | Plugins | Packages                                                                                                                                                                         | Mobile | Notes                                                          |
|--------------------------------------------------------------|---------------------|-----------------------------------|---------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|----------------------------------------------------------------|
| [Fluent Terminal](https://github.com/felixse/FluentTerminal) | :heavy_check_mark:² | :heavy_check_mark: Fluent, In app | :x:     | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/fluent-terminal), [MS Store](https://www.microsoft.com/store/productId/9P2KRLMFXF9T)                        | :x:    | A brand new and very customizable terminal                     |
| [Windows Terminal](https://github.com/microsoft/terminal)    | :heavy_check_mark:² | :heavy_check_mark: In app         | :x:     | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/microsoft-windows-terminal/1.6.10571.0), [MS Store](https://www.microsoft.com/store/productId/9N0DX20HK701) | :x:    | Microsoft's own open source Terminal, very intuitive and sleek |

### FTP Clients

| Application                                | Free                | Themes                           | Plugins | Packages                                                                                                                                                | Mobile | Notes                                                        |
|--------------------------------------------|---------------------|----------------------------------|---------|---------------------------------------------------------------------------------------------------------------------------------------------------------|--------|--------------------------------------------------------------|
| [CarotDAV](http://rei.to/carotdav_en.html) | :heavy_check_mark:  | :yellow_circle: Background image | :x:     | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/carotdav)                                                                          | :x:    | Very minimalistic interface and includes WebDAV Local Server |
| [FFFTP](https://github.com/ffftp/ffftp)    | :heavy_check_mark:² | :x:                              | :x:     | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/ffftp)                                                                             | :x:    | Many features packed in a small and open source package      |
| [WinSCP](https://winscp.net/eng/index.php) | :heavy_check_mark:  | :heavy_check_mark: In app        | :x:     | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/winscp), [MS Store (Paid)](https://www.microsoft.com/store/productId/9P0PQ8B65N8X) | :x:    | The most popular out of the three, this is a no-brainer      |

### Torrent Clients

| Application                                   | Free                | Themes                    | Plugins                                                                  | Packages                                                                          | Mobile | Notes                                      |
|-----------------------------------------------|---------------------|---------------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------|--------|--------------------------------------------|
| [Deluge](https://deluge-torrent.org/)         | :heavy_check_mark:  | :heavy_check_mark: In app | :heavy_check_mark: [Browse](https://dev.deluge-torrent.org/wiki/Plugins) | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/deluge)      | :x:    | Very fast bittorrent client made in Python |
| [qBitTorrent](https://github.com/ffftp/ffftp) | :heavy_check_mark:² | :heavy_check_mark: In app | :x:                                                                      | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/qbittorrent) | :x:    | Very popular open source bittorrent client |

### Media Players

| Application                              | Free                | Themes                                                                 | Plugins                                                                             | Packages                                                                                                                                                  | Mobile                                                                                                                                                                    | Notes                                                |
|------------------------------------------|---------------------|------------------------------------------------------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------|
| [mpv](https://mpv.io/)                   | :heavy_check_mark:² | :x:                                                                    | :x:                                                                                 | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/mpv)                                                                                 | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=is.xyz.mpv)                                                                                    | Small and clean open source media player             |
| [PotPlayer](https://potplayer.daum.net/) | :heavy_check_mark:  | :heavy_check_mark: [Browse](https://daumpotplayer.com/category/skins/) | :x:                                                                                 | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/potplayer)                                                                           | :x:                                                                                                                                                                       | Good looking media player, plays most types of files |
| [VLC](https://www.videolan.org/vlc/)     | :heavy_check_mark:² | :heavy_check_mark: [Browse](https://www.videolan.org/vlc/skins.html)   | :heavy_check_mark: [Browse](https://addons.videolan.org/browse/cat/323/ord/latest/) | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/vlc), [MS Store (Different)](https://www.microsoft.com/store/productId/9NBLGGH4VVNH) | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=org.videolan.vlc&hl=en&gl=US), [iOS](https://apps.apple.com/us/app/vlc-for-mobile/id650377962) | The most feature-rich player available               |

### Photo Viewers

| Application                                                                | Free               | Themes                                                           | Plugins                                                            | Packages                                                                                                                                            | Mobile | Notes                                                                            |
|----------------------------------------------------------------------------|--------------------|------------------------------------------------------------------|--------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|--------|----------------------------------------------------------------------------------|
| [IrfanView](https://www.irfanview.com/)                                    | :heavy_check_mark: | :heavy_check_mark: [Browse](https://www.irfanview.com/skins.htm) | :heavy_check_mark: [Browse](https://www.irfanview.com/plugins.htm) | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/IrfanView), [MS Store](https://www.microsoft.com/store/productId/9PJZ3BTL5PV6) | :x:    | An all-round complete viewer, great community                                    |
| [Microsoft Photos](https://www.microsoft.com/store/productId/9WZDNCRFJBH4) | :heavy_check_mark: | :heavy_check_mark: Fluent                                        | :x:                                                                | :heavy_check_mark: [MS Store](https://www.microsoft.com/store/productId/9WZDNCRFJBH4)                                                               | :x:    | The default photo viewer in Windows 10, it's getting better, but it's very basic |
| [XnViewMP](https://www.xnview.com/en/xnviewmp/)                            | :heavy_check_mark: | :heavy_check_mark: In app                                        | :heavy_check_mark: In app                                          | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/XnViewMP)                                                                      | :x:    | A very nice photo viewer in a small package                                      |

### PDF Readers

| Application                                           | Free                | Themes                    | Plugins | Packages                                                                              | Mobile                                                                                                                                                                                     | Notes                                                                          |
|-------------------------------------------------------|---------------------|---------------------------|---------|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| [Adobe Acrobat Reader](https://get.adobe.com/reader/) | :heavy_check_mark:  | :heavy_check_mark: In app | :x:     | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/adobereader)     | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=com.adobe.reader&hl=en&gl=US), [iOS](https://apps.apple.com/us/app/adobe-acrobat-reader-pdf-maker/id469337564)  | The most popular PDF reader ever, free version is useful for signing           |
| [Xodo](https://www.xodo.com/)                         | :heavy_check_mark:  | :heavy_check_mark: In app | :x:     | :heavy_check_mark: [MS Store](https://www.microsoft.com/store/productId/9WZDNCRDJXP4) | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=com.xodo.pdf.reader&hl=en&gl=US), [iOS](https://apps.apple.com/us/app/pdf-reader-annotator-by-xodo/id805075929) | The most feature packed free PDF viewer, able to edit, export and import pages |
| [Okular](https://okular.kde.org/)                     | :heavy_check_mark:² | :x:                       | :x:     | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/okular)          | :x:                                                                                                                                                                                        | Very simple interface, but A TON of features, plus it's open source            |

### Instant Messengers

| Application                           | Free                | Themes                    | Plugins | Packages                                                                                                                                           | Mobile                                                                                                                                                                                        | Notes                                                                  |
|---------------------------------------|---------------------|---------------------------|---------|----------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------|
| [Signal](https://signal.org/en/)      | :heavy_check_mark:² | :heavy_check_mark: In app | :x:     | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/signal)                                                                       | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms&hl=en&gl=US), [iOS](https://apps.apple.com/us/app/signal-private-messenger/id874139669) | The newest, open source instant messaging app                          |
| [Telegram](https://telegram.org/)     | :heavy_check_mark:² | :heavy_check_mark: In app | :x:     | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/telegram), [MS Store](https://www.microsoft.com/store/productId/9NZTWSQNTD0S) | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=org.telegram.messenger&hl=en&gl=US), [iOS](https://apps.apple.com/us/app/telegram-messenger/id686449807)           | The most feature rich messaging app, including bots, channels and more |
| [WhatsApp](https://www.whatsapp.com/) | :heavy_check_mark:  | :heavy_check_mark: In app | :x:     | :heavy_check_mark: [Choco](https://community.chocolatey.org/packages/WhatsApp), [MS Store](https://www.microsoft.com/store/productId/9NKSQGP7F2NH) | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=com.whatsapp&hl=en&gl=US), [iOS](https://apps.apple.com/us/app/whatsapp-messenger/id310633997)                     | Old and popular, but has the least features out of the three           |

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
