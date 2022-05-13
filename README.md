<img src="logo.webp" alt="Mirai Face" align="right">
<div align="center">
  <h1>Mirai 的 purpur 版本</h1>
  <h5><i>我无法保证它是稳定的, 此分支会尝试在作者更新 purpur 版本后重置并开始更新</i></h5>
  
  <h3>一个来自未来的强大的MC服务器</h3>
  <h5><b>这个项目是实验性的, 如果你没准备好面对可能的错误, 不推荐在生产环境中使用它.</b></h5>
  
  ![Build status](https://img.shields.io/github/workflow/status/etil2jz/Mirai/Build/ver/1.18?style=for-the-badge)
  [![Discord](https://img.shields.io/discord/928402257605701683?color=5865F2&label=discord&style=for-the-badge)](https://discord.gg/DdH6Yfu9gM)
</div>

## 特性

- **使用 [Pufferfish](https://github.com/pufferfish-gg/Pufferfish) 和 [purpur](https://github.com/PurpurMC/Purpur)** 以获得最佳性能.
- **包含 [Lithium](https://github.com/CaffeineMC/lithium-fabric) 补丁** 不影响原版特性.
- **高效红石** 使用 [Alternate Current](https://github.com/SpaceWalkerRS/alternate-current), 比 Paper 的算法快4倍.
- **(WIP) Implements [C2ME](https://github.com/RelativityMC/C2ME-fabric)** 提高区块生成, I/O, 和加载速度.
- **减少带宽消耗和 CPU 使用** 避免在某些情况下发送无用的数据包.
- **预调整配置** 配置文件以在对正常行为影响最小的情况下达到最佳性能.
- **登录位置隐藏** 为管理员在日志中添加另一个安全层.
- **可切换指标**, 没有人可以收集数据, 即使是我们.
- **错误修复** 对于 Minecraft 的一些bug.
- **快速处理** 对于 Vanilla 方法.
- **插件兼容** 对于 Spigot & Paper 插件.

**注意 Java 版本必须大于等于 17.**

## 此分支
删除了阻止 `reload commands` 的程序, 它没有错, 但我需要用于测试插件. 请不要在生产环境中使用它

## 许可
Patches are licensed under GPL-3.0.  
All other files are licensed under MIT.

