# SA_Assignment06

## Read through the assignment and generate your estimate for your estimation assignment


## PIMPL

Using the repo https://github.com/olekaspt/PIMPL_HW

Your goal is to make it so StableClass uses the PIMPL pattern so we can add new functionality (the newly added comments) without requiring recomiples.

Use https://github.com/olekaspt/SoftwareArchitectureCLassApplication AutomationAPI_Part.h (uses PIMPL) and NonPimplVersionOfPart.h_ (doesn't use PIMPL pattern) as a guide.

Your goal is make sure the external facing class (StableClass) doesn't use virtual or override methods, and doesn't have any private data members other than the PIMPL.

If you do this right, you only need to modify StableClass.h and StableClass.cpp


PDF Report:
WHat value does the PIMPL pattern provide.



## Document an API

Pick your favorite language from the following list. - Python, Java, C++, or C#

Generate a stub API to do following (image it works like excel)

1) API to obtain an Session object
3) API to represent an Workbook object
2) API to manipulate the Workbooks (open, close, save) off of Session
3) API to represent an Worksheet object
4) API to manipulate an Work sheet object (make active, delete, rename)

An Session can have mutliple work books, and each workbook contains 1 or more worksheets.

Document the API using the rules put forth in the slide deck.  

Generate the API reference using doxygen or javadoc (doxygen can handle C#, Python, and C++).  If you use Python use PEP 484 as a guide on how to docuemnt the signatures.


## Participation Rubric
PDF:
The usual rubric of your partners particpation.

## Deliverable \ Rubric

10% Readability of code and Report
45 % PIMPL
45 % Document an API

Submission
1) PDF with desired information specified above.
2) Zip of HTML pages of API
3) Zip of PIMPL implementation and header files for StableClass
