# DATA-ACQUISITION USING FTK IMAGER
This repository documents a digital forensic exercise focused on acquiring an image of a removable storage device using FTK Imager, a widely-used tool for digital evidence collection and analysis.

Project Overview

Title: Removable Media Acquisition with FTK Imager  

Author: Adenike Oluwabusola Oni  

Tool Used: [FTK Imager](https://accessdata.com/product-download/ftk-imager)

This project demonstrates:

- Acquiring a disk image from a removable drive

- Verifying image integrity

- Saving image metadata for documentation


Step-by-Step Procedure
1. Select Evidence Source

- Launch FTK Imager

- Go to `File` → `Add Evidence Item`

- Choose *hysical Drive

- Click Next and select the attached removable media

- Click Finish


2. Create Disk Image

- Go to `File` → `Create Disk Image`

- Select the same physical drive and click **Next**


3. Set Image Options

- Click **Add** to create a new image

- Select image type: `E01` (Expert Witness Format)

- Enter evidence item information (Case ID, Examiner name, Notes)

- Set image destination folder and file name

- Set image fragment size to `0`

- Set compression level to `6`

- Click Finish


4. Image Creation & Verification

- FTK Imager creates the disk image

- Verifies image hash to ensure integrity

- Generates metadata text file


Output Files
- `.E01` Forensic image file

- `.txt` Metadata report file (hashes, evidence details, etc.)

All files are created in a structured evidence folder for easy access and audit.


Skills & Tools Demonstrated
- Forensic image acquisition techniques

- Using FTK Imager for disk cloning

- Best practices in digital evidence handling

- Image hashing and verification


Disclaimer: 
This is an academic/educational project carried out in a controlled environment. No real user or criminal data was involved. For instructional use only.


For questions, suggestions, or collaborations:  
📧 [adenikeoluwabusolaoni@gmail.com]
