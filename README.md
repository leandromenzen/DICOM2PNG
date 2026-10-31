# DICOM2PNG

**DICOM to PNG converter directly in your browser.**

DICOM2PNG is a simple, free tool that allows you to convert medical examination files in DICOM format into grayscale PNG images, including batch processing, without installing any software or uploading files to external servers.

## 💡 How did this project come about?

The idea came from a rather personal experience.
Recently, I had to undergo an MRI scan of my knee. Being naturally curious and interested in understanding how things work, even before receiving the medical report, I decided to download the files made available through the MRI machine's system and try opening the images on my computer.
That's when I ran into a small obstacle: the files were in **DICOM (Digital Imaging and Communications in Medicine)** format, a standard used in the medical field to store and transmit medical images and examination data. Unlike conventional formats such as JPG and PNG, these files cannot be easily opened with just any image viewer.
While researching alternatives, I realized that many online converters either limit the number of files you can convert or charge for batch processing.
So, I decided to develop my own solution.

That's how **DICOM2PNG** was born. An HTML file that allows you to select individual DICOM files or an entire folder containing multiple images, convert them directly in your browser, and download everything neatly organized into a single `.zip` file, with all images in PNG format.

## 🚀 How to use

1. Open the `DICOM2PNG.html` file in your browser.
2. Select the DICOM files or the folder containing the images.
3. Wait for the files to be processed and converted.
4. Download the `.zip` file containing all the converted PNG images.

No additional software installation is required.

## ✨ Features

- Conversion of DICOM files to PNG.
- Batch processing of multiple files.
- Individual file selection or entire folder selection.
- Conversion of images to grayscale.
- Download of all converted images in a single ZIP file.
- Runs directly in your browser.
- No registration or installation required.

## 🔒 Privacy

**All processing takes place locally in your browser.** The selected DICOM files are never uploaded to external servers, are not stored in the cloud, and remain on your own computer throughout the conversion process.

This is especially important when dealing with medical images, which may contain personal and sensitive information.

## &#x20;

## ⚠️ Important notes

DICOM2PNG was developed to make medical images easier to view and convert.

The generated PNG files are intended for viewing purposes and do not replace the original DICOM files, which may contain metadata and technical information that are important for medical interpretation.

**This tool does not provide diagnoses, interpret medical examinations, or replace the evaluation of a healthcare professional.**

## 👨‍💻 Development

A project developed by **Leandro Menzen**, inspired by a personal need that eventually turned into a tool that may be useful to others.

If you've also needed to open files from an MRI, CT scan, or another medical examination provided in DICOM format, I hope this tool makes the process a little easier.

**Curiosity, research, and a little bit of code can turn an everyday problem into a solution worth sharing.**

Fix the incomplete section headingAdd a clearer opening call to action
