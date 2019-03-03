# Dissertation

What files are included:

Data.py is the primary file for cleaning the data, it uses two helper files:
  HelperFrames.py: Creates three objects, a DataFrame describing all imported variables (what file they are sourced from, if they should be normalised etc.) called "variables", a DataFrame describing the source files used to import data (what the location of the file is expected to be, if the file contains duplicate entried for cohort members, etc.) called "files", and a dictionary containing the mappings used for non-numeric variables.
  
  TimeUseDiaries.py: The procedure used for turning the time use diaries into a usable format is different and more memory intensive than other variables, it is conducted in this file. When the time use diaries have been cleaned they are stored in a .pkl file to save time in the future, this .pkl file is not included in this folder and must be initially generated the first time the 
