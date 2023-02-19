# Posex - Estimated Image Generator for Pose2Image

## How to use

```
Click:      select body
Left Drag:  move joint (on joint)
            rotate camera (otherwise)
Right Drag: move whole body (if selected)
            move camera (otherwise)
Wheel:      zoom
```

## Installation

### Standalone

```
$ pip install -r requirements.txt
$ python app.py
```

Then open `localhost:55502` or `127.0.0.1:55502` in your browser.

### With [Web UI](https://github.com/AUTOMATIC1111/stable-diffusion-webui)

Go to `Extensions` tab, then select `Install from URL` tab and input `https://github.com/hnmr293/posex`.

Or move to `extensions` directory and type `git clone https://github.com/hnmr293/posex`.

In webui, open `Posex` accordion in `txt2img` or `img2img` tab, then click a checkbox. The canvas will be opened.

## Example

### Standalone

![sample](./image/sample.png)

### Web UI

![sample](./image/sample-webui.png)

result:

![sample result](./image/sample-webui2.jpg)

## History

### v0.2 -> v0.3 features
- Web UI extension

### v0.1 -> v0.2 features
- copying the image to clipboard
- multiple bodies
- canvas size changing
- UI has become ugly >_<;
