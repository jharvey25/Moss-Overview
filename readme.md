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
  - Differences in whitespace (indentation/between blocks/etc.) and identifier names are ignored.
- **Noise suppression**
  - Potential matches must be long enough to be considered significant.
- **Position independence**
  - Blocks can match regardless of position in the source files.

## What counts as cheating?  
In the School of Computing at UNL, academic dishonesty can take many forms. A list of examples can be found on the policy [webpage](https://computing.unl.edu/academic-integrity-policy/). Some of those examples are listed below, but it's up to you to decide whether they sound like dishonesty according to our policy. You can check your answer by clicking each statement.  

<details>
  <summary>Talking with peers about what programming concepts you should keep in mind for the assignment</summary>  
  
    Acting honestly! ^_^

    Hashing things out at a high level is often encouraged in comp sci courses.
    Note that "high level" just means "keep things general".

</details>

<details>
  <summary>Posting your solutions online or showing them to peers before submissions close</summary> 

    Acting dishonestly... >_<

    There’s a fine line between helping someone debug and helping them rewrite a whole block.  
    When in doubt, have them reach out to a TA to get help.

</details>

<details>
  <summary>Viewing code from a video/forum and writing the same block into your own solution</summary> 

    Acting dishonestly... >_<

    Every year, somebody will decide that they’ve beaten the system by manually typing some code 
    exactly instead of hitting copy/paste. 
    Avoiding ⌘+c ≠ avoiding copying. It's not a loophole, people!
  
</details>

<details>
  <summary>Meeting an instructor or TA in office hours to figure out how to approach a problem</summary> 

    Acting honestly! ^_^

    This is usually your safest bet when it comes to getting help! They know exactly what kind of 
    solution you should be working toward and can provide tips that won't get you in trouble.
  
</details>

<details>
  <summary>Taking code and renaming identifiers and/or shuffling the order of blocks</summary> 

    Acting dishonestly... >_<

    Seems like a pretty straightforward one, this is an example of deliberately trying to "trick" graders.
    If you feel the need to do this with your file, you're likely already about to get caught.
  
</details>

<details>
  <summary>Working on the same source file with a peer for a partner assignment</summary> 

    Acting honestly! ^_^

    When instructors explicitly allow working together for an assignment, you'll know it.
    You should assume no collaboration on coding assignments otherwise.
  
</details>

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
