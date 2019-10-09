# FWConverter (Mac & Win)
### ---> Download [here](https://github.com/micutil/Odroid-GO_FWConverter/releases)

FWConverter is the converting application. You can convert a android bin file that build for Odroid-ESP32 with arduino to fw file. See [Make Arduino Applications for ODROID-GO](https://wiki.odroid.com/odroid_go/arduino_app).

![preview](image/icnFWC128.png)

### Update
v1.1.3 (2019/10/9)

- Fixed bug of the opening for icon editor.
- In case of the selected a bin file. if there's not a image file of the same name of bin, opening dialog for select image.


## How to use

- Make a bin file and a picture file (jpg, png, tiff or color565 raw file), then, these files place in a same folder and same name. Their file names have to be same, like 12345.bin and 12345.jpg.
- You just drag & drop the picture file (or bin file) to main window of FWConverter or icon of FWConverter app.


- Icon editer: File menu -> New Icon editor
	1. Add images.
	2. Set buckground color (click the center of rectangle).
	2. Set the top-left position with x, y value in listbox.
	3. Set the zoom (%) in listbox.
	4. Save.
![preview](image/editimage.png)

#### Version history

- You can now drop files in the shell console field of the main window (v1.1.2: 2019/10/7).
- Fixed a bug that the fwcnv file that became unnecessary in v1.1 does not start unless it is in the "tool" folder (v1.1.1: 2019/10/7).
- Included the Windows version (v1.1.0: 2019/10/5).
- 86x48 pixel icon picture editor (v1.1.0: 2019/10/5). 


## License

CC 4.0 BY Micono @ https://github.com/micutil/FWConverter
