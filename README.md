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

Tip 3: 
Select a specific number of lines from a large text file in Notepad++

1.	Open Notepad++
2.	Open the desired text file
3.	To select lines from 123 to 34567:
- Place the cursor on line number 123
-	Go to Edit > Begin/End Select to mark the starting point
-	Press Ctrl + G, type in line number 34567, and press Enter to navigate to the desired end line
-	Go to Edit > Begin/End Select again to mark the ending point
  
That's it!!! 

If you want to copy the selected lines, simply press Ctrl + C
