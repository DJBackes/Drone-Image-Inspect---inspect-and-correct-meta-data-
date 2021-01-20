# DroneImage-MetaData-Manipulation

Authors:<br> 
[Dietmar Backes](https://wwwfr.uni.lu/recherche/fstm/doe/members/dietmar_backes) Engineering Department, Faculty of Sciences, Technologies and Medicine, University of Luxembourg<br>
[Frank Soboczenski](https://h21k.github.io/) School of Population Health and Life Sciences, King's College London, London, UK<br>

## Contributors
[![Contributors Display](https://badges.pufler.dev/contributors/puf17640/git-badges?size=50&padding=5&bots=true)](https://badges.pufler.dev)

## What is this about?
This code provides functions to read, query and manipulate drone image meta data in exif and xmp headers.

## Problem Scenario
![Alt text](DJI-Image1.png?raw=true "Optional Title")
The above image shows that in some cases the gimbals during the image collection get flipped. We are providing a solution for this problem here.




## Structure of the repository

Data folder:<br> 

+ `TimeAnalysis2_1.xlsx` (main data file)<br>
+ `UXData1.xlsx` (aux data file - mainly including qualitative answers)<br>
              
Jupyter Notebook: Analysis.ipynb<br>
Structure:<br>  
1. `Main Analysis` (distribution of the data, Wilcoxon significance tests, boxplots, scatterplots)<br>


Provides functions to read, query and manipulate drone image meta data in exif and xmp headers.
