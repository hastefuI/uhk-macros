# uhk-macros

A collection of portable [Ultimate Hacking Keyboard](https://www.ultimatehackingkeyboard.com/) Macros built on the [UHKM specification](https://github.com/hastefuI/uhkm-spec) by hasteful 🐇

## Macros
| Macro | Description | Source |
| --- | --- | --- |
| $onInit | Event macro that runs at power-on to initialize the keyboard. | [macros/event-on-init.uhkm](macros/event-on-init.uhkm) |
| Dark Mode | Toggles keyboard lighting and LEDs off/on. | [macros/dark-mode.uhkm](macros/dark-mode.uhkm) |
| Launch 1Password | Opens 1Password on macOS via Spotlight. | [macros/launch-1password.uhkm](macros/launch-1password.uhkm) |
| Lock Screen | Lock macOS + UHK, or wake UHK if already locked. | [macros/lock-screen.uhkm](macros/lock-screen.uhkm) |

## Installation
1) Install [UHK Agent](https://ultimatehackingkeyboard.com/agent) and connect your keyboard.
2) In Agent, open the Macros tab and import the desired macro from the uhkm file in this repo.
3) Assign each macro to a key, layer, or keymap slot as needed.
4) Click **Save to keyboard** to update the configuration for your UHK.

## License

MIT
