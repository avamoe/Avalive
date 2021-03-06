# 用户文档

[English](https://github.com/avamoe/Avalive/blob/master/Doc/UserDocumentation.md) | 简体中文

## 使用指南

### 开始

启动 Avalive 会看到这个界面

* ① 更换语言
* ② 你可以扮演虚拟形象，成为 VTuber、Vuper、虚拟主播
* ③ 一个鼠标交互的看板娘

![](../Assets/Resources/Avalive-Tutorial1.png)

### 虚拟形象

#### 虚拟形象模型

你可以使用网络摄像头捕获你的面部表情，像①，模型将会做同样的表情，像这个爱酱。

你也可以点击添加按钮 ② 来导入自定义的模型，现在只支持 Live2d v2 格式的模型。

![](../Assets/Resources/Avalive-Tutorial2.png)

#### 虚拟形象背景

你也可以添加 ① 自定义的图片（png, jpg, jpeg）作为 Avalive 的背景。

![](../Assets/Resources/Avalive-Tutorial3.png)

#### 虚拟形象选项

在选项中，你可以切换摄像头 ①，设置摄像头画面 ② 与 FPS ③ 是否显示。

所有模型、背景和用户配置都可以通过 Steam 云进行同步。

![](../Assets/Resources/Avalive-Tutorial4.png)

#### 导入模型

你可以导入 **Live2d v2** 版本的模型

带**星号（ * ）的文件必填**，不带星号（ * ）的物理、姿势文件选填。

**图标文件**是虚拟形象中的模型按钮，推荐使用 100*100 像素的图片。

你可以**选择多个纹理文件**，每个纹理文件以英文分号（ ; ）分隔开。

![](../Assets/Resources/Avalive-Tutorial5.png)

一旦你导入模型成功，就会出现导入成功的通知。

然后你需要退出到（选择语言的）开始界面，**重新进入虚拟形象场景**才会显示你刚刚导入的模型。

![](../Assets/Resources/Avalive-Tutorial6.png)

#### 导入背景

导入背景与导入模型相似，**带星号（*）的所有文件都是必填**。

**图标文件**是背景的按钮图片，推荐使用 100*100 像素的图片。

**背景文件**是 Avalive 的背景图片，推荐使用 1920*1080 像素的图片。

![](../Assets/Resources/Avalive-Tutorial7.png)

### 看板娘

你可以使用鼠标与看板娘交互，它可以做鼠标跟踪、唇形模仿、呼吸运动、自动眨眼。

![](../Assets/Resources/Avalive-Tutorial8.png)

## 高级功能

### 模型

#### Live2d Cubism v3 模型转换为 v2 模型（需要 cmo3 文件）

1. 官网下载 [Live2D Cubism Editor 3](https://www.live2d.com/download/cubism/) 软件。

2. 使用 `Live2D Cubism Editor 3` 打开模型的 `cmo3`，菜单栏 `Modeling` - `Convert Model ID`，转化 v2 模型。
    ![Live2DConversionOptions.png](../Assets/Resources/Live2DConversionOptions.png)

3. `File` - `Export For Runtime` - `Export as moc file(For 2.1)`，保存为 v2 的 Runtime 模型。
    ![LivedDExportRuntimeSettings.png](../Assets/Resources/LivedDExportRuntimeSettings.png)