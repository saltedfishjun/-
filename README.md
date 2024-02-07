这里是说明文档，这里会简单介绍各个核心以及插件。了解更多请自行bing，百度是个**。
部分介绍收集自网络
# 核心介绍 #
核心是一个.jar文件，使用启动命令将其启动并完成配置就可以开服开服教程可以看我的blog文章：[使用mcsm面板搭建我的世界服务器|meiのblog (mmeiblog.cn)](https://mmeiblog.cn/archives/shi-yong-mcsmmian-ban-da-jian-wo-de-shi-jie-fu-wu-qi)


## 原版 ##
由mojang官方制作的核心，不推荐使用。

## Hose ##
Java版 核心
> MITE 是一款提高游戏的生存方面难度的综合类 MOD，通过重新定义并调整游戏机制来增加生存的难度。此为 MITE 官方服务端，无法安装其他任何 MOD 包括 Forge。 
作者：PixelBBS https://www.bilibili.com/read/cv19386482/ 出处：bilibili


### Vanilla ###
我的世界Vanilla核心是官方提供的原版游戏服务器核心，它是最基本的服务器核心，可以提供原版游戏的所有功能。Vanilla有着简单的配置方式和不错的稳定性，但功能不够强大，无法满足大多数服务器的需求。

## Fabric ##
Fabric服务端需要搭配Fabric API才可以安装mod，本站不提供Fabric服务端下载，因为你可以在官网自行搭配Fabric组合。
[Download Minecraft Server Launcher | Fabric (fabricmc.net)](https://fabricmc.net/use/server/)
>Fabric是一个轻量级的MOD API，用于Minecraft1.14及以上版本，主要作者是asiekierka和modmuss50。
Fabric由两部分组成，包括Fabric API和Fabric Loader，Fabric Loader主要用来实现MOD加载功能，Fabric提供一些基础的接口供开发者使用，允许其他MOD注册物品、模型、方块、图形界面等，允许MOD通过SpongePowered Mixin修改Minecraft字节码，这一点相对于Forge来说更加安全，因为Mixin能够更好的控制字节码的改动。
Fabric并不采用 Mod Coder Pack。它有自己的反混淆工程，名叫“yam”（原名 pomf）。yarn 是开源的，任何人可以贡献，开源协议是 CC0 1.0 Universal。因为 Mod Coder Pack 协议限制，给 Fabric 的贡献的内容不能来源于 Mod Coder Pack。
Fabric更新的速度非常快，基本上党最新版本的Minecraft发行的时候，Fabric会在最短的时间内跟进，真的非常方便！---zeruns

## Forge ##
### 支持 ###
Forge服务端，支持Forge mods
### 介绍 ###
>目前 Minecraft 的主流 API，目前有半数以上的模组都在使用 Forge，以易于与 Minecraft Java Edition 的驳接。
一般情況下 Forge 的更新速度很快，一般在 Minecraft 正式版本发布后的一天内更新，偶尔有出现因为一些测试需求在 Minecraft 快照发布后更新的（出现过适用于特定快照版本的 FML）。
Forge 是一个版本支持度极高的 API，远古版本 ~ 最新版本 均有支持。
运行任何带有 Forge 的 Minecraft 时，在主界面点击“Mods...”按钮均可显示正在运行的模组，其中 Minecraft、Minecraft Forge、Forge Mod Loader (FML) 和 Mod Code Pack (MCP) 都是 Forge 的核心模组（旧版没有 Minecraft，新版没有 FML 和 MCP），必定默认出现在模组列表。---mcbbs


## 混合端 ##
同时支持模组和插件的服务端


### Kcauldron ###
#### 支持 ####
Forge模组，Spigot插件
#### 介绍 ####
老式 Forge 服务端，兼容插件 + Mod

### Thermos ###
#### 支持 ####
Forge模组和Bukkit插件
#### 介绍 ####
1.7.10 Forge 服务端，兼容插件 + Mod，兼容性好.KCauldron的优化版本

### Uranium ###
#### 支持 ####
Bukkit, Spigot 插件以及 1.7.10 的 Forge mod
#### 介绍 ####
1.7.10 Forge 服务端，兼容插件 + Mod。Uranium端（不断更新）是kc（停止更新）以及Thermos（停止更新）的优化以及后续版本，修复了更多的mod以及服务器bug，稳定性和适用性更强，并且是国人制作的服务端，更适合中国的腐竹。Uranium 是一款基于 KCauldron 进行大量修复以及优化的服务端，并且整合了部分 Thermos 对服务端进行的修复，能够兼容 Bukkit, Spigot 插件以及 1.7.10 的 Forge mod，并没有计划向高版本兼容

### Arclight ###
#### 支持 ####
Arclight支持Forge模组，Bukkit插件。
#### 介绍 ####
我的世界Arclight核心是一个开源的我的世界服务器核心，它是为那些寻求一个轻量级、可扩展的我的世界服务器核心而设计的。它包括了原版游戏的全部功能，并且拥有高度的自定义和扩展性。

### Catserver ###
#### 支持 ####
CatServer支持Forge模组，Bukkit+Spigot插件。
#### 介绍 ####
国内最早开发的高版本核心, 支持大部分MOD和插件同时稳定运行

### Mohist ###
#### 支持 ####
Mohist支持Forge模组，Paper系列插件。
#### 介绍 ####
>Mohist 是一个全新的 Minecraft Forge 服务端，核心采用 Forge + Paper 结构，开发环境使用 ForgeGradle，支持 Forge mod 和 Paper 系列插件。Mohist 目前稳定性良好，仍在不断更新。---zeruns
ps:据说现在mod开发者都很讨厌mohist

### SpongeForge ###
#### 支持 ####
SpongeForge支持Forge模组，Sponge插件。
#### 介绍 ####
>Sponge 是一个全新的服务端，支持 Sponge 的专用插件，可装 Mod，兼容性比 Cauldron 相比提高了不少，适合开 MOD 服，支持的版本非常高，是目前支持 MOD 的服务端里兼容版本最高的服务端。
但是 Sponge 本身不支持 Bukkit 插件（即使有兼容层，效果也不是很好，只能支持一般的插件），需要服务器的配置比较高，启动速度不佳。---zeruns


## 插件服 ##
顾名思义，支持插件的服务端，很多。


### CubeRite ###
#### 支持 ####
Bukkit插件
#### 介绍 ####
> CubeRite 是一个基于 C++ 编写的开源高性能 Minecraft 服务端
目前 Cuberite 已经可以做到大部分的基于 Bukkit 架构的 Minecraft 服务端（例如 Spigot）的功能，并且在性能方面具有更大的优势。
作者：PixelBBS https://www.bilibili.com/read/cv19386482/ 出处：bilibili

### GlowStone ###
#### 支持 ####
Sponge,Bukkit插件
#### 介绍 ####
> GlowStone 萤石是一款开源的 Bukkit 服务端，开发者可以根据自己需求修改或制作一个服务端，内置了 Sponge 支持的插件。
作者：PixelBBS https://www.bilibili.com/read/cv19386482/ 出处：bilibili

### Akarin ###
#### 支持 ####
Paper系列插件
#### 介绍 ####
基于 Paper 进行优化的服务端，性能较好

### Folia ###
#### 支持 ####
Folia支持Paper系列插件
#### 介绍 ####
>Folia是PaperMC组织最新的项目，旨在实现真正的多线程和区域化心跳。该项目的目标是提供更好的可伸缩性和性能，并修复一些长期以来限制Minecraft服务器扩展的问题。Folia是由Minecraft优化传奇Spottedleaf开发的Paper的分支版本，旨在为真正多线程的服务器提供无妥协的解决方案，通过全新的API集成，实现了每个区域都具有自己的独立线程池和心跳循环的实现。本文旨在以易于理解的方式呈现信息，并提供一些在官方公告中可能没有涵盖的详细见解。
Folia项目的优势包括：可有效缩放的性能、局部化的性能优化、更加接近Vanilla单人游戏的实体生成行为、TPS报告的增强以及支持Folia的插件。Folia适用于中型到大型服务器，尤其是那些拥有足够硬件（线程）支持的服务器。对于那些散落的玩家比较多的游戏模式，如生存多人游戏、空岛等，Folia可以完全利用Regioniser提供的性能优势。同时，对于那些想要扩大运营规模的小型服务器网络来说，Folia可以使他们不必过多地复杂化设置。
Folia项目是一个有着革命性意义的项目，旨在提升Minecraft服务器的性能表现，让游戏体验更加顺畅。
原文：Folia - Multithreading Coming to your Minecraft server | Paper Chan hideout (paper-chan.moe)
作者：contextual_bandit
链接：https://juejin.cn/post/7216594359115726904
来源：稀土掘金
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。

### Paper ###
#### 支持 ####
Paper支持Paper系列插件
#### 介绍 ####
>PaperMC 通过快速、安全的软件和扩展的插件 API 改进了 Minecraft 的生态系统，作为使用最广泛、性能最稳定、最稳定的软件，提供快速发布和有用的支持。---paper官网

### Pufferfish ###
#### 支持 ####
Pufferfish支持Paper系列插件
#### 介绍 ####
Pufferfish是Paper的高性能分支，旨在提供企业功能并最大限度地提高性能。
#### Pufferfish Plus ####
Pufferfish Plus是我们Pufferfish的改进版本，其中包括企业支持和其他异步功能，例如异步实体跟踪器和异步寻路系统。在基准测试中，它比标准版本的河豚快约 25-30%。

### Mirai ###
**已停止更新**
#### 支持 ####
支持Paper系列插件
#### 介绍 ####
来自“未来”的服务器核心,基于 Pufferfish.此项目是实验性的，如果您还没有准备好面对可能的错误，则不鼓励在生产环境中使用它。

### Purpur ###
#### 支持 ####
Purpur支持Paper系列插件
#### 介绍 ####
>Purpur 是 Paper 服务器的直接替代品，专为可配置性和新的、有趣的、令人兴奋的游戏玩法而设计 特征。---purpur官网介绍机翻

### Spigot ###
#### 支持 ####
Spigot支持Bukkit插件
#### 介绍 ####
>Spigot 是 CraftBukkit 服务端之后的延续版本，比 CraftBukkit 优化了不少地方，支持 CraftBukkit 的插件，性能比 CraftBukkit 好很多，并且自带反作弊功能---zeruns

### CraftBukkit ###
#### 支持 ####
CraftBukkit支持 Bukkit API插件
#### 介绍 ####
老式的 Bukkit API 服务端，现在已经很少使用

### Airplane ###
#### 支持 ####
Airplane支持Paper系列插件
#### 介绍 ####
在 Purpur 基础上进行更多优化的服务端，性能好

### Tuinity ###
#### 支持 ####
Paper系列插件
#### 介绍 ####
SpongeForge是Minecraft Forge平台上Sponge API的实现。
在 Paper 基础上进行更多优化的服务端

### SpongeVanilla ###
#### 支持 ####
SpongeVanilla支持Sponge插件
#### 介绍 ####
SpongeForge是Minecraft Forge平台上Sponge API的实现。


## 代理端 ##
用于搭建群组服
>我的世界代理端，或者称之为Geyser，是一个允许我的世界基岩版和我的世界Java版的玩家在同一个服务器游玩的中介软件。
具体来说，Geyser充当了一个中间代理端，它翻译所有传入和传出的数据包，使得Java版服务器的数据包能被基岩版客户端正确理解，从而让基岩版的客户端能够进入Java版服务器。Geyser既可以作为独立代理工作，也可以作为插件安装在服务器上。---文心一言


### BungeeCord ###
BungeeCord 是一个高性能的反向代理服务端，它可以将多个 Minecraft 服务器变成一个 “群组服务器”。

### Velocity ###
Velocity 是一款全新的服务器代理，与 BungeeCord 相比，它拥有更高的性能与更好的安全性，它不仅能为高版本服务端提供更高效，更安全的传输协议，也能为低版本服务端提供 BungeeCord 的原始传输协议。Velocity 快得惊人：登录、服务器切换等，充分利用服务器的硬件进行优化

### Waterfall ###
>Waterfall is an upgraded BungeeCord, offering full compatibility with improvements to performance and stability.---官网

大致意思为Waterfall比BungeeCord更好


## 基岩版 ##


### PocketMine-MP ###
> PocketMine-MP 是一个用 PHP 开发的 Minecraft Bedrock 基岩版服务端，也是目前使用最为广泛的服务端之一。
因为高可扩展性和插件编写起来相对简易，深受广大手机版服主喜爱。 作者：PixelBBS https://www.bilibili.com/read/cv19386482/ 出处：bilibili
# 关于插件 #
**Paper支持CraftBukkit 和 Spigot 插件，上文Paper系列插件指的就是这个**
本站提供了几个好用的插件，均为汉化版并不全为最新版，我也懒得去搞最新版，现在版本也够用，它们的命令请在控制太输入“help”或者“？“来了解

## CoreProtect ##
CoreProtect - 快速，高效的方块记录，回滚和恢复
CoreProtect是一种快速，高效的数据记录和防止恶意破坏的工具。可以回滚和恢复破坏。为大型服务器设计，CoreProtect将记录和管理数据，而不会影响服务器性能。
CoreProtect是最常用的服务器保护的插件，并自2012年年初得到了大力发展。
了解更多:
[CoreProtect - Minecraft插件百科 (mineplugin.org)](https://mineplugin.org/CoreProtect)

## EssentialsX ##
EssentialsX 是一个基于 Spigot 服务端的基础插件，为从大到小的服务器提供核心功能。这些功能包括：
玩家可以自由设置家 服务器传送或给玩家提供物品套组，可以设置跨世界或单独世界。 玩家与玩家间的私有消息，传送，发送传送请求 玩家自定义昵称 很多的管理员工具包括踢出服务器，临时禁止登陆服务器、禁言与监禁 内建经济系统，包括木牌商店、付费执行命令和完全的 Vault 支持 此外，EssentialsX 的选择模块提供了更多综合的功能如聊天、世界保护、GeoIP查找还有更多
了解更多:
[EssentialsX - Minecraft插件百科 (mineplugin.org)](https://mineplugin.org/EssentialsX)

## BlockLocker ##
该插件允许您仅使用标志即可保护箱子、门、炉子、分配器、滴管、料斗和许多其他块。贴上标志后，只有标志上列出的人才能访问容器。它不使用数据库，所有信息都存储在附加到受保护块的标志上。因此，如果您使用 WorldEdit 移动宝箱，宝箱仍将受到保护。
[瞒块锁 |SpigotMC - 高性能我的世界](https://www.spigotmc.org/resources/blocklocker.3268/)

## AuthMe ##
AuthMe Reloaded可以防止在未登录的情况下放置方块、移动、使用其他命令，或者查看当前的在线玩家数。只有输入正确的密码才能正常登陆。特别是防止被盗号，自动通过UUID更新ID。登陆失败可能是你没有在指定时间内登陆。
每个命令和每个设置都可以用极其简单的配置文件来启用或者禁用。如果你不喜欢英语，或者不喜欢作者的翻译，你也可以轻松的自主编辑语言环境！
[Authme - Minecraft插件百科 (mineplugin.org)](https://mineplugin.org/Authme)

## CMILib ##
一个支持库，我也不知道是哪个的。

## Vault ##
Vault 插件是一个关于权限、聊天以及经济插件的前置插件，他能让这些插件快速地与Vault插件挂钩而不需要依赖于其他个别插件。多数关于注册和权限的前置插件配置过于繁琐且缺乏大部分功能，于是这个插件便诞生了。Vault插件可以通过更加直观明了的方式解决这些问题，并为这些插件提供他们可能所需要的支持与依赖服务。
[Vault - Minecraft插件百科 (mineplugin.org)](https://mineplugin.org/Vault)

## Residence ##
Residence是大多数服务器都会使用的插件，它不同于其他保护类插件，它可以让玩家自己保护自己的家园，无需再麻烦管理员。新版的Residence更是增添了许多新特性，为服主减轻了不少负担。
[Residence - Minecraft插件百科 (mineplugin.org)](https://mineplugin.org/Residence)

## LuckPerms ##
LuckPerm是一款先进、高等的权限插件，仅仅以快速、稳定可靠、灵活多变的特点，
便可以替代现有的许多权限插件，例如PermissionsEX、GroupManagerX、z/bPermissions、BungeePerms等主流权限插件。
LuckPerms这个插件的计划，本来是围绕着两个主要特点来制作的：高性能、强大且广泛的功能，
填补其他同类插件的功能缺陷、并且建立在同类现有功能上更进一步的优化功能。
LuckPerms还包括了非常广泛的API支持，这是为开发人员的添加的，
并且，luckperms还兼容各式各类Minecraft服务器软件&支持多种数据存储的选择。
[LuckPerms - Minecraft插件百科 (mineplugin.org)](https://mineplugin.org/LuckPerms)

## QuickShop ##
QuickShop是一个商店插件, 不需要使用命令, 玩家可以直接用箱子来售卖物品, 也可以简单的输入要购买的数量。 实际上, 玩家不需要掌握任何的命令, 就可以使用这个插件了。
这个插件需要安装前置Vault插件
[QuickShop - Minecraft插件百科 (mineplugin.org)](https://mineplugin.org/QuickShop)

## SkinsRestorer ##
SkinsRestorer是一个插件，用于恢复离线模式服务器和网络的皮肤，使玩家能够通过键入单个命令来更改皮肤。
[皮肤修复剂 |SpigotMC - 高性能我的世界](https://www.spigotmc.org/resources/skinsrestorer.2124/)

## ViaVersion ##
ViaVersion旨在允许新版本的客户端进入旧版本的服务器，支持CraftBukkit/Spigot/Paper/Sponge/BungeeCord/Velocity服务端核心，支持到最新游戏版本。
搭配ViaBackwards和ViaRewind甚至可以向下兼容，允许旧版本的客户端进入新版本的服务器。
ViaBackwards和ViaRewind都需要ViaVersion作为前置插件。
[ViaVersion - Minecraft插件百科 (mineplugin.org)](https://mineplugin.org/ViaVersion)

## worldedit ##
我的世界地图编辑器...在游戏中运行！
具有选择、原理图、复制和粘贴、画笔和脚本。
在创意中使用它，或在生存中暂时使用它。
需要 Java 版本。
与基于 Bukkit 的平台（Spigot 和 Paper）兼容。
[WorldEdit/命令 - Minecraft插件百科 (mineplugin.org)](https://mineplugin.org/WorldEdit/%E5%91%BD%E4%BB%A4)

## EasyWhitelist ##
白名单插件
白名单用法：（控制台中无需输入斜杠）
1.在游戏或控制台中执行“/easywl add <玩家名>”添加白名单
2.在游戏或控制台中执行“/easywl remove <玩家名>”删除白名单
3.在游戏或控制台中执行“/easywl list”查看白名单列表
4.在游戏或控制台中执行“/easywl on”开启白名单
5.在游戏或控制台中执行“/easywl off”关闭白名单
6.在游戏或控制台中执行“/easywl reload”重新加载

# <center>![图](https://picdl.sunbangyan.cn/2023/11/24/9e47bf4551239e4bb97a7472412828b6.png)</center>

 