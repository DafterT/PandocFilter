This filter for pandoc, written according to an assignment at the university.
___
### What it does:
1. Finds the same headings in the document and gives the user a warning about it.
2. Replaces all headings at level 3 and below with uppercase headings.
3. Finds the word "bold" in the text and makes it bold
___
### How to use:
```
pandoc -s input.md --filter filter.py -o output.md
```
___
Examples of work can be seen in the repository