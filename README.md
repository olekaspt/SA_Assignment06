# SA_Assignment06

## Read through the entire assignment and generate your estimate for your estimation assignment.  It is important to read through all steps first to understand the end state desired.  

This assignment is to practice two points.  How to evolve an API so that you evolve it in a controlled manner so you don't break down stream clients.  And the second point is how to document an API.

You are going to be making three different version of an API.  
1) 1.0 will be your base API
2) 1.5 which represent an extension that is not a breaking change to your API, but also deprecate an API
3) 2.0 In which you remove the deprecated API

It is highly suggested to generate your "base" API.  Document the API per that section. And then make a copy for the 1.5, and 2.0 versions.

## Generate "base" API
Pick your favorite language from the following list. - Python, Java, C++, or C#

Generate an interesting API, that does CRUD operations (Create, Update, Update, and Delete).  An example API of the complexity I'm looking for is below.

Sample API - imagine it works like excel
1) API to obtain an Session object
3) API to represent an Workbook object
2) API to manipulate the Workbooks (open, close, save, save as) off of Session
3) API to represent an Worksheet object
4) API to manipulate an Work sheet objects (make active, delete, rename)
5) API to edit a cell in a Worksheet object
6) Your methods should take in inputs if applicable.
7) If applicable describe what an error will occur.  I.e. file not found, or bad path?
An Session can have mutliple work books, and each workbook contains 1 or more worksheets.

## Document an API

Document the API using the rules put forth in the slide deck.  

1) Use Active Voice (not Passive Voice)
1) Use Present Tense
1) Use Second Person to Refer to the Reader
1) Be Polite; Don’t Be Bossy
1) Be Specific; Don’t Be Vague
1) Avoid Complex English or Figures of Speech
1) Summary and remarks sections

Generate the API reference using doxygen or javadoc (doxygen can handle C#, Python, and C++).  If you use Python use PEP 484 as a guide on how to document the signatures.

## API Evolution

Using the rules listed previously.  Make a 1.5 and 2.0 API.  And then generate the API refs.

For you deliverable, you will want to submit three folders (1.0, 1.5, 2.0).

PDF Report:  Describe what you enhanced and deprecated for 1.5.  And for the 2.0 what did you remove from the API, and why is this acceptable?

## Participation Rubric
PDF:
The usual rubric of your partners particpation.

## Deliverable \ Rubric

10% Readability of code and Report
45 % API evolution
45 % Document an API

Submission
1) PDF with desired information specified above.
2) Zip of HTML pages of API for 3 versions

