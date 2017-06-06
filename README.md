# Overview

This application takes the developer through the process of making a project easier to understand by making a series of updates. It is part of the [Writing Professional Code](https://www.edx.org/school/microsoft) course on edX. 

> The order in which you perform these updates is not important. We are trying to show a set of smells that can exist in a small codebase such as this one and how you can make thigns better. 


# Commits/ Tutorial Outline

You can check out any point of the tutorial using:

> git checkout update-?

To see the changes made between any two lessons use the git diff command:

> git diff update-?...update-?

### update-0 Initial Project
The project that is checked in is a **.NET Core** console app. To run the app, type the following at the command line. 

> `dotnet run -a`

You should then explore the code to see what other options are available, how the app is structured and what improvement can be. 

### update-1 Consistency

Coding style matters in a project, because it removes one more thing to worry about as you try to rad and understand the code. In this update, we'll re-position some brackets to make sure the style is consistent. We'll also make sure there is space above code comments. All of this makes the source code easier to read at a glance. 

### update-2 Guard Clauses

If you can bail early from a method, you should consider doing so. It is a good technique for handling obvious error conditions in a code path and helps the reader of your code "park" those paths in their head. In this update, we will make sure to check whether the user is calling the program with the correct argument count before proceeding.

### update-3 Naming conventions

### update-4 Refactor Common Code

Includes disposing of stream objects. 

### update-5 Remove String Literals

Avoid errors - for example, "," and ", " when inserting values and counting them. Avoid mistakes since I can clearly read intent and decide if that is what we wanted to do. 

### update-6 Eliminate Temporary Variables

### update-7 Eliminate Control Flow Variables
+ Bug

### update-8 Simplification (of count operation)

### update-9 Handle invalid arguments

ShowUsage + Check argument count comment

## update-10 Naming and Comment Pass



## update-11 One More Thing
Brittle code - Contains -> StartsWith

A better way to search with Linq

### update-11 One last Naming and Comment pass
More student-centric because no matter how much we pretend, the code is very specific to our current schema.
TODO for future work





