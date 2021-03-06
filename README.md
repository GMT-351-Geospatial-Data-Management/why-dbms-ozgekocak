# why-dbms-ozgekocak
why-dbms-ozgekocak created by GitHub Classroom

# First Assignment

__________________________________

## What is a Spreadsheet ?
+ It is an electronic ledger, an electronic version of paper 
accounting worksheets.
+ It was created to facilitate people who needed to store their
accounting information in tabular form digitally.
So, it is possible to create tables in a spreadsheet.

> There are similarities between database and spreadsheet but 
they aren't interchangeable.
Both:
* can contain a large amount of tabular data
* can use existing data to make calculations
* are used by many users

## Database VS. Spreadsheet

* In spreadsheet, every cell is treated as a unique entity.
It can store any type of information -a date, an integer value, a string name.
And then, not only can we have different types of values on various cells, 
but we can also apply a specific format to these cells.

* This is not inherent to databases.
 They contain only raw data.
 Each cell is a container of a single data value.
 It is the smallest piece of information there is.
 You must pre-set the type of data contained in a certain field.
 This feature prevents inadvertent mistakes
 * For example, in a field containing date
values, should the user try to insert a string, the software will show an error and she will
have the chance to correct herself.
This won’t happen in Excel. If you insert a string in the column with date values, you
wouldn’t obtain an error message, and Excel will store the string value.


* In a spreadsheet, data can be stored in a cell, while in a database, data is stored
in a record of a table, meaning you must count the records in a table to express how long
the data table is, not the number of the cells.
You cannot pick a font colour or size.

* In a spreadsheet, different cells can contain
calculations, such as functions and formulas.
This means, if you want to combine two integers, the result will be stored in another cell.
In a database, all calculations and operations are based on the existing data and are done
after its retrieval.

* Data integrity is a strong advantage when working with databases.
Naturally, you might think a spreadsheet can contain multiple worksheets, so one can create
tables in the worksheets, and then use the worksheets to create relations between the
tables.
Why bother using relational databases?
In a spreadsheet, such relations will be logically limited.
Instead of setting up spreadsheets or worksheets, one can set up relations between the tables,
and this will boost the performance of operations, increasing the speed with which you could
manipulate your dataset.

* Excel is incapable of handling over 1 million rows of data.
This immediately induces us to look for a solution.
Usually, the fix is to use databases, where having 2, 5, or 10 million records is not
a problem.

* Referring to the multi-user property, spreadsheets are lagging.
Essentially, every person must update their own spreadsheet with new data.
For instance, if there is a new purchase to register or a last name in the “Customers”
table to correct, every user must make these changes manually.
As opposed to that, you saw in the Data Control Language lecture that databases provide a
stable structure, controlling access permissions and user restrictions.
One person can make a change that is visible to everybody instantly.
This feature increases efficiency and data consistency when using databases.

* Considering data integrity and data consistency, using databases eliminates duplicate information,
which is another way to save space and increase efficiency.

* So, what we discussed why databases are a better environment for
storing and keeping track of data when working with multiple dimensions and large amounts
of data.
Spreadsheets have their advantages as well – they are an excellent tool that allows
us to carry out extensive analysis.
But for the:
  * retrieval data and updating of data efficiency, 
  * data consistency, 
  * data integrity, 
  * speed, 
  * security,

  relational databases are definitely the structure to opt for.
They can store lots of raw data and are excellent when separating the data from the way it is
displayed for analysis.


> * If you just need to track numbers or keep a list that you occasionally share
with others, a spreadsheet is a solid choice. 
* In situations where you’re dealing with more complex data, 
or need to use one source of data for multiple purposes,
a database often works best.
* In Geomatics Engineering, we have to deal with so many complex data. So,
DBMS is a better choice to work on.


