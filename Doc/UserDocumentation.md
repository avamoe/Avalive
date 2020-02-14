# User Documentation

English | [简体中文](https://github.com/avamoe/Avalive/blob/master/Doc/UserDocumentation_zh-Hans.md)

## Usage

### Start

Start Avalive and you can see this scene

* ① Change language
* ② You can role play a avatar and become a VTuber
* ③ A Yuru-chara with a mouse interaction

![](../Assets/Resources/Avalive-Tutorial1.png)

### Avatars

#### Avatar Models

You can use the webcam to capture your facial expressions, like ①, Avatar model will do the same expressions, like the Kizuna AI.

You can also click the Add button ② to import custom models. Currently only Live2d version 2 models are supported.

![](../Assets/Resources/Avalive-Tutorial2.png)

#### Avatar Backgrounds

The backgrounds can also add a custom picture (png, jpg, jpeg) background, like ①.

![](../Assets/Resources/Avalive-Tutorial3.png)

#### Avatar Options

In Options, you can switch the camera ①, set the camera image ② and FPS ③ display.

All models, backgrounds, and user configurations are synchronized via the Steam Cloud.

![](../Assets/Resources/Avalive-Tutorial4.png)

#### Avatar Import Model

You can import **Live2d version 2** models.

Files marked with **an asterisk ( * )** are required. **Physical and pose files without an asterisk ( * ) can be empty**.

The **icon file** is a button icon displayed in avatars. We recommend that you use 100*100 pixels.

You can **select multiple texture files**, and each path is separated by a semicolon ( ; ) .

![](../Assets/Resources/Avalive-Tutorial5.png)

This prompt appears when you import the model successfully.

Then you need to return to the start scene (changing the language) and **re-enter the Avatars scene** to see the model you imported.

![](../Assets/Resources/Avalive-Tutorial6.png)

#### Avatar Import Background

Importing the background is similar to importing the model, all the files with **asterisks ( * ) are required**.

The **icon file** is a button icon displayed in Backgrounds. We recommend that you use 100*100 pixels.

The **background file** is the background image of Avalive. We recommend that you use 1920*1080 pixels.

![](../Assets/Resources/Avalive-Tutorial7.png)

### Poster

This is a Yuru-chara, you can use mouse interaction, it can mouse tracking, lip tracking, automatic breathing, automatic blink.

![](../Assets/Resources/Avalive-Tutorial8.png)

## Advanced Features

### model

#### Live2d Cubism v3 model to v2 model

1. Download [Live2D Cubism Editor 3](https://www.live2d.com/download/cubism/) on the official website.

2. Use `Live2D Cubism Editor 3` to open the v3 model, and the menu bar `Modeling` - `Convert Model ID`, convert the v2 model.
    ![Live2DConversionOptions.png](../Assets/Resources/Live2DConversionOptions.png)

3. `File` - `Export For Runtime` - `Export as moc file(For 2.1)`, saved as v2 runtime model.
    ![LivedDExportRuntimeSettings.png](../Assets/Resources/LivedDExportRuntimeSettings.png)