# Farmers World Bot Free

## Video instruction

https://youtu.be/D028TAAe5H8

## Instalation guide

1. Open the game and log in.
2. **Important!** Confirm any operation and in the wax confirmation window check the auto-confirmation checkbox.
3. To open the console in Chrome, use this keyboard shortcut: `Cmd + Option + J` (on a Mac) or `Ctrl + Shift + J` (on Windows).
4. Copy the [script](https://github.com/SmartBotBlack/farmers-world-bot/blob/master/index.js) and paste it into the console. Press Enter.

## Current functionality

- Working with all the maps. Able to work with any kind of NFT.
- The script presses the "Mine"/"Hatch" button on any map when the button is available.
- If energy is less than 400, it exchanges back to zero
- If the strength of the mining tool is less than half, it is repaired. Make sure you have enough gold in your account.
- Currently *DOES NOT* do cow/bull breeding
- Currently *DOES NOT* replant crops after they are harvested

## Changelog

### 2022-02-28

- Changed mining time: On tools, wait for max mining slots full before mining instead of mining every hour
- General refactoring related to above change

### 2022-02-27

### FORKED here (fredrgrs)


### 16/12/2021

- Now the bot tries to restore work, even if there was an error.

### 14/12/2021

- Fix error mine on first map, if you have Member card.

### 13/12/2021

- Improved algorithm for closing succes popups.
- The energy system has been redesigned. The bot now tries to always maintain the maximum amount of energy. This fixes a bug on some single player maps.
- Improved algorithm for closing CPU error popups.
- Added a random pause between actions.
- Fixed a mining bug when using Member card.

### 29/11/2021

- Added the ability to select maps for mining. [issues #4](https://github.com/SmartBotBlack/farmers-world-bot/issues/4)
- Improved the setting of pauses in the game. [issues #4](https://github.com/SmartBotBlack/farmers-world-bot/issues/4)

## Support

_Any problems? [Submit an issue](https://github.com/SmartBotBlack/farmers-world-bot/issues/new) or send message in telegram [@smartbotofficial](https://t.me/smartbotofficial) or email [hello@smartbot.black](hello@smartbot.black)!_

### Official site

https://smartbot.black
