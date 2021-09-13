# DAT250: Software Technology Experiment Assignment 2
by Sindre Larsen

## Technical problems
No technical problems when installing, however there were some
issues using OpenJDK 16 with Eclipselink as EL did not support this
 (according to the error message). I resolved this by changing the JDK to 
version 11.0.2 instead, after this I encountered no more error messages.

## Experiments
1: Source code found here: [https://github.com/SiLar92/expass2.1a](https://github.com/SiLar92/expass2.1a)
and here: [https://github.com/SiLar92/expass2.1b](https://github.com/SiLar92/expass2.1b)

2: Source code found here: [https://github.com/SiLar92/expass2.2](https://github.com/SiLar92/expass2.2)

## Database inspection
I inspected the database using the built-in database features of Intellij.
For the first experiment a table called "TODO" was created.
With the columns ID, Summary and Description

Id is the primary key and is generated automatically using 
GeneratedValue(strategy = GenerationType.IDENTITY)
summary and description were both strings, in this case always
given the value "This is a test" as I didn't make any changes.
![](images/expass2/db-table.png?raw=true)

The tables giving me sensible content after running the JPATest.java were these:
![](images/expass2/db-tables2.png?raw=true)

I'm not sure if I missed something in the tutorial about how it should be run to produce
content in the other tables as shown on the right-hand side, or if IntelliJ's viewer is
missing some data or relation that exists in the db which should be visible.

In any case I'll test out on monday with a different viewer as well as complete the remaining
experiment (Banking/Credit Card example JPA). Here are the other tables shown
in Intellij's viewer:
![](images/expass2/db-tables2.1.png?raw=true)

Experiment 2 seems to have worked fine, same issue with the "empty" tables for the relations between the different entities.
![](images/expass2/tables2.2.png?raw=true)

## Pending issues:
- Not sure what is causing the db tables to show up almost empty as shown above. Just placeholder to show relations, or am I missing something?
