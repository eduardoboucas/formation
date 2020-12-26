> _**Please note** that this specific repo is a customised version of the [original project](https://github.com/minamarkham/formation) by [@minamarkham](https://github.com/minamarkham). All props go to her!_ 👏🏻


# 🐝 Formation <a href="https://www.patreon.com/minamarkham"><img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="100"></a>

![Let's get in formation](assets/formation.gif)
> Formation is a shell script to set up a macOS laptop for design and development.

It can be run multiple times on the same machine safely. It installs, upgrades, or skips packages based on what is already installed on the machine.

## Install

Download the script and review it (please don't run scripts you don't understand):

```sh
git clone git@github.com/eduardoboucas/formation.git && cd formation && less slay
```

Slay:

```sh
git clone git@github.com/eduardoboucas/formation.git && cd formation && ./slay 2>&1 | tee ~/slay.log
```

Just follow the prompts and you’ll be fine. 👌

⚠️ Warning: I advise against running [this script](slay) unless you understand what it’s doing to your computer.

I created this based on my own preferences; your mileage may vary.

Once the script is done, quit and relaunch Terminal.

It is highly recommended to run the script regularly to keep your computer up to date.

Your last Formation run will be saved to `~/slay.log`. To review it, run `less ~/slay.log`.

That's it! :sparkles:

## Known Issues
Cask does not recognize applications installed outside of Homebrew Cask – in the case that the script fails, you can either remove the application from the install list or uninstall the application causing the failure and try again.

## Acknowledgements

Inspiration and code was taken from many sources, including:

* [Mathias Bynens'](https://github.com/mathiasbynens) [dotfiles](https://github.com/mathiasbynens/dotfiles)
* thoughtbot's [laptop](https://github.com/thoughtbot/laptop/)

## 📜  License

Formation is customized for my own needs. It is free software, and may be redistributed under the terms specified in the [LICENSE] file.

[LICENSE]: LICENSE
