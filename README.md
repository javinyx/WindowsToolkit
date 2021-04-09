# WindowsToolkit
A collection of **Windows 10 apps and scripts** to optimize user and poweruser experience.

To make it in this list, apps must meet two or more of the following criteria:
* *Open Source* / *Free to use*
* *Customizable UI* / *Fluent Design*
* *Available in [Chocolatey Repository](https://community.chocolatey.org/packages)* / [Microsoft Store](https://www.microsoft.com/en-us/store/apps/windows)
* *Cross-device compatibility*

The list tries to give at least one alternative to each top pick for each app section, if a Chocolatey Package is available I prioritize it over the Microsoft Store alternative.

## Why was this made?

I believe that Windows is still far behind in terms of application installation, making us of a packet manager like Chocolatey can help you keep track of what's installed and of updates.

I also think that many applications are simply unknown to many people, therefore I want to give light to some of them. If, like me, you're using Windows, Android and iPadOS on a daily basis you will be able to find some nice cross-platform apps.

If you want to provide feedback please do so using GitHub Issues.

# Applications

While [Microsoft Store](https://www.microsoft.com/en-us/store/apps/windows) is pre-installed in Windows 10, [Chocolatey](https://chocolatey.org/install) is not, so here is how to install it.

> All of the information below is taken from the official Chocolatey site, link above.

**Requirements:**
* Windows 7+ / Windows Server 2003+
* PowerShell v3+
* .NET Framework 4.5+

**Installation:**
1. Press **Windows+R** to open the *Run* box.
2. Type `cmd` into the box and then press **Ctrl+Shift+Enter** to run the command as an administrator.
3. Run `Get-ExecutionPolicy`. If it returns `Restricted`, then run `Set-ExecutionPolicy AllSigned` ***OR*** `Set-ExecutionPolicy Bypass -Scope Process`.
4. Run the code below:

       Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

5. Wait a few seconds for the command to complete.
6. If you don't see any errors, you are ready to use Chocolatey! Type `choco` or `choco -?` now, or see [Getting Started](https://docs.chocolatey.org/en-us/getting-started) for usage instructions.

Now that the Chocolatey installation is done, let's get started!

## Browsers
Application | Free | Design | Ch / MS | X | Notes |
--- | --- | --- | --- | --- | --- |
Google Chrome        | :heavy_check_mark: |                    |                    |                    |                    |
Microsoft Edge       | :heavy_check_mark: |                    |                    |                    |                    |
Mozilla Firefox      | :heavy_check_mark:	|                    |                    |                    |                    |

## Text Editors
- Notepad++
- Visual Studio Code

## Gaming
- Steam
- Playnite
- GOG Galaxy

## FTP Client
- WinSCP
- FileZilla

## Media Players
- Pot Player
- VLC

## Media Viewers
- IrfanView

## PDF
- Acrobat Reader
- Xodo

## Audio
- EarTrumpet
- VB-AudioCable
- VoiceMeeter

## SoundBoard
- SoundPad
- Resanance

## Social
- Telegram
- WhatsApp Web
- Discord

## Password Managers
- BitWarden
- KeePass

## To do lists
- Microsoft To-do
- Trello

## Utilities
- File Converter
- CCleaner
- Ditto Clipboard
- Everything

## Torrent Client
- qBitTorrent

## Other
- PreMid
- PowerToys
- ShareX
