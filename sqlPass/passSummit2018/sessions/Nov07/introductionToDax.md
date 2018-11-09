[Site Home](../../../../index) | [SQL PASS Summit Home](../../../index) | [Pass Summit 2018 Home](../../index) | [November 7th Sessions](./index)

Legend:

- ? = Question needing answering

- T = Tool to examine

- I = Information for follow up

- ! = ToDo at work

- \* Exciting item

### Introduction to DAX

\- Calculate function is missused

\- DAX is __***NOT***__ TSQL. It is __***NOT***__ the Excel Formula Language. It is it's own thing

\- You access the column in the data object much like you would access an named index in a list.

\- 99% of the time you will be doing measures (in PowerBI)

\- DAX ignores white space, so you can format your statements in a pretty and readable way

! Create an ETL to injest information about our codebase and ci/cd and use the result for BI

\- Calculated columns go row by row, aka Row Context. This is done once, when the data is imported, and persisted

\- The Calculate function allows you to override the filter context.
* ? Is this like a CTE?
* \- Useful for comparison analysis

\- You can use DAX to create a table; a calculated table

\- "Values", "All", and "Filter" are all function which will return an __***ENTIRE TABLE***__

I Use measures as folders to store organize calculations; organize by type.

\- Multi-line DAX avoids paren hell!

\- Data type for DAX is "var". No primitives :)

! Learn windowed functions

\- Dax functions are for Row Context. They iterate one row at a time

\- Avoid the use of acronyms

\- Most times there is a problem in PowerBI it is caused by a bad model or a bad datatype

T* DAX Studio