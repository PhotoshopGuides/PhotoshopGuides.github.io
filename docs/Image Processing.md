## Image Processing Preferences: AI and Selection Speed

The Image Processing tab controls how Photoshop handles complex AI-driven tasks like selecting subjects, removing backgrounds, and using the powerful "Remove Tool." These settings determine whether your computer's local hardware (GPU/CPU) or Adobe’s cloud servers do the heavy lifting.

- [x] Select Subject and Remove Background: Device (Faster)
- [x] Selections Processing: Faster
- [x] Remove Tool Processing: Faster
- [x] Enhance Detail Processing: Faster

##### Under the Image Processing Section

- [x] **1. Select Subject and Remove Background: Device**
*(AI Cloud processing vs local processing)*

This setting determines which "engine" Photoshop uses to identify subjects in your photos.
* **Device (Recommended):** Uses your local computer's resources (CPU and GPU). This is significantly faster and doesn't require an internet connection.
* **Cloud:** Sends the image to Adobe's servers for processing. This produce higher-quality selections but it requires and active Adobe Creative Cloud Subscription, is slower and depends entirely on your internet speed.

**Navigation:** `Edit > Preferences > Image Processing > Select Subject and Remove Background`

- [x] **2. Selections Processing: Faster**
*(Reduces lag when using AI selection tools)*

This affects how Photoshop calculates boundaries for tools like the Object Selection Tool. 
* **Faster:** Uses optimized algorithms to give you a selection nearly instantly.
* **More Stable:** Uses a more conservative approach that is slower but less likely to cause crashes on older, low-end hardware. For modern systems, keep this on **Faster**.

**Navigation:** `Edit > Preferences > Image Processing > Selections Processing`

- [x] **3. Remove Tool Processing: Faster**
*(Speeds up the Generative AI-powered Remove Tool)*

The Remove Tool is one of the most resource-heavy features in Photoshop. Setting this to "Faster" allows your GPU to process the "fill" area quickly. If you find that the Remove Tool is taking forever to process even small areas, ensure this is set to **Faster** and that your Graphics Processor is enabled in the Performance tab.

**Navigation:** `Edit > Preferences > Image Processing > Remove Tool Processing`

- [x] **4. Enhance Detail Processing: Faster**
*(Optimizes raw image enhancement)*

This setting controls the speed of AI-based upscaling and detail enhancement. Unless you are experiencing frequent crashes when using "Enhance Detail" on high-resolution Raw files, keep this set to **Faster** to minimize processing wait times.

**Navigation:** `Edit > Preferences > Image Processing > Enhance Detail Processing`

---

### Troubleshooting Image Processing Speed
**Why is my selection taking 30 seconds to process?**
If you have switched from **Device** to **Cloud** processing, every selection you make must be uploaded, processed by Adobe, and downloaded back to your machine. For 99% of workflows, keeping this on **Device** and **Faster** will provide the best performance and eliminate that 30-second lag.
