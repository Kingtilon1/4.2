# 4.2
To create this api server you will need postman, sql query, visual studio code and node.js.
First in your sql query yuou will need to create a database, this data base
In Object Explorer, connect to an instance of the SQL Server Database Engine and then expand that instance.

Right-click Databases, and then click New Database.

In New Database, enter a database name.

To create the database by accepting all default values, click OK; otherwise, continue with the following optional steps.

To change the owner name, click (...) to select another owner.
To change the default values of the primary data and transaction log files, in the Database files grid, click the appropriate cell and enter the new value. For more information, see Add Data or Log Files to a Database.

To change the collation of the database, select the Options page, and then select a collation from the list.

To change the recovery model, select the Options page and select a recovery model from the list.

To change database options, select the Options page, and then modify the database options. For a description of each option, see ALTER DATABASE SET Options (Transact-SQL).

To add a new filegroup, click the Filegroups page. Click Add and then enter the values for the filegroup.

To add an extended property to the database, select the Extended Properties page.

In the Name column, enter a name for the extended property.

In the Value column, enter the extended property text. For example, enter one or more statements that describe the database.

To create the database, click OK.

Then you will create your table in visual studui code.
After running npm install and connecting to visual studio code from the same command promt, check to find your port number in sqquery.
After running code in node. js I was able to succesfully connect the the sql database to the code from node.js succesfully. After running succesfully the out put looked like this
FirstName MiddleName  LastName    Age
Homer  	  NULL	      Simpson	    42
Lisa    	NULL	      Simpson	    10
Marge 	  NULL	      Simpson	    40
Bart	    NULL	      Simpson	    12
