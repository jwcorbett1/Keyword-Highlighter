# Keyword-Highlighter
Web-based text editor with syntax highlighting for on-the-go C programming.

This is a basic text editor implemented in HTML and Javascript with new/open/save functionality and syntax highlighting geared toward use for C programming.  The program is packaged into a single HTML file so it can be downloaded and run on any computer with an Internet connection and a basic web browser.

Syntax elements identified and highlighted by this program include:
* comments
* keywords
* literals (character, string, and numeric)
* preprocessor directives and macros (separate coloring for both)
* local and global variables (again, separate coloring for both)
* typedefs
* tag types (structures, unions, and enumerations)
* enumeration constants
* function names
* function parameters
* function pointers

Additionally, it implements identifier shadowing/masking; local variables hide global variables and are correctly colored as local variables.

The primary purpose of this project was to improve my understanding of regular expressions.  Rather than implementing a tokenizer/parser system, this program applies regular expressions extensively to identify language elements within the user's text.  It also works directly with raw HTML pulled directly from the main editable \<div\>, which provided some interesting challenges.  Completing this project was a very informative experience.
