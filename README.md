# 针对RuyiSDK Eclipse插件的测试

测试版本为 [v0.1.4](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/releases/tag/v0.1.4)

## 测试说明

以手动测试的方法，测试 [ruyisdk-eclipse-plugin](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/)

## 安装方法

- 见 [ruyisdk-eclipse-plugins/releases](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/releases)

## 环境配置

+ OS: Ubuntu 24.04 (Plucky Puffin)
+ CPU: 16 核 x86-64
+ 内存：4G
+ 镜像：https://releases.ubuntu.com/24.04/ubuntu-24.04-desktop-amd64.iso

## 测试结果

共 17 个测试用例，成功 13 个，失败 2 个。
| 测试用例 | 结果 | 备注 | issues |
| :------------------------: | :----: | :----------------------------------------------------------------------------------------------------------: | :---: |
| 包管理器/安装包 | 失败 | 包在下载完成前还是关闭，并重新打开，导致下载失败 | [#82](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/issues/82) |
| 新闻/切换仅未读 | 失败 | 在白色主题下，Unread Only 勾选不明显 | [#98](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/issues/98) |
