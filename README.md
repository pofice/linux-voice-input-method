# linux-voice-input-method

这是在linux本地部署的基于Whisper的语音输入法

![Demo webpage](demo.png)

长按即可输入，它会自动把输出文本复制到剪贴板

要求有桌面环境，最好是kde

建议使用NVIDIA显卡，以提高推理速度

# 安装
无需创建虚拟环境，直接安装即可
```sh
pip install PyQt5
pip install -U openai-whisper
pip install zhconv
```
如果pip不能直接安装，可以使用以下参数来强制pip安装
```sh
--break-system-packages
```
装好依赖后即可运行
```sh
python qt.py
```
 
既然Linux的输入法不好用，那我为什么不直接用手机的输入法呢？
https://github.com/pofice/linux-voice-input-method-2
