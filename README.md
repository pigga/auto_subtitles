# auto_subtitles
自动为视频配上字幕
**实现思路**
1. 获取音频文件
2. 按段分割音频文件，并标记对应的时间轴
3. 若需要翻译，进行对应文件的翻译

*核心问题*
1. 从音轨中取出人声，且按照自然标准进行分割。（自然标准即正常的人类自然语言内的中断）
