# HSQLDB_And_Firebird

A download link that contains two videos.

In my recent project using Eclipse and HSQLDB, I created a user management system with a database table. 
I granted the SELECT privilege on the table to each user along with the GRANT option allowing them to share the privilege with others. This setup enabled users to pass on their SELECT privileges to one another. 
To test the cascading effect of privileges i executed REVOKE commands with the CASCADE option. This allowed me to verify that when one user lost their SELECT privilege all downstream users also lost access. 
The project successfully demonstrated the dynamics of privilege management in a database. 
