
# NucTrack — Usability Test (R2)

Evaluation protocol for the NucTrack Fiji plugin.  
Please follow the steps below before filling out the feedback form.

---

# New features

- Batch Mode
  - You can now choose to batch process a folder with the files
- Tooltips (information when hovering mouse on UI)

---

## Prerequisites

- [Fiji](https://fiji.sc/) installed on your computer
- The plugin JAR file
- Sample data (in the `sample_data/` folder of this repo)

---

## Installation

1. Download `NucTrack-1.0.0.jar`
2. Copy it into your Fiji `plugins/` folder\
   Could be in (or any other location when downloading fiji): 
   - Windows: `C:\...\Fiji.app\plugins\`
   - Mac: `/Applications/Fiji.app/plugins/`
4. Restart Fiji
5. The plugin will appear under **Plugins → Tracking → NucTrack**

---

## Sample Data

Use the sample dataset located in `sample_data/folder/`.  
For example `sample_data/Mic10ctrl_10/`
It contains (among other files):
- `mito.tif` - segmented reference object
- `nuc.tif` — tracked object raw image
- `segmito.mdf` — segmented mitochondria image stack
- `tracks.mdf` — MTrackJ tracking file

---

## Test Tasks

Please try to complete the following tasks on your own.  
Note anything that was confusing, unclear, or required guessing.

1. Open Fiji and launch **Plugins → Tracking → NucTrack**
2. In the plugin window, load `segmito.tif` using the Browse button
3. Load `tracks.mdf` using its Browse button
4. Set the output folder to a folder of your choice
5. Observe the preview panel — verify the image loads correctly
6. Press **Process** and wait for processing to complete
7. Open the output folder and check that result files were generated

---

## Feedback Form

After completing the tasks, please fill out the evaluation form:

👉 **[[Link to Google Form](https://forms.gle/CrytE5S3yNzRFVN36)]**

---
