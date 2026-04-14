## Type Preferences: Optimizing Typography and System Memory

Whenever Photoshop launches, it scans the fonts installed on your system. If you have thousands of fonts, this can lead to high RAM usage and startup delays. Optimizing these settings helps manage the Photoshop font cache and keeps your text tools responsive.

- [x] Use Smart Quotes
- [x] Enable Missing Glyph Protection
- [x] Show Font Names in English
- [x] Use ESC key to commit text
- [ ] Set default font size automatically
- [x] Enable Type layer glyph alternates
- [ ] Fill new type layers with placeholder text
- [x] Automatic detection of Bulleted and Numbered lists while typing
- [x] Number of Recent Fonts to Display: 5

##### Under the Type Options Section

- [x] **1. Check "Use Smart Quotes"**
*(Ensures professional typography)*

Checking this automatically converts straight quotes (") into "curly" or "typographer's quotes" as you type. This is standard practice for high-end graphic design and makes your text look professionally typeset.

**Navigation:** `Edit > Preferences > Type > Check "Use Smart Quotes"`

- [x] **2. Check "Enable Missing Glyph Protection"**
*(Prevents "broken" characters)*

If you type a character that doesn't exist in your selected font (like a specific symbol or foreign character), Photoshop will automatically search for a similar font that contains that character instead of showing an empty box (the "tofu" character). This prevents your design from looking broken.

**Navigation:** `Edit > Preferences > Type > Check "Enable Missing Glyph Protection"`

- [x] **3. Check "Show Font Names in English"**
*(Improves font list readability)*

If you have international fonts installed (Japanese, Arabic, etc.), they can sometimes display in their native script, making it impossible to find them in your list. Checking this forces all font names to display in English.

**Navigation:** `Edit > Preferences > Type > Check "Show Font Names in English"`

- [x] **4. Check "Use ESC key to commit text"**
*(Improves workflow speed)*

Checking this allows you to quickly "finish" or commit your text layer by hitting `Esc`, rather than having to manually click the checkmark icon.

**Navigation:** `Edit > Preferences > Type > Check "Use ESC key to commit text"`

- [ ] **5. Uncheck "Set default font size automatically"**
*(Gives you manual control over font sizing)*

If checked, Photoshop tries to guess the "ideal" font size based on your document's resolution. This often leads to fonts appearing too large or too small. Uncheck this if you prefer your text to start at a standard size (like 12pt) every time.

**Navigation:** `Edit > Preferences > Type > Uncheck "Set default font size..."`

- [x] **6. Check "Enable Type layer glyph alternates"**
*(Access hidden font features)*

This enables the small pop-up menu that appears when you highlight a letter, showing you different stylistic versions (ligatures or swashes) of that letter if the font supports OpenType features.

**Navigation:** `Edit > Preferences > Type > Check "Enable Type layer glyph alternates"`

- [ ] **7. Uncheck "Fill new type layers with placeholder text"**
*(Reduces "Lorem Ipsum" clutter)*

If you prefer to start with a blank cursor instead of Photoshop automatically filling every new text box with "Lorem Ipsum" text, uncheck this option.

**Navigation:** `Edit > Preferences > Type > Uncheck "Fill new type layers..."`

- [x] **8. Check "Automatic detection of Bulleted and Numbered lists"**
*(Speeds up text formatting)*

Similar to modern word processors, this setting detects when you start a line with a dash or a number and automatically formats the paragraph as a list.

**Navigation:** `Edit > Preferences > Type > Check "Automatic detection of..."`

- [x] **9. Number of Recent Fonts to Display: 5**
*(Reduces Photoshop memory usage)*

Keeping a long list of recently used fonts "ready" in the menu consumes system resources. Lowering this to **5** helps streamline the font menu and helps reduce the overall Photoshop font cache load.

**Navigation:** `Edit > Preferences > Type > Set "Number of Recent Fonts to Display" to 5`

---

### Troubleshooting Font Lag
**Why is my text tool lagging so badly?**
If Photoshop is using too much memory while you use the Type tool, you may have a corrupt font. To speed things up, ensure **Type > Font Preview Size** is set to **None**. This stops Photoshop from rendering a visual preview of every single font, which is a major cause of performance drops.
