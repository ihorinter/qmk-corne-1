# Inter’s keymap for Corne v1 on QMK

## Instructions for installation
1. Install the QMK with `brew install qmk/qmk/qmk`
2. Move to `repos` folder and run `qmk setup`. Clone the `qmk_firmware` repository
3. Go to `.../repos/qmk_firmware/keyboards/crkbd/keymaps` and `git clone` this repository
4. Run `qmk compile -kb crkbd/r2g -km qmk_keymap_crkbd-1`

## To do
- [ ] Add [“minus” symbol](https://www.compart.com/en/unicode/U+2212)
- [ ] Set up [QMK CLI Configuration to qmk.ini](https://github.com/qmk/qmk_firmware/blob/master/docs/cli_configuration.md)
- [ ] Add text selection layer
- [ ] Visualize the keymap
- [ ] Set up `QK_MAKE` [Quantum Keycode](https://github.com/qmk/qmk_firmware/blob/master/docs/quantum_keycodes.md)

## Useful links
- GitHub: [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- GitHub: [About Git](https://docs.github.com/en/get-started/using-git/about-git)
- [QMK CLI Commands](https://github.com/qmk/qmk_firmware/blob/master/docs/cli_commands.md)
