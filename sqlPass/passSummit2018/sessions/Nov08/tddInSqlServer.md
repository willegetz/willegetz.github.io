[Site Home](../../../../index) | [SQL PASS Summit Home](../../../index) | [Pass Summit 2018 Home](../../index) | [November 8th Sessions](./index)

Legend:

- ? = Question needing answering

- T = Tool to examine

- I = Information for follow up

- ! = ToDo at work

- \* Exciting item

### Test Driven Development in SQL Server – How to Deploy Code Safer

\- TDD is a crystal ball which grants insight into what functionality to give the client

\- calling for increased agility in the data world

\- TDD is hard on databases because refactoring doesn't happen
- Furthermore, trying to apply software development refactoring principles to SProcs and scripts will result in poor performance

T [TSQLT](https://tsqlt.org), [Redgate SQL Test](https://www.red-gate.com/products/sql-development/sql-test/), [Visual Studio SSDT](https://docs.microsoft.com/en-us/sql/ssdt/download-sql-server-data-tools-ssdt?view=sql-server-2017)
- As of this post the most recently available SSDT is for VS2017

? Source control your data?

? Can you unit test user/application role security?

? Shift-Left principle?

\- Continuous monitoring for permformance analysis

\- Don't use SELECT * because of the performance hit

\- TSQLT can be run in containers
- Alter Assembly tsqltclr with "permissions_set=external_access"