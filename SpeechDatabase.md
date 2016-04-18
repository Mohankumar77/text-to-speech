Currently all the speech files and related information  are stored on flat file system. Accessing it and searching for the required data is taking a lot of time which has resulted in low efficiency. Moving these into a Relational/XML database might improve the speed and would definitely simplify code. Need to explore this. Preferred databases to be used: MySQL, Apache Derby.

To Do:
  * Explore the best approach to be used - RDBMS (Relational Database Management Systems) /XML/LDAP? Derby/MySQL? etc.
  * Design the database/XML schema.
  * Modify TTS source code to read speech units from database/XML.