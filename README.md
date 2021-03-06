# base16-alacritty

[Base16](https://github.com/chriskempson/base16) for the [Alacritty Terminal
Emulator](https://github.com/jwilm/alacritty)

**NOTE:** All files in this repository are generated by a base16-builder 

## Installation

After cloning this repo, simply copy the contents of your desired color scheme
into your `alacritty.yml` configuration file. Make sure to remove or comment
out the original color scheme.

## "256" Variations
The 256 variations are provided so that anyone who wishes to continue using
the 16 ANSI colors won't end up with weird colors instead of bright colors.
However since base16 uses only 16-color themes, this results in all of the
bright colors mirroring their non-bright colors, rather than being additional
colors. If you use the 256 variations, you will also need to use the [Base16
Shell](https://github.com/chriskempson/base16-shell) script to maintain proper
compatibility with the base16 themes.
