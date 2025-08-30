# base16-scintillua <img alt="Color wheel" src="https://raw.githubusercontent.com/tinted-theming/home/refs/heads/main/color_wheel.png" width="100" align="right" style="padding-top:0.6rem;">

[Base16] [scintillua] ([SciTE]) template / theme(s) (automatically) built using [Tinted Theming color schemes].

## Previews

See https://github.com/tinted-theming/base16-scintillua/tree/main/docs/images for some sample SciTE + scintillua screen shots.

See https://tinted-theming.github.io/tinted-gallery/ for gallery of all color schemes.
This page shows all supported color themes, using a bash script
https://github.com/tinted-theming/tinted-gallery/blob/main/build.sh
as the demo syntax highlighted file (as seen in vim).

## Installation

 1. Copy the theme(s) you are interested in from `themes/base16` into the scintillua `themes` directory.
 2. Edit `scintillua.properties` (in the parent directory of the `themes` directory)
 3. Locate the themes section, search for `import scintillua/themes`
 4. Add (or edit) to add an import line for the theme of interest, for example:

        #import scintillua/themes/scite
        import scintillua/themes/base16-tokyo-night-moon

For more information about scintillua config, see scintillua documentation at https://github.com/orbitalquark/scintillua
For information about SciTE config see https://www.scintilla.org/SciTEDoc.html

## Team

This theme is maintained by the following person(s) and a bunch of [awesome contributors](https://github.com/tinted-theming/base16-scintillua/graphs/contributors).

| [![Jamy](https://github.com/jamygolden.png?size=100)](https://github.com/JamyGolden) | [![clach04](https://github.com/clach04.png?size=100)](https://github.com/clach04) |
| ------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------- |
| [Jamy](https://github.com/JamyGolden)                                                | [clach04](https://github.com/clach04)                                             |

## Community

  * [Tinted Theming Home](https://github.com/tinted-theming/home)
  * Have something you want to discuss, but you're not sure it warrants an issue? Feel free to stop by
    [#tinted-theming:matrix.org](https://matrix.to/#/#tinted-theming:matrix.org) on [Matrix](https://matrix.org/).

## License

[MIT License](./LICENSE)


[Base16]: https://github.com/tinted-theming/home/blob/main/styling.md
[scintillua]: https://github.com/orbitalquark/scintillua
[SciTE]: https://scintilla.org/SciTE.html
[Tinted Theming color schemes]: https://github.com/tinted-theming/schemes
