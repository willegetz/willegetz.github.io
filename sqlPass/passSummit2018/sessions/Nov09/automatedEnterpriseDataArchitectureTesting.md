[Site Home](../../../../index) | [SQL PASS Summit Home](../../../index) | [Pass Summit 2018 Home](../../index) | [November 9th Sessions](./index)

Legend:

- ? = Question needing answering

- T = Tool to examine

- I = Information for follow up

- ! = ToDo at work

- \* Exciting item

## Automated Testing in an Enterprise Data Architecture

### Speaker: Ike Ellis

### Abstract
> *Testing tools are very mature in the software development side of the house, but very immature in the business intelligence/reporting side. As the transactional developers release faster and faster, this is putting a burden on the business intelligence professionals. As we strive to keep up, teams are struggling with providing a consistent, reliable solution where bugs don't repeatedly surface. Couple that with the fact that in data warehousing, we move data from the source to several different places, while using many different tools. It becomes difficult to untangle where the bug exists and to prove the bug was fixed and will never appear again. Come to this session to arm yourself with data testing strategies that will improve the quality of your data, visualizations, and reports and preserve trust with your users and business stakeholders.*

\- SQL is a command language

\- Devs are taking ownership of the quality of their code with automated testing. On the data side of things, there are not tests

\- Testing is difficult with data

\- We test to build user confidence

\- If you dont't test, you are gambling on someone else to do their job right
- Take ownership of your data by testing

T Ike and Scott wrote a tool to test data

\- CI is a fancy script runner

I Test names: Why it exists, not what it does

\- Tests preserve intent

\- Change lock: A change is requested but the dev says "no thanks" because the code base is too fragile, difficult, etc

\- Testing pushback is often a political fight, not a technical fight

\- Small things are changeable, big things are not

\- Data architectures all have one thing in common: They move data

\- Most Exploritory Data Analysis (EDA) have some insane complexity

\- Problems which interfere with testing
- Testing the weather: Ever changing data
- Side Effects: SProcs always violate Don't Repeat Yourself (DRY)
- Queries take a long time to run
- Source systems don't really want us there
- EDA's have a lot of repeditive data
- Accuracy is DEADLY IMPORTANT

\- Record outages and bugs to identify fragile an breaking systems and then shore them up

\- Ike has written a datatable formatter for Approvals which formats a .NET Datatable to look like tabular output

T! [Query Approvals](https://github.com/CraftingBytes/QueryApprovals) can be written against any OLDB/OLDBC data sources!
- Can test SProcs
- Query becomes the testing language
- Query files become the test name