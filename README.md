
# NucTrack — Usability Test (R2)

Evaluation protocol for the NucTrack Fiji plugin.  
Please follow the steps below before filling out the feedback form.

---

# New features

- Batch Mode
  - You can now choose to batch process a folder with the files
- Tooltips (information when hovering mouse over the UI)

<img width="833" height="704" alt="interfaz" src="https://github.com/user-attachments/assets/d2a9c2ea-a487-493b-929e-49757670cce6" />

---

# What are we doing?

We are testing a plugin to calculate relative movement of an object moving inside another, this is a common case in biology with organelles and other cells where there is one container and things move inside of it, in this case mithocondria with nucleoids, the purpose of the plugin is to reduce the cognitive load of learning new tools that people working in biology might have to use for obtaining data for analysis.

For this test you will be following some instructions to achieve what was previously explained, try to pay attention to the interface, is it intuitive, difficult, or whatever else you may notice about it.

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
For example `sample_data/Mic10Ctrl/`
It contains folders with these files (among others):
- `mito.tif` - segmented reference object
- `nuc.tif` — tracked object raw image
- `segmito.mdf` — segmented mitochondria image stack
- `tracks.mdf` — MTrackJ tracking file

---

## Test Tasks

Please try to complete the following tasks on your own.  
Note anything that was confusing, unclear, or required guessing.

You can now choose 2 ways:

To batch process the whole folder:

1. Open Fiji and launch **Plugins → Tracking → NucTrack**
2. Check the tooltips! If you dont understand something they have useful information
3. In the plugin window, check batch mode box, and load the input root folder `Mic10KD_Ctrl` using the Browse button
4. Load the segmented object filename, in this case `segmito.tif` using its Browse button
5. Load the tracked object filename, in this case `tracks.mdf` using its Browse button
6. Set the output folder to a folder of your choice
7. Observe the preview panel — if you selected batch, there is no preview
8. Press **Process** and wait for processing to complete
9. Open the output folder and check that result files were generated

To process a single folder:

1. Open Fiji and launch **Plugins → Tracking → NucTrack**
2. Check the tooltips! If you dont understand something they have useful information
3. In the plugin window load the following files for a folder, for example `Mic10ctrl_0`
4. Load the reference object segmented file, in this case `segmito.tif` using its Browse button
5. Load the tracked object tracking file, in this case `tracks.mdf` using its Browse button
6. Set the output folder to a folder of your choice
7. Observe the preview panel — to see the preview of the loaded files
8. Press **Process** and wait for processing to complete
9. Open the output folder and check that result files were generated

---

## Feedback Form

After completing the tasks, please fill out the evaluation form:

👉 **[[Link to Google Form](https://forms.gle/CrytE5S3yNzRFVN36)]**

---
