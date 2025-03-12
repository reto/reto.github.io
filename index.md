# Welcome to my Github page

## (Mainly free) Windows tools collection
Whenever I set up a new PC I need some tools to install. Often I forget one or two. Therefore I created this page. It is mainly for myself. But if it useful to you as well, then it is even better!

### Internet/Messenger
* [Chrome](https://www.google.com/chrome/) Google's Browser
  * [uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm?hl=en) Ad- and tracking-blocker plugin for Chrome
* [Firefox](https://www.mozilla.org/en-US/firefox/) Mozilla's browser
  * [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) Ad- and tracking-blocker plugin for Firefox
* [Skype](https://www.skype.com/en/get-skype/) Internet telephony
* [Slack](https://slack.com/downloads/windows) Group messenger

### FileSync/CloudSpace
* [Dropbox](https://www.dropbox.com)
* [GoogleDrive](https://g.co/BackupAndSyncDrive)
* [Tresorit](https://tresorit.com/)
* [SpiderOak](https://spideroak.com/)

### Security
* [Putty Suite](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html) SSH client
* [Winscp](https://winscp.net/eng/download.php) SCP/SFTP/FTP client (works well with Keepass/KeeAgent)
* [Keepass](https://keepass.info/) Password manager
  * [KeeAgent](https://lechnology.com/software/keeagent/) Keepass SSH Agent, serves SSH-Keys stored in keypass to putty & winscp
  * [KeeAutoExec](https://keepass.info/plugins.html#keeautoexec) Automatically open other databases

### Audio/Video
* [VLC](https://www.videolan.org/) Video Player with extensive format support
* [EqualizerAPO](https://sourceforge.net/projects/equalizerapo/) Equalizer for Windows with advanced support for channel mixing/copying.
* [Audacity](https://www.audacityteam.org/) Free sound editor
* [Open Broadcast Software](https://obsproject.com/) Screen recorder (focus on live uploading for gamers, but works very well for normal screen redording too).

### Imaging
* [IrfanView](https://www.irfanview.com/) Fast image viewer, also great for batch processing (scaling, conversion, ...)
* [Inkscape](https://inkscape.org/)  Open Source vector graphics editor (think InDesign, but free)
* [Paint.net](https://www.getpaint.net/) Pixel-based image editing. Somewhere between Photoshop and MS Paint
* [GIMP](https://www.gimp.org/downloads/) GNU Image Manipulation Program - alternative to Photoshop
* [RawTherapee](http://rawtherapee.com/downloads) Free RAW image editor - alternative to Lightroom

### Desktop / Productivity
* [7-zip](https://www.7-zip.org/) Zip and LZMA2 compression tool
* [SumatraPDF](https://www.sumatrapdfreader.org/free-pdf-reader.html) Free PDF reader without bloat- or adware
* [Greenshot](http://getgreenshot.org/) Screenshot utility
* [Everything](https://www.voidtools.com/) Index file search
* [LibreOffice](https://www.libreoffice.org/) Open source Office Suite (Word processor, Spreadsheet, Presentation tool, ...)
* [Notepad++](https://notepad-plus-plus.org/) Great text file editor
  * [XML Plugin for Notepad++](https://sourceforge.net/projects/npp-plugins/files/XML%20Tools/) With schema validation on save/demand
* [Kdiff3](http://kdiff3.sourceforge.net/) File/Directory comparison too. Diff viewer (3-way capable). With recursive directory compare
* [PDFCreator](http://download.pdfforge.org/download/pdfcreator/PDFCreator-stable) Free PDF Creator (Warning: Make sure you disable all the additional software the installer tries to install. E.g. PDFArchitect and what not...)

### Development
* [Github Desktop](https://desktop.github.com/) Github Desktop client
* [TortoiseHG](https://tortoisehg.bitbucket.io/) Mercurial Windows client (comes with kdiff3 (3-way diff tool))
* [TortoiseGit](https://tortoisegit.org/download/) Git Windows client
* [TortoiseSVN](https://tortoisesvn.net/) Subversion Windows client (comes with TortoiseMerge (2-way diff tool)
* [Python](https://www.python.org/) Python interpreter
  * [Python(x,y)](https://python-xy.github.io/) Python for scientists, including an IDE
  * [PyCharm](https://www.jetbrains.com/pycharm/) Jetbrains Python IDE (*not free*)
* [Eclipse](https://www.eclipse.org/) Multilingual development IDE
* [Jetbrains IntelliJ IDEA](https://www.jetbrains.com/idea/) Non-free! Multilingual development IDE
* [XML Notepad](https://github.com/Microsoft/XmlNotepad/wiki) XML Editor

### Sysadmin Tools
* [KeyStore Explorer](http://keystore-explorer.org/)  A GUI replacement for keytool and jarsigner
* [Win32OpenSSL](https://slproweb.com/products/Win32OpenSSL.html) OpenSSL for Windows (also 64bit available)
* [TreeSize Free](https://www.jam-software.com/treesize_free/) Analyze where your disk space has gone
* [USB Tree View](https://www.uwe-sieber.de/usbtreeview_e.html) USB Device Tree Viewer with lots of low-level USB information

### Research & Science
* [JabRef](http://www.jabref.org/) Open source bibliography reference manager
* [Octave](https://www.gnu.org/software/octave/) Drop-in replacement for Matlab

## Chocolatey config file

https://docs.chocolatey.org/en-us/choco/setup/

Load it like this: `choco install packages.config`

```
<?xml version="1.0" encoding="utf-8"?>
<packages>
  <package id="7zip" />
  <package id="7zip.install" />
  <package id="anytype" />
  <package id="autohotkey" />
  <package id="autohotkey.install" />
  <package id="bind-toolsonly" />
  <package id="chocolatey" />
  <package id="chocolatey-compatibility.extension" />
  <package id="chocolatey-core.extension" />
  <package id="chocolatey-dotnetfx.extension" />
  <package id="chocolatey-font-helpers.extension" />
  <package id="chocolateygui" />
  <package id="chocolatey-windowsupdate.extension" />
  <package id="cpu-z" />
  <package id="cpu-z.install" />
  <package id="DotNet4.6.1" />
  <package id="dotnetfx" />
  <package id="em-client" />
  <package id="Everything" />
  <package id="FiraCode" />
  <package id="Firefox" />
  <package id="git" />
  <package id="git.install" />
  <package id="github-desktop" />
  <package id="GoogleChrome" />
  <package id="googledrive" />
  <package id="googleearthpro" />
  <package id="gpu-z" />
  <package id="greenshot" />
  <package id="heidisql" />
  <package id="hg" />
  <package id="InkScape" />
  <package id="irfanview" />
  <package id="irfanviewplugins" />
  <package id="josm" />
  <package id="KB2919355" />
  <package id="KB2919442" />
  <package id="KB2999226" />
  <package id="KB3033929" />
  <package id="KB3035131" />
  <package id="keepass" />
  <package id="keepass.install" />
  <package id="keepass-plugin-keeagent" />
  <package id="keepass-plugin-keeautoexec" />
  <package id="keepass-plugin-keeotp2" />
  <package id="keystore-explorer.portable" />
  <package id="nerd-fonts-DejaVuSansMono" />
  <package id="nextcloud-client" />
  <package id="notepadplusplus" />
  <package id="notepadplusplus.install" />
  <package id="notion" />
  <package id="nvm" />
  <package id="nvm.install" />
  <package id="openjdk" />
  <package id="OpenSSL.Light" />
  <package id="pandoc" />
  <package id="postgresql" />
  <package id="postgresql17" />
  <package id="putty" />
  <package id="putty.portable" />
  <package id="python" />
  <package id="python3" />
  <package id="python311" />
  <package id="python312" />
  <package id="python313" />
  <package id="rawtherapee" />
  <package id="rdcman" />
  <package id="rufus" />
  <package id="sharpkeys" />
  <package id="signal" />
  <package id="speccy" />
  <package id="sql-server-management-studio" />
  <package id="starship" />
  <package id="starship.install" />
  <package id="sumatrapdf" />
  <package id="sumatrapdf.install" />
  <package id="svn" />
  <package id="sysinternals" />
  <package id="teamviewer" />
  <package id="Temurin17" />
  <package id="thunderbird" />
  <package id="vcredist140" />
  <package id="vcredist2015" />
  <package id="vcredist2017" />
  <package id="vcxsrv" />
  <package id="vivaldi" />
  <package id="vivaldi.portable" />
  <package id="vlc" />
  <package id="vlc.install" />
  <package id="vscode" />
  <package id="vscode.install" />
  <package id="WinDirStat" />
  <package id="winscp" />
  <package id="winscp.install" />
  <package id="zotero" />
</packages>
```

And pinned are these
```
❯ choco pin list
Chocolatey v2.4.3
GoogleChrome|116.0.5845.180
googledrive|100.0.2
signal|7.31.0
vivaldi|7.0.3495.23
vivaldi.portable|7.0.3495.23
vscode|1.98.0
vscode.install|1.98.0
```

# Starship & Fish
Follow the installation here:
https://starship.rs


## On Windows
```
choco install starship -y
choco install nerd-fonts-DejaVuSansMono -y
```
Make sure you have the choco package `nerd-fonts-DejaVuSansMono` installed. (It is above in the package.config)

In powershell you need to set the font manually.
In putty you need to set the font manually and safe as default!

## On Linux
Install fish using ppa-launchpad
https://fishshell.com
DejaVuSansMono or firacode `apt install fonts-firacode`
```
add-apt-repository ppa:fish-shell/release-4
apt update
apt install fish
```

```
nano ~/.bashrc
```

at the very end add a line `fish`
(I like this approach so that all the scripts that do not specify a shell will still launch with the system default shell sh or bash and not with fish).

Install starship using

```
curl -sS https://starship.rs/install.sh | sh
```

This is also how to to update

Inside the interactive block of the file 

```
nano ~/.config/fish/config.fish
```

add the following oneliner:

```
starship init fish | source
```
