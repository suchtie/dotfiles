# Ocean v2

![temp-screenshot](https://i.imgur.com/g0AN1Bx.png)

WIP screenshot. Still got a few things to change and add later.

# Requirements

- [i3-gaps](https://github.com/Airblader/i3)
- [polybar](https://github.com/jaagr/polybar)
- terminal emulator with 256 colors and Unicode support (configs provided for termite and rxvt-unicode)
- compton

I use the i3-gaps "next" branch but the stable branch should work too. Not gonna test it, you're on your own.

## Other software you may want

- dunst
- i3lock

## Other resources

- colorscheme: [Nord](https://github.com/arcticicestudio/nord)
- GTK theme: [Arc-Dark](https://github.com/horst3180/Arc-theme)
- Icons: [Moka icon theme](http://snwh.org/moka/download/moka-icon-theme)
- Fonts: termsyn, Wuncon Siji, scientifica (optionally), FuraCode Nerd Font Mono (or any other monospace Nerd Font,
or any font that includes a ton of unicode glyphs - FontAwesome may work too)

On Arch, you can install all these, including the Nord theme for vim and plugins, from the AUR.

I also recommend installing the full Nerd Fonts package.

# TODO

In order of significance:

- [x] find a better colorscheme because base16-ocean just doesn't fit that well
- [x] improve polybar config
- [ ] improve dunst config
- [ ] setup mpd/ncmpcpp
- [ ] rice zathura
- [ ] maybe make a midnightcommander theme?

# Disclaimer

Use at your own risk. I'm not responsible if you broke something because you just used everything
as-is, without modifying files to fit your system.

I'm working on making the config files cleaner and comment them nicely. Until then, things may be a little chaotic.

Please pretend that the MIT license applies to all files in this repository. I don't really care what you do
with them - share, copy, modify, fork, whatever. Just don't post them elsewhere and say you made them. I use
material from other people too, with varying licenses, so I don't want to actually apply a license.

# Acknowledgments

Github usernames.

- Airblader - author of i3-gaps, and I stole some parts of his configs
- adi1090x - master of rice whom I stole some configs from. Has an incredible i3 rice, check it out!
- emkay443 - a friend who helped me with bash
- lokesh-krishna - for the Nord theme for rofi
- reddit user /u/\_\_\_\_\_frost\_\_\_ - even though they never actually post their dotfiles, they were
great inspiration. I copied the polybar configuration as well as I could.

# Trivia

- I currently use this setup by keeping this repo in a folder in my $HOME, and symlinking
all files from their actual locations. This way I can more easily keep things up-to-date
on both my desktop PC and laptop, since I just need to add/commit/push changed files,
and pull on the other device. Then I just need to change comments around since a few
things differ between my laptop and desktop setups. (A more elegant way of doing this would be making
my entire home folder a git repo and taking care of include/exclude files... but I'm not a programmer,
I literally only use git to sync this rice, and in the spirit of "don't fix what's not broken"
I have no intention of changing it.)
- I am also  using xfce4-power-manager. That's because my chinaware
abomination of a laptop uses some arcane technology which makes the screen brightness buttons very difficult
to work with, but Xfce's power manager can do it somehow. I also use it on my desktop for energy saving.

*Constructive* criticism concerning my rice is very welcome.

Criticism, constructive as it may be, concerning my methods, writing style, formatting etc. will more than
likely fall on deaf ears. I have no interest in "doing things the right way".
I just want things to work, and as I am not a programmer, you will not
have to deal with my atrocities anywhere but in this exact git repo. So, deal with it. :)
