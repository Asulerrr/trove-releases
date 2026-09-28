# Spira 安装包

这个仓库只放 Spira 桌面应用的 Windows 安装包，每个版本一个 release。源码仓库是私有的，不在公开范围内。

## 下载

到 [Releases](https://github.com/Asulerrr/trove-releases/releases) 里挑最新那个：

- `Spira_<版本号>_x64-setup.exe` —— Windows x64 安装包
- tag 形如 `v0.1.0`，与应用内「关于 Spira」里显示的版本号一致

## 关于这个仓库

应用里的「检查更新」读的就是本仓库的 `releases/latest`，所以这个仓库是对外承诺的一部分：

- **只发正式版本，不发测试包。** 一旦发出去就收不回来——所有装了旧版的用户都会看到这次更新提示。
- **tag 的版本号必须和安装包的版本号一致。** 对不上会让用户永远被告知有新版本，而提示本身看起来完全正常。
- 仓库里没有源码，只有安装包。
