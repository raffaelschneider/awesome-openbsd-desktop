![Awesome OpenBSD wallpaper](https://raw.githubusercontent.com/raffaelschneider/awesome-openbsd-desktop/main/awesome_openbsd_desktop_hero.png)

# Awesome OpenBSD Desktop 🐡

A curated list of awesome applications, software, tools, and resources for using OpenBSD as a daily driver. Inspired by the various Awesome lists that exist for a wide variety of tech ecosystems and the robust, secure, and quality codebase of OpenBSD.

➡️ If you want more of these OpenBSD visuals, go check [here](https://github.com/raffaelschneider/openbsd-wallpapers) to get one of these wallpapers for yourself!

## Contents

- [Desktop Environments](#desktop-environments)
- [Window Managers](#window-managers)
- [Terminal Emulators](#terminal-emulators)
- [Text Editors](#text-editors)
- [Web Browsers](#web-browsers)
- [Email Clients](#email-clients)
- [File Managers](#file-managers)
- [Multimedia](#multimedia)
- [Office](#office)
- [System Monitoring](#system-monitoring)
- [Security Tools](#security-tools)
- [Miscellaneous Tools](#miscellaneous-tools)
- [Desktop Setup Guides](#desktop-setup-guides)
- [Resources](#resources)
- [Contributing](#contributing)

## Desktop Environments

- [Xfce](https://www.xfce.org/) - A lightweight desktop environment, popular on OpenBSD due to low resource usage. Available as xfce-4.20.
- [GNOME](https://www.gnome.org/) - A modern, full-featured desktop environment. OpenBSD 7.7+ includes GNOME 47.
- [KDE Plasma](https://kde.org/plasma-desktop/) - A polished, highly configurable desktop. KDE Plasma 6.4 is available in OpenBSD packages.
- [MATE](https://mate-desktop.org/) - A continuation of GNOME 2, providing a traditional desktop experience.
- [LXQt](https://lxqt-project.org/) - A lightweight Qt-based desktop environment. Available as LXQt 2.3.0.

## Window Managers

- [cwm](https://man.openbsd.org/cwm) - OpenBSD's native calm window manager. Lightweight, keyboard-oriented, and included in base.
- [fvwm](https://www.fvwm.org/) - A virtual window manager for X11, included in OpenBSD base.
- [twm](https://man.openbsd.org/twm) - Tab window manager, also included in OpenBSD base.
- [i3](https://i3wm.org/) - A tiling window manager, completely written from scratch.
- [dwm](https://dwm.suckless.org/) - A dynamic window manager for X11 from suckless.
- [spectrwm](https://github.com/conformal/spectrwm) - A small dynamic tiling window manager for X11.
- [Openbox](http://openbox.org/) - A highly configurable stacking window manager with extensive standards support.
- [bspwm](https://github.com/baskerville/bspwm) - A tiling window manager based on binary space partitioning.

## Terminal Emulators

- [xterm](https://man.openbsd.org/xterm) - The standard terminal emulator for the X Window System, included in base.
- [st](https://st.suckless.org/) - A simple terminal implementation for X from suckless.
- [Alacritty](https://alacritty.org/) - A cross-platform, GPU-accelerated terminal emulator written in Rust.
- [kitty](https://sw.kovidgoyal.net/kitty/) - A fast, feature-rich, GPU-based terminal emulator.
- [foot](https://codeberg.org/dnkl/foot) - A fast, lightweight, and minimalistic terminal emulator.
- [rxvt-unicode](http://software.schmorp.de/pkg/rxvt-unicode.html) - A customizable terminal emulator (urxvt).
- [Zutty](https://tomscii.sig7.se/zutty/) - A high-end terminal for low-end systems.
- [xfce4-terminal](https://docs.xfce.org/apps/terminal/start) - The Xfce terminal emulator.

## Text Editors

- [vi](https://man.openbsd.org/vi) - The classic visual editor, included in OpenBSD base (nvi).
- [ed](https://man.openbsd.org/ed) - The standard line editor, included in OpenBSD base.
- [vim](https://www.vim.org/) - Vi Improved, an advanced text editor with a complete feature set.
- [Neovim](https://neovim.io/) - A modern, extensible Vim-based editor with Lua scripting.
- [helix](https://helix-editor.com/) - A post-modern modal text editor written in Rust.
- [kakoune](https://kakoune.org/) - A modal editor with multiple selections and orthogonal design.
- [emacs](https://www.gnu.org/software/emacs/) - An extensible, customizable, self-documenting editor.
- [nano](https://www.nano-editor.org/) - An easy to use, modeless text editor.
- [micro](https://micro-editor.github.io/) - A modern, intuitive terminal-based text editor.

## Web Browsers

- [Firefox](https://www.mozilla.org/firefox/) - A free and open-source web browser developed by Mozilla.
- [LibreWolf](https://librewolf.net/) - A privacy-focused Firefox fork with telemetry removed and uBlock Origin included.
- [Chromium](https://www.chromium.org/) - An open-source browser project. Supports VA-API hardware acceleration on OpenBSD.
- [Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium) - Chromium with Google services and telemetry removed. VA-API supported.
- [Iridium](https://iridiumbrowser.de/) - A privacy-focused Chromium-based browser.
- [Lynx](https://lynx.browser.org/) - A highly configurable text-based web browser.
- [w3m](https://w3m.sourceforge.net/) - A text-based web browser and pager.

## Email Clients

- [Thunderbird](https://www.thunderbird.net/) - A free, full-featured email application.
- [mutt](http://www.mutt.org/) - A small but powerful text-based mail client.
- [neomutt](https://neomutt.org/) - A command-line mail reader based on Mutt with added features.
- [aerc](https://aerc-mail.org/) - A pretty good email client for your terminal.
- [alpine](https://alpine.x10host.com/) - A fast, easy to use email client.

## File Managers

- [Thunar](https://docs.xfce.org/xfce/thunar/start) - A modern file manager for Xfce.
- [PCManFM](https://github.com/lxde/pcmanfm) - A lightweight file manager with tabbed browsing.
- [Dolphin](https://apps.kde.org/dolphin/) - KDE's feature-rich file manager.
- [Midnight Commander](https://midnight-commander.org/) - A powerful console file manager (mc).
- [ranger](https://ranger.github.io/) - A console file manager with VI key bindings.
- [lf](https://github.com/gokcehan/lf) - A terminal file manager written in Go, inspired by ranger.
- [nnn](https://github.com/jarun/nnn) - A tiny, lightning fast terminal file manager.
- [vifm](https://vifm.info/) - A file manager with ncurses interface providing Vim-like environment.

## Multimedia

- [mpv](https://mpv.io/) - A free, open-source, cross-platform media player.
- [VLC](https://www.videolan.org/vlc/) - A versatile multimedia player supporting most formats.
- [ffmpeg](https://ffmpeg.org/) - A complete solution for recording, converting, and streaming audio/video. Version 8.0+ in ports.
- [Audacity](https://www.audacityteam.org/) - A free, open-source audio editor and recorder.
- [GIMP](https://www.gimp.org/) - GNU Image Manipulation Program for image editing.
- [Inkscape](https://inkscape.org/) - A professional vector graphics editor.
- [sndio](https://sndio.org/) - OpenBSD's native audio and MIDI framework.
- [cmus](https://cmus.github.io/) - A small, fast, and powerful console music player.

## Office

- [LibreOffice](https://www.libreoffice.org/) - A powerful, full-featured office suite.
- [Calligra](https://calligra.org/) - A KDE-based office suite.
- [Gnumeric](http://www.gnumeric.org/) - A fast, accurate spreadsheet application.
- [AbiWord](http://www.abisource.com/) - A lightweight word processor.
- [Zathura](https://pwmt.org/projects/zathura/) - A minimalistic document viewer with vim-like keybindings.
- [Evince](https://wiki.gnome.org/Apps/Evince) - GNOME's document viewer for PDF and other formats.

## System Monitoring

- [top](https://man.openbsd.org/top) - Display and update information about the top CPU processes, included in base.
- [systat](https://man.openbsd.org/systat) - Display system statistics, included in base.
- [htop](https://htop.dev/) - An interactive process viewer for Unix systems.
- [btop](https://github.com/aristocratos/btop) - A modern resource monitor with a sleek interface.
- [glances](https://nicolargo.github.io/glances/) - A cross-platform system monitoring tool written in Python.
- [iftop](http://www.ex-parrot.com/~pdw/iftop/) - Display bandwidth usage on an interface.
- [bandwhich](https://github.com/imsnif/bandwhich) - Terminal bandwidth utilization tool.

## Security Tools

- [OpenSSH](https://www.openssh.com/) - A suite of secure networking utilities, developed by OpenBSD and included in base.
- [LibreSSL](https://www.libressl.org/) - A TLS/crypto stack forked from OpenSSL by the OpenBSD project.
- [pf](https://man.openbsd.org/pf) - OpenBSD's packet filter firewall, included in base.
- [doas](https://man.openbsd.org/doas) - A simpler sudo alternative, developed by OpenBSD and included in base.
- [signify](https://man.openbsd.org/signify) - Cryptographically sign and verify files, included in base.
- [GnuPG](https://gnupg.org/) - A complete implementation of the OpenPGP standard.
- [nmap](https://nmap.org/) - A network exploration tool and security scanner.
- [tcpdump](https://www.tcpdump.org/) - A powerful command-line packet analyzer, included in base.
- [Wireshark](https://www.wireshark.org/) - A graphical network protocol analyzer.

## Miscellaneous Tools

- [tmux](https://github.com/tmux/tmux/wiki) - A terminal multiplexer for managing multiple terminal sessions.
- [fzf](https://github.com/junegunn/fzf) - A command-line fuzzy finder.
- [ripgrep](https://github.com/BurntSushi/ripgrep) - A fast line-oriented search tool (rg).
- [fd](https://github.com/sharkdp/fd) - A simple, fast alternative to find.
- [bat](https://github.com/sharkdp/bat) - A cat clone with syntax highlighting.
- [eza](https://github.com/eza-community/eza) - A modern replacement for ls.
- [fastfetch](https://github.com/fastfetch-cli/fastfetch) - A fast system information tool (replaces archived neofetch).
- [starship](https://starship.rs/) - A minimal, fast, customizable shell prompt.
- [zoxide](https://github.com/ajeetdsouza/zoxide) - A smarter cd command.

## Desktop Setup Guides

- [OpenBSD Handbook - Graphical Environments](https://www.openbsdhandbook.com/graphical-environments/) - Comprehensive guide covering X11, window managers, and desktop environments.
- [What To Do After A Fresh OpenBSD Install](https://i-bsd.com/openbsd-first-steps/) - Step-by-step post-installation guide.
- [How to Install GNOME on OpenBSD](https://www.musabase.com/2025/08/install-and-configure-desktop-sessions-on-openbsd.html) - Guide to setting up GNOME desktop.
- [Setting Up a Desktop Environment for OpenBSD](https://btxx.org/wiki/openbsd/desktop_environment/) - dwm-focused desktop setup guide.
- [Building an OpenBSD Desktop](https://nfalcone.net/blog/building-openbsd-desktop-laptop/) - Desktop/laptop setup walkthrough.
- [OpenBSD on a Laptop by c0ffee.net](https://www.c0ffee.net/blog/openbsd-on-a-laptop/) - Classic laptop setup guide, highly recommended.
- [OpenBSD on the Desktop (Part I) by Patrick Bucher](https://www.paedubucher.ch/articles/open-bsd-on-the-desktop-part-1/)
- [OpenBSD on the Desktop (Part II) by Patrick Bucher](https://www.paedubucher.ch/articles/open-bsd-on-the-desktop-part-2/)
- [OpenBSD Minimalist Desktop by Daniel Nechtan](https://www.nechtan.io/articles/openbsd_minimalist_desktop.html)

## Resources

- [Official OpenBSD Website](https://www.openbsd.org/) - The official project website.
- [OpenBSD FAQ](https://www.openbsd.org/faq/) - Official documentation and FAQ.
- [OpenBSD Handbook](https://www.openbsdhandbook.com/) - Community-maintained comprehensive handbook.
- [OpenBSD Ports](https://openports.pl/) - Searchable OpenBSD ports database.
- [OpenBSD man pages](https://man.openbsd.org/) - Official online manual pages.
- [r/openbsd](https://www.reddit.com/r/openbsd/) - OpenBSD subreddit community.
- [Lobsters - OpenBSD](https://lobste.rs/t/openbsd) - OpenBSD discussions on Lobsters.
- [Awesome OpenBSD](https://github.com/ligurio/awesome-openbsd) - A curated list of awesome OpenBSD resources.
- [OpenBSD Journal (Undeadly)](https://undeadly.org/) - News and articles about OpenBSD.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

---

Feel free to fork this repository, add your contributions, and send a pull request to expand the Awesome OpenBSD Desktop list!
