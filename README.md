# TLG - File processor app
Project setup:
Db script for table creation-
1.Open DbScipts folder and execute UserTable.sql on your local db
2.Open TLG.FileProcessor\ClientApp folder,cmd and run 'npm install' command to install the node modules
3.Open launchSettings file under API project properties - TLG.FileProcessor.API\Properties. Update connection string for your local db user/pwd and db_name
    "ConnectionString": "Server=tcp:localhost; Database=ZZZ; User Id=YYY; Password=XXX!; MultipleActiveResultSets=true"
4.Go to Run and locate %temp% folder. Create a folder with name 'upload'
5 Go to Solution properties and slect Multiple startup projects and select below projects
  a.TLG.FileProcessor.API
  b.TLG.FileProcessor
6. Run the application from visual studio

Note- Upload any file with .csv extension provided all the fields inside are separated by the tab and each entity on new line
e.g.  schemeId	firstName	LastName	email	mobile 
      1 Liam	Kenneth	lia@tengroup.com	9191919191

  
