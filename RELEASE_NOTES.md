# AI Cut Studio v0.3.2-beta.1 · 首次免费内测

这是独立AI视频粗剪工具的安装包内测发布，支持FCPXML导出，自有源码暂不公开。建议先用一小组有代表性的素材验证。

提供项目隔离、素材原位引用、本地代理与转录、画面观察和故事初剪、审核预览、可编辑字幕与FCPXML导出。导出可选不带字幕或明确继续带未校验字幕，并自主选择保存位置。

下载 `AI-Cut-Studio-0.3.2-beta.1-AppleSilicon.dmg`；复制App到“应用程序”后推出镜像。三工具和两模型已内置。软件内测使用免费，DeepSeek Key和API费用由用户自行承担。

**未完成Apple签名公证；M1/macOS14及目标M2尚未完成实机验证。混说字幕可能出错，画面抽帧可能漏动作，故事方案须审核。** 详细说明见仓库INSTALL.md、PRIVACY.md及KNOWN_ISSUES.md。反馈请使用Issue模板，不附Key或私密素材。

本次候选包基于0.3.2/build5，清理主程序调试符号，并重建语音工具以移除开发电脑编译路径；App内显示版本仍为0.3.2。不是新的剪辑算法版本，未重新运行付费AI全片流程。

本软件使用FFmpeg（LGPLv2.1或以后版本），对应源码和构建说明可从本Release的 `ThirdParty-Sources-and-Licenses.zip` 下载，也包含在DMG中。其他第三方许可见附件。

附件：安装DMG、SHA256SUMS.txt、ThirdParty-Sources-and-Licenses.zip。

兼容性记录：剪映专业版11.7曾通过特定工程与双轨小样导入验证，不代表所有版本通用。AI Cut Studio与剪映及其运营方不存在隶属、合作或授权关系；第三方名称只用于说明兼容性。
