# CS300-DSA
Final Projects for CS-300 Data Structures and Algorithms

What was the problem you were solving in the projects for this course?

In this course we explored Vectors, Hash Tables and Binary Search Trees as data structures in C++. We analyzed the advantages and disadvantage of each data structure. There may be times when a certain data structure may be more efficient depending on the use case, and we learned how to make a decision about how to make this decision. In our final project I chose to use a Binary Search Tree to store data loaded from a .csv file. It was the most efficient at printing a sorted list of all data.

My program:

Prompts user to enter a .csv file from which to load data.
Creates a BST from this file.
Prompts user to enter a course and searches the BST for this course. If found, detailed information about the course is displayed to the user.
Prints an alphabetically sorted list of all courses that have been loaded.


How did you approach the problem? Consider why data structures are important to understand.

To approach this problem, I noted the features required for the final product. Since it required printing a sorted list of all courses, I felt that using a Binary Search Tree was the most reasonable choice. The data is sorted when creating the Binary Search Tree, so by using an In Order traversal of the BST, this was easy to implement. The BST also excels at searching for a certain course, especially as the amount of data loaded to it increases. A Hash Table was not a reasonable choice for this project because that data structure does not cater well to sorting the data that it contains. A vector could have been used, but sorting and searching would have been costly operations to perform.


How did you overcome any roadblocks you encountered while going through the activities or project?

When working on this project, I originally felt overwhelmed. It helped me to explain the goal of the project to a friend, working through each step I would take to meet the requirements. I also found that taking breaks from coding helped me approach the project with a clear mind and recognize new steps I could take to complete the project. Part of my roadblock in this project involved editing code that we had used in other projects to meet updated requirements. It involved reading through code that was more complicated than I was used to and identifying where I needed to make adjustments. 


How has your work on this project expanded your approach to designing software and developing programs?

I have a better understanding of data structures and can recognize the benefits and drawbacks of using each. I have a better ability of reading through code and understanding what actions are taking place during nested loops and conditional statements.


How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?

By keeping my code modular, it stays clear and understandable when changes or updates need to be made. I continued my practice of including whitespace so that the code is not cluttered. Comments explain what each section of code accomplish or how they interact elsewhere. 
