done bleow things to one of the i/p text file (Temparature file)

Note: Since i dont have Hadoop environment, i've connected Spark from Local (i/p file in local machine)

1. Defined Spark context
2. Defined SQL context
3. Read the text file in to RDD
4. Defined the Header for dataframe
5. Defined the schema for above header
6. Concerted the string RDD to row RDD after cleansing the data. (Each collumn value in the i/p file had different multiple spaces as separator, so  i had to clean the data so that each value separated by once space. So that data will be insertedin to table correctly.)
7. Created dataframe on anove row RDD and schema
8. Created temparory table
9. Retrieved all the records from temp table
10. Displayed 5 records from temp table.

Now we can apply what ever the tranformations we want on topof this.