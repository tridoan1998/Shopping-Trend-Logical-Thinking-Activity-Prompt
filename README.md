Jira Board for tracking work progress:
https://tridoanresearchanalystassessment.atlassian.net/jira/software/projects/MBA/boards/1

Work Documentation: 
Installed SQL Server (mssql) through VsCode extension.
Configuring Database Connection. Open the Connection Dialog on the left side bar of VsCode. Create a new connection, give it the name, server name, and Authentication type. Issue running into is we don't have an instance of SQL server to connect to.
Search on how to download a SQL server. Issue is we using MAC hence Window does not support download.
Found out that I need to use Azure Data Studio because this will support MAC. Download it from the Microsoft website and follow the step to install.
Failed: This method still require me to have a SQL Server.
Watching a Youtube video on how to make a SQL Server for MAC. (https://www.youtube.com/watch?v=glxE7w4D8v8)
Finger out the solution is not from the above as these are not needed for the requirement for this work.
Hence, disregard the work above as it is only useful for a full stack web application, but for aanlyst type of work, it generally better to just have a Microsoft Excel file and then perform SQL database Query code directly on there. 

Move on to this tutorial: https://www.youtube.com/watch?v=Xa5lUd6Fq_c
Convert from CSV to Excel to perform SQL code. CSV will have another version in Python if we have time.

We will start working one question at a time, and it will be specially be label as one different branch for each commit to make sure if we make any mistakes along the way, we can fix it.


TO-DO:
insert security layers so only needed users can see. One way to do this is to map the object as key value pair so they don't need the real data but only the ID.
