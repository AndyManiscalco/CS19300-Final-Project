# CS19300-Final-Project

## Workout and Study Tracker

A simple java command tool to log workout and study hours

## MVP

1) Log the entry (type, duration, date)
2) Short note describing what was done
3) Entries are saved and can be viewed
4) Weekly stats report
5) Input sanitization (no negatives or invalid inputs)

## Future Plans

1) Editing/deleting past entries
2) Weekly goals with a progress bar/percentage
3) More categories maybe stuff thats notso positive so I canrealize how much time I waste
4) Past stats on a weekly/monthly basis

## Project Structure

src/ Java code
tests/ test code
docs/ my png and pdfs
data/ where the entries will be saved (not yet created)
ReadME.md project rundown

## Tech Stack

- Language: Java
- Libraries: LocalDate, IO, Util
- Tools: VS Code, Git + GitHub

## Build Plan

Step 1: Set up the Git repo and environment
Step 2: Read the user command
Step 3: Create the class that holds the data
Step 4: log an entry
Step 5: Save the entries to a file
Step 6: Load the saved entries 
Step 7: Display the weekly stats
Step 8: Add checks for invalid inputs
Step 9: clean up code/revisions

## Design documents

CS 19300 final project matrix.pdf
flowchart.png

## Possible Commands

log: Add workout or study session
stats: Shows this week's hours
help: lists the commands
quit: exits the program
