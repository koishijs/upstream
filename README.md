# Upstream Plugins

这个仓库用于同步来自上游框架的插件。

Koishi 采用了框架派生技术。一个 Koishi 应用本身就是一个 Satori 应用，后者又是一个 Cordis 应用。这意味着 Koishi 可以安装为 Satori 或 Cordis 开发的插件。

然而，目前 Koishi 插件市场对插件名称有严格的限制，来自 Satori 或者 Cordis 的插件虽然是合法的 Koishi 插件，却不能进入 Koishi 的插件市场。因此，使用这个仓库对上游插件做进一步的封装。

未来会有方案允许 Koishi 直接安装来自上游生态的插件，届时此仓库将被废弃。

## 插件

- adapter：来自 [satorijs/satori](https://github.com/satorijs/satori) 的适配器插件
- server：来自 [satorijs/satori](https://github.com/satorijs/satori) 的服务器扩展插件

## 许可证

[MIT](./LICENSE)
