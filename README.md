## Nevysha's Cozy Nest (Pro)

Minimum requirements: 

• SD-WebUI [20ae71f] (https://github.com/AUTOMATIC1111/stable-diffusion-webui/commit/20ae71faa8ef035c31aa3a410b707d792c8203a3) 

!Warning!: Not designed to be compatible with Vlad's fork of WebUI.

## Features

• Simplified and stylized UI for smooth interaction

• Fullscreen image viewer redesigned for distractionless viewing of generated images

• PNG info tab redesigned to allow for full size 512x512 viewing and centered display of generation parameters

• Subpixel sampling for ultra smooth font display

• Various UI bug fixes and tweaks

## Screenshot

![](https://github.com/pflky/Cozy-Nest-Pro/blob/main/assets/screenshot.png?raw=true)

## Installation

Use "Install from URL" in the Extensions section of WebUI. 

## Notes

[1] This is a personally customized version of Cozy Nest, as such it has limitations to the UI itself. 

Firstly, it uses an earlier version of Cozy Nest, and will not be updated to accomodate future versions. Secondly, these customizations are made to my own personal liking, and there are limitations to how far these customizations extend to other features. For example, thirdy party extensions may not match the theme perfectly. Also the tab navigation menu is fixed to the left side and some other features have been removed. These decisions were done for the overall good of this fork's intent. 

Despite this, I believe this fork is an overall improvement. Since I cannot cover all the bases at once, there may be bugs or alignment issues with certain less used features, such as anything but the Checkpoint/VAE/Clip skip menu's in the top quicksettings bar. Anything else added to the quicksettings bar may be aligned a bit differently. For most users this probably won't be an issue.

[2] Some seldom used features have been removed from the UI. Such as the checkpoint and styles refresh buttons, and X/Y plot comparison scripts. To restore them, open style.css with notepad and remove the annotated code found at the end of the file. They are segmented so you can easily identify and remove the appropriate code if you want to pick and choose which of these features you want visible. 

## Credits
* [Nevysha] https://github.com/Nevysha/Cozy-Nest the base for this customized version
* [anapnoe] (https://github.com/anapnoe/stable-diffusion-webui-ux)'s incredible work on its fork of sd-webui
* [AUTOMATIC1111] (https://github.com/AUTOMATIC1111/stable-diffusion-webui)'s work on sd-webui
