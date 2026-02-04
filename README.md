# 针对RuyiSDK Eclipse插件的测试

测试版本为 [v0.1.2](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/releases/tag/v0.1.2)

## 测试说明

以手动测试的方法，测试 [ruyisdk-eclipse-plugin](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/)

## 安装方法

- 见 [ruyisdk-eclipse-plugins/releases](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/releases)

## 环境配置

+ OS: Ubuntu 25.04 (Plucky Puffin)
+ CPU: 16 核 x86-64
+ 内存：4G
+ 镜像：https://releases.ubuntu.com/25.04/ubuntu-25.04-desktop-amd64.iso

## 测试结果

共 12 个测试用例，成功 8 个，失败 4 个。
| 测试用例 | 结果 | 备注 | issues |
| :------------------------: | :----: | :----------------------------------------------------------------------------------------------------------: | :---: |
| 虚拟环境/创建虚拟环境并应用到项目 | 失败 | 创建虚拟环境时选择的路径若不在项目目录下则无法使用 | [#84](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/issues/84) |
| 虚拟环境/创建虚拟环境并应用到项目 | 失败 | 创建虚拟环境时 profile 列表的排序不一致 | [#89](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/issues/89) |
| 虚拟环境/创建虚拟环境并应用到项目 | 失败  |创建虚拟环境时 profile 列表无法适配新版本(0.45.0) ruyi 的中文输出   | [#109](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/issues/109)|
| 虚拟环境/虚拟环境删除后项目目录更新 | 失败 | 无法自动更新，只能手动 | [#99](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/issues/99) |
| 包管理器/安装包 | 失败 | 选择开发板的界面没有排序文本 | [#83](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/issues/83) |
| 包管理器/安装包 | 失败 | 包在下载完成前还是可以点击继续 | [#82](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/issues/82) |
| 新闻/切换仅未读 | 失败 | 在白色主题下，Unread Only 勾选不明显 | [#98](https://github.com/ruyisdk/ruyisdk-eclipse-plugins/issues/98) |