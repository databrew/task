# task

## Instructions


Spend no more than 10 hours on the following task. 

Create and document a basic shiny app which:

- Reads data from a PostgreSQL database (either local or remote)
- Has log-in (using a username / password combination from a file of usernames/passwords that you create)  
- Has differential privileges (one kind of user should be read-only; another kind should be read and write)
- Shows that data in the app
- Allows the data to be modified by the user (if that user has write access)
- Saves the modified data to the database
- Has some version of "version control" (ie, one should be able to recover the modification history, rather than simply overwrite database values)


## Evaluation criteria


- Is the entire codebase is entirely reproducible by another based on documentation alone (including how to spin up the database, credentials, run code, install packages, etc.).

- Is the code clear, organized, and well-commented?  

- Is the code efficient and technically correct?  

- Is the app aesthetically pleasant?  
