## Transparency & Gamut Preferences: Customizing Visual Guides

These settings control how Photoshop displays "empty" pixels (transparency) and how it warns you about colors that your printer cannot handle (out-of-gamut colors). Proper configuration here prevents eye strain and ensures color accuracy for print.

- [x] Grid Size: Medium (Standard)
- [x] Grid Colors: Light (Default)
- [x] Gamut Warning Color: Gray (Neutral)
- [x] Gamut Warning Opacity: 100%

##### Under the Transparency Settings Section

- [x] **1. Grid Size**
*(Customizes the transparency checkerboard size)*

The checkerboard pattern represents areas of your canvas that contain no data. 
* **None:** Removes the grid entirely (transparent areas will look solid white).
* **Small / Medium / Large:** Adjusts the size of the squares. **Medium** is the standard, but **Small** is often preferred by web and UI designers working with tiny assets.

**Navigation:** `Edit > Preferences > Transparency & Gamut > Grid Size`

- [x] **2. Grid Colors**
*(Improves contrast against your artwork)*

If you are working on a very light or very dark project, the default gray grid can be hard to see. 
* **Light / Medium / Dark:** Changes the intensity of the gray.
* **Custom (Colors):** You can click the color swatches to choose a custom color (like light blue or pink). This is helpful if your artwork contains a lot of gray, making it difficult to tell where the transparency begins.

**Navigation:** `Edit > Preferences > Transparency & Gamut > Grid Colors`

##### Under the Gamut Warning Section

- [x] **3. Color and Opacity**
*(Visual alerts for non-printable colors)*

What is a Gamut Warning in Photoshop? When you are working in RGB (web) but intend to print in CMYK, some bright colors (like neon greens or deep blues) simply cannot be reproduced by ink. 
* **Color:** When you turn on `View > Gamut Warning`, Photoshop will cover those "illegal" colors with this specific highlight. **Gray** is the default, but many pros change this to a bright, obnoxious color like **Neon Green** or **Bright Red** so they don't miss any out-of-gamut areas.
* **Opacity:** Determines how solid that warning color appears. 100% is recommended so the warning is unmistakable.

**Navigation:** `Edit > Preferences > Transparency & Gamut > Gamut Warning`

---

### Pro Tip: When to change these settings?
If you are doing a lot of "Cut out" work or removing backgrounds from white objects, the default **Light** grid can be deceptive. Change your **Grid Colors** to **Dark** or a custom color temporarily to ensure you haven't left any "stray pixels" or semi-transparent edges around your subject.
