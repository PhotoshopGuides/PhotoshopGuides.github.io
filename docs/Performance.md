## Performance

##### Memory Usage - Ram - (Personal preference)
Ram doesn’t magically make Photoshop run faster, but it can remove bottle necks and make it more efficient. If you are running multiple programs or filtering large files, then you will need lots of ram available, You can buy more, or make better use of what you have.
Set your RAM to 75-80% to get the most to Photoshop while still leaving enough for your OS and utilities, If you have a large amount such as 64GB and don’t run other programs with Photoshop, bump it up to 80-90%.

        . If Lower than 16gb ->  70%
        . If Lower than 32gb and dont run other programs with PS (Google Chrome) ->  80-90%
        . If More than 32gb and run other programs with PS (Google Chrome) ->  75-80%

##### History & Cache - (Personal preference)

**1. History State - (Personal preference)**

History States allow you to go back in time and undo your mistakes. If you’re terrible at Photoshop, you probably need a lot of these. But if You’re a Photoshop samurai, you can lower the history state count.
Each operation saved in the history increases the “scratch disk size”. Accordingly, the less data you will be storing in history, the less storage space scratch disk will take.

        . Powerfull system configuration and high storage
            If Master of Photoshop and dont use Undo option Much - Less history state ≤ 50
            If Still a biginer and dont use Undo option alot -  More history state ≥ 50-70
        . Weak system configuration and less storage - Less history state ≤ 50

**2. Cache Levels -**

Photoshop uses cache to display an image quickly. If you work with small or average files, 1280x1024 pixels and many layers (50 and more), set cache levels to 2. If you work with large files, 10 MB and more, set cache levels to 4 and more. The higher value of cache level speeds up the display process.
Note that the more Cache Levels you have, the faster Photoshop CC will work. Adjust the following setting according to your use. History & cache size allows you to undo the changes for images. I use the following for fast performance.

        . If work with small size images( ≤	2k pixels) - Cache Level - 2
        . If work with large size images( ≥	2k pixels) - Cache Level - 4-6

Three cache presets are available in the Performance preferences. Choose the one that matches your primary use case/purpose of using Photoshop:

**Web/UI Design:**  Choose this option if you use Photoshop primarily for web, app, or screen design. This option is appropriate for documents having numerous layers of low-to-medium pixel dimension assets.

**Default/Photos:**  Choose this option if you use Photoshop primarily to retouch or edit moderate-sized images. For example, use this option if you normally edit photos originating from your mobile or digital camera in Photoshop.

**Huge Pixel Dimensions:**  Choose this option if you work extensively with heavy documents in Photoshop; for example, panoramas, matte paintings, etc.

**3. Cache Tile Size -**
Responds to the volume of data, that photoshop processes at a time. Larger volumes speed up the overall manipulations with an image, for example, sharpening. Smaller volumes work faster when you change small areas of the picture, for instance, work with a brush. For new processors, it's recommended to choose 128 K or 1024 K. For old ones (very old) 132 K or 1032 K.

        . Newer more powerfull processors -> 128 K or 1024 K
        . Old less powerfull processors -> 132 K or 1032 K

### Legacy Compositing - 

Only if having problems and Blending modes don’t look right, or the color are weird.
In the last few updates some people were complaining that their Blending modes didn’t look right, or the color was weird.
This can be fixed by using the legacy compositing engine. (Make it work like it did in CC 20018 and earlier).

        Preferences -> Performance -> check: Legacy Compositing




