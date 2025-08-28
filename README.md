# Vehicle Number Plate Detection System

This project implements a **Vehicle Number Plate Detection System** using MATLAB.  
It detects and recognizes alphanumeric characters from vehicle number plates.

---

## Features
- Detects number plates from vehicle images
- Recognizes alphanumeric characters using template matching
- Includes a dataset of templates (A–Z, 0–9)
- MATLAB-based implementation

---

## Project Structure
Vehicle_Number_Plate_Detection/ 
│── Alpha/    # Template images for characters (A–Z, 0–9) 
│── Number Plate Images/    # Sample images for testing 
│── Letter_detection.m    # Character recognition code 
│── Plate_detection.m    # Number plate detection code 
│── template_creation.m    # Template generation code 
│── NewTemplates.mat    # Stored templates

---

## Requirements
- MATLAB R2018a or later
- Image Processing Toolbox

---

## Usage
1. Open MATLAB.
2. Run `template_creation.m` to generate templates (only once).
3. Run `Plate_detection.m` to detect the plate from input images.
4. Run `Letter_detection.m` to recognize characters.

---

## Sample
- Input: Car image with number plate  
- Output: Detected plate + Recognized characters  

---

## Author

Developed by Vishnu Prasad A, BE. ECE

For learning, research, and assistive technology development.

---
