# Finance_Tracker
## Author:
Roctek
## Date:
7/5/2019
## Description:
This is an excel spreadsheet designed to help keep track of daily spending.
  
## Features:
1. User defined categories (tags) of spending
2. Optional calculation of total or remaining untagged spending per entry
3. Calculation of daily and total spending of each category
4. Pretty awesome conditional formatting, so you don't have to (but feel free to change colors and stuff)

## Usage:
- enter data in the rows of the upper table (entries)
- totals appear in the bottom table
- Put a number in the TOTAL column of the entry if you would like to compute the remaining value not in any categories (OTHER)
- Put a number in the OTHER column if you would like the TOTAL to be a sum of all categories (including other)
- add more tags (categories) or change the existing ones to match your needs
- You should delete the four example entries
- dates are of the format dd/mm/yyyy (dd/mm will likely work the same) 

## Entries:
- Entries represent rows in the upper table
- Entries with no date will assume the most recent date entered
- Entries in red text represent unused or incorrect entries (incorrect entries are still included in totals)
- incorrect entries will likely have an incorrect OTHER value. this is because you have not replaced the formula in either the OTHER or the TOTAL column with a number

## Inserting Rows (entries):
1. select the entire row of an unused entry by hitting the row number on the far left
    - note: you can click and drag to select more than one to insert multiple at a time
2. right click and select insert
3. the red 0's may be missing from the new columns. simply select one of these cells and click and drag the green square in the bottom right corner so that you have moved the selected region over cells needing or already containing red 0's and release your click. Do this for both the TOTAL and OTHER COLUMN

## Deleting Rows (entries):
1. click and drag to select the row numbers on the far left of the screen that represent the entries you would like to remove
2. right click and select Delete
3. try to always leave at least one unused entry for copying
  
## Inserting Columns (categories/tags):
1. only columns in the yellow region should be added
2. select an entire category column by clicking the Letter at the top of it
    - note: this works better for columns after the first yellow and including OTHER
3. right click and choose insert
4. enter a name for your category in the first row
5. drag the formula from an adjacent column by clicking a cell and dragging the green square to the newly created empty column for the following:
    - the bottom row of the first table containing a repeat of the category name
    - the top three rows of the bottom table
    - the row directly below "Address Ranges" (should have a bunch of $'s, letters, and numbers)
  
## Removing Columns (categories/tags):
  1. only columns in yellow should be deleted
  2. select the entire column(s) you wish to delete by selecting the letter at the top of it
  3. right click and select delete
  
  
