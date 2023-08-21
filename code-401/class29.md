# Room

[Overview: Saving data with Room](https://developer.android.com/training/data-storage/room)

[Defining entities in Room](https://developer.android.com/training/data-storage/room/defining-data)

[Related entities in Room](https://developer.android.com/training/data-storage/room/relationships)

[Accessing data with Room](https://developer.android.com/training/data-storage/room/accessing-data#java)

What database engine is Room wrapped around? Do you think this is a good choice? Why or why not?

Local database, this is a good choice because it is an appropriate use of local storage to keep track of preferences/ minor data. It allows for browsing of content while offline.

Do Rooms have any similarities to JPA?

Yes, they can be seen as similar. Both use labels like @Entity and both aid in queries.

Describe a DAO in your own words

A DAO is an interface or abstract class. It is used to define what and how to access data in the database. This is done using SQL methods.
