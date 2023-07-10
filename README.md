# DotnetCore
Dotnet Core Assessment

Prerequisites
-------------

* Please Extract the MVCCore.zip file and keep the files in a drive i.e. D:// or E://
* Get the file TestDB.bak and restore it in the MS SQL Server
* Launch the MVCCore application (ASP.Net Core 3.1 or above) in Visual Studio
* Launch the application (Press F5)

Assessment Progress
-------------------

1.	Create a REST API using .Net Core MVC and write a method to return a sorted list of these by Publisher, Author (last, first), then title.

	 - Done (API is available in https://localhost:44395/sortedbypublisher

2.	Write another API method to return a sorted list by Author (last, first) then title.

	-  Done (API is available in https://localhost:44395/sortedbyauthor
	
3.	If you had to create one or more tables to store the Book data in a SQL Server/Sql Lite database, outline the table design along with fields and their datatypes.

	 - Done (API is available in https://localhost:44395/savebook - Post request
	 
4.	Write stored procedures for steps 1 and 2, and use them in separate API methods to return the same results.

	 - Done (API is available in https://localhost:44395/sortedbyauthorsql & https://localhost:44395/sortedbypublisher
	 
5.	Write an API method to return the total price of all books in the database.

	 - Done (API is available in https://localhost:44395/totalprice
	 
6.	If you have a large list of these in memory and want to save the entire list to the database, with only one call to the DB server.

	 - Done (During screen launch itself data will be returned and shown)
	 
7.	Add a property to the Book class that outputs the MLA (Modern Language Association) style citation as a string (https://images.app.goo.gl/YkFgbSGiPmie9GgWA). Please add whatever additional properties the Book class needs to generate the citation.

	 - Done (API is available in https://localhost:44395/getbookswithmlacitation

8.	Add another property to generate a Chicago style citation (Chicago Manual of Style) (https://images.app.goo.gl/w3SRpg2ZFsXewdAj7).

	 - Done (API is available in https://localhost:44395/getbookswithchicagocitation

9.	Need to store a image as base64 value also show this image in list table and edit.

	 - Partially done, to preview the data and save part is not handled properly


P.S: Port number shall vary, please use the appropriate
