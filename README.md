<h1 align="center">
  <samp style="color: #ffffff; background-color: #ffbc00;">Awesome Wayland</samp>

[![Link Check](https://github.com/rcalixte/awesome-wayland/actions/workflows/link_check.yml/badge.svg?branch=master)](https://github.com/rcalixte/awesome-wayland/actions/workflows/link_check.yml)
</h1>

A curated list of [Wayland-rs](https://github.com/Smithay/wayland-rs) resources. Please investigate these projects on your own before fully committing to them!

This repository is a fork of [rcalixte/awesome-wayland](https://github.com/rcalixte/awesome-wayland) for people only interested in software built with rust.

There are no current plans to apply to the [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) project for inclusion.

> [!NOTE]
> If you want to contribute, feel free to open a PR.


TABLE OF CONTENTS
-----------------

- [SCOPE](#scope)
- [TABLE OF CONTENTS](#table-of-contents)
- [BINDINGS](#bindings)
- [BREAK NOTIFIERS](#break-notifiers)
- [BRIGHTNESS CONTROL](#brightness-control)
- [CLIPBOARD MANAGERS](#clipboard-managers)
- [COMPOSITORS](#compositors)
- [DISPLAY CONFIGURATION](#display-configuration)
- [EMULATION](#emulation)
- [IMAGE VIEWING](#image-viewing)
- [LAUNCHERS](#launchers)
- [LIBRARIES](#libraries)
- [NOTIFICATIONS](#notifications)
- [ON-SCREEN KEYBOARDS](#on-screen-keyboards)
- [REFERENCE APPLICATIONS](#reference-applications)
- [SCREEN LOCKING](#screen-locking)
- [SCREENCASTS](#screencasts)
- [SCREENSHOTS](#screenshots)
- [SESSION MANAGEMENT](#session-management)
- [THEMING](#theming)
- [TOOLS](#tools)
- [WALLPAPER](#wallpaper)
- [WIDGETS (BARS, PANELS, ETC.)](#widgets-bars-panels-etc)

BINDINGS
--------

These are language-specific bindings for use with Wayland development.

- None made from Rust

BREAK NOTIFIERS
---------------

- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [Ianny](https://github.com/zefr0x/ianny) - Periodically informs user to take breaks by keeping track of usage patterns

BRIGHTNESS CONTROL
------------------

No Wayland-specific requirements, so you can use your Xorg solution of choice to control screen brightness, like [brightnessctl](https://github.com/Hummer12007/brightnessctl), [brillo](https://gitlab.com/cameronnemo/brillo), or just directly manipulate `/sys/class/backlight`.

- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [wluma](https://github.com/maximbaz/wluma) - A tool for wlroots-based compositors that automatically adjust screen brightness based on screen contents and ambient light

CLIPBOARD MANAGERS
------------------

- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [clapboard](https://github.com/bjesus/clapboard) - A clipboard manager with support for images and saved entries
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [gemclip](https://codeberg.org/novenary/gemclip) - A simple clipboard utility for Wayland implementing the `wlr-data-control-unstable-v1` protocol

COMPOSITORS
-----------

- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [Jay](https://github.com/mahkoh/jay) - A tiling Wayland compositor inspired by i3wm
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [niri](https://github.com/YaLTeR/niri) - A Smithay-based scrollable tiling Wayland compositor
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [pinnacle](https://github.com/pinnacle-comp/pinnacle) - A Smithay-based Wayland compositor inspired by AwesomeWM

DISPLAY CONFIGURATION
---------------------

- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [shikane](https://gitlab.com/w0lff/shikane) - A wlroots-based dynamic output configuration tool similar to autorandr, usable on Wayland compositors supporting the `wlr-output-management` protocol
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [wayout](https://git.sr.ht/~shinyzenith/wayout) - A simple output management tool for wlroots-based compositors implementing `wlr-output-management-unstable-v1`

EMULATION
---------

- None made from Rust

IMAGE VIEWING
-------------

- None made from Rust

LAUNCHERS
---------

- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [Anyrun](https://github.com/anyrun-org/anyrun) - A GTK-based Wayland-native launcher, customizable via CSS
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [kickoff](https://github.com/j0ru/kickoff) - A wlroots-based application launcher
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [sirula](https://github.com/DorianRudolph/sirula) - A simple application launcher for Wayland
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [waylauncher](https://github.com/tomipkoskinen/waylauncher) - A GTK-based application launcher implementing the `gtk4-layer-shell` protocol
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [wldash](https://github.com/kennylevinsen/wldash) - A dashboard, launcher, or control panel for Wayland, using the `wlr-layer-shell-unstable-v1` protocol
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [yofi](https://github.com/l4l/yofi) - A minimalistic menu for Wayland-based compositors

LIBRARIES
---------

- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [client-toolkit](https://github.com/Smithay/client-toolkit) - A toolkit for writing Wayland clients in Rust
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [smithay](https://github.com/Smithay/smithay) - A compositor library for Wayland

NOTIFICATIONS
-------------

- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [SwayOSD](https://github.com/ErikReider/SwayOSD) - A GTK-based OSD window for common actions like volume and Caps Lock

ON-SCREEN KEYBOARDS
-------------------

- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [wkeys](https://github.com/ptazithos/wkeys) - An on-screen keyboard featuring a configurable layout and style for Wayland compositors supporting the `gtk4-layer-shell` protocol

REFERENCE APPLICATIONS
----------------------

These are mainly for developers looking for example implementations.

- None made from Rust
- 
SCREEN LOCKING
--------------

- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [cthulock](https://github.com/FriederHannenheim/cthulock) - A Slint-based customizable screen-locker for Wayland compositors implementing the `ext-session-lock-v1` protocol
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [Shaderlock](https://github.com/RobinMcCorkell/shaderlock) - A wlroots-based screen-locker for Wayland utilizing GPU shaders

SCREENCASTS
-----------

- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [Kooha](https://github.com/SeaDve/Kooha) - Minimalistic screen recorder for Wayland sessions implementing the `org.freedesktop.impl.portal.ScreenCast` protocol
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [wl-screenrec](https://github.com/russelltg/wl-screenrec) - A screen recorder for wlroots-based Wayland compositors leveraging DMA-BUF and the DRM and implementing the `wlr-output-management-unstable-v1` and `wlr-screencopy-unstable-v1` protocols

SCREENSHOTS
-----------

- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [haruhishot](https://github.com/Decodetalkers/haruhishot) - A screenshot utility for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` and `wlr-screencopy-unstable-v1` protocols
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [Satty](https://github.com/gabm/Satty) - A screenshot annotation tool inspired by Swappy and Flameshot
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [shotman](https://git.sr.ht/~whynothugo/shotman) - A screenshot GUI for Wayland compositors implementing `wlr-layer-shell-unstable-v1`, `wlr-screencopy-unstable-v1`, and `single-pixel-buffer-v1` protocols
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [Watershot](https://github.com/Kirottu/watershot) - A simple Wayland-native screenshot tool inspired by Flameshot
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [Wayshot](https://git.sr.ht/~shinyzenith/wayshot) - A screenshot tool for wlroots-based compositors implementing `wlr-screencopy-unstable-v1`
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [waysip](https://github.com/waycrate/waysip) - An area selector for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [Weye](https://github.com/Yakkhini/Weye) - A lightweight screenshot tool for sway users

SESSION MANAGEMENT
------------------

- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [wleave](https://github.com/AMNatty/wleave) - A Wayland-based logout menu implementing the `gtk3-layer-shell` protocol

THEMING
-------

- None made from Rust

TOOLS
-----

- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [lan-mouse](https://github.com/feschber/lan-mouse) - A mouse and keyboard sharing software
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [Vigiland](https://github.com/Jappie3/vigiland) - An application implementing the `idle-inhibit-unstable-v1` protocol
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [waycorner](https://github.com/AndreasBackx/waycorner) - Hot corners for wlroots-based Wayland compositors implementing the `xdg-output-unstable-v1` protocol
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [waylevel](https://git.sr.ht/~shinyzenith/waylevel) - A simple debugging tool which prints Wayland toplevels and other compositor specific information
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [whisper-overlay](https://github.com/oddlama/whisper-overlay) - A tool providing speech-to-text functionality for Wayland compositors implementing `virtual-keyboard-unstable-v1` and `wlr-layer-shell-unstable-v1` protocols
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [wlr-which-key](https://github.com/MaxVerevkin/wlr-which-key) - A keymap manager for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol

WALLPAPER
---------

- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [rwpspread](https://github.com/0xk1f0/rwpspread) - A multi-monitor wallpaper utility spanning input wallpapers across all monitors, supporting Wayland compositors implementing `xdg-output-unstable-v1` with integrations for `wpaperd`, `swaybg`, `hyprpaper`, `swaylock`, and `hyprlock`
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [swww](https://github.com/LGFae/swww) - An animated wallpaper daemon for Wayland, controlled at runtime and implementing the `wlr-layer-shell-unstable-v1` and `xdg-output-unstable-v1` protocols
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [wpaperd](https://github.com/danyspin97/wpaperd) - A wallpaper daemon that shows random wallpapers from a directory and changes them after some time

WIDGETS (BARS, PANELS, ETC.)
----------------------------

- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [Dvvidget](https://github.com/BL-CZY/dvvidget) - A widget system for Wayland compositors implementing the `wlr-layer-shell-unstable-v1` and `gtk4-layer-shell` protocols
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [dynisland](https://github.com/cr3eperall/dynisland) - An extensible bar for wlroots-based Wayland compositors implementing the `gtk4-layer-shell` protocol
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [Eww](https://github.com/elkowar/eww) - A standalone widget system that allows for implementing custom widgets in any window manager
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [i3status-rust](https://github.com/greshake/i3status-rust) - A resource-friendly and feature-rich replacement for i3status
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [Ironbar](https://github.com/JakeStanger/ironbar) - A customizable and feature-rich GTK bar for wlroots-based compositors
- ![Dart](https://img.shields.io/badge/dart-29b6f6?style=plastic&logo=dart&logoColor=01579b)&nbsp;![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [kitshell](https://github.com/bootloopmaster636/kitshell) - A Flutter-based panel for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
- ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic&logo=rust&logoColor=fff) [way-edges](https://github.com/way-edges/way-edges) - A lightweight application providing off-screen widgets hidden along the edges of the screen
