# Video Broker 视频爆破装置
一款使用Python脚本爆破视频的利器。
---

## Usage
```
app [--buffer <buffer-size>] [--source <input-file>] [--target <output-file>] [--record]
```
### Buffer Size

设置此项来定义每次更改的字节数有多少。默认值为`114514`。

### Source File

设置此项来定义输入文件，默认值为`source.mp4`。

### Output File

设置此项来定义输出文件，默认值为`output.mp4`。

### Record

设置此项以便记录每次生成的、用于替换参数的随机数。

## Build

使用Nuitka和Pyinstaller均可。在使用Pyinstaller时注意使用空白环境来减少生成文件大小。

实验证明Nuitka比Pyinstaller生成的文件大，希望有人能帮我看看为什么。