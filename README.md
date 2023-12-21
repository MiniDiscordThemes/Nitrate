[light]: https://user-images.githubusercontent.com/29710355/225917345-ab76e004-5fab-4f06-bd5e-a5ff007e82e9.png
[dark]: https://user-images.githubusercontent.com/29710355/225917696-9d29a4ea-f3b4-403c-8640-69e407ec5179.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[css-angle]:        https://developer.mozilla.org/en-US/docs/Web/CSS/angle
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-bd-dl]:     https://img.shields.io/github/downloads/MiniDiscordThemes/Nitrate/Nitrate.theme.css?color=purple&label=Downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/MiniDiscordThemes/Nitrate/net.saltssaumure.Nitrate.asar?color=purple&label=Downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/MiniDiscordThemes/Nitrate?label=Repository&style=flat-square "Total size"

[github]:           https://github.com/MiniDiscordThemes/Nitrate
[issues]:           https://github.com/MiniDiscordThemes/Nitrate/issues
[license]:          https://github.com/MiniDiscordThemes/Nitrate/blob/main/LICENSE
[.theme.css]:       https://github.com/MiniDiscordThemes/Nitrate/blob/main/Nitrate.theme.css

[release-bd]:       https://betterdiscord.app/theme/?id=000 "BetterDiscord store page"
[release-rp]:       https://replugged.dev/store/net.saltssaumure.Nitrate "Replugged store page"
[release-bd-gh]:    https://github.com/MiniDiscordThemes/Nitrate/releases/latest/download/Nitrate.theme.css "Get latest release"
[release-rp-gh]:    https://github.com/MiniDiscordThemes/Nitrate/releases/latest/download/net.saltssaumure.Nitrate.asar "Get latest release"

# Nitrate Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![BetterDiscord GitHub downloads][shield-bd-dl]][release-bd-gh]
[![Replugged GitHub downloads][shield-asar-dl]][release-rp-gh]
[![Total repository size][shield-repo-size]][github]

***A knockoff Nitro gradient Discord theme.***

| Light mode                                                    | Dark mode                                                   |
| ------------------------------------------------------------- | ----------------------------------------------------------- |
| ![Screenshot of Nitrate light mode applied to Discord][light] | ![Screenshot of Nitrate dark mode applied to Discord][dark] |

## Installation

### [BetterDiscord][BetterDiscord]
1. Download `Nitrate.theme.css`:
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `BetterDiscord` > `Themes` > `Open Themes Folder`
3. Toggle on the theme card.

### [Replugged][Replugged]
#### Automatic
1. Click to install:
    - [Replugged store][release-rp]
#### Manual
1. Download `net.saltssaumure.Nitrate.asar`:
    - [GitHub][release-rp-gh]
2. Place the file in the themes folder:
    - `Settings` > `Replugged` > `Themes` > `Open Themes Folder`
3. Click `Load Missing Themes` and toggle on the theme card.

### [Vencord][Vencord]
#### Local
1. Download `Nitrate.theme.css`:
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
#### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://minidiscordthemes.github.io/Nitrate/Nitrate.theme.css`

## Customisation

| Description             | Variable name                                                                | Valid values                            | Default value          |
| ----------------------- | ---------------------------------------------------------------------------- | --------------------------------------- | ---------------------- |
| Custom gradient angle   | `--nitro-custom-angle`                                                       | Any [CSS-recognised angle][css-angle].  | `180deg`               |
| Custom gradient colours | `--nitro-custom-color-1`, `--nitro-custom-color-2`, `--nitro-custom-color-3` | Any [CSS-recognised colour][css-color]. | `red`, `green`, `blue` |

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Comment out unwanted lines and save changes.

### Replugged
1. Enable `Automatically Apply Quick CSS` in `Settings` > `Replugged` > `General`.
2. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste lines 15-59 of [`Template.theme.css`][.theme.css].
4. Edit the variable values and save.

### Vencord
#### Local
1. `Open Themes Folder` in `Settings` > `Vencord` > `Themes` > `Local Themes`
2. Open `Template.theme.css` with your favourite text editor.
3. Edit the variable values and save.
#### Online
1. `Enable Custom CSS` in `Settings` > `Vencord` > `Vencord` and click `Open QuickCSS File`.
2. Copy and paste lines 15-59 of [`Template.theme.css`][.theme.css].
3. Edit the variable values.

## License
[MIT License][license]
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, just include the original license.

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].
