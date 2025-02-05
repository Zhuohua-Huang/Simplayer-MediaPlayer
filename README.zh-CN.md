<h1 align="center">
  <img src="https://user-images.githubusercontent.com/71301342/177238397-d2113bbf-67e5-4ed5-916d-75ba7cf9d8b0.png" alt="Simplayer" width="200"/>
  <br>简播<br>
</h1>
<div align="center">
  <img src="https://img.shields.io/badge/build-passing-brightgreen" />
  <img src="https://img.shields.io/badge/Qt-v6.2.2-blue" />
</div>
<div align="center">

  [English](README.md) | [简体中文](README.zh-CN.md)
</div>
<p align="center">
简播，英文是“Simplayer”，由“simple”和“player”组成，是一个由ffmpeg、OpenGL 和 MultiMedia 搭建的简单但强大的多媒体播放器。Made by Zhuohua Huang and Tianyin Wang.
</p>


## 普通功能

* 可播放各种主流格式的音视频文件；

* 播放控制包括：暂停，播放，快进，快退，停止，上一首，下一首，0.5 ~ 4 倍速，选择进行单曲循环或者顺序播放，并且可以使用快捷键进行控制，选择视频文件打开并自动播放；

* 媒体库由所有过去打开过的文件所组成，可以使用上一首，下一首选择视频文件播放，同时考虑当文件已被删除的情况，如过去曾打开过的文件在本地已不存在，选择到这一文件时将自动删除并继续向下搜索下一首可以播放的文件，并可以由用户自由选择进行循环播放或者顺序播放；

* 程序打包：使用qt的打包工具进行程序的打包并可以在任何平台上进行运行；

## 高级功能

* 进度条预览：用户将鼠标悬停在进度条上的有效位置时，在进度条对应位置的上方将显示该位置处的一帧图像；

* 视频倒放：（非实时）用户选择需要进行倒放操作的视频文件，后台进行处理，等待一段时间后，就可以从视频的结尾播放到开头；

* 倍速播放：实现0.5 ~ 4倍的倍速播放；

* 查看媒体信息：在播放列表右边显示当前媒体的元数据信息，使用key-value形式展示；

* 进度微调（快进，快退）：点击快进或快退键，即可向前或向后快进（退）1s，除此之外可以通过快捷键进行实现；

* 音频波形图：如果是没有画面输出的音频文件，可以进行音频频谱图的动态展示并与音频的播放进度保持一致；

<div align="center">
  <img width="850" src="https://user-images.githubusercontent.com/78400045/172119035-a30b5d08-d148-45b4-af80-3e9b558c3d26.jpg" />
</div>



