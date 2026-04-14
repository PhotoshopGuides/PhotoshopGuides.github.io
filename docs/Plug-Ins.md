## Plugins Preferences: Managing Extensions and External Tools

Plugins and Extensions allow you to add extra functionality to Photoshop, but they can also be a major source of startup lag and background memory usage. Optimizing these settings ensures that Photoshop only loads the external tools you actually use.

- [ ] Show all Filter Gallery groups and names
- [ ] Enable Developer Mode
- [ ] Enable Generator
- [ ] Enable Remote Connections
- [ ] Allow Extensions to Connect to the Internet
- [x] Load Extension Panels

##### Under the Options Section

- [ ] **1. Uncheck "Show all Filter Gallery groups and names"**
*(Simplifies the Filter menu)*

When checked, Photoshop expands every single folder in the Filter Gallery by default. If you prefer a cleaner menu and don't want to scroll through a massive list of filter names every time you open the gallery, keep this unchecked.

**Navigation:** `Edit > Preferences > Plugins > Uncheck "Show all Filter Gallery groups and names"`

- [ ] **2. Uncheck "Enable Developer Mode"**
*(Unless you are building your own plugins)*

This setting is specifically for software developers creating new UXP or CEP plugins. For 99% of users, leaving this enabled adds unnecessary overhead and potential instability. Ensure it is unchecked for a standard professional workflow.

**Navigation:** `Edit > Preferences > Plugins > Uncheck "Enable Developer Mode"`

##### Under the Generator Section

- [ ] **3. Uncheck "Enable Generator"**
*(Reduces background CPU usage)*

What is Adobe Generator? It is a background process that allows you to automatically export image assets in real-time as you work. While useful for web designers, it runs a "Node.js" process in the background that consumes RAM and CPU. If you don't use the `File > Generate > Image Assets` feature, turn this off to make Photoshop run faster.

**Navigation:** `Edit > Preferences > Plugins > Uncheck "Enable Generator"`

- [ ] **4. Uncheck "Enable Remote Connections"**
*(Security and Performance optimization)*

This allows external apps (like mobile apps or secondary computers) to connect to your Photoshop instance over a network. Unless you are specifically using a remote control app or a specialized cross-device workflow, this should be disabled to prevent unauthorized access and save network resources.

**Navigation:** `Edit > Preferences > Plugins > Uncheck "Enable Remote Connections"`

##### Under the Legacy Extensions Section

- [ ] **5. Uncheck "Allow Extensions to Connect to the Internet"**
*(Privacy and Speed)*

Many older extensions try to "call home" to check for updates or load external web content. This can cause Photoshop to hang or lag during startup while it waits for a server response. If your plugins work fine offline, unchecking this will result in a more stable experience.

**Navigation:** `Edit > Preferences > Plugins > Uncheck "Allow Extensions to Connect to the Internet"`

- [x] **6. Check "Load Extension Panels"**
*(Ensures your installed tools actually appear)*

If you have installed third-party panels (like retouching bundles or color grade wheels) and they aren't appearing under `Window > Extensions`, it is likely because this box is unchecked. Keep this enabled if you rely on any third-party panels.

**Navigation:** `Edit > Preferences > Plugins > Check "Load Extension Panels"`

---

### Troubleshooting Plugins
**Why is Photoshop taking so long to start up?**
Photoshop scans your plugins folder every time it launches. If you have many old or "Legacy" extensions, the startup process can take minutes. If you aren't using a plugin, consider moving it out of the `C:\Program Files\Adobe\Adobe Photoshop [Version]\Plug-ins` folder to a backup location to drastically speed up your launch time.
