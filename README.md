# Bouncing Logo

This is an HTML page that shows a bouncing logo similar to the DVD logo screensaver. You can customize the image to be whatever you want and use it in OBS for streams and stuff.

## How to download

Download the ZIP file from GitHub: [here](https://github.com/lmntr/bouncing-logo/archive/refs/heads/main.zip).

## How to use in OBS

1. Add a new source.
2. Choose Browser.
3. Set URL to `file:///` + file path. (Note: if your on Windows, you can copy and paste it from Explorer.)
4. Set width and height to what you want. I recommend making it the same as the canvas resolution. For example, if **Base (Canvas) Resolution** in Settings > Video is set to **1920x1080**, then set **Width** to **1080** and **Height** to **1920**.
5. You can set the framerate by clicking **User custome frame rate**. The image will move at the same speed regardless of framerate.
6. I recommend clicking **Shutdown source when not visible** and **Refresh browser when scene becomes active** so that it will start in a new position each time you load the scene.

## How to change the image

Overwrite or edit `image.png` to change what image is shown on screen. The script will use the image's actual size, so make sure that it fits within the screen.
