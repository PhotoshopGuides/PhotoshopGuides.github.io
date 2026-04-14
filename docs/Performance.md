## Photoshop Performance Settings: How to Make Photoshop Run Faster

If you are dealing with Photoshop lagging, freezing, or running very slowly, your hardware settings are likely the culprit. Your system's RAM, CPU, and Graphics Processor dictate how fast Photoshop runs. By optimizing your Photoshop performance settings, you can fix memory leaks, speed up brush strokes, and prevent annoying crashes.

### Photoshop Memory Usage Settings: How Much RAM for Photoshop?

RAM doesn’t magically make Photoshop run faster, but lacking it causes severe bottlenecks. When Photoshop is using too much memory or runs out of RAM, it starts writing temporary data to your hard drive (the Scratch Disk), which is significantly slower. 

To allocate more RAM to Photoshop, set the slider to **70% to 80%**. This gives maximum resources to the application while leaving enough for your Operating System.

* **The 70% Rule (Recommended):** By default, Photoshop allocates 70%. If you have 16GB of RAM or less, leave it here. 
* **The 80% Rule:** If you have 32GB+ of RAM and you strictly run Photoshop without heavy background applications (like Google Chrome), you can bump this to 80%.
* **Warning:** If you are trying to figure out how to make Photoshop use less RAM, do not lower this below 50%, or the program will become unusable. Conversely, never allocate 90% or higher. Starving your OS of RAM will cause your entire computer to freeze.

**Navigation:** `Edit > Preferences > Performance > Adjust the "Let Photoshop Use" slider`

### Fix Photoshop Lagging: Graphics Processor Settings

If you have a dedicated graphics card, Photoshop can offload heavy visual tasks to it, massively speeding up your workflow.

- [x] **Check "Use Graphics Processor":** Ensure this is turned on. It is required for features like smooth panning, animated zoom, and the Select and Mask workspace.
- [x] **Check "Multithreaded Compositing":** This should be checked by default. It allows Photoshop to use multiple CPU and GPU threads to render layer blends faster.

### Photoshop Cache Levels and Cache Tile Size Settings

This section dictates how Photoshop handles the history panel and how it loads image data onto your screen. 

#### A. History States
History States allow you to go back in time and undo your mistakes. Each operation saved in the history increases your temporary cache. The more data you store in history, the faster you will see the dreaded "Scratch Disk Full" error.
* **50 States (Default):** Perfect balance for most graphic design and UI workflows.
* **20-30 States:** Use this if you want to speed up Photoshop and have a very small hard drive.
* **100+ States:** Use this only if you do heavy digital painting. *Warning: This requires massive amounts of free scratch disk space.*

#### B. Cache Levels
Photoshop uses cache levels to speed up screen redraws when you zoom in and out. 
* **Cache Level 2:** Best for small file sizes (≤ 2k pixels) with dozens or hundreds of layers (Web/UI Design).
* **Cache Level 4 (Default):** Best for moderate-sized images and standard photography.
* **Cache Level 6+:** Best for massive files (10MB+, panoramas, matte paintings) with very few layers.

#### C. Cache Tile Size
Cache tile size responds to the volume of data that Photoshop stores or processes at a single time. Larger tiles are more efficient for complex math operations (like filters), while smaller tiles are more responsive for frequent screen redraws (like painting).

The dropdown gives you four specific options: **128K, 132K, 1024K, and 1028K**.

* **128 K (Recommended for UI/Digital Art):** Choose this for documents with small pixel dimensions but many layers. This size is optimized for faster processing when changing small areas of a picture, such as working with a brush or moving small UI elements.
* **1024 K (Recommended for Photography/Print):** Choose this for faster processing of documents with large pixel dimensions (like 4K+ photos or large canvases) and fewer layers. Larger tiles speed up global manipulations like sharpening, blurring, or noise reduction.
* **132 K and 1028 K (Legacy Settings):** These are "non-standard" tile sizes designed for extremely old processor architectures (over a decade old). On modern systems, using these can actually cause a slight performance dip. Stick to **128K** or **1024K** for optimum compatibility with your GPU and CPU.

**Pro Tip:** If you notice "checkerboarding" (tiles appearing slowly) when you zoom or pan, try switching to a larger tile size (1024K) to see if your Graphics Processor handles the data chunks more efficiently.

**Navigation:** `Edit > Preferences > Performance > Cache Tile Size`

#### D. The Quick Presets (Auto-Optimize)
If you don't want to manually configure Cache Levels and Tile Sizes, you can use the three built-in preset buttons to automatically adjust them based on your primary workflow:
* **Web / UI Design:** Automatically sets Cache Levels to 2 and Tile Size to 128K. Perfect for documents with numerous layers of low-to-medium pixel dimensions.
* **Default / Photos:** Automatically sets Cache Levels to 4 and Tile Size to 1024K. Ideal for retouching or editing moderate-sized images originating from a digital camera.
* **Huge Pixel Dimensions:** Automatically sets Cache Levels to 6 and Tile Size to 1024K. Use this if you work extensively with heavy documents like panoramas or matte paintings.

**Navigation:** `Edit > Preferences > Performance > Optimize Cache Levels and Tile Size`

---

### Photoshop Performance FAQ & Troubleshooting

**Under which preference option can one set their Photoshop memory usage?**
You can set your memory allocation by navigating to `Edit > Preferences > Performance` (on Windows) or `Photoshop > Preferences > Performance` (on Mac). Look for the "Memory Usage" section at the top left.

**Why does my Photoshop keep freezing or lagging on a high-end PC?**
If Photoshop is lagging on a high-end PC, it is usually because Cache Levels and Tile Sizes are misconfigured for your specific workflow, or your Graphics Processor is disabled. Ensure "Use Graphics Processor" is checked in the Performance tab, and try reducing your History States if your scratch disk is nearing capacity.

**What is Legacy Compositing in Photoshop?**
*(Note: This option is only available in Photoshop CC 2020 and earlier).* If you are running an older version of CC and notice your Blending Modes don’t look right, checking the "Legacy Compositing" box under Performance Preferences forces Photoshop to use the pre-2019 rendering engine, which often fixes visual glitches.
