# CI expansion

本拓展来源于[minecraftctl](https://github.com/MemoryShadow "点击查看")的[CI](https://github.com/MemoryShadow/minecraftctl/blob/2d69b1c88c2c99ba91781c0183d13a606c7b47a1/.github/workflows/main.yml#L244-L287 "点击查看"), 部分.

将其抽出来以验证拓展功能的正确运作.

## 用法

要使用很简单, 只需要在config中设置CheckID变量(例如: `export CheckID=000000`), 然后启动服务器, CI会自动的完成所有工作以检测minecraftctl的功能.

不过要注意的是, 你需要在`~/pyCraft`里准备好[pyCraft](https://github.com/MemoryShadow/pyCraft.git "点击查看"), 还要记得准备好python的环境.
