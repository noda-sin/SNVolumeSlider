SNVolumeSlider
==============

UISlider subclass to sync with device volume value like default music app.

Installation
------------
1. Drag SNVolumeSlider.h and SNVolumeSlider.m to your project.
2. Add "MediaPlayer.framework" and "AudioToolbox.framework" to your linked frameworks.

Usage
-----

      SNVolumeSlider *volumeSlider = [[SNVolumeSlider alloc] init];
      [[self view] addSubView:volumeSlider];

You can also use in Interface Builder.

![IBuilder](https://raw.github.com/nottihub/SNVolumeSlider/master/ibusage.png)

Please check the included demo project for more options.

License
-------
SNVolumeSlider is licensed under the terms of the MIT License. Please see the LICENSE file for full details.
