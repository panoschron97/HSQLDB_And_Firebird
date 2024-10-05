# HSQLDB_And_Firebird

A download link that contains two videos.

In my recent project using eclipse with hsqldb and Firebird separate i created a user management system with a database table. 
I granted the select privilege on the table to each user along with the grant option allowing them to share the privilege with others. This setup enabled users to pass on their select privileges to one another. 
To test the cascading effect of privileges i executed revoke commands with the cascade option. This allowed me to verify that when one user lost their select privilege all downstream users also lost access. 
The project successfully demonstrated the dynamics of privilege management in a database. 
