CIS-165 Lab 3
Name: Chad Brown 
Course section: CIS-165-W198
Initial Plans
Diamond Pattern
I will use seven cout statements to print each line of the diamond. I will use spaces and asterisks to match the required pattern without using loops.
Video Game Level Times
I will store the two assigned times, 78 and 144 minutes, in named constants. I will use integer division by 60 to calculate hours and the remainder operator to calculate remaining minutes. I will subtract the two times to calculate the difference.
How to Run the Programs
Open each source file separately in OnlineGDB, select C++, and click Run.
- diamond.cpp prints the diamond pattern.
- game_time.cpp calculates both level times and their difference.
Test Records
Complete the actual-output and match/correction columns after running each test. Record only results you personally observed.
Program/test	Values or pattern checked	Expected result before running	Actual output	Match or correction
diamond.cpp	Seven required lines	7 lines; star counts are 1, 3, 5, 7, 5, 3, 1, with leading spaces matching the assignment	[Fill in after your run]	[Fill in after comparing every line]
game_time.cpp — assigned values	Level 1 = 78 min; Level 2 = 144 min	Level 1 = 1 hour, 18 minutes; Level 2 = 2 hours, 24 minutes; difference = 1 hour, 6 minutes	[Fill in after your run]	[Fill in after comparing]
game_time.cpp — changed values	Level 1 = 95 min; Level 2 = 167 min	Level 1 = 1 hour, 35 minutes; Level 2 = 2 hours, 47 minutes; difference = 1 hour, 12 minutes	[Fill in after your run]	[Fill in after comparing]


After the changed-values test, restore the assigned values of 78 and 144 in game_time.cpp and rerun both programs.
Final rerun after restoring assigned values: [Record what you ran and observed.]
Code Explanations
Diamond Pattern
The program uses seven cout statements, one for each line. Spaces before the asterisks position the stars to create the diamond. I checked the output against the required pattern. [Revise this explanation to match how you personally checked the spaces and output.]
Integer Division and Remainder
Integer division by 60 gives the whole number of hours. The remainder operator (% 60) gives the minutes left over after dividing by 60.
Trace of Assigned Values
Level 1 takes 78 minutes. Dividing 78 by 60 gives 1 whole hour, and the remainder is 18 minutes.
Level 2 takes 144 minutes. Dividing 144 by 60 gives 2 whole hours, and the remainder is 24 minutes.
The difference is 144 - 78 = 66 minutes. Dividing 66 by 60 gives 1 whole hour, with 6 minutes remaining.
Why Store Calculations First?
Storing calculations in variables before displaying them makes the program easier to read, check, and understand.
GitHub Submission Checklist
- [ ] diamond.cpp, game_time.cpp, README.md, and AI_REFLECTION.md are at the repository's top level.
- [ ] Both programs compile and run separately.
- [ ] Test records reflect runs I actually performed.
- [ ] The assigned values are restored to 78 and 144 minutes.
- [ ] The repository cis165-lab3 is public.
- [ ] I checked the repository and final commit while signed out of GitHub.
- [ ] I submitted my name, repository URL, and final commit URL in Canvas.
