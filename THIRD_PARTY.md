# 第三方组件与源码

“AI Cut Studio源码不公开”只指本App的自有代码，不包括必须按许可提供的第三方源码。

|组件|版本/来源|许可与提供方式|
|---|---|---|
|FFmpeg、ffprobe|8.1.1 / 官方n8.1.1源码|LGPL-2.1-or-later；源码归档、构建脚本和许可在DMG及同Release源码附件内|
|whisper.cpp、ggml|1.8.4|MIT；保留版权/许可，随附源码归档|
|Whisper small、large-v3-turbo-q5_0|维护者模型库固定修订98aa99a0a9db05ae2342309f5096248665f7cba3|MIT；模型版权通知在App和源码附件内|
|Apple系统框架、SQLite系统库|随macOS提供|不随包复制macOS系统库|

FFmpeg采用独立命令行进程调用，未链接进Swift App；当前构建禁用GPL、version3、nonfree及外部库自动探测，动态依赖限系统库。whisper采用静态CLI与内嵌Metal程序。准确构建选项见附件 `rebuild_standalone_tools.sh`；它是第三方工具重建脚本，不是App自有源码。

本软件使用FFmpeg（LGPLv2.1或以后版本），对应源码可从同一Release的 `ThirdParty-Sources-and-Licenses.zip` 或DMG“第三方源码与许可”目录取得。

[FFmpeg许可说明](https://www.ffmpeg.org/legal.html) · [whisper.cpp许可](https://github.com/ggml-org/whisper.cpp/blob/v1.8.4/LICENSE) · [模型固定版本](https://huggingface.co/ggerganov/whisper.cpp/tree/98aa99a0a9db05ae2342309f5096248665f7cba3)
