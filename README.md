# README
> ZEBRA: Similarity Detector

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
Add more general information about project. What the purpose of the project is? Motivation?

## Screenshots
![Example screenshot](./img/screenshot.png)

## Technologies
* Tech 1 - version 1.0
* Tech 2 - version 2.0
* Tech 3 - version 3.0

## Setup
Describe how to install / setup your local environement / add link to demo version.

## Code Examples
Show examples of usage:
`put-your-code-here`

## Features
List of features ready and TODOs for future development
* Awesome feature 1
* Awesome feature 2
* Awesome feature 3

To-do list:
* Wow improvement to be done 1
* Wow improvement to be done 2

## Status
Project is: _in progress_, _finished_, _no longer continue_ and why?

## Inspiration
Add here credits. Project inspired by..., based on...

## Contact
Created by [@flynerdpl](https://www.flynerd.pl/) - feel free to contact me!







# README 

ZEBRA: Similarity Detector

## How to Run
<img src="demo.gif" alt="demo of running software">
1. Download the executable and save if in the folder where the files to compare and located.
2. Open terminal and go to the directory where the executable and files to compare are located.
3. Run ```dir /b > filenames.txt``` in terminal. (The name "filenames" is optional. The file can be named something else.)
4. Optional: For testing student submissions, if you want the program output to have the student's names listed as FIRST LAST, instead of the Canvas naming system LASTFIRST, then copy the names of all the students and paste them into a file with each line being a single name.
Ex:
Charles Babbage
James Gosling
Grace Hopper
Ada Lovelace
Alan Turing
5. Run ```ZEBRA filenames.txt```. If using a list of student names, run ```ZEBRA filenames.txt studentnames.txt```. (Use the names of the textfiles within the folder, not the names given here, unless the textfiles are named filenames and studentnames, respectivly.)
6. Choose an option in the menu that matches the language used within the files for better results. If none of the options match, choose the "None Listed" option.

## Understanding Results
<img src="Results_Screenshot.png" alt="A screenshot of the results">
[ ]  There are three colors for results: green, yellow, and red. 
*  Green: Low to no similarity. This coloring is used to signify any submissions that are under 10% above the average similarity. Any similarities are most likely due to assignment requirments. 
*  Yellow: Slightly higher than normal similarity. This coloring is used to signify any submissions that are between green and red standards. 
*  Red: High similarity. This coloring is used to signify any submissions that are over 30% above the average similarity. These submissions may have identical code.

## Additional Notes
If Canvas anonymous grading is used, the file names will have numbers instead of names. The program output will output these numbers instead of the student's names.
