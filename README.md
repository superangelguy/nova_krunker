# NovaKrunker

[![GitHub All Releases](https://img.shields.io/github/downloads/superanelguy/novakrunker/total.svg)](https://github.com/superanelguy/novakrunker/releases/latest)
[![Latest release](https://img.shields.io/github/downloads/superanelguy/novakrunker/latest/total)](https://github.com/superanelguy/novakrunker/releases/latest)
[![Chat](https://img.shields.io/discord/966300714060116008)](https://discord.gg/ZeVuxG7gQJ)
[![One-time donation via ko-fi.com](https://img.shields.io/badge/donate-ko--fi-%23ff5e5b?logo=kofi)](https://ko-fi.com/superanelguy)

> A fast, feature-rich Krunker client written in TypeScript

**Download:**
[Windows (x64)](https://github.com/superanelguy/novakrunker/releases/latest/download/novakrunker-setup-win-x64.exe) -
[Mac (x64)](https://github.com/superanelguy/novakrunker/releases/latest/download/novakrunker-portable-mac-x64.dmg) -
[Mac (arm64)](https://github.com/superanelguy/novakrunker/releases/latest/download/novakrunker-portable-mac-arm64.dmg) -
[Linux (x86_64 AppImage)](https://github.com/superanelguy/novakrunker/releases/latest/download/novakrunker-portable-linux-x86_64.AppImage) -
[Other](https://github.com/superanelguy/novakrunker/releases/latest)

![splash](assets/blank_splash.png)

## Client Features
- Very good performance with additional performance enhancing settings
- Highly customizable, many different settings
- Hides ads by default (can be disabled)
- Resource swapper (CSS, sounds & all other assets)
- Userscript support
- Discord RPC (gamemode, map, class & skin)
- Customizable matchmaker (Gamemode, Region, Min/Max players, Time)
- Quick class switcher using `#hiddenClasses`
- Built-in hotkeys
- Maintained & open source

## Quality of Life
- All client-specific features can be turned off to ensure maximum performance
- Written in TypeScript
- Secure: `web security` is on, the `remote` module and `nodeIntegration` are disabled
- Splash screen is not a separate window, shows only while Krunker is actually loading
- Doesn't automatically open free spin URLs in browser
- Discord RPC: if enabled, only updates while you're not actually in game
- No-compromise mac, linux and windows support

## Userscripts
- Any `.js` file in `%APPDATA%/novakrunker/config/scripts` will be considered a userscript and executed if enabled in settings.
- All userscripts are disabled when they are first added.
- `%APPDATA%/novakrunker/config/tracker.json` is used to keep track of enabled userscripts.

> **Use userscripts at your own risk.** The author(s) of this client are **not responsible for any damage done** with userscripts because the user is the author of the script.
> **Do not write or use any userscripts which would give the user a competitive advantage.**

## Hotkeys

Press `Alt` to show electron menu. Here you can find all hotkeys.  
Standard hotkeys like zooming, copying/pasting and devtools also included.  
**Client's hotkeys:**
- `F5`: reload
- `F6`: find a new match
- `F7`: copy game link
- `Ctrl+F7`: join game from clipboard
- `F12`: devtools (alternative hotkey)

## Matchmaker
A customizable matchmaker (with GUI settings!) that you can use alongside/instead of the regular `F6` matchmaker.

## Building from Source
1. **You have to have [git](https://git-scm.com/downloads), [nodejs](https://nodejs.org/en/download/), and [pnpm](https://pnpm.io/installation) installed.**
2. **Installation:**
   - `git clone https://github.com/superanelguy/novakrunker`
   - `cd novakrunker`
   - `pnpm i`
3. **Building from source:** `pnpm dist`

## Contributing
1. Follow previous steps 1 & 2
2. Make your changes + running from source: `pnpm start`/`pnpm dev` (rebuilds on changes, refresh Krunker with `F6`)
3. After your changes, try it out with `pnpm testbuild` - this will minify the code & run the app.
- Please report any bugs/feature requests in the Issues.
- Feel free to submit pull requests, they will be merged as long as they support the client ideology.

## Support Development
[![One-time donation via ko-fi.com](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/superanelguy)

You can support ongoing development & maintenance by donating. All donations are highly appreciated! <3
