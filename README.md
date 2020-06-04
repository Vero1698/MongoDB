# MongoDB

# Introduction:
### What is MongoDB?
![imagenmongo](https://user-images.githubusercontent.com/48557621/83740396-64e13f80-a61c-11ea-812b-c330dbbc1975.png)

"MongoDB is a distributed database at its core, so high availability, horizontal scaling, and geographic distribution are built in and easy to use" MongoDB(s.a)

As mentioned before, mongodb is a distributed database that adapts to different operating systems, either windwos or linux, making it easier and more satisfying for its users.

# Cheat sheet of Mongo on Windows
## Basic Commands
#### 1,1: Start Mongodb
In windows mongoDB, to access the database you first have to open our terminator and run the code "mongodb":

![2](https://user-images.githubusercontent.com/48557621/83737555-c8696e00-a618-11ea-9f08-49b712a9c24e.PNG)

After, we are going to open a new "cmd" and run "mongo", so, the result will be:

![3](https://user-images.githubusercontent.com/48557621/83737823-25652400-a619-11ea-8af7-f783c45ece6f.PNG)


#### 1.2: If we want to see the name of databases on Mongodb,  we use "show dbs"
![1](https://user-images.githubusercontent.com/48557621/83736373-2ac16f00-a617-11ea-85ef-7d2bbcc78c23.PNG)


#### 1.3: Create a new database, we are going to use  "use" + "nameofyourdatabase"
![4](https://user-images.githubusercontent.com/48557621/83738651-2f3b5700-a61a-11ea-95db-b30dcb96180c.PNG)

A funny thing is that the database after this command will not be created unless I know how to use it.

#### 1.4: Add a new collection  "db.CreateCollection("name_collection")"
![5](https://user-images.githubusercontent.com/48557621/83740394-6448a900-a61c-11ea-97b7-859b794ad341.PNG)

#### 1.5 : Show all collections that you have in your database  "show collections"
![collection](https://user-images.githubusercontent.com/48557621/83773458-26627980-a64a-11ea-8941-34d59c4bf1aa.PNG)

#### 1.6: Insert a record into a collection  " db.name_collection.insert({"clname":"data")}
![insertCollection](https://user-images.githubusercontent.com/48557621/83774456-52cac580-a64b-11ea-8a29-4f21da5df131.PNG)

#### 1.7:Display list of records of a collection , "db.name_collection.find()" or "db.name_collection.find().pretty()"
![find](https://user-images.githubusercontent.com/48557621/83774783-c66cd280-a64b-11ea-9f2d-6bcb36c022e8.PNG)

#### 1.8 : Display a list of records matching with specific value   "db.name_collection.find({"clname": "data"})"
![displayalist](https://user-images.githubusercontent.com/48557621/83775527-a8ec3880-a64c-11ea-8a77-88ca704421c0.PNG)

#### 1.9 : Drop a collection   "db.name_of_collection.drop()"
![drop](https://user-images.githubusercontent.com/48557621/83776316-a50ce600-a64d-11ea-8b8b-9ae96abc1233.PNG)

#### 1.10 : Ordering in MongoDB, "db.name_coleccion.find(filtro_by_user).sort(ordenacion_As_or_Des)"
First, we need to insert some values for collection (collection called "Prueba")
![insertdata](https://user-images.githubusercontent.com/48557621/83779138-303bab00-a651-11ea-85fd-0b7693e7da5c.PNG)

After, we can sort the collection in an ascending order    "(filtro: 1) "
![sortdata](https://user-images.githubusercontent.com/48557621/83779136-2fa31480-a651-11ea-98c8-8e3664f2000e.PNG)

But, if we want to sort in an descending order     "(filtro : -1 ) "
![descendingorder](https://user-images.githubusercontent.com/48557621/83781662-76463e00-a654-11ea-97fc-075d7bbfe21d.PNG)

#### REFERENCES:
https://www.mongodb.com/what-is-mongodb
https://dzone.com/articles/mongodb-commands-cheat-sheet-for-beginners
http://lineadecodigo.com/mongodb/ordenaciones-en-mongodb/



