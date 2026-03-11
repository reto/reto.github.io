# Welcome to my Github page

I mainly use this page to set up a new pc...

## Chocolatey

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

For starhip in cmd.exe see this
https://chrisant996.github.io/clink
https://chrisant996.github.io/clink/clink.html#starship

```
choco install clink-maintained
````

## On Linux
Install fish using ppa-launchpad
https://fishshell.com
DejaVuSansMono or firacode `apt install fonts-firacode`
```
add-apt-repository ppa:fish-shell/release-4
apt update
apt install fish
echo 'exec fish' >>  ~/.bashrc
fish
```

(I like this approach (loading fish on top of bash) so that all the scripts that do not specify a shell will still launch with the system default shell sh or bash and not with fish).

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
