# CIS-165 Lab 3

**Name:** Chad Brown  
**Course section:** CIS-165-W198

## Initial Plans

### Diamond Pattern

I planned to use seven `cout` statements, one for each line of the diamond. I used spaces and asterisks to reproduce the pattern without loops.

### Video Game Level Times

I planned to store the assigned times, 78 minutes and 144 minutes, in named constants. I used integer division by 60 to calculate whole hours and the remainder operator to calculate remaining minutes. I also calculated the difference between the two level times.

## How to Run the Programs

I opened each source file separately in OnlineGDB, selected C++, and clicked **Run**.

- `diamond.cpp` prints the diamond pattern.
- `game_time.cpp` calculates both level times and their difference.

## Test Records

| Program/test | Values or pattern checked | Expected result before running | Actual output | Match or correction |
|---|---|---|---|---|
| `diamond.cpp` | Seven required lines | 7 lines; star counts are 1, 3, 5, 7, 5, 3, 1, with leading spaces matching the assignment | The seven-line diamond pattern displayed as required, with star counts of 1, 3, 5, 7, 5, 3, 1 and matching leading spaces | Match |
| `game_time.cpp` — assigned values | Level 1 = 78 min; Level 2 = 144 min | Level 1 = 1 hour, 18 minutes; Level 2 = 2 hours, 24 minutes; difference = 1 hour, 6 minutes | Level 1 time: 1 hour(s) and 18 minute(s). Level 2 time: 2 hour(s) and 24 minute(s). Difference: 1 hour(s) and 6 minute(s). | Match |
| `game_time.cpp` — changed values | Level 1 = 95 min; Level 2 = 167 min | Level 1 = 1 hour, 35 minutes; Level 2 = 2 hours, 47 minutes; difference = 1 hour, 12 minutes | Level 1 time: 1 hour(s) and 35 minute(s). Level 2 time: 2 hour(s) and 47 minute(s). Difference: 1 hour(s) and 12 minute(s). | Match |

After the changed-values test, I restored the assigned values of 78 and 144 in `game_time.cpp` and reran both programs.

**Final rerun after restoring assigned values:** The diamond displayed the required seven-line pattern. The time program displayed Level 1 as 1 hour and 18 minutes, Level 2 as 2 hours and 24 minutes, and the difference as 1 hour and 6 minutes.

## Code Explanations

### Diamond Pattern

The program uses seven `cout` statements, one for each line. Spaces before the asterisks position the stars to create the diamond. I compared the output with the required pattern and checked the number of spaces and asterisks on each line.

### Integer Division and Remainder

Integer division by 60 gives the whole number of hours. The remainder operator (`% 60`) gives the minutes left over after dividing by 60.

### Trace of Assigned Values

Level 1 takes 78 minutes. Dividing 78 by 60 gives 1 whole hour, and the remainder is 18 minutes.

Level 2 takes 144 minutes. Dividing 144 by 60 gives 2 whole hours, and the remainder is 24 minutes.

The difference is 144 - 78 = 66 minutes. Dividing 66 by 60 gives 1 whole hour, with 6 minutes remaining.

### Why Store Calculations First?

Storing calculations in variables before displaying them makes the program easier to read, check, and understand. It also follows the assignment requirement to calculate results before using `cout` to display them.

## GitHub Submission Checklist

- [ ] `diamond.cpp`, `game_time.cpp`, `README.md`, and `AI_REFLECTION.md` are at the repository's top level.
- [ ] Both programs compile and run separately.
- [ ] Test records reflect runs I performed.
- [ ] The assigned values are restored to 78 and 144 minutes.
- [ ] The repository `cis165-lab3` is public.
- [ ] I checked the repository and final commit while signed out of GitHub.
- [ ] I submitted my name, repository URL, and final commit URL in Canvas.
