# Welcome to my Github page

I mainly use this page to set up a new pc...

## Chocolatey

https://docs.chocolatey.org/en-us/choco/setup/

```
choco install 7zip anytype autohotkey bind-toolsonly chocolatey chocolateygui clink-maintgained cpu-z em-client Everything FiraCode Firefox git github-desktop GoogleChrome googledrive googleearthpro greenshot InkScape irfanview irfanviewplugins josm keepass keepass-plugin-keeagent keepass-plugin-keeautoexec keepass-plugin-keeotp2 keystore-explorer nerd-fonts-DejaVuSansMono notepadplusplus nvm OpenSSL.Light putty python3 rawtherapee rdcman rufus sharpkeys signal speccy starship sumatrapdf sysinternals teamviewer Temurin17 thunderbird vcxsrv vivaldi vlc vscode WinDirStat winscp zotero
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
