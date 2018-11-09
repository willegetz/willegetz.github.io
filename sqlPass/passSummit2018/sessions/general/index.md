[Site Home](../../../../index) | [SQL PASS Summit Home](../../../index) | [Pass Summit 2018 Home](../../index)

Legend:

- ? = Question needing answering

- T = Tool to examine

- I = Information for follow up

- ! = ToDo at work

- \* Exciting item

### General Notes

#### Women in Tech Lunch
\- An observer of the opening keynote remarked that the talk was more directed to men "as if seeking their approval"

#### Breakfast November 9th
? Turn "4199" on your SQL Server to trace queries on the server?

\- Temp db: Turn on "1118" to distribute access to multiple files used by temp db if you are working with SQL Server pre 2016

\- A server can have multiple temp db files per core.
* It recommended to have 8 files if your instance has 8 cores
* ? For more than 8 cores the number of files is core count -2?

? Where do you enable these multiple temp db files?

\* "That's a weird place to put a piano"

? Do we need such a large team?

#### Lunch November 9th
I AWS with containers for unit testing and DB testing

? How do we handle mobbing at the scale of thousands of developers and tens of thousands of lines of code?

\- Microsoft has an interecting concept called "Neighborhoods" where devs are grouped by project and the product owners/managers, as well as the engineering managers are present in the neighborhood.

\- While the engineering manager directs the work of the developers based on strories created by the product owner/manager, it is the product owner/manager who keeps the engineering manager accountable to the customers