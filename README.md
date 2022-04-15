# edge-TTS-record

![edge-TTS-record-img](https://github.com/LuckyHookin/edge-TTS-record/raw/master/demo.png)

一个可以录制 Microsoft  Edge 浏览器的语音合成（TTS）语音并输出为 `.wav` 音频的（windows平台）工具。

Microsoft Edge 浏览器中有两款非常逼真的**在线**（Online）中文（zh-CN）语音：Xiaoxiao、Yunyang。

用法：

1. 下载 [edge-TTS-record.exe](https://github.com/LuckyHookin/edge-TTS-record/releases)，运行并允许联网
2. 在文本编辑框中输入文本，调整参数，点击试听
3. 没问题就可以点击录制了，音频文件会保存在指定的目录下

注意：

- 需要 Microsoft Edge 浏览器 Chromium 内核版，一般是 Windows 10 自带的，如果系统中没有安装，程序将自动为你下载安装
- 不管是试听还是录制，使用**在线**（Online）语音都需确保电脑是联网的
- 录制是全局的，应避免其他软件声音的干扰
- 在线（Online）语音似乎无法调整音调

TODO:

- [ ] 路劲配置
- [ ] 可自定义选择要录制的设备
- [ ] 软件更新检测


相关仓库：

界面（vue.js）：https://github.com/LuckyHookin/tts-record-html

音频录制模块（C#，NAudio）：https://github.com/LuckyHookin/RecordAudio
