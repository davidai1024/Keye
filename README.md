# 咸鱼课页桌面版

在自己的电脑上读取公开视频链接，整理视频画面和字幕，预览并保存 PDF。

下载：[Windows / Mac 桌面版](https://www.davidai1024.com/keye/desktop/) · [全部发行文件](https://github.com/davidai1024/Keye/releases)

支持 Windows 10/11 x64、macOS 13+（Apple Silicon / Intel 分别下载）。
安装包内置所需组件，无需配置 Python、Node 或 FFmpeg。
视频限 256 MB / 30 分钟，不支持直播。平台要求登录或验证时，请改用有权保存的本地视频。

AI 课堂笔记需要用户自己的 DeepSeek API Key；仅在选择 AI 时发送相关截图和字幕。
用户可选择由系统加密保存密钥。任务保存在应用内存，退出前请先保存 PDF。

0.1.0 为测试版，尚未完成发行者签名；Mac 尚未做 Apple 公证，系统可能阻止打开。
此仓库仅用于发行安装包、说明、校验和与第三方组件源码。
第三方源码包 `Keye-Media-Sources.zip` 与安装包在同一 Release，包含匹配的 FFmpeg/x264 源码、许可及构建脚本。
