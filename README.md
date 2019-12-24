# RT-Thread-AI

# ffmpeg.exe 使用方法
> ffmpeg {通用参数} {输入音频参数}  {输出音频参数}
```
ffmpeg -y  -i aidemo.mp3  -acodec pcm_s16le -f s16le -ac 1 -ar 16000 16k.pcm
通用参数： -y
输入音频mp3文件参数： -i aidemo.mp3
输出音频 16000采样率 单声道 pcm 格式：  -acodec pcm_s16le -f s16le -ac 1 -ar 16000 16k.pcm
```

