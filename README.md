# zzelia65

65% keyboard with external ProMicro-compatible controller.

Design inspired by [Neo Zelia](https://geekhack.org/index.php?topic=62449.0)

**⚠️ Design-stage only, not even a working prototype.**

## Main features

- Swappable controller, aimed to be wireless with [nice!nano](https://nicekeyboards.com/nice-nano/)
- Portable
- No plate
- No RGB
- Soldered switches

## Project structure

- `keyboard-layout.json` Layout file that can be imported into [keyboard-layout-editor](http://www.keyboard-layout-editor.com)
- `matrix-layout.json` Wiring configuration to be imported into [Keyboard Firmware Builder](https://builder.mrkeebs.com)
- `kicad` - KiCad project
- `gerber` - gerber files

## Layout

Standard 65% ANSI with exploded design.

<img src='images\keyboard-layout.png' width="600">

## Wiring

ProMicro has only 18 pins by default so wiring is a bit tricky as we need to stay in the limit. The most logical was to use 10 rows and 8 columns. Can be improved, probably.

<img src='images\wiring.png' width="600">

## Similar/inspirational projects

- [Contra](https://github.com/ai03-2725/Contra)
- [KBIC65](https://github.com/b-karl/KBIC65)
- [horizon](https://github.com/skarrmann/horizon)
