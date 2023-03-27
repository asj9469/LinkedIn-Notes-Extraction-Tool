# Linked In Learning Annotation Extraction Tool 
<img align="right" src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue">

## Brief Description:
A python-based tool that extracts and organizes annotations from [Linked In Learning (LIL)](https://www.linkedin.com/learning) notebooks in a more readable format (.txt, .md, .docx).

## Background:
- The exported notebook from LIL includes formatting and details such as time stamps of the location of which the note was taken.
- Although the included details may be helpful when referring back to the video, it adds unnecessary challenges to students who try to study with the annotations only and/or merge them with other study materials

## What Does This Tool Do?
- Takes in the original .txt file downloaded directly from [Linked In Learning](https://www.linkedin.com/learning) as an input
- Provides user the option to pick from different output formats (.txt, .md, .docx)
- "Cleans up" the original text file into a more readable and organized structure
- Filers out necessary information (course title, chapter, video title, and annotations) and adds to the new output file
- Creates a new file if user chooses to create a file that does not previously exist
- Appends to the file if user chooses a path with an existing file as output file path

