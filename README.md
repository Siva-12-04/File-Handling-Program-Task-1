# File-Handling-Program-Task-1
NAME : Siva A

COMPANY : CODTECH IT SOLUTIONS

INTERN ID : CT08RJU

DOMAIN :  C Programming

DURATION : FEBRUARY 5th, 2025 to MARCH 5th, 2025 (4 WEEKS)

MENTOR : NEELA SANTHOSH

Objective:
1)File Creation:
Learn how to create a new file or overwrite an existing file using the "w" file mode.
Understand how to write initial content to a newly created file.

2)Reading from a File:
Learn how to open a file in "r" mode and read its contents line by line using fgets().
Handle cases where the file might not exist or fail to open.

3)Appending to a File:
Learn how to append content to an existing file without overwriting its current content using the "a" file mode.
Understand how new content is added at the end of the file.

4)Overwriting a File:
Learn how to overwrite the entire content of a file using the "w" file mode.
Understand the implications of overwriting (existing content is replaced with new content).


The main function demonstrates these operations sequentially:

It creates and writes to a file.

Reads and displays its content.

Appends additional content and displays the updated file.

Overwrites the content and shows the final result.

The program illustrates key concepts in file manipulation such as using different file modes ("w", "r", "a"), handling errors with perror(), and performing sequential file operations. The result is a simple, practical example of file I/O in C.

conclusion:

Initially, the content written to the file is shown after the file is created.

After appending, the new content is displayed when the file is read again.

Finally, after overwriting, the content is updated and displayed.

File created and initial content written. 

Output: 

Contents of the file:

This is the initial content of the file.

Content appended to the file.

Contents of the file:

This is the initial content of the file.

This is additional content appended to the file.

File overwritten with new content.

Contents of the file:

This is the new content written to the file.

