# C# 离线小工具合集｜WPF / WinForm
> 系列自媒体项目：把常用在线小工具，使用 C# WPF / WinForm 独立实现为本地离线客户端

## 📖 项目介绍
网上很多在线工具需要联网、带有广告、部分工具存在隐私顾虑。
本仓库是配套自媒体系列教程的开源Demo，**仅用于学习交流**，使用 WPF / WinForm + 开源UI库实现各类离线小工具。

✅ 离线使用，不需要联网
✅ 源码全部开放，可直接运行学习
✅ 统一技术栈：.NET8 + HandyControl / WPFUI
✅ 配套B站视频、掘金文章讲解开发过程

> ⚠️ 重要声明
> 本项目仅参考公开在线工具的**功能需求**，所有代码均独立编写，没有复制、扒取原在线工具的JS源码、UI样式与资源。
> 图标、控件库均使用开源免费资源，遵循对应开源协议。
> 本仓库所有 Demo **禁止商用**，仅限个人学习。

## 🛠️ 开发环境
- IDE：Visual Studio 2022
- 框架：.NET 8
- UI库：HandyControl / WPFUI
- 依赖：NuGet 在线还原

## 📂 仓库目录结构
ToolCollection/
├─ Tool01-Base64Converter      // Base64 编解码工具
├─ Tool02-TimestampConverter   // 时间戳转换工具
├─ Tool03-JsonFormatter        // JSON 格式化 & 校验工具
├─ Tool04-QRCodeGenerator      // 二维码生成工具
├─ Tool05-RegexTester          // 正则表达式测试器
└─ CommonTemplate              // 公共模板项目（主题、辅助类、异常处理）

每个工具文件夹都是独立可启动项目。

## 🧰 工具清单（持续更新）
| 序号 | 工具名称 | 技术 | 配套教程 |
| ---- | ---- | ---- | ---- |
| 01 | Base64编解码 | WPF + HandyControl | B站/掘金 |
| 02 | 时间戳转换 | WPF + HandyControl | B站/掘金 |
| 03 | JSON格式化校验 | WPF + HandyControl | B站/掘金 |
| 04 | 二维码生成器 | WPF + HandyControl | B站/掘金 |
| 05 | 正则测试工具 | WPF + HandyControl | B站/掘金 |

> 后续会持续新增工具，同步更新自媒体教程。

## 📌 配套自媒体信息
- B站主页：【这里填你的B站主页链接】
- 掘金主页：【这里填你的掘金主页链接】
- 系列合集：【B站合集链接】

## 📝 使用说明
1. 使用 Visual Studio 2022 打开对应工具的 `.sln`
2. NuGet 自动还原包
3. 直接启动调试；也可以发布成单文件exe
4. 所有工具自带深色/浅色主题切换

## 🤝 欢迎交流
- 发现bug可以提 Issue
- 想要什么工具，可在评论区或者Issue留言提需求
