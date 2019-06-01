# arch-linux-apple-emojis
Apple Emojis (iOS 12) for Arch Linux

<p align="center">
    <img src="https://raw.githubusercontent.com/chrisdruta/arch-linux-apple-emojis/master/scrot.png" width="60%">
</p>

## Install

1. Remove any emoji configs from `/etc/fonts/conf.d/`

2. Install ttf-emojione from the AUR and follow the directions at the end of the install about font configs

3. Replace `/usr/share/fonts/emojione/emojione.ttf` with the provided one in this repo

4. Run `fc-cache -f -v`

5. ???

6. Profit

## Credit

Inspired by https://github.com/Magisk-Modules-Repo/systemless-unicode9-ios10-Emoji
