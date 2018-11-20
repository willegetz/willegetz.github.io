[Site Home](../../../../index) | [SQL PASS Summit Home](../../../index) | [Pass Summit 2018 Home](../../index) | [November 8th Sessions](./index)

Legend:

- ? = Question needing answering

- T = Tool to examine

- I = Information for follow up

- ! = ToDo at work

- \* Exciting item

### Principle of Least Privilege: The Key to Strong Security

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