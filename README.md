# legacy-qBittorrent

This is a very minimal qbtheme for qBittorrent that brings back the compact layout for the transfer list from pre-4.2.2.

## Downloading

Get the .qbtheme file from this repo by cloning it or from the [Releases](https://github.com/FoxInFlame/legacy-qBittorrent/releases) page.

## Using

Copy the downloaded .qbtheme file to a permanent location.  Load the theme in qBittorrent from `Options → Behavior → Interface`, enable `[x] Use custom UI Theme` and select the file.  Restart qBittorrent.

See the official [How to use custom UI themes](https://github.com/qbittorrent/qBittorrent/wiki/How-to-use-custom-UI-themes).

## Compiling (Windows only)

With a python3 executable called `python`, run `compile.bat`.

## Making Your Own Styles

Due to the minimal nature of this repository, it also serves as a useful starting point for new theme developers. Here's what you need to know about qBittorrent theming:

- `.qbtheme` files are binary resource packages for Qt, and they are compiled using the Resource Compiler (`rcc`) tool.
- `make-resource.py` (by @jagannatharjun) is a wrapper for `rcc` specifically designed for qBittorrent, which makes compilation as easy as calling the python file with input and output file arguments.

To get started with making your own style:

1. `git clone` this repository to your file system.
2. Edit `style.qss` to your liking. Although I haven't tried, you can certainly include custom icon assets to your compilation. Take a look at other developers for examples.
3. Compile using `compile.bat`.

See the official [Create custom themes for qBittorrent](https://github.com/qbittorrent/qBittorrent/wiki/Create-custom-themes-for-qBittorrent).

And a list of other themes from [List of known qBittorrent themes](https://github.com/qbittorrent/qBittorrent/wiki/List-of-known-qBittorrent-themes).
