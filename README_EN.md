# <img src="src/main/resources/assets/ocelotsignmod/icon.png" width="32" align="absmiddle" /> Ocelot Sign Mod

[简体中文](./README.md) · English


[![Official Site & Documentation](https://img.shields.io/badge/Ocelot_Sign_Mod-Official_Docs-00a1d6)](https://creeper-cola123.github.io/OcelotSignMod_Docs/)
[![Modrinth](https://img.shields.io/modrinth/dt/ocelotsignmod?logo=modrinth&label=Modrinth&color=00af5c)](https://modrinth.com/mod/ocelotsignmod)
[![CurseForge](https://img.shields.io/badge/CurseForge-Ocelot_Sign_Mod-f16436?logo=curseforge)](https://www.curseforge.com/minecraft/mc-mods/ocelotsignmod)
[![MCMOD](https://img.shields.io/badge/MCMOD-28882-blue)](https://www.mcmod.cn/class/28882.html)
[![Bilibili](https://img.shields.io/badge/Bilibili-Trailer-ff69b4?logo=bilibili)](https://www.bilibili.com/video/BV1kFgq6PE4D/)
[![QQ Group](https://img.shields.io/badge/QQ_Group-871229937-12b7f5?logo=tencentqq)](https://qun.qq.com/universal-share/share?ac=1&authKey=4Nn/HUptHFXeX0LvwZ7aVyW/psDyh8tgyhMhHEGnCtr0EuQzFpoIvXeOd%2Ba6cW%2BN&busi_data=eyJncm91cENvZGUiOiI4NzEyMjk5MzciLCJ0b2tlbiI6ImxUK1UwN25ybGVaWnpDakwxdy9zZEYwQ1ZHWnhkM25tYkRXUWVrUXRYMmk3c0RUT0JFWEVESFUxNUsyUVZjSnciLCJ1aW4iOiIxNTk5Mjk0OTU3In0=&data=-XUNHn2ONLeDg7l3sslDVejgEuAq73ALu_2TClospj7g4S3rv98L3mZCSgnivTvV_yUbZ7-xv-b6Owi73v6CdkAT1lxJ3l9MzYfWaiOT7pg&svctype=5&tempid=h5_group_info)
[![License](https://img.shields.io/badge/License-LGPL_3.0-blue.svg)](LICENSE)

> [!IMPORTANT]
> RongMC maintains this Fabric 26.3 port of Ocelot Sign Mod. See the official documentation above for the original project.

**Ocelot Sign Mod** is an add-on for [Mishang Urban Construction](https://github.com/SolidBlock-cn/mishanguc), built on the Fabric platform. It inherits Mishang UC's highly flexible text and pattern editing system, focuses on road traffic guidance and public wayfinding details, and further refines the sign editing experience of the base mod.

---

## Features

1. Built-in road sign graphics based on the GB 5768 standard, covering the road signs of Chinese Mainland, adding realistic detail to your road projects;
2. A large collection of public information symbols, suited to scenes such as subway stations and airports;
3. New dedicated road sign blocks with full custom editing support, along with matching sign pillars;
4. On top of Mishang UC's road blocks, extra ground-level advance direction arrows, orange arrows and various prohibition arrows;
5. Sign graphics can be customised through resource packs — you can reproduce the road signs of Chinese Mainland, or build your own pack to recreate the signage of other regions;
6. The official website hosts a Creative Plaza where you can submit your own sign works and download resource packs shared by other players.

## What changed in the RongMC 26.3 port

The port updates concrete block registration, SDL input, GUI drawing and sign block-entity rendering for Fabric 26.3 and the matching Mishang Urban Construction build.

## Installation

Download **v1.0.2-rongmc.1+26.3** from [GitHub Releases](https://github.com/OpenRongMC/OcelotSign/releases/tag/v1.0.2-rongmc.1%2B26.3) for Minecraft Java **26.3** on **Fabric** with **Java 25**. Dependencies include [Fabric API](https://modrinth.com/mod/fabric-api), [迷上城建 / Mishang Urban Construction](https://github.com/OpenRongMC/Mishang-Urban-Construction). Place the release JAR in the instance’s `mods/` directory. Install matching OcelotSign and Mishang Urban Construction builds on both sides. Check Fabric mod IDs in the release metadata, especially if mixing distribution channels.

## Links

- **Documentation & Creative Plaza**: [Pattern and Font List plus the online tools](https://creeper-cola123.github.io/OcelotSignMod_Docs/)
- **Downloads**: [Modrinth](https://modrinth.com/mod/ocelotsignmod) · [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ocelotsignmod) · [MCMOD](https://www.mcmod.cn/class/28882.html)
- **Video showcase**: [Bilibili trailer](https://www.bilibili.com/video/BV1kFgq6PE4D/)
- **Feedback**: please open an [Issue](https://github.com/OpenRongMC/OcelotSign/issues) for bugs; or join the [official QQ group (871229937)](https://qun.qq.com/universal-share/share?ac=1&authKey=4Nn/HUptHFXeX0LvwZ7aVyW/psDyh8tgyhMhHEGnCtr0EuQzFpoIvXeOd%2Ba6cW%2BN&busi_data=eyJncm91cENvZGUiOiI4NzEyMjk5MzciLCJ0b2tlbiI6ImxUK1UwN25ybGVaWnpDakwxdy9zZEYwQ1ZHWnhkM25tYkRXUWVrUXRYMmk3c0RUT0JFWEVESFUxNUsyUVZjSnciLCJ1aW4iOiIxNTk5Mjk0OTU3In0=&data=-XUNHn2ONLeDg7l3sslDVejgEuAq73ALu_2TClospj7g4S3rv98L3mZCSgnivTvV_yUbZ7-xv-b6Owi73v6CdkAT1lxJ3l9MzYfWaiOT7pg&svctype=5&tempid=h5_group_info).

## Development

Use JDK 25. See [build.gradle](./build.gradle) for the Mishang Urban Construction build dependency.

```sh
./gradlew build
```

## Credits

Thanks to every community member who helped with development, testing and porting!

### Core development team

| Member | Role | Links |
| :--- | :--- | :--- |
| **Ocelot Creeper Cola** | Project lead / code / models / art | [Bilibili](https://space.bilibili.com/226720371) · [GitHub](https://github.com/Creeper-Cola123) |
| **Hualaohua** | Traffic sign standards advisor | [Bilibili](https://space.bilibili.com/646146582) |
| **XFunny** | Game testing | [Bilibili](https://space.bilibili.com/34849566) · [GitHub](https://github.com/X-Funny) |

### Dependency mod author

| Member | Role | Links |
| :--- | :--- | :--- |
| **Solid-Block** | Author of Mishang Urban Construction (MISHANGUC) | [Bilibili](https://space.bilibili.com/87328531) · [GitHub](https://github.com/SolidBlock-cn) |

### Community contributors (PR)

| Member | Contribution | Links |
| :--- | :--- | :--- |
| **Beigu** | 1.19.2 port | [Bilibili](https://space.bilibili.com/3493084226652280) · [GitHub](https://github.com/BGSDT) |
| **Pigeon0v0** | 26.1.2 port | [Bilibili](https://space.bilibili.com/354878609) · [GitHub](https://github.com/Pigeon0v0) |

---

## License & Copyright

See the [LICENSE](LICENSE) file in the repository root for the full terms.

### 1. Mod license (LGPL-3.0)

This mod is open-sourced under the **LGPL-3.0** license. You are free to use, modify and redistribute its code and art assets (for example, building other Minecraft add-ons on top of it, or porting the assets to city-building games such as *Cities: Skylines*), provided that you follow these rules:

#### 1.1 Requirements for derivative works
- **Keep it open source**: the core code of any modified version must also be released under LGPL-3.0.
- **Keep attribution**: when publishing a modified version, clearly credit the original author and link to this repository in the mod, on the release page, in the docs and in the README, and state explicitly that it is "based on Ocelot Sign Mod". Do not claim it was made entirely on your own or by your team.
- **Avoid confusion**: the name, icon and marketing of a modified version must not be confused with the official release, so players are not misled. For substantial derivative work, please contact the original author in advance.

#### 1.2 Red lines (strictly prohibited)
- Redistributing the code while keeping it closed source in violation of LGPL-3.0.
- Planting malicious, destructive or privacy-stealing code in a redistributed version.
- Impersonating the original author, or passing a modified version off as an official release.
- **Commercial resale**: selling this mod on marketplaces such as Taobao or Xianyu, or moving it to the NetEase (China Edition) mod centre as a paid download.

#### 1.3 About unofficial ports and forks
The original team is responsible only for the **official releases** published in this repository. For unofficial community forks (specific version ports, heavily modified variants, and so on), code quality and compatibility are the responsibility of their respective maintainers. If you run into problems with an unofficial fork, please contact that fork's maintainer first. Community contributions are very welcome, but with limited time we cannot provide fallback technical support for unofficial forks — we appreciate your understanding.

### 2. Dependency mod compliance

- **Dependency project**: MISHANGUC (Mishang Urban Construction)
- **License**: [GNU LGPL v3.0](https://www.gnu.org/licenses/lgpl-3.0.html)
- **Project URL**: [SolidBlock-cn/mishanguc](https://github.com/SolidBlock-cn/mishanguc)
- **Compliance note**: this mod calls the dependency dynamically as a library, within the scope permitted by LGPL-3.0, and keeps the original author's copyright information intact.

### 3. Bundled font licenses

This mod embeds the following open-source / free-for-commercial-use fonts:

- **MiSans**: © Xiaomi Corporation, used under the [MiSans Free Commercial Use and Embedding License](https://hyperos.mi.com/font/zh/faq/) ([official font site](https://hyperos.mi.com/font/zh/)).
- **Roadgeek 2014**: designed by Sammi Ta based on FHWA standards, licensed under **CC BY-SA 4.0** ([GitHub repository](https://github.com/sammdot/roadgeek-fonts)).
- **Source Han Sans**: licensed under the **SIL Open Font License 1.1** ([GitHub repository](https://github.com/adobe-fonts/source-han-sans)).
- **Source Han Serif**: licensed under the **SIL Open Font License 1.1** ([GitHub repository](https://github.com/adobe-fonts/source-han-serif)).

### 4. Website and tool copyright

The mod's [documentation website and online tools (including the web-based resource pack creator)](https://creeper-cola123.github.io/OcelotSignMod_Docs/) are publicly hosted but are **not covered by the open-source license**; the author retains all rights. Scraping, modifying, mirroring or redistributing the website code, tools and site assets is strictly prohibited.

*Note: resource packs (ZIP files) uploaded by players to the Creative Plaza remain the copyright of their uploader; the specific license is as stated by the author of each upload.*
