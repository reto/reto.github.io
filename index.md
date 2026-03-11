# Welcome to my Github page

I mainly use this page to set up a new pc...

## Chocolatey

https://docs.chocolatey.org/en-us/choco/setup/

Load it like this: `choco install packages.config`

Export it like this `choco export --output-file-path="'c:\temp\packages.config'"`

```
<?xml version="1.0" encoding="utf-8"?>
<packages>
  <package id="7zip" />
  <package id="autohotkey" />
  <package id="autohotkey.install" />
  <package id="bind-toolsonly" />
  <package id="chocolateygui" />
  <package id="chocolatey-windowsupdate.extension" />
  <package id="cpu-z" />
  <package id="Everything" />
  <package id="FiraCode" />
  <package id="git" />
  <package id="github-desktop" />
  <package id="googledrive" />
  <package id="googleearthpro" />
  <package id="gpu-z" />
  <package id="greenshot" />
  <package id="irfanview" />
  <package id="irfanviewplugins" />
  <package id="josm" />
  <package id="keepass" />
  <package id="keepass.install" />
  <package id="keepass-plugin-keeagent" />
  <package id="keepass-plugin-keeautoexec" />
  <package id="keystore-explorer.portable" />
  <package id="nerd-fonts-DejaVuSansMono" />
  <package id="notepadplusplus" />
  <package id="nvm" />
  <package id="openjdk" />
  <package id="OpenSSL.Light" />
  <package id="putty" />
  <package id="python" />
  <package id="rdcman" />
  <package id="rufus" />
  <package id="sharpkeys" />
  <package id="signal" />
  <package id="speccy" />
  <package id="starship" />
  <package id="sumatrapdf" />
  <package id="sysinternals" />
  <package id="teamviewer" />
  <package id="vivaldi" />
  <package id="vlc" />
  <package id="vscode" />
  <package id="WinDirStat" />
  <package id="winscp" />
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
