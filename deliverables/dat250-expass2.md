# DAT250: Software Technology Experiment Assignment 1
by Sindre Larsen

## Technical problems
No technical problems when installing, however there were some
issues using OpenJDK 16 with Eclipselink as EL did not support this
 (according to the error message). I resolved this by changing the JDK to 
version 11.0.2 instead, after this I encountered no more error messages.

## Experiments
1: Source code found here: [https://github.com/SiLar92/expass2.1a](https://github.com/SiLar92/expass2.1a)
and here: [https://github.com/SiLar92/expass2.1b](https://github.com/SiLar92/expass2.1b)


## Database inspection
I inspected the database using the built-in database features of Intellij.
For the first experiment a table called "TODO" was created.
With the columns ID, Summary and Description

Id is the primary key and is generated automatically using 
GeneratedValue(strategy = GenerationType.IDENTITY)
summary and description were both strings, in this case always
given the value "This is a test" as I didn't make any changes.

The second part of the first experiment...
