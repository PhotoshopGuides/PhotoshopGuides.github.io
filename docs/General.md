## General Preferences: Core Photoshop Settings

##### Under the Options Section

- [ ] **1. Uncheck "Auto show the Home Screen"**
*(Disables the resource-heavy welcome screen)*

When you launch Photoshop, you see a welcome screen that takes over the entire window. While this can be useful for showing recent files or accessing Lightroom photos, it runs in the background. When you close your active document, instead of showing a blank, lightweight workspace, Photoshop loads this Home screen again. If you want to speed up your workflow and prefer a clean interface, disable it.

**Navigation:** `Edit > Preferences > General > Uncheck "Auto show the Home Screen"`

**Troubleshooting:** If unchecking the option does not disable the home screen, follow these steps to force the change:
1. Go to `Edit > Preferences > General` and uncheck "Auto show the Home Screen".
2. Click "Reset Preferences On Quit", click OK to the prompt, then close the preferences window.
3. Press `Ctrl + N` (Windows) or `Cmd + N` (Mac) and create a quick new canvas.
4. Close everything down. Reopen Photoshop, and the home screen should finally be gone.

- [ ] **2. Check "Use Legacy 'New Document' Interface"**
*(Speeds up the new document dialog)*

Have you noticed the default "New Document" window takes a few seconds to load and keeps growing in size? This is because the modern dialog connects to the internet to load Adobe Stock templates. If you want to make Photoshop run faster and instantly load a regular dialog box without the lag, switch back to the old interface. 

**Navigation:** `Edit > Preferences > General > Check "Use Legacy 'New Document' Interface"`

- [ ] **3. Uncheck "Export Clipboard"**
*(Helps reduce Photoshop memory usage)*

"Export Clipboard" is only useful if you frequently copy image elements from Photoshop and paste them into *other* external applications or vice versa. When you copy an image, that data is pushed to your computer's system RAM and stays there until you restart your computer or copy something else. This limits the memory Photoshop has available. To make Photoshop use less RAM, turn this off. If you need to move elements between different Photoshop documents, simply drag and drop the layers instead of copying and pasting.

**Navigation:** `Edit > Preferences > General > Uncheck "Export Clipboard"`

- [ ] **4. Uncheck "Resize Image During Place" (Personal Preference)**
*(Prevents automatic upscaling and distortion bugs)*

While having Photoshop automatically resize an image to fit the canvas when you import it can be useful, it can also be frustrating. Occasionally, Photoshop has a bug where dragging an image from your desktop onto the canvas forces it to upscale beyond its original resolution or distorts its aspect ratio. If you want strict, manual control over the exact size and pixels of the images you place, disable this option.

**Navigation:** `Edit > Preferences > General > Uncheck "Resize Image During Place"`
