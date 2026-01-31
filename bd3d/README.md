# Blu-ray 3D

MVC-encoded stereoscopic 3-D media on 3D Blu-ray.

See also [win-scripts/3d](https://github.com/xenago/win-scripts/tree/main/3d) for more Windows-specific playback notes.

## Downloading 3D Blu-ray media to PC

3D media is usually obtained by buying 3D Blu-ray discs and a Blu-ray drive. These discs are encumbered by DRM that can be worked around with MakeMKV to produce digital versions that can be played on more devices and in more scenarios.

When MakeMKV is first installed, the 3D MVC video track is not selected by default. To fix this, update the default selection rules.

In `View > Preferences`, select the `Advanced` tab and for the `Default selection rule` make sure to change `-sel:mvcvideo` to `+sel:mvcvideo`. 

![Select MVC video by default with MakeMKV](makemkv_select_mvc_track_default.png)
