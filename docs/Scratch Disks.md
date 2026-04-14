## Scratch Disk Preferences: Fixing "Scratch Disk Full" Errors

When Photoshop runs out of RAM (Random Access Memory) to perform an operation, it uses your hard drive as temporary "virtual memory." This temporary storage area is called a **Scratch Disk**. If your drive is too slow or too full, you will experience extreme lagging or the dreaded "Photoshop scratch disk are full" error.

- [x] Use SSD or NVMe drives for primary scratch space.
- [x] Maintain at least 50GB to 100GB of free space.
- [x] Set your fastest drive as the primary disk.

##### Managing Your Scratch Disks

Photoshop allows you to nominate multiple drives as scratch space. If you have more than one internal drive, you can tell Photoshop which one to use first.

**1. Use Your Fastest Drive (SSD vs. HDD)**
Always set your fastest drive (NVMe or SSD) as your primary scratch disk. Using an old-fashioned mechanical Hard Drive (HDD) as a scratch disk will make Photoshop run incredibly slow. If you have a secondary SSD that doesn't host your OS, it is the perfect candidate for a primary scratch disk.

**2. The "Dedicated Drive" Strategy**
For maximum performance, professional retouchers often install a dedicated SSD used *only* for Photoshop scratch space. By not running your OS or applications from this drive, you eliminate "data traffic jams," allowing Photoshop to read and write temporary files with zero interference.

**3. Set a Failsafe (Secondary Disks)**
If you work with massive files, panoramas, or hundreds of layers, a single drive might fill up. Check the box for a secondary drive in the list to act as a failsafe. This prevents Photoshop from crashing mid-save if your primary drive hits its limit.

**Navigation:** `Edit > Preferences > Scratch Disks`

---

### FAQ: How to fix "Photoshop Scratch Disk is Full"

**Why is my scratch disk full when I still have space?**
Photoshop requires "contiguous" free space. We recommend keeping at least **15-20% of your drive empty**. If your drive has 10GB left, but you are working on a large file with high history states, Photoshop may reject the drive.

**Can I clear the Photoshop cache to free up scratch space?**
Yes. If you are stuck and can't save, go to **Edit > Purge > All**. This clears your undo history and clipboard cache, instantly shrinking the size of the temporary scratch file on your hard drive.

**How often should I clear the scratch disk?**
Photoshop is supposed to delete its temporary `.tmp` files automatically when you close the program. However, if Photoshop crashes, these files stay behind, hogging space. Check your drive's root folder for large files starting with "Photoshop Temp" and delete them if Photoshop is currently closed.
