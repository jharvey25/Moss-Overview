# Moss Overview
**[University of Nebraska-Lincoln](https://unl.edu)**  
**[College of Engineering](https://engineering.unl.edu/)**  
**[School of Computing](https://computing.unl.edu/)**  

This repository provides a brief outline of Stanford's Measure of Software Similarity (Moss) system 
as well as a rundown of how academic dishonesty is handled at the UNL School of Computing.

## Links
Repository is hosted at:
https://github.com/jharvey25/Moss-Overview

SoC academic integrity policy:
https://computing.unl.edu/academic-integrity-policy/

Moss documentation:
https://theory.stanford.edu/~aiken/moss/

## What is Moss?
From the documentation:  

_"Moss (for a Measure Of Software Similarity) is an automatic system for determining 
the similarity of programs. To date, the main application of Moss has been in detecting plagiarism in 
programming classes."_  

### How it works
The Moss server mostly acts as a black box. Instructors submit the files they wish to compare using a script and 
the system does the rest. The resulting HTML pages can then be viewed to decide whether a match instance 
was a result of cheating. It does **not** determine whether plaigarism actually occurred, that is up to the 
instructors to conclude.  

Moss uses `document fingerprinting` and selects from those fingerprints with an algorithm called `winnowing` 
to gauge file similarity. Then we get to see the resulting matches as highlighted HTML pages. 
Feel free to view the [sigmod03 PDF](https://github.com/jharvey25/Moss-Overview/blob/main/documents/sigmod03.pdf) 
for details on the algorithm. It's a pretty interesting read!  

### Features
- **Whitespace insensitivity**
  - Differences in whitespace (indentation/between blocks/etc.) and variable names are ignored.
- **Noise suppression**
  - Potential matches must be long enough to be considered significant.
- **Position independence**
  - Blocks can match regardless of position in the source files.

## What counts as cheating?  
TODO

## Grading/Code review process

### General timeline
TODO

### How cheating is caught
TODO

## Getting flagged for cheating
TODO

## Discussion with instructors 

### General structure
TODO

### Appeals process
TODO

## FAQ 
TODO
