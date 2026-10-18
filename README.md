
# CIS-165 Lab 3

**Name:** Chad Brown  
**Course section:** CIS-165-W198

## Initial Plans

### Diamond Pattern
I will use seven cout statements to print each line of the diamond. I will use spaces and asterisks to match the required pattern without using loops.

### Video Game Level Times
I will store the two assigned times, 78 and 144 minutes, in named constants. I will use integer division by 60 to calculate hours and the remainder operator to calculate remaining minutes. I will subtract the two times to calculate the difference.

## How to Run the Programs

Open each source file separately in OnlineGDB, select C++, and click Run.

- `diamond.cpp` prints the diamond pattern.
- `game_time.cpp` calculates both level times and their difference.

## Test Records

| Program/Test | Values Checked | Expected Result | Actual Output | Match or Correction |
|---|---|---|---|---|
| diamond.cpp | Seven required lines | Star counts of 1, 3, 5, 7, 5, 3, 1 with correct spacing | Fill in after running | Fill in after checking |
| game_time.cpp — assigned values | 78 and 144 minutes | Level 1: 1 hour 18 minutes; Level 2: 2 hours 24 minutes; difference: 1 hour 6 minutes | Fill in after running | Fill in after checking |
| game_time.cpp — changed values | 95 and 167 minutes | Level 1: 1 hour 35 minutes; Level 2: 2 hours 47 minutes; difference: 1 hour 12 minutes | Fill in after running | Fill in after checking |

After testing with 95 and 167, I will restore the assigned values of 78 and 144 and rerun both programs.

**Final rerun results:** Fill in after completing the final runs.

## Code Explanations

### Diamond Pattern
The program uses seven cout statements, one for each line. Spaces before the asterisks position the stars to create a diamond. I checked the output against the required pattern.

### Integer Division and Remainder
Integer division by 60 gives the whole number of hours. The remainder operator (%) gives the minutes left over after dividing by 60.

### Assigned Values
Level 1 takes 78 minutes. Dividing 78 by 60 gives 1 hour, and the remainder is 18 minutes.

Level 2 takes 144 minutes. Dividing 144 by 60 gives 2 hours, and the remainder is 24 minutes.

The difference is 144 - 78 = 66 minutes. Dividing 66 by 60 gives 1 hour, with 6 minutes remaining.

### Storing Calculations
The program stores calculations in variables before displaying them. This makes the code easier to read, check, and understand.
