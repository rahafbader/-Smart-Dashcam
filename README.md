# Smart Dashcam - Accident Analysis and Fault Assignment


## Table of Contents:

- Project Title

- Description

- Data Collect

- Getting Started

- Prerequisites

- Installation

- Usage

- Running the Code

- Generating Reports

- Dependencies

- Libraries

- Authors


## Project Title
Smart Dashcam - Accident Analysis and Fault Assignment


## Description

This project, Smart Dashcam, automates the process of analyzing dashcam footage of car accidents and assigns the percentage of fault to each driver involved. It leverages AI-based models to detect accidents from video feeds, generate detailed reports in PDF format, and outline the percentage of responsibility for each driver based on the analyzed footage. The project is designed to run on Google Colab with GPU support for faster execution.

## Data collect
This dataset includes 500 dashcam videos of collisions (head-on, rear, and side) along with 1,000 manually labeled accident images. It also contains traffic laws in PDF format for analysis. The data is suitable for training accident detection and analysis models.

-- [Accident Detection in Dashcam POV Dataset(Manual gathering & Labeling)]()
-- [Traffic laws as pdf](https://drive.google.com/file/d/1aKrGPVZ2W32BfBGhQtVzk9HyDI8NS8VX/view?usp=drive_link)
-- [Rear_collision](https://drive.google.com/drive/folders/1XAzc9qJ9c0peERNgByfD3-hLLIy9eFu8?usp=drive_link)

 ### Key Features:

-Automated accident detection from dashcam videos.

-Calculation of percentage fault for each driver involved.

-PDF generation with accident reports, including decision details and responsibility percentages.


## Getting Started

## Prerequisites

### Before running the code, ensure you have the following:

A Google account for accessing Google Colab.

Access to Google Colab with GPU support (recommended for faster execution).

All files from this repository.

A dashcam video file. You can either use the sample video provided in this repository or upload your own dashcam footage.

## Installation

### Clone this repository using the following command:
```
!git clone https://github.com/HamadJu1/Capstone.git
```
Open Google Colab and upload the necessary files from this repository.


## Usage

Running the Code

After cloning the repository and opening the notebook in Google Colab, upload your dashcam video or use the sample video included in the repository.

Run the code to analyze the dashcam footage.

The code will process the video, detect any accidents, and assign a percentage of fault to each driver involved in the accident.


## Generating Reports

### After the analysis is complete, a PDF report will be generated with the following details:

A frame from the accident video.

Detailed analysis of the accident, including fault percentages for each driver.

The report will be available for download from the Colab environment once the process is complete.

![PDF_report](https://github.com/HamadJu1/Smart-Dashcam/blob/c8d03bd9d967d5995ae241cef35e8a175e79d8b2/Report_Picture.png)


## Dependencies
```
!pip install -r requirements.txt
```

## Deployment 

You can try the deployment space at 

https://huggingface.co/spaces/hamad121/Accident_percent_of_erorr


## Project Members : 

- Project Member: *Hamad Aljumah*
  - Email: Hamad_aljumah@hotmail.com


- Project Member : *Alanoud Basulaiman*
  - Email : alanuodsultan@gmail.com


- Project Member: *Alrasheed Khalid Alrasheed* 
  - Email : r2sheedkhaled@gmail.com


- Project Member : *Rahaf Alshalahi*
  - Email :rahaf.b.alshalahi@gmail.com


- Project Member : *Abdulaziz Sulaiman Alosayl*
  - Email :abdulaziz.alosayl@gmail.com
