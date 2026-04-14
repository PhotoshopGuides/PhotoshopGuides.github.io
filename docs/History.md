## History Log Preferences: Tracking Your Editing Steps

The History Log is different from the "History States" used for undoing mistakes. Instead of a visual list of undos, the History Log creates a text-based record of every action you take in Photoshop. While useful for legal evidence, client billing, or educational tutorials, it can add unnecessary metadata bloat to your files if left enabled.

- [ ] History Log (Uncheck for most users)

##### Under the History Log Section

- [ ] **1. Uncheck "History Log"**
*(Reduces metadata bloat and protects privacy)*

When checked, Photoshop starts recording every command you perform. This record is then saved either into the image file itself (Metadata) or as an external text file. For 99% of graphic designers and photographers, this is not necessary and only serves to increase the file size of your PSDs. 

**Navigation:** `Edit > Preferences > History > Uncheck "History Log"`

##### Log Configuration Options (If Enabled)

If you are a professional who needs to provide an audit trail for a client or a court case, you can configure the log as follows:

**A. Save Log Items To:**
* **Metadata:** Saves the text log inside the image file. *Warning: This makes your final image files larger and allows anyone who receives the file to see exactly how you edited it.*
* **Text File:** Saves the log to a simple `.txt` file on your hard drive. This is the recommended "clean" way to keep records without affecting the image file itself.
* **Both:** Saves the log in both locations.

**B. Edit Log Items:**
* **Sessions Only:** Only records when you open and close the file.
* **Concise:** Records a brief summary of each tool used (e.g., "Used Brush Tool").
* **Detailed:** Records every single change, including exact coordinates, opacity values, and filter settings. This produces a massive amount of data.

---

### FAQ: History Log vs. Performance History

**Does the History Log help me undo more mistakes?**
No. The History Log is simply a text diary of your work. To increase the number of times you can press "Undo," you must go to **Edit > Preferences > Performance** and increase your **History States**.

**Why are my Photoshop files getting too large?**
If your PSD files seem unusually heavy even with a few layers, check if the History Log is set to **Metadata**. Over months of editing, a "Detailed" metadata log can add several megabytes of hidden text data to every single file you save. Unchecking the History Log will prevent this bloat on all future files.
