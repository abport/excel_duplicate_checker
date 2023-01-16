# Python script that allows you to easily compare two Excel files and check for duplicate values.


Hello everyone! Today, we're going to talk about a really cool program that helps us work with Excel files.

You know what Excel is, right? It's a program that lets us organize information in a neat and tidy way, using rows and columns. And this program we're going to talk about today can help us compare two different Excel files, and see if they have the same information.

First, we're going to start by importing a special library called "openpyxl". This library is like a tool that helps our program understand how to work with Excel files.

Next, we're going to set the "file paths" for the two Excel files we want to compare. A file path is just the location of the file on our computer. So, we're telling the program where to find the first Excel file, and then where to find the second one.

Then, we're going to "open" the first Excel file using the openpyxl library. This is like telling the program, "Hey, we're going to use this file now!" We're also going to set the first Excel file's first sheet as the "active" sheet, which just means that this is the sheet we're going to be working with.

After that, we're going to do the same thing for the second Excel file. We're going to open it, and set the first sheet as the active sheet.

Now that we have both Excel files open, we're going to start comparing them! We're going to look at each row in the first Excel file, one at a time. We're going to check if all the values in that row are also in the second Excel file.

If they are, the program will print a message saying that the values in that row were found in the second Excel file, and it will also show the entire row values. But if they're not, the program will print a message saying that the values in that row were not found in the second Excel file.

And finally, after we've compared all the rows in the first Excel file, we're going to close both Excel files. This is like telling the program, "Okay, we're done using these files now."

Isn't that so cool? With this program, we can easily compare two Excel files and check if they have the same information. It's like having a super smart helper that can check for us!
