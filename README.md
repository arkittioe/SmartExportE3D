# SmartExportE3D - Automated Attribute Export for AVEVA E3D

## Overview
This repository contains scripts for automating the export of attributes from AVEVA E3D. The scripts are written in PML and are designed to extract tube attributes and other component data efficiently.

## Features
- Automatic extraction of tube attributes and other piping components.
- Customizable data formatting for easy integration with external software.
- Structured output in a readable and processable format.

## Prerequisites
- **AVEVA E3D** installed and properly configured.
- **Administrator access** to modify and run PML scripts.
- Required directories available for exporting data.

## Installation
1. Clone this repository or download the necessary files.
   ```bash
   git clone https://github.com/arkittioe/SmartExportE3D.git
   ```
2. Copy the PML scripts to the AVEVA E3D script directory.
3. Ensure that the export directory paths in the scripts match your system settings.

## Files
- `ATT.txt`: Extracts attributes of various components in AVEVA E3D.
- `TUATT.txt`: Focuses on tube attributes and organizes them per branch.
- `P01.bat`: Batch file to automate script execution.
- `P01.mac`: Macro file to facilitate integration.
- `SmartExportE3D.hta`: HTML Application for user-friendly interaction.

## Usage
1. Initial Setup:

Before running the scripts, set your site names in the hierarchy structure inside ATT.txt and TUATT.txt.
Apply the same settings in macro files (P01.mac and other related files).
In all files, adjust the directory paths according to your file structure.



2. Configure Username and Password:

You must enter your actual username and password in the relevant files.
The username and password included in the scripts are placeholders and not functional—replace them with your real credentials.



3. Run the Script:

Execute the batch file (P01.bat).
The extracted data will be stored in the specified directory.


## Contact
For any issues or contributions, reach out via email: hossein.pa.ad@gmail.com.

