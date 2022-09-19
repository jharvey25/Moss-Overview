# Moss Overview
**[University of Nebraska-Lincoln](https://unl.edu)**  
**[College of Engineering](https://engineering.unl.edu/)**  
**[School of Computing](https://computing.unl.edu/)**  

This repository provides a brief outline of Stanford's Measure Of Software Similarity (Moss) system 
as well as a rundown of how academic dishonesty is handled at the UNL School of Computing (SoC). The content found here can be originally found on the webpages linked in the section below.  

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
The Moss server acts as a black box. Instructors submit the files they wish to compare using a script and 
the system does the rest. The resulting HTML pages can then be viewed to decide whether a match instance 
was a result of cheating. It does **not** determine whether plaigarism actually occurred, that is up to the 
instructors to conclude.  

Moss uses `document fingerprinting` and selects from those fingerprints with an algorithm called `winnowing` 
to gauge file similarity. The resulting matches are then reported via HTML pages. 
Feel free to view the [sigmod03 PDF](https://github.com/jharvey25/Moss-Overview/blob/main/documents/sigmod03.pdf) 
for details on the algorithm. It's a pretty interesting read!  

### Features
- Whitespace insensitivity
  - Differences in whitespace (indentation/between blocks/etc.) and identifier names are ignored.
- Noise suppression
  - Potential matches must be long enough to be considered significant.
- Position independence
  - Blocks can match regardless of position in the source files.

## What counts as cheating?  
In the School of Computing at UNL, academic dishonesty can take many forms. A list of examples can be found on the policy [webpage](https://computing.unl.edu/academic-integrity-policy/). Some of those examples are listed below, but it's up to you to decide whether each sounds like dishonesty according to our policy. You can check your answers by clicking each statement.  

<details>
  <summary>Talking with peers about what class concepts you should use for the assignment</summary>  
  
    Acting honestly! ^_^

    Hashing things out at a high level is often encouraged in comp sci courses.
    Note that "high level" just means "keep it general".

</details>

<details>
  <summary>Posting your solutions online or showing them to peers before submissions close</summary> 

    Acting dishonestly... >_<

    There’s a big difference between helping someone debug and helping them rewrite a whole block.  
    When in doubt, have them reach out to a TA to get help.

</details>

<details>
  <summary>Viewing code from a video/forum and writing the same block in your own solution</summary> 

    Acting dishonestly... >_<

    Every year, somebody will decide they’ve beaten the system by manually typing the copied code  
    instead of using copy/paste shortcuts.
    Avoiding cmd + c ≠ avoiding copying. It's not a loophole, people!
  
</details>

<details>
  <summary>Meeting an instructor or TA in office hours to talk about out how to approach a problem</summary> 

    Acting honestly! ^_^

    This is usually your safest bet when it comes to getting help! They know exactly what kind of 
    solution you should be working toward and can provide tips that won't get you in trouble.
  
</details>

<details>
  <summary>Taking code and renaming identifiers or shuffling the order of blocks</summary> 

    Acting dishonestly... >_<

    Seems like a pretty straightforward one, this is an example of deliberately trying to "trick" graders.
    If you feel the need to do this with your file, you're likely already about to get caught.
  
</details>

<details>
  <summary>Working with someone on the same source file for a partner assignment</summary> 

    Acting honestly! ^_^

    When instructors explicitly allow working together for an assignment, they'll make it clear.
    By default, you can safely assume no direct collaboration is allowed on coding assignments.
  
</details>

## Grading/Code review process

### Grading outline
For CSCE 155A, assignment grading is done by Learning Assistants (LA's) and managed by Course Leaders (CL's). A general layout of the grading process can be found below:  

- Grading is assigned to LA's after the assignment deadline has passed.
  - Late policy is `-20% per day`, tracked by Canvas.
  - Scores are hidden during this time.
- Student scores are posted by CL's after grading is completed.
- Any student with questions about their received score has up to `7 calendar days` after grades are posted to discuss with their respective grader.
  - The grader of an assignment can be found in the submission comments on Canvas.
  - After this period, scores are treated as finalized and future requests by students to revisit their score may be denied.

### How cheating is caught
During grading, LA's will report any suspicions to the CL's. Anything missed by the graders will often be picked up by Moss. Regardless of how a potential match was identified, the instructors and CL's will review it and discuss whether the source files show enough evidence to flag the students for violating the academic integrity policy.  

## Getting flagged for cheating
If it is decided that a potential match is an instance of cheating, every student involved will be flagged as being in violation of the academic integrity policy. Each student will receive a sanction and a submission comment on Canvas explaining the sanction with deadlines for next steps.  

### Discussion with instructors 
Any student flagged for cheating has the opportunity to meet with instructors to discuss the situation. If they know they didn't cheat, this is the time for them to clear things up and remove the sanction. If a student does not reach out by the deadline given, it is assumed they did cheat and the sanction stands.  

Note that being flagged for a violation is **not** to be taken lightly. Before moving forward with even flagging a student's submission, it is reviewed by multiple members of the instructor team and discussed at length. This is not something done on a whim.  

### Consequences
A complete explanation of possible consequences for policy violations can be found on the policy [webpage](https://computing.unl.edu/academic-integrity-policy/). In general, the SoC uses a three-strike system for students as outlined below:  

1. For a first offense, they will receive no credit for the assignment.
   1. The sanction can increase straight to a failing grade in the class if the violation was bad enough.
2. For a second offense, they will receive a failing grade in the class and will not be permitted to drop the class.
   1. F stays on transcript.
3. For a third offense, they will be expelled from their computing major or minor and will be barred from enrolling in future SoC courses.

All offenses will be reported to the Office of Student Conduct, regardless of the sanction imposed.  

### Appeals process
In the case that a student believes they are not guilty of academic dishonesty or feels the sanction was worse than was called for, the Chair of the School of Computing can be contacted. Once the student does this, an appropriate committee will be assigned to review the case and provide a recommendation to the instructors. The instructors can then choose whether to alter the sanction in light of the committee's decision.  

## FAQ 
**Q:** thought-provoking question  
**A:** thorough-yet-concise answer (you get how this works)  