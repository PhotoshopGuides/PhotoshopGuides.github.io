## File Handling Preferences: Saving Speed and File Compatibility

Your file handling preferences determine how Photoshop reads, writes, and backs up your data. Optimizing these settings is crucial for preventing crashes, reducing the time it takes to save large files, and managing your hard drive storage.

- [ ] Image Previews: Never Save (Recommended for speed)
- [x] Save As to Original Folder
- [x] Save in Background
- [x] Automatically Save Recovery Information Every: 10 Minutes
- [ ] Enable legacy "Save As" (Optional workflow choice)
- [ ] Do not append "copy" to filename when saving a copy
- [x] Prefer Adobe Camera Raw for Supported Raw Files
- [x] Ask Before Saving Layered TIFF Files
- [ ] Disable Compression of PSD and PSB Files (Depends on your storage space)
- [ ] Maximize PSD and PSB File Compatibility: Never (If working alone)
- [x] Recent File List Contains: 20 files (Personal preference)

##### Under the File Saving Options Section

- [ ] **1. Image Previews: Never Save**
*(Speeds up the saving process)*

Image previews generate a small thumbnail version of your file. They are useful when browsing through visual folders in Mac Finder or Windows Explorer, but generating this thumbnail forces Photoshop to process extra data, and also increase the PSD file size. The dropdown gives you three options: *Never Save*, *Always Save*, or *Ask When Saving*. If you properly name your files and dont need thumbnail previews, change this to **Never Save**. 

**Navigation:** `Edit > Preferences > File Handling > Set "Image Previews" to Never Save`

- [x] **2. Check "Save in Background"**
*(Prevents Photoshop from freezing while saving)*

When checked, Photoshop will process saving commands in the background, allowing you to continue editing your document or switch to another tab while a massive file writes to your hard drive. You should keep it enabled.

**Navigation:** `Edit > Preferences > File Handling > Check "Save in Background"`

- [x] **3. Check "Automatically Save Recovery Information Every: 10 Minutes"**
*(Crash protection)*

If you are dealing with Photoshop lagging or crashing, this setting is your lifeline. It creates a temporary backup of your file at the specified interval. The dropdown options are *5 Minutes, 10 Minutes, 15 Minutes, 30 Minutes, and 1 Hour*. 

**10 Minutes** is generally the best balance. Setting it to 5 minutes can cause annoying micro-stutters while working on huge files because Photoshop is constantly saving in the background, while 30 minutes or 1 hour risks losing too much progress during a crash.

**Navigation:** `Edit > Preferences > File Handling > Check "Automatically Save..."`

##### Under the File Compatibility Section

- [ ] **4. Check "Disable Compression of PSD and PSB Files" (Optional)**
*(Trades hard drive storage space for faster saving speeds)*

When you save a layered document, Photoshop naturally compresses the data to save storage space on your hard drive. However, compressing large files requires CPU processing power, which takes time. If you have plenty of free terabytes on your hard drive and you want your massive PSB files to save instantly, check this box. If you are low on disk space, leave it unchecked.

**Navigation:** `Edit > Preferences > File Handling > Check "Disable Compression of PSD and PSB Files"`

- [ ] **5. Maximize PSD and PSB File Compatibility: Never / Always**
*(Prevents file bloat)*

What is the purpose of the maximize PSD and PSB file compatibility setting? It saves a flattened, composite version of your image alongside the layered data. This makes it easier to open your files in older, legacy versions of Photoshop or third-party applications (like Lightroom or After Effects). However, it adds a massive amount of bloat to your file size. 

The dropdown gives you three choices: *Always, Never, and Ask*.
* If you work with a team or import PSDs into other video/animation software, set this to **Always**. 
* If you are working by yourself and just want smaller file sizes, set it to **Never**. 
* Avoid **Ask**, as it will bring up an annoying dialog box every single time you save a new file.

**Navigation:** `Edit > Preferences > File Handling > Set "Maximize PSD and PSB File Compatibility" to your preference`

- [x] **6. Recent File List Contains: 20 Files (Personal Preference)**
*(Controls the start screen history)*

When you choose `File > Open Recent` or look at your Home Screen, you will see your recent documents. You can change this to show the last 5 or up to 100 documents you've previously worked on. You don’t need to restart Photoshop for this one; it will immediately update your recent files list.

**Navigation:** `Edit > Preferences > File Handling > Change "Recent File List Contains"`
