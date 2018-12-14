[Site Home](../../../../index) | [SQL PASS Summit Home](../../../index) | [Pass Summit 2018 Home](../../index) | [November 8th Sessions](./index)

Legend:

- ? = Question needing answering

- T = Tool to examine

- I = Information for follow up

- ! = ToDo at work

- \* Exciting item

## Principle of Least Privilege: The Key to Strong Security

### Speaker: Ed Leighton-Dick

### Abstract
> *A truly strong security model starts with no permissions and adds what is necessary to allow the user or application to do their assigned task - no more, no less. This is called the Principle of Least Privilege. It's a simple concept, but it can be quite difficult to implement in practice, especially if the prevailing practice has been much more permissive.*
>
> *In this session, we'll talk about the Principle of Least Privilege in more detail, and we'll discuss ways to implement it for the three primary classes of users - general users, applications, and administrators. Each has their own set of needs that requires a separate approach to allowing the security to meet those needs. You'll leave with actionable ideas on ways that you can improve your company's security while minimizing the impact of the changes.*

\- Get involved in PASS!

\- Protect the data at the source

! Crypto Jacking is the new malware hotness

\- California GDPR-like regulation, AB 375, goes into effect in 2020

? Where does Database Security fall in the Secure SDLC?

! "I am an accidental DBA"

? What is "Transparent Data Encryption" (TDE)?

\- DBA's are not brought in at the start of feature/product development or tool analysis. This leaves the DBA in the dark and forced to play catch-up down the line, creating and exacerbating rifts in between departments

\- The more permissions you allow a user or role, the more monitoring must be done. Repudiation, the R in the STRIDE model
- Alerts can be setup to notify concerned individuals when the baseline app activity changes

\- Need seperation of duties to go down to the object level

? Use "impersonation" to debug permissions?

I sys.fn_my_permissions(db, object)

? The "Trustworthy Hole"

! Audit access rights of our dev team

\- You can create a user associated with a role; though not necessarily a good idea

\- Start role creation from scratch. Build permissions up from nothing rather than basing the role on an existing fixed role. It's easier to grant permissions rather than taking them away by applying "deny" many, many times on each role