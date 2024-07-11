Tip 1: 
Remove empty lines using reqular expressions in notepad++ on a windows machine
- Open Notepad++ and open your file
- Press Ctrl+H to open the 'Replace' popup
- In the 'Find what' field, enter the regular expression for matching empty lines:     ^\s*\r?\n
- Leave the 'Replace with' field empty
- Check the boxes 'Match case' and 'Wrap around' options
- Search Mode set to 'Regular expression'
- Click 'Replace All

Tip 2:
Remove duplicate lines using Notepad++ (Manual method)
- Open the text file in notepad++
- Step1: Go to - Edit >> Line Operatios >> Sort Lines Lexicographically Ascending
- Step2: Go to - Edit >> Line Operatios >> Remove Consecutive Duplicate Lines
