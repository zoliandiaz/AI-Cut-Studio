# AI Cut Studio v0.3.2-beta.1 · 免费内测

**先把故事剪出来：把一堆拍摄素材，整理成一版能预览、能调整、能继续精修的初剪。**

## 它解决什么问题

拍完活动或Vlog后，素材里既有口播，也有现场互动和拍摄过程。AI Cut Studio帮助你先梳理这些内容：根据你设定的类型、目标时长和要求，结合画面观察与语音转录，尝试建立故事章节、选择片段并安排顺序。

你得到的是供审核的故事结构、初剪时间线和预览，再导出FCPXML去兼容的编辑软件继续精修。它是独立Mac App，不需要Codex或聊天助手代为选段。

## 怎样用

1. 新建项目，导入视频；原文件保留原位。
2. 填写要求，例如“约15分钟的活动Vlog，允许浮动，保留精彩拍摄过程与有趣互动，讲清活动经过”。
3. 生成初剪，看片检查故事、镜头、段落和时长，调整审核清单。
4. 选择导出位置，保存FCPXML工程；需要字幕时，可先生成原文与中文翻译，再选择带或不带字幕导出。

本轮主要验证活动Vlog。AI不会保证每次都选中最精彩的镜头，也不保证故事或字幕完全正确；配乐、转场、调色和最终精修不在本版范围内。

## 下载、安装和费用

附件 `AI-Cut-Studio-0.3.2-beta.1-AppleSilicon.dmg` 约1GB。把App复制到“应用程序”，完成后推出镜像再打开。三项工具和两套语音模型已包含。

App内测使用免费；需自行配置DeepSeek API Key，并承担其API服务费。AI处理会发送低清抽帧、相关转录和剪辑要求，原视频不会整文件上传。请先阅读仓库[安装说明](https://github.com/zoliandiaz/AI-Cut-Studio/blob/main/INSTALL.md)、[隐私说明](https://github.com/zoliandiaz/AI-Cut-Studio/blob/main/PRIVACY.md)和[已知限制](https://github.com/zoliandiaz/AI-Cut-Studio/blob/main/KNOWN_ISSUES.md)。

## 本次内测边界

- 未完成Apple Developer ID签名和公证，首次打开可能被系统阻止。不要关闭系统安全保护。
- 支持目标是Apple Silicon/macOS14+；M1 16GB、macOS14及目标M2尚未实机验收。
- 中外语混说字幕可能误判或重复；可明确选择导出未校验字幕，不会因此改成已审核。
- FCPXML曾在剪映专业版11.7验证特定工程与双轨小样导入，不代表所有工程或版本通用。AI Cut Studio独立开发，与剪映及其运营方不存在隶属、合作或授权关系；第三方名称仅说明兼容性。

## 版本与第三方

本次为免费内测首发，使用范围见仓库[BETA_TERMS.md](https://github.com/zoliandiaz/AI-Cut-Studio/blob/main/BETA_TERMS.md)。App显示版本为0.3.2/build5；首发包同步了产品介绍和使用说明，没有新增剪辑功能或重新运行付费全片AI流程。

AI Cut Studio自有源码不上传。本软件使用FFmpeg（LGPLv2.1或以后版本），对应源码、重建说明与许可证在本Release的 `ThirdParty-Sources-and-Licenses.zip`，也包含在DMG中；该附件不含App自有源码。

请使用仓库Issue模板反馈安装、故事剪辑和字幕问题，不上传API Key、私人素材或完整项目库。
