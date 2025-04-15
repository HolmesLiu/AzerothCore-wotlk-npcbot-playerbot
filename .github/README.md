# ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md)
## Build Status

3.3.5
:------------:
[![nopch-build](https://github.com/trickerer/AzerothCore-wotlk-with-NPCBots/actions/workflows/core-build-nopch.yml/badge.svg?branch=npcbots_3.3.5)](https://github.com/trickerer/AzerothCore-wotlk-with-NPCBots/actions/workflows/core-build-nopch.yml)
[![windows-build](https://github.com/trickerer/AzerothCore-wotlk-with-NPCBots/actions/workflows/windows_build.yml/badge.svg)](https://github.com/trickerer/AzerothCore-wotlk-with-NPCBots/actions/workflows/windows_build.yml)

## 介绍

AzerothCore 是一个开源游戏服务器应用程序和框架，旨在托管大型多人在线角色扮演游戏（MMORPG）。它基于流行的 MMORPG《魔兽世界》（WoW），并旨在重现原始游戏 3.3.5a 补丁版本的游戏体验。

原始代码基于 MaNGOS、TrinityCore 和 SunwellCore，经过广泛开发，改进了稳定性、游戏机制和模块化，使游戏更加完善。AzerothCore 也发展成了一个由社区驱动的项目，拥有大量贡献者和开发人员。它使用 C++ 编写，为创建模拟官方 WoW 服务器的私人服务器提供了坚实的基础。

[NPCBots](https://github.com/trickerer/Trinity-Bots) 是 AzerothCore 的一个模块。
[PlayerBots](https://github.com/liyunfan1223/mod-playerbots/) 是 AzerothCore 的一个模块。
基于一些玩家对不同机器人的需求不同，我将两个模块做了合并整合，可以实现双机器人共存。


## 安装

安装说明可以在 [这里](http://www.azerothcore.org/wiki/Installation) 获取。

NPCBots 使用指南可以在 [NPCBots Readme](https://github.com/trickerer/Trinity-Bots#npcbot-mod-installation) 中找到。
PlayerBots 使用指南可以在 [PlayerBots Readme](https://github.com/liyunfan1223/mod-playerbots/blob/master/README_CN.md) 中找到。

## 支持

AzerothCore 自制的 wiki 可能有很多问题的答案。

对于求助请求，建议将问题发布到 [StackOverflow](https://stackoverflow.com/questions/tagged/azerothcore) 。


## 报告问题

NPCBots 的问题可以通过[Github 问题跟踪器](https://github.com/HolmesLiu/AzerothCore-wotlk-npcbot-playerbot/issues/) 报告。 

请花时间查看现有问题，防止提交重复的问题。


## 提交修复

C++ 修复可以通过 [拉取请求](https://github.com/HolmesLiu/AzerothCore-wotlk-npcbot-playerbot/pulls) 提交。


## Important Links

- [NPCBots Readme](https://github.com/trickerer/Trinity-Bots/)
- [PlayerBots Readme](https://github.com/liyunfan1223/mod-playerbots/)

## 许可证

- 新版 AzerothCore 源代码组件发布在 [GNU AGPL v3](https://www.gnu.org/licenses/agpl-3.0.en.html) 下。
- 旧版基于 MaNGOS/TrinityCore 的源代码发布在[GNU GPL v2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html) 下。

重要的是要注意，AzerothCore 不是 Blizzard Entertainment 的官方产品，也与《魔兽世界》或 Blizzard Entertainment 无关。AzerothCore 绝不赞助或支持非法的公共服务器。如果你使用这个项目来运行非法的公共服务器而不是为了测试和学习，那是你个人的选择。
