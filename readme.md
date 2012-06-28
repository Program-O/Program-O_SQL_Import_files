Program-O_SQL_Import_files
==========================
The files in this repo are mysql dump files for the main Program-O Chatbot.
These files are just for convenience
The normal way to upload AIML to the database is via the admin panel built into Program O
The bot_id is set to '1' throughout

aiml.sql
--------
This file contains the standard ALICE AIML set converted into SQL format ready to import into the aiml table in the Program-O Database
This file contains the same data as files aiml-1..6.sql
If you cannot import using this file because of the size of the file use the smaller ones below

aiml-1..6.sql
-------------
These files contains the same data as aiml.sql, split into smaller files incase you have problems uploading the big aiml.sql
You do not need these files if you have managed to import the aiml using aiml.sql

learn-aiml.sql
--------------
MySQL dummp of the learn.aiml (Squarebears version)